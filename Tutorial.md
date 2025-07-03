# Complete ASP.NET Core Blazor Server Tutorial with Entity Framework Core

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Project Setup](#project-setup)
4. [Understanding the Architecture](#understanding-the-architecture)
5. [Database Configuration](#database-configuration)
6. [Models and Entity Framework](#models-and-entity-framework)
7. [Services Layer](#services-layer)
8. [API Controllers](#api-controllers)
9. [Blazor Components](#blazor-components)
10. [Authentication](#authentication)
11. [Running the Application](#running-the-application)
12. [API Testing](#api-testing)
13. [Best Practices](#best-practices)
14. [Common Issues and Solutions](#common-issues-and-solutions)

## Project Overview

This comprehensive tutorial demonstrates how to build a full-stack web application using:
- **ASP.NET Core 8.0** - Backend framework
- **Blazor Server** - Frontend framework with C# instead of JavaScript
- **Entity Framework Core** - Object-Relational Mapping (ORM)
- **SQL Server** - Database
- **ASP.NET Core Identity** - Authentication and authorization
- **Web API** - RESTful API endpoints
- **Bootstrap** - UI styling

### What You'll Build
A Product Management System with:
- User authentication and authorization
- Complete CRUD operations (Create, Read, Update, Delete)
- RESTful API endpoints
- Interactive Blazor components
- Responsive web interface
- Database integration with relationships

## Prerequisites

### Software Requirements
1. **Visual Studio 2022** (Community, Professional, or Enterprise)
   - Or **Visual Studio Code** with C# extension
2. **NET 8.0 SDK** or later
3. **SQL Server** (LocalDB, Express, or full version)
4. **Git** (optional, for version control)

### Knowledge Requirements
- Basic C# programming
- Understanding of HTML/CSS
- Basic database concepts
- Object-oriented programming principles

## Project Setup

### Step 1: Create the Project

```bash
# Create a new Blazor Server project with authentication
dotnet new blazorserver --auth Individual --use-local-db false --name BlazorTutorial

# Navigate to the project directory
cd BlazorTutorial
```

### Step 2: Update to .NET 8.0

Update the `BlazorTutorial.csproj` file:

```xml
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>net8.0</TargetFramework>
    <Nullable>enable</Nullable>
    <ImplicitUsings>enable</ImplicitUsings>
    <UserSecretsId>aspnet-BlazorTutorial-1062060e-07a1-48f6-b4ed-36a60e124fbd</UserSecretsId>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore" Version="8.0.0" />
    <PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="8.0.0" />
    <PackageReference Include="Microsoft.AspNetCore.Identity.UI" Version="8.0.0" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="8.0.0" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="8.0.0" />
    <PackageReference Include="Swashbuckle.AspNetCore" Version="9.0.1" />
  </ItemGroup>
</Project>
```

### Step 3: Install Entity Framework Tools

```bash
# Install EF Core CLI tools globally
dotnet tool install --global dotnet-ef

# Restore packages
dotnet restore
```

## Understanding the Architecture

### Project Structure
```
BlazorTutorial/
├── Areas/                  # Identity UI areas
├── Controllers/            # API Controllers
├── Data/                   # DbContext and migrations
├── Models/                 # Entity models and DTOs
├── Pages/                  # Blazor pages/components
├── Services/               # Business logic layer
├── Shared/                 # Shared Blazor components
├── wwwroot/               # Static files (CSS, JS, images)
├── Program.cs             # Application configuration
└── appsettings.json       # Configuration settings
```

### Architecture Layers

1. **Presentation Layer** - Blazor Server components and pages
2. **API Layer** - Web API controllers for external access
3. **Service Layer** - Business logic and data access services
4. **Data Layer** - Entity Framework Core and database

## Database Configuration

### Step 1: Update Connection String

In `appsettings.json`:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BlazorTutorialDb;Trusted_Connection=true;MultipleActiveResultSets=true"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*"
}
```

### Step 2: Configure Services in Program.cs

```csharp
using Microsoft.AspNetCore.Components;
using Microsoft.AspNetCore.Components.Web;
using Microsoft.AspNetCore.Components.Authorization;
using Microsoft.AspNetCore.Identity;
using Microsoft.AspNetCore.Identity.UI;
using Microsoft.EntityFrameworkCore;
using BlazorTutorial.Areas.Identity;
using BlazorTutorial.Data;
using BlazorTutorial.Services;

var builder = WebApplication.CreateBuilder(args);

// Add services to the container.
var connectionString = builder.Configuration.GetConnectionString("DefaultConnection") 
    ?? throw new InvalidOperationException("Connection string 'DefaultConnection' not found.");

builder.Services.AddDbContext<ApplicationDbContext>(options =>
    options.UseSqlServer(connectionString));

builder.Services.AddDatabaseDeveloperPageExceptionFilter();

builder.Services.AddDefaultIdentity<IdentityUser>(options => {
    options.SignIn.RequireConfirmedAccount = false; // Simplified for tutorial
    options.Password.RequireDigit = true;
    options.Password.RequiredLength = 6;
    options.Password.RequireNonAlphanumeric = false;
    options.Password.RequireUppercase = false;
    options.Password.RequireLowercase = false;
})
    .AddEntityFrameworkStores<ApplicationDbContext>();

builder.Services.AddRazorPages();
builder.Services.AddServerSideBlazor();

// Add API controllers
builder.Services.AddControllers();

// Add API documentation (Swagger)
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen(c =>
{
    c.SwaggerDoc("v1", new Microsoft.OpenApi.Models.OpenApiInfo 
    { 
        Title = "Blazor Tutorial API", 
        Version = "v1",
        Description = "A comprehensive ASP.NET Core Blazor Server tutorial API"
    });
});

builder.Services.AddScoped<AuthenticationStateProvider, RevalidatingIdentityAuthenticationStateProvider<IdentityUser>>();

// Register our services
builder.Services.AddScoped<IProductService, ProductService>();

var app = builder.Build();

// Configure the HTTP request pipeline.
if (app.Environment.IsDevelopment())
{
    app.UseMigrationsEndPoint();
    
    // Enable Swagger in development
    app.UseSwagger();
    app.UseSwaggerUI(c =>
    {
        c.SwaggerEndpoint("/swagger/v1/swagger.json", "Blazor Tutorial API V1");
        c.RoutePrefix = "swagger"; // Access at /swagger
    });
}
else
{
    app.UseExceptionHandler("/Error");
    app.UseHsts();
}

app.UseHttpsRedirection();
app.UseStaticFiles();
app.UseRouting();
app.UseAuthorization();

app.MapControllers();
app.MapRazorPages();
app.MapBlazorHub();
app.MapFallbackToPage("/_Host");

app.Run();
```

## Models and Entity Framework

### Step 1: Create Entity Models

**Models/Category.cs**
```csharp
using System.ComponentModel.DataAnnotations;

namespace BlazorTutorial.Models
{
    public class Category
    {
        public int Id { get; set; }
        
        [Required]
        [StringLength(50)]
        public string Name { get; set; } = string.Empty;
        
        [StringLength(200)]
        public string Description { get; set; } = string.Empty;
        
        public DateTime CreatedDate { get; set; } = DateTime.Now;
        
        public bool IsActive { get; set; } = true;
        
        // Navigation property
        public virtual ICollection<Product> Products { get; set; } = new List<Product>();
    }
}
```

**Models/Product.cs**
```csharp
using System.ComponentModel.DataAnnotations;

namespace BlazorTutorial.Models
{
    public class Product
    {
        public int Id { get; set; }
        
        [Required]
        [StringLength(100)]
        public string Name { get; set; } = string.Empty;
        
        [StringLength(500)]
        public string Description { get; set; } = string.Empty;
        
        [Required]
        [Range(0.01, double.MaxValue, ErrorMessage = "Price must be greater than 0")]
        public decimal Price { get; set; }
        
        [Required]
        [Range(0, int.MaxValue, ErrorMessage = "Stock quantity cannot be negative")]
        public int StockQuantity { get; set; }
        
        [StringLength(50)]
        public string Category { get; set; } = string.Empty;
        
        // Foreign key for Category
        public int? CategoryId { get; set; }
        
        // Navigation property
        public virtual Category? CategoryNavigation { get; set; }
        
        public DateTime CreatedDate { get; set; } = DateTime.Now;
        
        public DateTime UpdatedDate { get; set; } = DateTime.Now;
        
        public bool IsActive { get; set; } = true;
    }
}
```

### Step 2: Create DTOs (Data Transfer Objects)

**Models/ProductDto.cs**
```csharp
using System.ComponentModel.DataAnnotations;

namespace BlazorTutorial.Models
{
    public class ProductDto
    {
        public int Id { get; set; }
        public string Name { get; set; } = string.Empty;
        public string Description { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public int StockQuantity { get; set; }
        public string Category { get; set; } = string.Empty;
        public int? CategoryId { get; set; }
        public string CategoryName { get; set; } = string.Empty;
        public bool IsActive { get; set; } = true;
    }

    public class CreateProductDto
    {
        [Required]
        [StringLength(100)]
        public string Name { get; set; } = string.Empty;
        
        [StringLength(500)]
        public string Description { get; set; } = string.Empty;
        
        [Required]
        [Range(0.01, double.MaxValue)]
        public decimal Price { get; set; }
        
        [Required]
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        [StringLength(50)]
        public string Category { get; set; } = string.Empty;
        
        public int? CategoryId { get; set; }
    }

    public class UpdateProductDto
    {
        [Required]
        [StringLength(100)]
        public string Name { get; set; } = string.Empty;
        
        [StringLength(500)]
        public string Description { get; set; } = string.Empty;
        
        [Required]
        [Range(0.01, double.MaxValue)]
        public decimal Price { get; set; }
        
        [Required]
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        [StringLength(50)]
        public string Category { get; set; } = string.Empty;
        
        public int? CategoryId { get; set; }
        
        public bool IsActive { get; set; } = true;
    }
}
```

### Step 3: Update DbContext

**Data/ApplicationDbContext.cs**
```csharp
using Microsoft.AspNetCore.Identity.EntityFrameworkCore;
using Microsoft.EntityFrameworkCore;
using BlazorTutorial.Models;

namespace BlazorTutorial.Data;

public class ApplicationDbContext : IdentityDbContext
{
    public ApplicationDbContext(DbContextOptions<ApplicationDbContext> options)
        : base(options)
    {
    }

    // DbSets for our entities
    public DbSet<Product> Products { get; set; }
    public DbSet<Category> Categories { get; set; }

    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        base.OnModelCreating(modelBuilder);

        // Configure Product entity
        modelBuilder.Entity<Product>(entity =>
        {
            entity.HasKey(e => e.Id);
            entity.Property(e => e.Name).IsRequired().HasMaxLength(100);
            entity.Property(e => e.Description).HasMaxLength(500);
            entity.Property(e => e.Price).HasColumnType("decimal(18,2)");
            entity.Property(e => e.Category).HasMaxLength(50);
            entity.Property(e => e.CreatedDate).HasDefaultValueSql("GETDATE()");
            entity.Property(e => e.UpdatedDate).HasDefaultValueSql("GETDATE()");
            
            // Configure relationship with Category
            entity.HasOne(p => p.CategoryNavigation)
                  .WithMany(c => c.Products)
                  .HasForeignKey(p => p.CategoryId)
                  .OnDelete(DeleteBehavior.SetNull);
        });

        // Configure Category entity
        modelBuilder.Entity<Category>(entity =>
        {
            entity.HasKey(e => e.Id);
            entity.Property(e => e.Name).IsRequired().HasMaxLength(50);
            entity.Property(e => e.Description).HasMaxLength(200);
            entity.Property(e => e.CreatedDate).HasDefaultValueSql("GETDATE()");
        });

        // Seed data
        modelBuilder.Entity<Category>().HasData(
            new Category { Id = 1, Name = "Electronics", Description = "Electronic devices and accessories" },
            new Category { Id = 2, Name = "Clothing", Description = "Apparel and fashion items" },
            new Category { Id = 3, Name = "Books", Description = "Books and educational materials" },
            new Category { Id = 4, Name = "Home & Garden", Description = "Home improvement and gardening supplies" }
        );

        modelBuilder.Entity<Product>().HasData(
            new Product { Id = 1, Name = "Laptop", Description = "High-performance laptop", Price = 999.99m, StockQuantity = 50, Category = "Electronics", CategoryId = 1 },
            new Product { Id = 2, Name = "T-Shirt", Description = "Cotton t-shirt", Price = 19.99m, StockQuantity = 100, Category = "Clothing", CategoryId = 2 },
            new Product { Id = 3, Name = "Programming Book", Description = "Learn ASP.NET Core", Price = 49.99m, StockQuantity = 25, Category = "Books", CategoryId = 3 }
        );
    }
}
```

## Services Layer

### Create Product Service

**Services/ProductService.cs**
```csharp
using BlazorTutorial.Data;
using BlazorTutorial.Models;
using Microsoft.EntityFrameworkCore;

namespace BlazorTutorial.Services
{
    public interface IProductService
    {
        Task<IEnumerable<ProductDto>> GetAllProductsAsync();
        Task<ProductDto?> GetProductByIdAsync(int id);
        Task<ProductDto> CreateProductAsync(CreateProductDto createProductDto);
        Task<ProductDto?> UpdateProductAsync(int id, UpdateProductDto updateProductDto);
        Task<bool> DeleteProductAsync(int id);
        Task<IEnumerable<Category>> GetCategoriesAsync();
    }

    public class ProductService : IProductService
    {
        private readonly ApplicationDbContext _context;

        public ProductService(ApplicationDbContext context)
        {
            _context = context;
        }

        public async Task<IEnumerable<ProductDto>> GetAllProductsAsync()
        {
            return await _context.Products
                .Include(p => p.CategoryNavigation)
                .Where(p => p.IsActive)
                .Select(p => new ProductDto
                {
                    Id = p.Id,
                    Name = p.Name,
                    Description = p.Description,
                    Price = p.Price,
                    StockQuantity = p.StockQuantity,
                    Category = p.Category,
                    CategoryId = p.CategoryId,
                    CategoryName = p.CategoryNavigation != null ? p.CategoryNavigation.Name : "",
                    IsActive = p.IsActive
                })
                .ToListAsync();
        }

        public async Task<ProductDto?> GetProductByIdAsync(int id)
        {
            var product = await _context.Products
                .Include(p => p.CategoryNavigation)
                .FirstOrDefaultAsync(p => p.Id == id && p.IsActive);

            if (product == null) return null;

            return new ProductDto
            {
                Id = product.Id,
                Name = product.Name,
                Description = product.Description,
                Price = product.Price,
                StockQuantity = product.StockQuantity,
                Category = product.Category,
                CategoryId = product.CategoryId,
                CategoryName = product.CategoryNavigation?.Name ?? "",
                IsActive = product.IsActive
            };
        }

        public async Task<ProductDto> CreateProductAsync(CreateProductDto createProductDto)
        {
            var category = await _context.Categories.FindAsync(createProductDto.CategoryId);
            
            var product = new Product
            {
                Name = createProductDto.Name,
                Description = createProductDto.Description,
                Price = createProductDto.Price,
                StockQuantity = createProductDto.StockQuantity,
                Category = createProductDto.Category,
                CategoryId = createProductDto.CategoryId,
                CreatedDate = DateTime.Now,
                UpdatedDate = DateTime.Now,
                IsActive = true
            };

            _context.Products.Add(product);
            await _context.SaveChangesAsync();

            return new ProductDto
            {
                Id = product.Id,
                Name = product.Name,
                Description = product.Description,
                Price = product.Price,
                StockQuantity = product.StockQuantity,
                Category = product.Category,
                CategoryId = product.CategoryId,
                CategoryName = category?.Name ?? "",
                IsActive = product.IsActive
            };
        }

        public async Task<ProductDto?> UpdateProductAsync(int id, UpdateProductDto updateProductDto)
        {
            var product = await _context.Products.FindAsync(id);
            if (product == null || !product.IsActive) return null;

            var category = await _context.Categories.FindAsync(updateProductDto.CategoryId);

            product.Name = updateProductDto.Name;
            product.Description = updateProductDto.Description;
            product.Price = updateProductDto.Price;
            product.StockQuantity = updateProductDto.StockQuantity;
            product.Category = updateProductDto.Category;
            product.CategoryId = updateProductDto.CategoryId;
            product.IsActive = updateProductDto.IsActive;
            product.UpdatedDate = DateTime.Now;

            await _context.SaveChangesAsync();

            return new ProductDto
            {
                Id = product.Id,
                Name = product.Name,
                Description = product.Description,
                Price = product.Price,
                StockQuantity = product.StockQuantity,
                Category = product.Category,
                CategoryId = product.CategoryId,
                CategoryName = category?.Name ?? "",
                IsActive = product.IsActive
            };
        }

        public async Task<bool> DeleteProductAsync(int id)
        {
            var product = await _context.Products.FindAsync(id);
            if (product == null) return false;

            // Soft delete
            product.IsActive = false;
            product.UpdatedDate = DateTime.Now;
            await _context.SaveChangesAsync();

            return true;
        }

        public async Task<IEnumerable<Category>> GetCategoriesAsync()
        {
            return await _context.Categories
                .Where(c => c.IsActive)
                .OrderBy(c => c.Name)
                .ToListAsync();
        }
    }
}
```

## API Controllers

### Create Products Controller

**Controllers/ProductsController.cs**
```csharp
using Microsoft.AspNetCore.Mvc;
using Microsoft.AspNetCore.Authorization;
using BlazorTutorial.Models;
using BlazorTutorial.Services;

namespace BlazorTutorial.Controllers
{
    [ApiController]
    [Route("api/[controller]")]
    [Authorize] // Require authentication for all endpoints
    public class ProductsController : ControllerBase
    {
        private readonly IProductService _productService;
        private readonly ILogger<ProductsController> _logger;

        public ProductsController(IProductService productService, ILogger<ProductsController> logger)
        {
            _productService = productService;
            _logger = logger;
        }

        /// <summary>
        /// Get all products
        /// </summary>
        /// <returns>List of products</returns>
        [HttpGet]
        public async Task<ActionResult<IEnumerable<ProductDto>>> GetProducts()
        {
            try
            {
                var products = await _productService.GetAllProductsAsync();
                return Ok(products);
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error retrieving products");
                return StatusCode(500, "An error occurred while retrieving products");
            }
        }

        /// <summary>
        /// Get a specific product by ID
        /// </summary>
        /// <param name="id">Product ID</param>
        /// <returns>Product details</returns>
        [HttpGet("{id}")]
        public async Task<ActionResult<ProductDto>> GetProduct(int id)
        {
            try
            {
                var product = await _productService.GetProductByIdAsync(id);
                if (product == null)
                {
                    return NotFound($"Product with ID {id} not found");
                }
                return Ok(product);
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error retrieving product {ProductId}", id);
                return StatusCode(500, "An error occurred while retrieving the product");
            }
        }

        /// <summary>
        /// Create a new product
        /// </summary>
        /// <param name="createProductDto">Product data</param>
        /// <returns>Created product</returns>
        [HttpPost]
        public async Task<ActionResult<ProductDto>> CreateProduct(CreateProductDto createProductDto)
        {
            try
            {
                if (!ModelState.IsValid)
                {
                    return BadRequest(ModelState);
                }

                var product = await _productService.CreateProductAsync(createProductDto);
                return CreatedAtAction(nameof(GetProduct), new { id = product.Id }, product);
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error creating product");
                return StatusCode(500, "An error occurred while creating the product");
            }
        }

        /// <summary>
        /// Update an existing product
        /// </summary>
        /// <param name="id">Product ID</param>
        /// <param name="updateProductDto">Updated product data</param>
        /// <returns>Updated product</returns>
        [HttpPut("{id}")]
        public async Task<ActionResult<ProductDto>> UpdateProduct(int id, UpdateProductDto updateProductDto)
        {
            try
            {
                if (!ModelState.IsValid)
                {
                    return BadRequest(ModelState);
                }

                var product = await _productService.UpdateProductAsync(id, updateProductDto);
                if (product == null)
                {
                    return NotFound($"Product with ID {id} not found");
                }

                return Ok(product);
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error updating product {ProductId}", id);
                return StatusCode(500, "An error occurred while updating the product");
            }
        }

        /// <summary>
        /// Delete a product (soft delete)
        /// </summary>
        /// <param name="id">Product ID</param>
        /// <returns>Success status</returns>
        [HttpDelete("{id}")]
        public async Task<ActionResult> DeleteProduct(int id)
        {
            try
            {
                var result = await _productService.DeleteProductAsync(id);
                if (!result)
                {
                    return NotFound($"Product with ID {id} not found");
                }

                return NoContent();
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error deleting product {ProductId}", id);
                return StatusCode(500, "An error occurred while deleting the product");
            }
        }
    }

    [ApiController]
    [Route("api/[controller]")]
    public class CategoriesController : ControllerBase
    {
        private readonly IProductService _productService;
        private readonly ILogger<CategoriesController> _logger;

        public CategoriesController(IProductService productService, ILogger<CategoriesController> logger)
        {
            _productService = productService;
            _logger = logger;
        }

        /// <summary>
        /// Get all categories
        /// </summary>
        /// <returns>List of categories</returns>
        [HttpGet]
        public async Task<ActionResult<IEnumerable<Category>>> GetCategories()
        {
            try
            {
                var categories = await _productService.GetCategoriesAsync();
                return Ok(categories);
            }
            catch (Exception ex)
            {
                _logger.LogError(ex, "Error retrieving categories");
                return StatusCode(500, "An error occurred while retrieving categories");
            }
        }
    }
}
```

## Database Migration

### Create and Apply Migrations

```bash
# Add initial migration
dotnet ef migrations add InitialCreate

# Update database
dotnet ef database update
```

## Running the Application

### Step 1: Build and Run

```bash
# Build the project
dotnet build

# Run the application
dotnet run
```

### Step 2: Access the Application

1. **Web Application**: `https://localhost:7xxx` (port may vary)
2. **API Documentation**: `https://localhost:7xxx/swagger`

### Step 3: Test Authentication

1. Click "Register" to create a new account
2. Fill in email and password
3. Click "Register" and you'll be automatically logged in
4. Navigate to the "Products" page to test CRUD operations

## API Testing

### Using Swagger UI

1. Navigate to `/swagger` in your browser
2. Click "Authorize" and login with your credentials
3. Test the API endpoints:
   - `GET /api/products` - Get all products
   - `GET /api/products/{id}` - Get specific product
   - `POST /api/products` - Create new product
   - `PUT /api/products/{id}` - Update product
   - `DELETE /api/products/{id}` - Delete product

### Using curl or Postman

```bash
# Get all products (requires authentication)
curl -X GET "https://localhost:7xxx/api/products" \
  -H "Authorization: Bearer YOUR_TOKEN"

# Create a new product
curl -X POST "https://localhost:7xxx/api/products" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_TOKEN" \
  -d '{
    "name": "New Product",
    "description": "Product description",
    "price": 29.99,
    "stockQuantity": 100,
    "category": "Electronics",
    "categoryId": 1
  }'
```

## Best Practices

### 1. Repository Pattern
Consider implementing the Repository pattern for better testability:

```csharp
public interface IRepository<T> where T : class
{
    Task<IEnumerable<T>> GetAllAsync();
    Task<T?> GetByIdAsync(int id);
    Task<T> CreateAsync(T entity);
    Task<T?> UpdateAsync(T entity);
    Task<bool> DeleteAsync(int id);
}
```

### 2. Error Handling
Implement global error handling:

```csharp
public class GlobalExceptionMiddleware
{
    private readonly RequestDelegate _next;
    private readonly ILogger<GlobalExceptionMiddleware> _logger;

    public GlobalExceptionMiddleware(RequestDelegate next, ILogger<GlobalExceptionMiddleware> logger)
    {
        _next = next;
        _logger = logger;
    }

    public async Task InvokeAsync(HttpContext context)
    {
        try
        {
            await _next(context);
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "An unhandled exception occurred");
            await HandleExceptionAsync(context, ex);
        }
    }

    private static async Task HandleExceptionAsync(HttpContext context, Exception exception)
    {
        context.Response.StatusCode = 500;
        context.Response.ContentType = "application/json";

        var response = new
        {
            error = "An error occurred while processing your request."
        };

        await context.Response.WriteAsync(JsonSerializer.Serialize(response));
    }
}
```

### 3. Validation
Use FluentValidation for complex validation scenarios:

```bash
dotnet add package FluentValidation.AspNetCore
```

```csharp
public class CreateProductDtoValidator : AbstractValidator<CreateProductDto>
{
    public CreateProductDtoValidator()
    {
        RuleFor(x => x.Name)
            .NotEmpty().WithMessage("Product name is required")
            .Length(1, 100).WithMessage("Product name must be between 1 and 100 characters");

        RuleFor(x => x.Price)
            .GreaterThan(0).WithMessage("Price must be greater than 0");

        RuleFor(x => x.StockQuantity)
            .GreaterThanOrEqualTo(0).WithMessage("Stock quantity cannot be negative");
    }
}
```

### 4. Caching
Implement caching for better performance:

```csharp
public class CachedProductService : IProductService
{
    private readonly IProductService _productService;
    private readonly IMemoryCache _cache;
    private const int CacheExpirationMinutes = 30;

    public CachedProductService(IProductService productService, IMemoryCache cache)
    {
        _productService = productService;
        _cache = cache;
    }

    public async Task<IEnumerable<ProductDto>> GetAllProductsAsync()
    {
        const string cacheKey = "all_products";
        
        if (_cache.TryGetValue(cacheKey, out IEnumerable<ProductDto>? cachedProducts))
        {
            return cachedProducts!;
        }

        var products = await _productService.GetAllProductsAsync();
        _cache.Set(cacheKey, products, TimeSpan.FromMinutes(CacheExpirationMinutes));
        
        return products;
    }
}
```

## Common Issues and Solutions

### 1. Migration Issues

**Problem**: "Cannot create migrations"
**Solution**: Ensure Entity Framework tools are installed and the connection string is correct.

```bash
dotnet tool install --global dotnet-ef
dotnet ef migrations add MigrationName
```

### 2. Authentication Issues

**Problem**: "User not authenticated"
**Solution**: Check that the user is logged in and the `[Authorize]` attribute is properly applied.

### 3. Database Connection Issues

**Problem**: "Cannot connect to SQL Server"
**Solution**: 
- Verify SQL Server is running
- Check connection string
- Ensure LocalDB is installed

### 4. Build Errors

**Problem**: "Cannot resolve service" errors
**Solution**: Ensure all services are registered in `Program.cs`:

```csharp
builder.Services.AddScoped<IProductService, ProductService>();
```

### 5. Blazor Component Issues

**Problem**: "Component not updating"
**Solution**: Call `StateHasChanged()` after data operations:

```csharp
private async Task LoadData()
{
    products = await ProductService.GetAllProductsAsync();
    StateHasChanged(); // Force UI update
}
```

## Conclusion

This tutorial demonstrates a complete ASP.NET Core Blazor Server application with:

- ✅ Entity Framework Core with SQL Server
- ✅ User authentication and authorization
- ✅ CRUD operations with proper validation
- ✅ RESTful API endpoints
- ✅ Interactive Blazor components
- ✅ Responsive UI with Bootstrap
- ✅ Best practices and error handling

### Next Steps

1. **Add unit tests** using xUnit and Moq
2. **Implement logging** with Serilog
3. **Add file upload** functionality
4. **Implement real-time updates** with SignalR
5. **Deploy to Azure** or another cloud provider
6. **Add more complex business logic**
7. **Implement role-based authorization**

### Additional Resources

- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Blazor Documentation](https://docs.microsoft.com/en-us/aspnet/core/blazor/)
- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)
- [ASP.NET Core Identity Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity/)

Happy coding! 🚀
