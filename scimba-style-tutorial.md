# Complete Course: Full-Stack .NET Development
## Building Industry-Standard Web Applications with ASP.NET, Blazor & MudBlazor

<div style="text-align: center; margin: 50px 0;">
<h3>A Comprehensive Interactive Course</h3>
<p><strong>Course Updated for .NET 9 SDK and Latest Tooling</strong></p>
<p><em>From Backend APIs to Frontend Components</em></p>
</div>

<div style="page-break-after: always;"></div>

---

## 🎯 Course Overview

<div style="background-color: #f8f9fa; padding: 20px; border-left: 4px solid #007acc; margin: 20px 0;">

Learn backend and frontend development using Microsoft's modern .NET stack. Build real-world applications from database to UI, covering everything essential for industry-standard software development.

**What You'll Build:** A complete task management application with authentication, CRUD operations, and modern UI components.

**Course Updated for:** .NET 9 SDK and latest tooling

**Prerequisites:** Basic programming knowledge in C# or similar language  
**Duration:** 40+ hours of content  
**Level:** Beginner to Intermediate  

</div>

<div style="page-break-after: always;"></div>

---

## 📋 Table of Contents

<div style="font-size: 14px; line-height: 1.6;">

### **Part 1: ASP.NET Core Fundamentals**
#### Module 1.1: Getting Started with ASP.NET Core
- [Section 1.1.1: Setting up your development environment](#section-111-setting-up-your-development-environment-visual-studiovs-code)
- [Section 1.1.2: Creating your first ASP.NET Core Web API project](#section-112-creating-your-first-aspnet-core-web-api-project)
- [Section 1.1.3: Understanding the project structure and startup configuration](#section-113-understanding-the-project-structure-and-startup-configuration)
- [Section 1.1.4: Running and testing your first API endpoint](#section-114-running-and-testing-your-first-api-endpoint)
- [Challenge 1.1: Create a "Hello World" API with custom routing](#challenge-11-create-a-hello-world-api-with-custom-routing)

#### Module 1.2: Controllers and Routing
- [Section 1.2.1: What are controllers and why do we need them?](#section-121-what-are-controllers-and-why-do-we-need-them)
- [Section 1.2.2: Creating your first controller and action methods](#section-122-creating-your-first-controller-and-action-methods)
- [Section 1.2.3: Understanding HTTP verbs (GET, POST, PUT, DELETE)](#section-123-understanding-http-verbs-get-post-put-delete)
- [Section 1.2.4: Route parameters and query strings](#section-124-route-parameters-and-query-strings)
- [Section 1.2.5: Model binding and validation](#section-125-model-binding-and-validation)
- [Challenge 1.2: Build a complete CRUD controller](#challenge-12-build-a-complete-crud-controller)

#### Module 1.3: Dependency Injection and Services
- [Section 1.3.1: What is dependency injection and why use it?](#section-131-what-is-dependency-injection-and-why-use-it)
- [Section 1.3.2: Creating and registering services](#section-132-creating-and-registering-services)
- [Section 1.3.3: Service lifetimes (Singleton, Scoped, Transient)](#section-133-service-lifetimes-singleton-scoped-transient)
- [Section 1.3.4: Injecting services into controllers](#section-134-injecting-services-into-controllers)
- [Section 1.3.5: Creating business logic services](#section-135-creating-business-logic-services)
- [Challenge 1.3: Create a service layer for your API](#challenge-13-create-a-service-layer-for-your-api)

### **Part 2: Data Access and Entity Framework**
#### Module 2.1: Data Models and DTOs
- [Section 2.1.1: Designing your data models](#section-211-designing-your-data-models)
- [Section 2.1.2: Entity relationships (One-to-Many, Many-to-Many)](#section-212-entity-relationships-one-to-many-many-to-many)
- [Section 2.1.3: Data Transfer Objects (DTOs) and why use them](#section-213-data-transfer-objects-dtos-and-why-use-them)
- [Section 2.1.4: AutoMapper for object mapping](#section-214-automapper-for-object-mapping)
- [Challenge 2.1: Design your task management data model](#challenge-21-design-your-task-management-data-model)

#### Module 2.2: Entity Framework Core Setup
- [Section 2.2.1: Setting up SQL Server (LocalDB for development)](#section-221-setting-up-sql-server-localdb-for-development)
- [Section 2.2.2: Connection strings and configuration](#section-222-connection-strings-and-configuration)
- [Section 2.2.3: Your first database migration](#section-223-your-first-database-migration)
- [Section 2.2.4: Seeding initial data](#section-224-seeding-initial-data)
- [Section 2.2.5: Using SQL Server Management Studio](#section-225-using-sql-server-management-studio)
- [Challenge 2.2: Set up your database](#challenge-22-set-up-your-database)

#### Module 2.3: CRUD Operations with Entity Framework
- [Section 2.3.1: Reading data - Find, Where, Include](#section-231-reading-data---find-where-include)
- [Section 2.3.2: Creating new records and handling relationships](#section-232-creating-new-records-and-handling-relationships)
- [Section 2.3.3: Updating existing records (tracking vs non-tracking)](#section-233-updating-existing-records-tracking-vs-non-tracking)
- [Section 2.3.4: Deleting records and cascade behaviors](#section-234-deleting-records-and-cascade-behaviors)
- [Section 2.3.5: Async/await patterns with EF Core](#section-235-asyncawait-patterns-with-ef-core)
- [Challenge 2.3: Build your data access layer](#challenge-23-build-your-data-access-layer)

#### Module 2.4: Advanced Entity Framework
- [Section 2.4.1: Querying with LINQ - filtering, sorting, grouping](#section-241-querying-with-linq---filtering-sorting-grouping)
- [Section 2.4.2: Eager loading, lazy loading, and explicit loading](#section-242-eager-loading-lazy-loading-and-explicit-loading)
- [Section 2.4.3: Raw SQL queries when needed](#section-243-raw-sql-queries-when-needed)
- [Section 2.4.4: Database transactions and error handling](#section-244-database-transactions-and-error-handling)
- [Challenge 2.4: Optimize your queries](#challenge-24-optimize-your-queries)

#### Module 2.5: CRUD Operations with Entity Framework
- [Section 2.5.1: The Repository Pattern in Practice](#section-251-the-repository-pattern-in-practice)
- [Section 2.5.2: Specialized Repository Implementation](#section-252-specialized-repository-implementation)
- [Section 2.5.3: Advanced CRUD with Business Logic](#section-253-advanced-crud-with-business-logic)

### **Part 3: Authentication and Authorization**
#### Module 3.1: ASP.NET Core Identity
- [Section 3.1.1: Understanding authentication vs authorization](#section-311-understanding-authentication-vs-authorization)
- [Section 3.1.2: Setting up ASP.NET Core Identity](#section-312-setting-up-aspnet-core-identity)
- [Section 3.1.3: User registration and login flows](#section-313-user-registration-and-login-flows)
- [Section 3.1.4: Password policies and security best practices](#section-314-password-policies-and-security-best-practices)
- [Challenge 3.1: Implement user registration](#challenge-31-implement-user-registration)

#### Module 3.2: Authorization Strategies
- [Section 3.2.1: Role-based authorization](#section-321-role-based-authorization)
- [Section 3.2.2: Claims-based authorization](#section-322-claims-based-authorization)
- [Section 3.2.3: Policy-based authorization](#section-323-policy-based-authorization)
- [Section 3.2.4: Protecting API endpoints with [Authorize]](#section-324-protecting-api-endpoints-with-authorize)
- [Challenge 3.2: Implement role-based access](#challenge-32-implement-role-based-access)

#### Module 3.3: JWT Token Authentication
- [Section 3.3.1: What are JWT tokens and when to use them](#section-331-what-are-jwt-tokens-and-when-to-use-them)
- [Section 3.3.2: Configuring JWT authentication in ASP.NET Core](#section-332-configuring-jwt-authentication-in-aspnet-core)
- [Section 3.3.3: Login endpoint returning JWT tokens](#section-333-login-endpoint-returning-jwt-tokens)
- [Section 3.3.4: Validating JWT tokens in API calls](#section-334-validating-jwt-tokens-in-api-calls)
- [Challenge 3.3: Build JWT authentication](#challenge-33-build-jwt-authentication)

### **Part 4: Frontend with Blazor**
#### Module 4.1: Blazor Fundamentals
- [Section 4.1.1: What is Blazor and why choose it?](#section-411-what-is-blazor-and-why-choose-it)
- [Section 4.1.2: Blazor Server vs Blazor WebAssembly - when to use which](#section-412-blazor-server-vs-blazor-webassembly---when-to-use-which)
- [Section 4.1.3: Creating your first Blazor Server application](#section-413-creating-your-first-blazor-server-application)
- [Section 4.1.4: Understanding components and the component lifecycle](#section-414-understanding-components-and-the-component-lifecycle)
- [Challenge 4.1: Create your first Blazor component](#challenge-41-create-your-first-blazor-component)

#### Module 4.2: Component Development
- [Section 4.2.1: Component parameters and data binding](#section-421-component-parameters-and-data-binding)
- [Section 4.2.2: Event handling and @onclick, @onchange](#section-422-event-handling-and-onclick-onchange)
- [Section 4.2.3: Forms and validation in Blazor](#section-423-forms-and-validation-in-blazor)
- [Section 4.2.4: State management and cascading parameters](#section-424-state-management-and-cascading-parameters)
- [Challenge 4.2: Build interactive components](#challenge-42-build-interactive-components)

#### Module 4.3: Calling APIs from Blazor
- [Section 4.3.1: HttpClient setup and dependency injection](#section-431-httpclient-setup-and-dependency-injection)
- [Section 4.3.2: Making HTTP requests (GET, POST, PUT, DELETE)](#section-432-making-http-requests-get-post-put-delete)
- [Section 4.3.3: Handling loading states and errors](#section-433-handling-loading-states-and-errors)
- [Section 4.3.4: Working with JSON serialization](#section-434-working-with-json-serialization)
- [Challenge 4.3: Connect your UI to your API](#challenge-43-connect-your-ui-to-your-api)

### **Part 5: UI Components with MudBlazor**
#### Module 5.1: MudBlazor Setup and Basics
- [Section 5.1.1: What is MudBlazor and why use it?](#section-511-what-is-mudblazor-and-why-use-it)
- [Section 5.1.2: Installing and configuring MudBlazor](#section-512-installing-and-configuring-mudblazor)
- [Section 5.1.3: Theming and customization](#section-513-theming-and-customization)
- [Section 5.1.4: Basic components (buttons, cards, typography)](#section-514-basic-components-buttons-cards-typography)
- [Challenge 5.1: Style your application](#challenge-51-style-your-application)

#### Module 5.2: Data Display Components
- [Section 5.2.1: Tables and data grids](#section-521-tables-and-data-grids)
- [Section 5.2.2: Charts and data visualization](#section-522-charts-and-data-visualization)
- [Section 5.2.3: Lists and repeating data](#section-523-lists-and-repeating-data)
- [Section 5.2.4: Pagination and virtual scrolling](#section-524-pagination-and-virtual-scrolling)
- [Challenge 5.2: Build a data dashboard](#challenge-52-build-a-data-dashboard)

#### Module 5.3: Forms and User Input
- [Section 5.3.1: Form components and validation](#section-531-form-components-and-validation)
- [Section 5.3.2: Date pickers, selects, and advanced inputs](#section-532-date-pickers-selects-and-advanced-inputs)
- [Section 5.3.3: File uploads and handling](#section-533-file-uploads-and-handling)
- [Section 5.3.4: Dialogs and confirmations](#section-534-dialogs-and-confirmations)
- [Challenge 5.3: Create comprehensive forms](#challenge-53-create-comprehensive-forms)

### **Part 6: Advanced Topics and Best Practices**
#### Module 6.1: Error Handling and Logging
- [Section 6.1.1: Global exception handling](#section-611-global-exception-handling)
- [Section 6.1.2: Structured logging with Serilog](#section-612-structured-logging-with-serilog)
- [Section 6.1.3: Health checks and monitoring](#section-613-health-checks-and-monitoring)
- [Section 6.1.4: User-friendly error pages](#section-614-user-friendly-error-pages)
- [Challenge 6.1: Implement comprehensive error handling](#challenge-61-implement-comprehensive-error-handling)

#### Module 6.2: Testing
- [Section 6.2.1: Unit testing controllers and services](#section-621-unit-testing-controllers-and-services)
- [Section 6.2.2: Integration testing with WebApplicationFactory](#section-622-integration-testing-with-webapplicationfactory)
- [Section 6.2.3: Testing Blazor components](#section-623-testing-blazor-components)
- [Section 6.2.4: Mocking dependencies](#section-624-mocking-dependencies)
- [Challenge 6.2: Add comprehensive tests](#challenge-62-add-comprehensive-tests)

#### Module 6.3: Performance and Deployment
- [Section 6.3.1: Caching strategies](#section-631-caching-strategies)
- [Section 6.3.2: Database optimization](#section-632-database-optimization)
- [Section 6.3.3: Preparing for production deployment](#section-633-preparing-for-production-deployment)
- [Section 6.3.4: CI/CD with GitHub Actions](#section-634-cicd-with-github-actions)
- [Challenge 6.3: Deploy your application](#challenge-63-deploy-your-application)

</div>

<div style="page-break-after: always;"></div>

---

## 💎 C# Essentials for Development

<div style="background-color: #f8f9fa; padding: 20px; border-left: 4px solid #6f42c1; margin: 20px 0;">

Before diving into web development, let's ensure you have a solid understanding of C# fundamentals that are essential for building professional applications. This section covers the core concepts, patterns, and modern C# features you'll use throughout this course.

**Why This Matters:** Understanding these fundamentals will make the rest of the course much easier to follow and help you write better, more maintainable code.

</div>

<div style="page-break-after: always;"></div>

### **Part 0: C# Language Fundamentals**

#### Module 0.1: Modern C# Syntax and Features

Modern C# development has evolved significantly with each version, introducing features that make code more concise, readable, and maintainable. Understanding these features is crucial for following modern .NET development patterns and writing code that aligns with industry standards. The language has moved toward being more functional, with better null safety, pattern matching, and expression-based programming.

##### **Section 0.1.1:** Record Types and Data Models

Record types, introduced in C# 9 and enhanced in later versions, represent a fundamental shift in how we think about data modeling in C#. Unlike traditional classes, records are designed specifically for immutable data containers, making them perfect for DTOs, configuration objects, and value objects in domain-driven design.

When working with web APIs, you'll frequently need to transfer data between different layers of your application. Records provide a clean, concise way to define these data structures while automatically providing value equality, immutability by default, and built-in deconstruction support.

**Basic Record Syntax:**
```csharp
// Simple record declaration
public record Book(int Id, string Title, string Author, int Year);

// Record with additional properties and methods
public record BookDto(string Title, string Author, int Year)
{
    public decimal? Price { get; init; }
    public List<string> Tags { get; init; } = new();
    
    // Records can have methods too
    public bool IsClassic() => Year < 1980;
    
    // Custom ToString override
    public override string ToString() => $"{Title} by {Author} ({Year})";
}

// Record inheritance
public record DigitalBook(string Title, string Author, int Year, string Format) 
    : BookDto(Title, Author, Year);

// Mutable record (use sparingly)
public record MutableBook
{
    public int Id { get; set; }
    public string Title { get; set; } = string.Empty;
    public string Author { get; set; } = string.Empty;
}
```

**Working with Records:**
```csharp
// Creating records
var book = new Book(1, "Clean Code", "Robert Martin", 2008);
var bookDto = new BookDto("The Pragmatic Programmer", "David Thomas", 1999)
{
    Price = 39.99m,
    Tags = { "Programming", "Best Practices" }
};

// Value equality (automatically implemented)
var book1 = new Book(1, "Clean Code", "Robert Martin", 2008);
var book2 = new Book(1, "Clean Code", "Robert Martin", 2008);
Console.WriteLine(book1 == book2); // True - value equality

// Immutable updates with 'with' expression
var updatedBook = book with { Year = 2009 };
Console.WriteLine(book.Year);        // 2008 (original unchanged)
Console.WriteLine(updatedBook.Year); // 2009 (new record created)

// Deconstruction
var (id, title, author, year) = book;
Console.WriteLine($"{title} was written by {author}");
```

**When to Use Records vs Classes:**
- **Use Records for:** DTOs, configuration objects, immutable data, value objects
- **Use Classes for:** Entities with behavior, mutable objects, inheritance hierarchies
- **Use Record Classes for:** When you need reference semantics but want record features

##### **Section 0.1.2:** Nullable Reference Types and Null Safety

Null reference exceptions have historically been one of the most common runtime errors in C# applications. Modern C# addresses this with nullable reference types, which provide compile-time null safety checking. This feature helps catch potential null reference issues before they become runtime problems.

Understanding nullable reference types is essential for modern .NET development because they're enabled by default in new .NET templates. This feature changes how you think about and handle nullability throughout your application, from API contracts to data access layers.

**Nullable Reference Types Configuration:**
```csharp
// Enable in project file
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>net9.0</TargetFramework>
    <Nullable>enable</Nullable>
    <TreatWarningsAsErrors>true</TreatWarningsAsErrors>
  </PropertyGroup>
</Project>
```

**Working with Nullable Types:**
```csharp
// Non-nullable reference types (default)
public class BookService
{
    // This property cannot be null
    public string ServiceName { get; set; } = "Book Service";
    
    // This method parameter cannot be null
    public Book? FindBook(string title)
    {
        // Return null if not found (notice Book? return type)
        return _books.FirstOrDefault(b => b.Title == title);
    }
    
    // This method guarantees non-null return
    public Book GetBookOrDefault(int id)
    {
        return _books.FirstOrDefault(b => b.Id == id) 
               ?? new Book { Id = 0, Title = "Unknown", Author = "Unknown", Year = 0 };
    }
}

// Handling nullable values safely
public class BookController : ControllerBase
{
    private readonly BookService _bookService;
    
    public BookController(BookService bookService)
    {
        _bookService = bookService; // Non-null parameter
    }
    
    [HttpGet("{title}")]
    public ActionResult<Book> GetByTitle(string title)
    {
        // Null-conditional operator
        var book = _bookService.FindBook(title);
        
        // Pattern matching with null check
        return book switch
        {
            null => NotFound($"Book '{title}' not found"),
            _ => Ok(book)
        };
    }
    
    [HttpPost]
    public ActionResult<Book> CreateBook(CreateBookRequest? request)
    {
        // Explicit null check with early return
        if (request is null)
            return BadRequest("Request cannot be null");
        
        // Null-coalescing assignment
        request.Description ??= "No description provided";
        
        // Now we know request is not null
        var book = new Book
        {
            Title = request.Title,
            Author = request.Author,
            Description = request.Description
        };
        
        return CreatedAtAction(nameof(GetByTitle), new { title = book.Title }, book);
    }
}
```

**Null Safety Patterns:**
```csharp
// Null-conditional operators
string? title = book?.Title?.Trim()?.ToUpperInvariant();

// Null-coalescing operators
string displayTitle = book?.Title ?? "Unknown Title";
book.Title ??= "Default Title"; // Assign only if null

// Pattern matching for null checks
if (book is not null && book.Title.Length > 0)
{
    ProcessBook(book);
}

// Null-forgiving operator (use sparingly)
string title = book!.Title; // Tells compiler "I know this isn't null"
```

#### Module 0.2: Advanced C# Concepts

As you become more comfortable with C#, it's important to learn about the advanced features and concepts that can help you write more efficient, maintainable, and robust code. This module covers some of the key advanced topics in C# that are particularly relevant for web development and working with ASP.NET Core.

##### **Section 0.2.1:** Asynchronous Programming with async/await

Asynchronous programming is essential for building responsive and scalable web applications. It allows your application to perform non-blocking operations, such as I/O tasks, without freezing the user interface or wasting system resources.

In C#, asynchronous programming is primarily achieved through the `async` and `await` keywords. These keywords enable you to write asynchronous code that is easy to read and maintain, resembling synchronous code in structure.

**Basic async/await Usage:**
```csharp
public class BookService
{
    private readonly HttpClient _httpClient;
    
    public BookService(HttpClient httpClient)
    {
        _httpClient = httpClient;
    }
    
    // Asynchronous method to fetch data
    public async Task<IEnumerable<Book>> GetBooksAsync()
    {
        // Asynchronously send a GET request
        var response = await _httpClient.GetAsync("api/books");
        
        // Ensure the response is successful
        response.EnsureSuccessStatusCode();
        
        // Asynchronously read and deserialize the response body
        return await response.Content.ReadAsAsync<IEnumerable<Book>>();
    }
}
```

**Key Points about async/await:**
- The `async` keyword is used to mark a method as asynchronous. It can be applied to any method that returns `void`, `Task`, or `Task<T>`.
- The `await` keyword is used to pause the execution of an asynchronous method until the awaited `Task` is complete. It can only be used inside `async` methods.
- When the `await` keyword is applied to a `Task`, the method in which it is used will return control to the caller until the `Task` is complete. This allows other work to be done in the meantime, such as handling UI events or processing other requests.

**Best Practices for Asynchronous Programming:**
- Use asynchronous methods for I/O-bound operations, such as network calls, file access, and database queries.
- Avoid blocking calls (e.g., `Task.Wait()`, `Task.Result`) in asynchronous code, as they can lead to deadlocks and reduce scalability.
- Prefer `ConfigureAwait(false)` in library code to avoid capturing the synchronization context, which can lead to performance issues and deadlocks in certain scenarios.

##### **Section 0.2.2:** Exception Handling and Custom Exceptions

Robust exception handling is crucial for building reliable and maintainable applications. In C#, exceptions are used to signal and handle error conditions that may occur during the execution of a program.

**Basic Exception Handling:**
```csharp
public class BookService
{
    public Book GetBookById(int id)
    {
        try
        {
            // Code that may throw an exception
            return _books.First(b => b.Id == id);
        }
        catch (InvalidOperationException ex)
        {
            // Handle specific exception type
            _logger.LogWarning(ex, "Book with ID {Id} not found", id);
            throw new NotFoundException($"Book with ID {id} was not found.", ex);
        }
        catch (Exception ex)
        {
            // Handle general exceptions
            _logger.LogError(ex, "An error occurred while getting the book");
            throw; // Rethrow the original exception
        }
    }
}
```

**Creating Custom Exceptions:**
```csharp
[Serializable]
public class NotFoundException : Exception
{
    public NotFoundException() { }
    public NotFoundException(string message) : base(message) { }
    public NotFoundException(string message, Exception inner) : base(message, inner) { }
    
    // Optional: Serialization constructor
    protected NotFoundException(
      SerializationInfo info,
      StreamingContext context) : base(info, context) { }
}
```

**Best Practices for Exception Handling:**
- Use exceptions for exceptional conditions, not for control flow or validation.
- Catch specific exception types rather than using a general `catch` block.
- Log exceptions at the appropriate level (e.g., `LogError`, `LogWarning`) with sufficient context to diagnose the issue.
- Avoid exposing internal exception details to the user. Return user-friendly error messages and codes.
- Consider using custom exception types to represent specific error conditions in your application.

##### **Section 0.2.3:** Pattern Matching and Switch Expressions

Pattern matching in modern C# goes far beyond simple switch statements. It provides a powerful way to test values against patterns and extract data in a single operation. This feature is particularly useful in web development for handling different types of requests, responses, and data transformations.

Switch expressions, introduced in C# 8 and enhanced in later versions, provide a more functional programming approach to conditional logic. They're expression-based rather than statement-based, making them perfect for mapping operations and transformation logic commonly found in web APIs.

**Basic Pattern Matching:**
```csharp
// Property patterns
public string GetBookCategory(Book book) => book switch
{
    { Year: var year } when year < 1900 => "Antique",
    { Year: >= 1900 and < 1950 } => "Early Modern",
    { Year: >= 1950 and < 2000 } => "Modern",
    { Year: >= 2000 } => "Contemporary",
    _ => "Unknown"
};

// Type patterns
public decimal CalculatePrice(object item) => item switch
{
    Book book => book.Price,
    DigitalBook { Format: "PDF" } => 9.99m,
    DigitalBook { Format: "EPUB" } => 12.99m,
    AudioBook audio => audio.Duration > 10 ? 24.99m : 19.99m,
    _ => throw new ArgumentException("Unknown item type")
};
```

**Advanced Pattern Matching in Web APIs:**
```csharp
// Pattern matching for HTTP response handling
public async Task<ActionResult<Book>> GetBookAsync(int id)
{
    var result = await _bookService.GetBookAsync(id);
    
    return result switch
    {
        { IsSuccess: true, Value: var book } => Ok(book),
        { IsSuccess: false, Error: "NotFound" } => NotFound($"Book with ID {id} not found"),
        { IsSuccess: false, Error: "Unauthorized" } => Forbid(),
        { IsSuccess: false, Error: var error } => BadRequest(error),
        _ => StatusCode(500, "An unexpected error occurred")
    };
}
```

<div style="page-break-after: always;"></div>

---

## 🎓 Course Content

Now that we've covered the essential C# concepts, let's dive into building real-world web applications. The following modules will take you from setting up your development environment to deploying a production-ready application with authentication, data persistence, and modern UI components.

<div style="background-color: #e3f2fd; padding: 20px; border-left: 4px solid #2196f3; margin: 20px 0;">

**Learning Philosophy:** This course follows a hands-on, project-based approach. Each module builds upon the previous one, and by the end, you'll have created a complete, industry-standard web application. Don't just read the code—type it out, experiment with it, and make it your own.

</div>

### **Part 1: ASP.NET Core Web API Fundamentals**

Web APIs are the backbone of modern web applications, serving as the communication layer between frontend interfaces and backend data. ASP.NET Core's Web API framework provides a robust, scalable foundation for building HTTP services that can serve various clients—from web browsers and mobile apps to other services and third-party integrations.

Understanding how to build well-designed APIs is crucial in today's development landscape. Modern applications are increasingly distributed, with frontend and backend often developed and deployed separately. This architectural approach, known as the "API-first" strategy, allows for greater flexibility, easier testing, and better separation of concerns.

Throughout Part 1, we'll explore the fundamental concepts that make ASP.NET Core Web APIs powerful and developer-friendly. We'll start with the basics—setting up your environment and creating your first API—then progressively add complexity as we introduce controllers, dependency injection, and data models. By the end of this part, you'll understand not just how to build APIs, but how to build them well, following industry best practices and modern .NET conventions.

#### Module 1.1: Getting Started with ASP.NET Core

Setting up a proper development environment is the foundation of productive software development. With .NET 9, Microsoft has streamlined the development experience significantly, but there are still important considerations for tooling, extensions, and project configuration that can make the difference between a frustrating experience and a smooth, productive workflow.

The modern .NET development experience centers around the .NET CLI (Command Line Interface), which provides powerful scaffolding, building, and deployment capabilities. Even if you prefer working in Visual Studio or Visual Studio Code, understanding the CLI commands will make you more versatile and help you automate development tasks.

##### **Section 1.1.1:** Setting up your development environment (Visual Studio/VS Code)

The choice of development environment significantly impacts your productivity and debugging capabilities. Visual Studio offers the most comprehensive development experience with advanced debugging, integrated testing tools, and sophisticated project management features. Visual Studio Code, while lighter, provides excellent .NET support through extensions and offers superior performance for many development scenarios.

Regardless of your IDE choice, certain extensions and configurations are essential for .NET development. IntelliSense, debugging support, integrated terminal access, and proper syntax highlighting form the foundation of any good .NET development setup. Additionally, modern development practices like GitLens for source control visualization, REST Client for API testing, and various productivity extensions can significantly enhance your workflow.

**Installing .NET 9 SDK:**
```bash
# Verify your installation
dotnet --version
# Should show 9.0.xxx

# List installed SDKs
dotnet --list-sdks

# List available project templates
dotnet new list
```

**Essential VS Code Extensions for .NET Development:**
If you choose Visual Studio Code, these extensions will provide a development experience comparable to Visual Studio for most scenarios:

- **C# Dev Kit** - Comprehensive C# and .NET support
- **C#** - Basic C# language support and debugging
- **NuGet Gallery** - Browse and install NuGet packages
- **REST Client** - Test APIs directly from VS Code
- **GitLens** - Enhanced Git capabilities
- **Bracket Pair Colorizer** - Visual bracket matching
- **Auto Rename Tag** - Automatically rename paired HTML/XML tags
- **Thunder Client** - API testing tool (alternative to Postman)

**Project Configuration Best Practices:**
Modern .NET projects use SDK-style project files that are much cleaner and more maintainable than their predecessors. Understanding how to configure these files properly ensures your projects work well in different environments and with various deployment scenarios.

```xml
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>net9.0</TargetFramework>
    <Nullable>enable</Nullable>
    <ImplicitUsings>enable</ImplicitUsings>
    <TreatWarningsAsErrors>true</TreatWarningsAsErrors>
    <WarningsAsErrors />
    <WarningsNotAsErrors>CS1591</WarningsNotAsErrors>
  </PropertyGroup>

  <PropertyGroup Condition="'$(Configuration)' == 'Debug'">
    <DefineConstants>DEBUG;TRACE</DefineConstants>
  </PropertyGroup>
</Project>
```

##### **Section 1.1.2:** Creating your first ASP.NET Core Web API project

The `dotnet new` command provides several templates for creating ASP.NET Core applications. For API development, the `webapi` template creates a minimal but complete starting point that follows current best practices. Understanding what this template provides and why helps you make informed decisions about project structure and configuration.

Modern ASP.NET Core applications use a streamlined approach compared to earlier versions. The traditional `Startup.cs` file has been consolidated into `Program.cs`, making the application bootstrap process more straightforward while maintaining all the configuration flexibility of previous versions.

**Creating the Project:**
```bash
# Create a new directory for your project
mkdir BookStoreApi
cd BookStoreApi

# Create the Web API project
dotnet new webapi --name BookStoreApi --framework net9.0

# Navigate into the project directory
cd BookStoreApi

# Restore dependencies
dotnet restore

# Build the project
dotnet build

# Run the project
dotnet run
```

**Understanding the Generated Project Structure:**
When you create a new Web API project, the template generates a specific folder structure designed to promote good organization and separation of concerns:

```
BookStoreApi/
├── Controllers/
│   └── WeatherForecastController.cs    # Sample controller
├── Properties/
│   └── launchSettings.json             # Development settings
├── appsettings.json                    # Application configuration
├── appsettings.Development.json        # Development-specific config
├── BookStoreApi.csproj                 # Project file
├── Program.cs                          # Application entry point
└── WeatherForecast.cs                  # Sample model
```

Each component serves a specific purpose:

- **Controllers/**: Contains your API controllers that handle HTTP requests
- **Properties/launchSettings.json**: Defines how your application launches in different environments
- **appsettings.json**: Configuration for different application aspects (connection strings, API keys, etc.)
- **Program.cs**: The application's entry point where services are configured and the request pipeline is built

##### **Section 1.1.3:** Understanding the project structure and startup configuration

The `Program.cs` file in .NET 9 represents a significant evolution in how ASP.NET Core applications are configured. This minimal hosting model reduces boilerplate code while maintaining full control over application behavior. Understanding this file is crucial because it's where you'll configure services, middleware, and application behavior.

**Examining Program.cs:**
```csharp
var builder = WebApplication.CreateBuilder(args);

// Add services to the container.
builder.Services.AddControllers();
// Learn more about configuring Swagger/OpenAPI at https://aka.ms/aspnetcore/swashbuckle
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen();

var app = builder.Build();

// Configure the HTTP request pipeline.
if (app.Environment.IsDevelopment())
{
    app.UseSwagger();
    app.UseSwaggerUI();
}

app.UseHttpsRedirection();
app.UseAuthorization();
app.MapControllers();

app.Run();
```

This seemingly simple file accomplishes several important tasks:

1. **Service Configuration**: The `builder.Services` section is where you register services for dependency injection
2. **Application Building**: `builder.Build()` creates the application instance with all configured services
3. **Middleware Pipeline**: The series of `app.Use...` calls define how HTTP requests are processed
4. **Controller Mapping**: `app.MapControllers()` sets up routing to your controller actions

**The Request Pipeline:**
Understanding the middleware pipeline is fundamental to ASP.NET Core development. Each piece of middleware can examine, modify, or respond to HTTP requests and responses. The order of middleware registration is crucial—each middleware component processes requests in the order they're added and processes responses in reverse order.

```csharp
// Middleware executes in this order for requests:
// 1. HTTPS Redirection - Ensures secure connections
// 2. Authorization - Validates user permissions
// 3. Controller routing - Matches URLs to controller actions

// And in reverse order for responses:
// 3. Controller routing generates response
// 2. Authorization may modify response headers
// 1. HTTPS Redirection ensures response is secure
```
##### **Section 1.1.4:** Running and testing your first API endpoint

Testing your API endpoints is an integral part of development, not an afterthought. Modern ASP.NET Core applications come with Swagger/OpenAPI integration by default, providing an interactive documentation and testing interface. This tool not only helps you test endpoints during development but also serves as living documentation for your API.

**Running Your Application:**
```bash
# Run with hot reload (recommended for development)
dotnet watch run

# Or run normally
dotnet run
```

When you run the application, you'll see output similar to:
```
info: Microsoft.Hosting.Lifetime[14]
      Now listening on: https://localhost:7173
info: Microsoft.Hosting.Lifetime[14]  
      Now listening on: http://localhost:5173
```

**Testing with Swagger UI:**
Navigate to `https://localhost:7173/swagger` (adjust port as needed) to access the Swagger UI. This interface shows all available endpoints, their parameters, and allows you to test them directly from your browser. The generated WeatherForecast endpoint demonstrates the basic structure of an API controller.

**Understanding the Sample WeatherForecast Controller:**
```csharp
[ApiController]
[Route("[controller]")]
public class WeatherForecastController : ControllerBase
{
    private static readonly string[] Summaries = new[]
    {
        "Freezing", "Bracing", "Chilly", "Cool", "Mild", "Warm", "Balmy", "Hot", "Sweltering", "Scorching"
    };

    private readonly ILogger<WeatherForecastController> _logger;

    public WeatherForecastController(ILogger<WeatherForecastController> logger)
    {
        _logger = logger;
    }

    [HttpGet(Name = "GetWeatherForecast")]
    public IEnumerable<WeatherForecast> Get()
    {
        return Enumerable.Range(1, 5).Select(index => new WeatherForecast
        {
            Date = DateOnly.FromDateTime(DateTime.Now.AddDays(index)),
            TemperatureC = Random.Shared.Next(-20, 55),
            Summary = Summaries[Random.Shared.Next(Summaries.Length)]
        })
        .ToArray();
    }
}
```

This controller demonstrates several important concepts:
- **Attribute routing** with `[Route("[controller]")]`
- **Dependency injection** with the logger parameter
- **HTTP verb mapping** with `[HttpGet]`
- **Data generation and transformation** in the action method

**Testing with REST Client Tools:**
While Swagger UI is convenient for quick testing, professional API development often requires more sophisticated testing tools. Here are examples using different approaches:

*Using curl:*
```bash
curl -X GET "https://localhost:7173/WeatherForecast" -H "accept: text/plain"
```

*Using PowerShell:*
```powershell
Invoke-RestMethod -Uri "https://localhost:7173/WeatherForecast" -Method GET
```

*Using VS Code REST Client extension:*
```http
### Get Weather Forecast
GET https://localhost:7173/WeatherForecast
Accept: application/json
```

---

#### **Challenge 1.1: Create a "Hello World" API with custom routing**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Create a simple API controller that demonstrates custom routing and returns personalized greetings. This challenge reinforces basic controller concepts while introducing route customization.

**What You'll Learn:**
- Custom route configuration
- Action method naming conventions
- Basic parameter handling
- HTTP status code responses

</div>

**Challenge Requirements:**
1. Create a new controller called `GreetingController`
2. Implement the following endpoints:
   - `GET /api/hello` - Returns "Hello, World!"
   - `GET /api/hello/{name}` - Returns "Hello, {name}!"
   - `GET /api/greet/{name}/{time}` - Returns appropriate greeting based on time of day
3. Add proper HTTP status codes and response types
4. Test all endpoints using Swagger UI

**Solution Approach:**
Think about how routes are structured and how parameters are passed to action methods. Consider what constitutes appropriate HTTP responses for different scenarios (successful responses, validation errors, etc.).

```csharp
// Starter template - complete the implementation
[ApiController]
[Route("api/[controller]")]
public class GreetingController : ControllerBase
{
    [HttpGet("/api/hello")]
    public ActionResult<string> SayHello()
    {
        // TODO: Return "Hello, World!"
    }

    [HttpGet("/api/hello/{name}")]
    public ActionResult<string> SayHelloToName(string name)
    {
        // TODO: Return personalized greeting
        // Consider validation - what if name is null or empty?
    }

    [HttpGet("/api/greet/{name}/{time}")]
    public ActionResult<string> GreetByTime(string name, string time)
    {
        // TODO: Return time-appropriate greeting
        // Handle different time values: morning, afternoon, evening
        // Consider validation for both parameters
    }
}
```

**Expected Output Examples:**
- `GET /api/hello` → `"Hello, World!"`
- `GET /api/hello/John` → `"Hello, John!"`
- `GET /api/greet/Sarah/morning` → `"Good morning, Sarah!"`
- `GET /api/greet/Mike/invalid` → Appropriate error response

<div style="page-break-after: always;"></div>

#### Module 1.2: Controllers and Routing in Depth

Controllers are the heart of any ASP.NET Core Web API, serving as the entry points for HTTP requests and coordinating the flow of data between clients and your application's business logic. Understanding how to design controllers effectively is crucial for building maintainable, testable, and scalable APIs.

Modern controller design emphasizes thin controllers with focused responsibilities. Rather than containing complex business logic, controllers should primarily handle HTTP concerns—request validation, response formatting, and coordination between services. This approach, known as the "thin controller, fat service" pattern, promotes better separation of concerns and makes your code easier to test and maintain.

##### **Section 1.2.1:** What are controllers and why do we need them?

Controllers serve as the bridge between the HTTP protocol and your application's domain logic. They handle the translation of HTTP requests into method calls on your business services, and then translate the results back into appropriate HTTP responses. This abstraction layer is essential because it allows your business logic to remain independent of HTTP concerns, making it more reusable and testable.

In the context of web APIs, controllers define the contract between your API and its consumers. Each controller typically represents a related group of operations on a specific resource or domain concept. For example, a `BooksController` would handle all HTTP operations related to books—creating, reading, updating, and deleting book records.

**The Role of Controllers in Modern APIs:**
Controllers in ASP.NET Core Web APIs have several key responsibilities:

1. **Request Routing**: Matching incoming HTTP requests to appropriate action methods
2. **Parameter Binding**: Converting HTTP request data into .NET objects
3. **Validation**: Ensuring incoming data meets your application's requirements
4. **Service Coordination**: Calling appropriate business services to fulfill requests
5. **Response Formatting**: Converting service results into HTTP responses
6. **Error Handling**: Gracefully managing exceptions and returning appropriate error responses

**Controller Design Principles:**
Effective controller design follows several important principles that promote maintainability and testability:

- **Single Responsibility**: Each controller should handle operations for one resource type
- **Thin Controllers**: Business logic should reside in services, not controllers
- **Consistent Naming**: Follow RESTful conventions for predictable APIs
- **Proper HTTP Usage**: Use appropriate HTTP verbs and status codes
- **Validation**: Validate input early and return meaningful error messages

##### **Section 1.2.2:** Creating your first controller and action methods

Let's create a practical controller for managing books in our bookstore API. This controller will demonstrate the fundamental patterns you'll use throughout your API development career.

**Creating the Book Model:**
Before building our controller, we need a model to represent our data. In a real application, this would likely correspond to a database entity, but for now, we'll use a simple class.

```csharp
// Models/Book.cs
namespace BookStoreApi.Models
{
    public class Book
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public string ISBN { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public DateTime PublishedDate { get; set; }
        public string Description { get; set; } = string.Empty;
        public int StockQuantity { get; set; }
    }
}
```

**Creating the Books Controller:**
```csharp
// Controllers/BooksController.cs
using Microsoft.AspNetCore.Mvc;
using BookStoreApi.Models;

namespace BookStoreApi.Controllers
{
    [ApiController]
    [Route("api/[controller]")]
    public class BooksController : ControllerBase
    {
        // In-memory storage for demonstration
        // In a real application, this would be injected as a service
        private static readonly List<Book> _books = new()
        {
            new Book 
            { 
                Id = 1, 
                Title = "Clean Code", 
                Author = "Robert C. Martin",
                ISBN = "978-0132350884",
                Price = 42.99m,
                PublishedDate = new DateTime(2008, 8, 1),
                Description = "A handbook of agile software craftsmanship",
                StockQuantity = 15
            },
            new Book 
            { 
                Id = 2, 
                Title = "The Pragmatic Programmer", 
                Author = "David Thomas",
                ISBN = "978-0201616224",
                Price = 39.99m,
                PublishedDate = new DateTime(1999, 10, 20),
                Description = "Your journey to mastery",
                StockQuantity = 8
            }
        };

        // GET: api/books
        [HttpGet]
        public ActionResult<IEnumerable<Book>> GetBooks()
        {
            return Ok(_books);
        }

        // GET: api/books/5
        [HttpGet("{id}")]
        public ActionResult<Book> GetBook(int id)
        {
            var book = _books.FirstOrDefault(b => b.Id == id);
            
            if (book == null)
            {
                return NotFound($"Book with ID {id} was not found.");
            }
            
            return Ok(book);
        }
    }
}
```

**Understanding Action Method Structure:**
Each action method in a controller follows a consistent pattern that makes APIs predictable and easy to understand:

1. **HTTP Verb Attribute**: `[HttpGet]`, `[HttpPost]`, etc., specify which HTTP method triggers this action
2. **Route Template**: Optional parameter in the attribute defines URL patterns
3. **Method Signature**: Parameters are automatically bound from the request
4. **Return Type**: `ActionResult<T>` allows returning both data and HTTP status codes
5. **Implementation**: Business logic or service calls to fulfill the request

##### **Section 1.2.3:** Understanding HTTP verbs (GET, POST, PUT, DELETE)

HTTP verbs (also called methods) define the type of operation being requested. RESTful APIs use these verbs consistently to create predictable, intuitive interfaces. Understanding when and how to use each verb is fundamental to good API design.

**GET - Retrieving Data:**
GET requests are used to retrieve data without modifying server state. They should be safe (no side effects) and idempotent (multiple identical requests have the same effect as a single request).

```csharp
// GET: api/books
[HttpGet]
public ActionResult<IEnumerable<Book>> GetBooks(
    [FromQuery] string? search = null,
    [FromQuery] int page = 1,
    [FromQuery] int pageSize = 10)
{
    var query = _books.AsQueryable();
    
    // Apply search filter if provided
    if (!string.IsNullOrEmpty(search))
    {
        query = query.Where(b => 
            b.Title.Contains(search, StringComparison.OrdinalIgnoreCase) ||
            b.Author.Contains(search, StringComparison.OrdinalIgnoreCase));
    }
    
    // Apply pagination
    var books = query
        .Skip((page - 1) * pageSize)
        .Take(pageSize)
        .ToList();
    
    return Ok(books);
}

// GET: api/books/5
[HttpGet("{id}")]
public ActionResult<Book> GetBook(int id)
{
    if (id <= 0)
    {
        return BadRequest("ID must be a positive number.");
    }
    
    var book = _books.FirstOrDefault(b => b.Id == id);
    return book == null ? NotFound() : Ok(book);
}
```

**POST - Creating New Resources:**
POST requests create new resources. They are neither safe nor idempotent—each request typically creates a new resource with a new identifier.

```csharp
// POST: api/books
[HttpPost]
public ActionResult<Book> CreateBook([FromBody] CreateBookDto bookDto)
{
    // Validate the model
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    // Check for duplicate ISBN
    if (_books.Any(b => b.ISBN == bookDto.ISBN))
    {
        return Conflict($"A book with ISBN {bookDto.ISBN} already exists.");
    }
    
    // Create new book
    var book = new Book
    {
        Id = _books.Count > 0 ? _books.Max(b => b.Id) + 1 : 1,
        Title = bookDto.Title,
        Author = bookDto.Author,
        ISBN = bookDto.ISBN,
        Price = bookDto.Price,
        PublishedDate = bookDto.PublishedDate,
        Description = bookDto.Description ?? string.Empty,
        StockQuantity = bookDto.StockQuantity
    };
    
    _books.Add(book);
    
    // Return 201 Created with location header
    return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
}

// DTO for creating books
public class CreateBookDto
{
    [Required]
    [StringLength(200)]
    public string Title { get; set; } = string.Empty;
    
    [Required]
    [StringLength(100)]
    public string Author { get; set; } = string.Empty;
    
    [Required]
    [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$", 
        ErrorMessage = "Invalid ISBN format")]
    public string ISBN { get; set; } = string.Empty;
    
    [Range(0.01, 9999.99)]
    public decimal Price { get; set; }
    
    public DateTime PublishedDate { get; set; }
    
    [StringLength(1000)]
    public string? Description { get; set; }
    
    [Range(0, int.MaxValue)]
    public int StockQuantity { get; set; }
}

// Handling duplicate ISBN conflict
public class BookService
{
    public ActionResult<Book> CreateBook(CreateBookDto bookDto)
    {
        // Check for duplicate ISBN
        if (_books.Any(b => b.ISBN == bookDto.ISBN))
        {
            return Conflict($"A book with ISBN {bookDto.ISBN} already exists.");
        }
        
        // Create new book
        var book = new Book
        {
            Id = _books.Count > 0 ? _books.Max(b => b.Id) + 1 : 1,
            Title = bookDto.Title,
            Author = bookDto.Author,
            ISBN = bookDto.ISBN,
            Price = bookDto.Price,
            PublishedDate = bookDto.PublishedDate,
            Description = bookDto.Description ?? string.Empty,
            StockQuantity = bookDto.StockQuantity
        };
        
        _books.Add(book);
        
        return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
    }
}
```

**PUT - Updating Resources:**
PUT requests replace entire resources. They should be idempotent—multiple identical requests should have the same effect as a single request.

```csharp
// PUT: api/books/5
[HttpPut("{id}")]
public ActionResult<Book> UpdateBook(int id, [FromBody] UpdateBookDto bookDto)
{
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        return NotFound($"Book with ID {id} was not found.");
    }
    
    // Check for ISBN conflicts with other books
    if (_books.Any(b => b.Id != id && b.ISBN == bookDto.ISBN))
    {
        return Conflict($"Another book with ISBN {bookDto.ISBN} already exists.");
    }
    
    // Update book properties
    book.Title = bookDto.Title;
    book.Author = bookDto.Author;
    book.ISBN = bookDto.ISBN;
    book.Price = bookDto.Price;
    book.PublishedDate = bookDto.PublishedDate;
    book.Description = bookDto.Description ?? string.Empty;
    book.StockQuantity = bookDto.StockQuantity;
    
    return Ok(book);
}
```

**DELETE - Removing Resources:**
DELETE requests remove resources. They should be idempotent—deleting a resource multiple times should have the same effect as deleting it once.

```csharp
// DELETE: api/books/5
[HttpDelete("{id}")]
public ActionResult DeleteBook(int id)
{
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        // Idempotent: returning 204 even if already deleted
        return NoContent();
    }
    
    _books.Remove(book);
    return NoContent(); // 204 No Content
}
```

**PATCH - Partial Updates:**
PATCH requests update specific fields of a resource. While more complex to implement correctly, they're useful for APIs where clients need to update individual properties without sending the entire resource.

```csharp
// PATCH: api/books/5
[HttpPatch("{id}")]
public ActionResult<Book> PatchBook(int id, [FromBody] JsonPatchDocument<Book> patchDoc)
{
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        return NotFound();
    }
    
    // Apply the patch
    patchDoc.ApplyTo(book, ModelState);
    
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    return Ok(book);
}
```

##### **Section 1.2.4:** Route parameters and query strings

Routing in ASP.NET Core Web APIs provides flexible ways to capture data from URLs and query strings. Understanding the different binding sources and how to use them effectively is crucial for building intuitive, RESTful APIs.

**Route Parameters:**
Route parameters are captured from the URL path and are typically used for resource identifiers. They're defined in the route template using curly braces.

```csharp
[ApiController]
[Route("api/[controller]")]
public class BooksController : ControllerBase
{
    // Single parameter: /api/books/5
    [HttpGet("{id}")]
    public ActionResult<Book> GetBook(int id)
    {
        // TODO: Implement get by ID
    }
    
    // Multiple parameters: /api/books/5/reviews/10
    [HttpGet("{bookId}/reviews/{reviewId}")]
    public ActionResult<Review> GetBookReview(int bookId, int reviewId)
    {
        // Both parameters are captured from the URL
        var book = _books.FirstOrDefault(b => b.Id == bookId);
        if (book == null) return NotFound("Book not found");
        
        // Logic to find review...
        return Ok(/* review */);
    }
    
    // Optional parameters: /api/books/search/programming or /api/books/search
    [HttpGet("search/{term?}")]
    public ActionResult<IEnumerable<Book>> SearchBooks(string? term = null)
    {
        if (string.IsNullOrEmpty(term))
        {
            return Ok(_books.Take(10)); // Return first 10 books
        }
        
        var results = _books.Where(b => 
            b.Title.Contains(term, StringComparison.OrdinalIgnoreCase) ||
            b.Author.Contains(term, StringComparison.OrdinalIgnoreCase));
            
        return Ok(results);
    }
    
    // Route constraints: /api/books/123 (only numeric IDs)
    [HttpGet("{id:int:min(1)}")]
    public ActionResult<Book> GetBookWithConstraints(int id)
    {
        // id is guaranteed to be a positive integer
        var book = _books.FirstOrDefault(b => b.Id == id);
        return book == null ? NotFound() : Ok(book);
    }
}
```

**Query String Parameters:**
Query strings are ideal for optional parameters, filtering, sorting, and pagination. They appear after the `?` in URLs and can be bound automatically to action method parameters.

```csharp
// GET: /api/books?category=programming&minPrice=20&maxPrice=50&sort=title&order=asc&page=2&pageSize=10
[HttpGet]
public ActionResult<IEnumerable<Book>> GetBooks(
    [FromQuery] string? category = null,
    [FromQuery] decimal? minPrice = null,
    [FromQuery] decimal? maxPrice = null,
    [FromQuery] string? sort = "title",
    [FromQuery] string order = "asc",
    [FromQuery] int page = 1,
    [FromQuery] int pageSize = 10)
{
    var query = _books.AsQueryable();
    
    // Apply filters
    if (!string.IsNullOrEmpty(category))
    {
        query = query.Where(b => b.Category?.Equals(category, StringComparison.OrdinalIgnoreCase) == true);
    }
    
    if (minPrice.HasValue)
    {
        query = query.Where(b => b.Price >= minPrice.Value);
    }
    
    if (maxPrice.HasValue)
    {
        query = query.Where(b => b.Price <= maxPrice.Value);
    }
    
    // Apply sorting
    query = sort?.ToLower() switch
    {
        "title" => order.ToLower() == "desc" 
            ? query.OrderByDescending(b => b.Title)
            : query.OrderBy(b => b.Title),
        "author" => order.ToLower() == "desc"
            ? query.OrderByDescending(b => b.Author)
            : query.OrderBy(b => b.Author),
        "price" => order.ToLower() == "desc"
            ? query.OrderByDescending(b => b.Price)
            : query.OrderBy(b => b.Price),
        _ => query.OrderBy(b => b.Title)
    };
    
    // Apply pagination
    var totalCount = query.Count();
    var books = query
        .Skip((page - 1) * pageSize)
        .Take(pageSize)
        .ToList();
    
    // Return with pagination metadata in headers
    Response.Headers.Add("X-Total-Count", totalCount.ToString());
    Response.Headers.Add("X-Page", page.ToString());
    Response.Headers.Add("X-Page-Size", pageSize.ToString());
    
    return Ok(books);
}
```

**Complex Query Parameters:**
For more complex scenarios, you can bind query parameters to custom objects:

```csharp
public class BookSearchCriteria
{
    public string? Title { get; set; }
    public string? Author { get; set; }
    public string? Category { get; set; }
    public decimal? MinPrice { get; set; }
    public decimal? MaxPrice { get; set; }
    public DateTime? PublishedAfter { get; set; }
    public DateTime? PublishedBefore { get; set; }
    public bool? InStock { get; set; }
    public string Sort { get; set; } = "title";
    public string Order { get; set; } = "asc";
    public int Page { get; set; } = 1;
    public int PageSize { get; set; } = 10;
}

[HttpGet("search")]
public ActionResult<IEnumerable<Book>> SearchBooks([FromQuery] BookSearchCriteria criteria)
{
    var query = _books.AsQueryable();
    
    // Apply all filters based on criteria properties
    if (!string.IsNullOrEmpty(criteria.Title))
    {
        query = query.Where(b => b.Title.Contains(criteria.Title, StringComparison.OrdinalIgnoreCase));
    }
    
    if (!string.IsNullOrEmpty(criteria.Author))
    {
        query = query.Where(b => b.Author.Contains(criteria.Author, StringComparison.OrdinalIgnoreCase));
    }
    
    if (criteria.MinPrice.HasValue)
    {
        query = query.Where(b => b.Price >= criteria.MinPrice.Value);
    }
    
    if (criteria.MaxPrice.HasValue)
    {
        query = query.Where(b => b.Price <= criteria.MaxPrice.Value);
    }
    
    if (criteria.PublishedAfter.HasValue)
    {
        query = query.Where(b => b.PublishedDate >= criteria.PublishedAfter.Value);
    }
    
    if (criteria.PublishedBefore.HasValue)
    {
        query = query.Where(b => b.PublishedDate <= criteria.PublishedBefore.Value);
    }
    
    return Ok(query.ToList());
}
```

##### **Section 1.2.5:** Model binding and validation

Model binding is the process by which ASP.NET Core automatically converts HTTP request data into .NET objects. This powerful feature eliminates much of the manual work involved in parsing request data, while validation ensures that incoming data meets your application's requirements before it reaches your business logic.

Understanding how model binding works and how to configure it properly is essential for building robust APIs. Poor validation can lead to security vulnerabilities, data corruption, and poor user experience. Modern ASP.NET Core provides several validation approaches, from simple data annotations to complex custom validators.

**Automatic Model Binding:**

ASP.NET Core can bind data from multiple sources automatically:

```csharp
public class BookOrderController : ControllerBase
{
    // Binding from route, query, and body
    [HttpPost("orders/{customerId}")]
    public ActionResult<Order> CreateOrder(
        int customerId,                    // From route
        [FromQuery] string? promocode,     // From query string
        [FromBody] CreateOrderDto order,   // From request body
        [FromHeader] string userAgent)     // From headers
    {
        // All parameters are automatically bound
        var newOrder = new Order
        {
            CustomerId = customerId,
            PromoCode = promocode,
            UserAgent = userAgent,
            Items = order.Items
        };
        
        return CreatedAtAction(nameof(GetOrder), new { id = newOrder.Id }, newOrder);
    }
}
```

**Data Annotations for Validation:**

Data annotations provide a declarative way to specify validation rules directly on your model properties:

```csharp
public class CreateBookDto
{
    [Required(ErrorMessage = "Title is required")]
    [StringLength(200, MinimumLength = 1, ErrorMessage = "Title must be between 1 and 200 characters")]
    public string Title { get; set; } = string.Empty;
    
    [Required(ErrorMessage = "Author is required")]
    [StringLength(100, MinimumLength = 2, ErrorMessage = "Author name must be between 2 and 100 characters")]
    public string Author { get; set; } = string.Empty;
    
    [Required(ErrorMessage = "ISBN is required")]
    [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$", 
        ErrorMessage = "Invalid ISBN format")]
    public string ISBN { get; set; } = string.Empty;
    
    [Range(0.01, 9999.99, ErrorMessage = "Price must be between $0.01 and $9999.99")]
    public decimal Price { get; set; }
    
    public DateTime PublishedDate { get; set; }
    
    [StringLength(1000, ErrorMessage = "Description cannot exceed 1000 characters")]
    public string? Description { get; set; }
    
    [Range(0, int.MaxValue, ErrorMessage = "Stock quantity cannot be negative")]
    public int StockQuantity { get; set; }
    
    [EmailAddress(ErrorMessage = "Invalid email format")]
    public string? ContactEmail { get; set; }
    
    [Url(ErrorMessage = "Invalid URL format")]
    public string? PublisherWebsite { get; set; }
}
```

**Custom Validation Attributes:**

For more complex validation rules, you can create custom validation attributes:

```csharp
public class FutureDateAttribute : ValidationAttribute
{
    public override bool IsValid(object? value)
    {
        if (value is DateTime date)
        {
            return date <= DateTime.Now.AddYears(2); // Books can be published max 2 years in future
        }
        return true; // Let other validators handle non-DateTime values
    }
    
    public override string FormatErrorMessage(string name)
    {
        return $"{name} cannot be more than 2 years in the future.";
    }
}

// Usage in DTO
public class CreateBookDto
{
    // ...existing properties...
    
    [Required]
    [ISBNValidation(ErrorMessage = "Invalid ISBN format or checksum")]
    public string ISBN { get; set; } = string.Empty;
    
    [FutureDate(ErrorMessage = "Publication date cannot be more than 2 years in the future")]
    public DateTime PublishedDate { get; set; }
}
```

**Handling Validation in Controllers:**
```csharp
[HttpPost]
public ActionResult<Book> CreateBook([FromBody] CreateBookDto bookDto)
{
    // Check model validation
    if (!ModelState.IsValid)
    {
        // Return detailed validation errors
        var errors = ModelState
            .Where(x => x.Value?.Errors.Count > 0)
            .ToDictionary(
                kvp => kvp.Key,
                kvp => kvp.Value?.Errors.Select(e => e.ErrorMessage).ToArray()
            );
            
        return BadRequest(new { 
            Message = "Validation failed", 
            Errors = errors 
        });
    }
    
    // Additional business logic validation
    if (_books.Any(b => b.ISBN == bookDto.ISBN))
    {
        ModelState.AddModelError("ISBN", "A book with this ISBN already exists");
        return BadRequest(ModelState);
    }
    
    // Create and save the book
    var book = new Book
    {
        Id = GenerateNewId(),
        Title = bookDto.Title,
        Author = bookDto.Author,
        ISBN = bookDto.ISBN,
        Price = bookDto.Price,
        PublishedDate = bookDto.PublishedDate,
        Description = bookDto.Description ?? string.Empty,
        StockQuantity = bookDto.StockQuantity
    };
    
    _books.Add(book);
    
    return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
}
```

<div style="page-break-after: always;"></div>

---

### **Part 2: Data Access and Entity Framework**

Moving from in-memory data storage to a proper database represents a crucial step in building production-ready applications. Entity Framework Core (EF Core) is Microsoft's modern object-relational mapping (ORM) framework that bridges the gap between object-oriented programming and relational databases. It enables developers to work with databases using .NET objects, eliminating the need for most of the data-access code that typically needs to be written.

Understanding EF Core is essential for modern .NET development because it provides a powerful, flexible way to interact with databases while maintaining type safety and leveraging LINQ for queries. EF Core supports multiple database providers, making it possible to switch between different database systems with minimal code changes.

Throughout Part 2, we'll explore how to design effective data models, establish relationships between entities, configure EF Core for your specific needs, and implement efficient data access patterns. We'll also cover advanced topics like query optimization, transaction management, and handling complex scenarios that arise in real-world applications.

#### Module 2.1: Data Models and DTOs
 
Proper data modeling is the foundation of any successful application. The way you design your entities and their relationships directly impacts performance, maintainability, and the overall architecture of your system. Entity Framework Core provides powerful tools for defining these models and relationships, but understanding the underlying principles is crucial for making informed decisions.

Modern data modeling in EF Core goes beyond simple property mapping. It involves understanding how your domain concepts translate to database structures, how to handle different types of relationships, and how to optimize for both development productivity and runtime performance.

##### **Section 2.1.1:** Designing your data models

Entity design in EF Core requires balancing several concerns: reflecting your domain accurately, optimizing for database performance, and maintaining clean, understandable code. The entities you create serve as both the foundation for your database schema and the objects your application logic works with.

When designing entities, it's important to consider not just the current requirements but also how your data model might evolve over time. EF Core's migration system makes schema changes manageable, but thoughtful initial design can prevent many future complications.

**Basic Entity Design Principles:**
```csharp
// Entities/Book.cs
using System.ComponentModel.DataAnnotations;
using System.ComponentModel.DataAnnotations.Schema;

namespace BookStoreApi.Entities
{
    [Table("Books")]
    public class Book
    {
        [Key]
        public int Id { get; set; }
        
        [Required]
        [MaxLength(200)]
        public string Title { get; set; } = string.Empty;
        
        [Required]
        [MaxLength(100)]
        public string Author { get; set; } = string.Empty;
        
        [Required]
        [MaxLength(20)]
        [Column("ISBN")]
        public string ISBN { get; set; } = string.Empty;
        
        [Column(TypeName = "decimal(10,2)")]
        public decimal Price { get; set; }
        
        [Column("PublicationDate")]
        public DateTime PublishedDate { get; set; }
        
        [MaxLength(1000)]
        public string? Description { get; set; }
        
        public int StockQuantity { get; set; }
        
        // Audit fields
        public DateTime CreatedAt { get; set; }
        public DateTime? UpdatedAt { get; set; }
        public string CreatedBy { get; set; } = string.Empty;
        public string? UpdatedBy { get; set; }
        
        // Navigation properties for relationships
        public int CategoryId { get; set; }
        public Category Category { get; set; } = null!;
        
        public int PublisherId { get; set; }
        public Publisher Publisher { get; set; } = null!;
        
        public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
        public ICollection<Review> Reviews { get; set; } = new List<Review>();
        public ICollection<OrderItem> OrderItems { get; set; } = new List<OrderItem>();
    }
}
```

**Supporting Entities:**
```csharp
// Entities/Category.cs
[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    [MaxLength(200)]
    public string? Description { get; set; }
    
    public bool IsActive { get; set; } = true;
    
    // Navigation properties
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

// Entities/Publisher.cs
[Table("Publishers")]
public class Publisher
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(100)]
    public string Name { get; set; } = string.Empty;
    
    [MaxLength(200)]
    public string? Address { get; set; }
    
    [MaxLength(100)]
    public string? Email { get; set; }
    
    [MaxLength(20)]
    public string? Phone { get; set; }
    
    [MaxLength(200)]
    public string? Website { get; set; }
    
    public DateTime CreatedAt { get; set; }
    
    // Navigation properties
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

// Entities/Author.cs
[Table("Authors")]
public class Author
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string FirstName { get; set; } = string.Empty;
    
    [Required]
    [MaxLength(50)]
    public string LastName { get; set; } = string.Empty;
    
    [MaxLength(1000)]
    public string? Biography { get; set; }
    
    }
    
    public DateTime? BirthDate { get; set; }
    public DateTime? DeathDate { get; set; }
    
    [MaxLength(50)]
    public string? Nationality { get; set; }
    
    [MaxLength(100)]
    public string? Email { get; set; }
    
    [MaxLength(200)]
    public string? Website { get; set; }
    
    // Computed property
    [NotMapped]
    public string FullName => $"{FirstName} {LastName}";
    
    [NotMapped]
    public bool IsLiving => !DeathDate.HasValue;
    
    // Navigation properties
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
}
```

##### **Section 2.1.2:** Entity relationships (One-to-Many, Many-to-Many)

Understanding and properly implementing entity relationships is crucial for building robust data models. EF Core supports all standard relationship types, and the way you configure these relationships affects both the generated database schema and how you can query and manipulate your data.

Relationships in EF Core are discovered by convention in many cases, but explicit configuration often provides better control and clearer intent. The choice between different relationship patterns also affects performance and the complexity of your queries.

**One-to-Many Relationships:**

One-to-many relationships are the most common in relational databases. They represent scenarios where one entity can be related to multiple instances of another entity, but each instance of the second entity relates to only one instance of the first.

```csharp
// One-to-Many: Category -> Books
// One category can have many books, but each book belongs to one category

[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    // Navigation property - one category has many books
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

[Table("Books")]
public class Book
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(200)]
    public string Title { get; set; } = string.Empty;
    
    // Foreign key property
    public int CategoryId { get; set; }
    
    // Navigation property - many books belong to one category
    public Category Category { get; set; } = null!;
}

// Fluent API configuration in DbContext
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<Book>()
        .HasOne(b => b.Category)
        .WithMany(c => c.Books)
        .HasForeignKey(b => b.CategoryId)
        .OnDelete(DeleteBehavior.Restrict); // Prevent cascade delete
}
```

**Many-to-Many Relationships:**

Many-to-many relationships occur when multiple instances of one entity can relate to multiple instances of another entity. In EF Core 5+, this can be configured automatically, but explicit join entities often provide better control.

```csharp
// Many-to-Many: Books <-> Authors
// A book can have multiple authors, and an author can write multiple books

// Explicit join entity approach (recommended for complex scenarios)
[Table("BookAuthors")]
public class BookAuthor
{
    public int BookId { get; set; }
    public Book Book { get; set; } = null!;
    
    public int AuthorId { get; set; }
    public Author Author { get; set; } = null!;
    
    // Additional properties for the relationship
    public string Role { get; set; } = "Author"; // Author, Co-Author, Editor, etc.
    public int Order { get; set; } = 1; // Order of authors for display
    public DateTime ContributedAt { get; set; }
}

// Updated Book entity
public class Book
{
    // ...existing properties...
    
    // Navigation to join entity
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
    
    // Computed property for easy access to authors
    [NotMapped]
    public IEnumerable<Author> Authors => BookAuthors.Select(ba => ba.Author);
}

// Updated Author entity
public class Author
{
    // ...existing properties...
    
    // Navigation to join entity
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
    
    // Computed property for easy access to books
    [NotMapped]
    public IEnumerable<Book> Books => BookAuthors.Select(ba => ba.Book);
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<BookAuthor>()
        .HasKey(ba => new { ba.BookId, ba.AuthorId });
    
    modelBuilder.Entity<BookAuthor>()
        .HasOne(ba => ba.Book)
        .WithMany(b => b.BookAuthors)
        .HasForeignKey(ba => ba.BookId);
    
    modelBuilder.Entity<BookAuthor>()
        .HasOne(ba => ba.Author)
        .WithMany(a => a.BookAuthors)
        .HasForeignKey(ba => ba.AuthorId);
}
```

**One-to-One Relationships:**

One-to-one relationships are less common but useful for scenarios like splitting large entities or representing optional detailed information.

```csharp
// One-to-One: Book -> BookDetails
// Each book has one set of detailed information

[Table("Books")]
public class Book
{
    [Key]
    public int Id { get; set; }
    
    // ...basic properties...
    
    // Navigation property for one-to-one relationship
    public BookDetails? Details { get; set; }
}

[Table("BookDetails")]
public class BookDetails
{
    [Key]
    public int BookId { get; set; } // Same as the Book's primary key
    
    public int PageCount { get; set; }
    public string? Language { get; set; }
    public string? Format { get; set; } // Hardcover, Paperback, etc.
    public decimal Weight { get; set; }
    public string? Dimensions { get; set; }
    
    [MaxLength(2000)]
    public string? DetailedDescription { get; set; }
    
    [MaxLength(500)]
    public string? TableOfContents { get; set; }
    
    // Navigation property back to Book
    public Book Book { get; set; } = null!;
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<BookDetails>()
        .HasOne(bd => bd.Book)
        .WithOne(b => b.Details)
        .HasForeignKey<BookDetails>(bd => bd.BookId);
}
```

**Self-Referencing Relationships:**

Sometimes entities need to relate to other instances of the same type, such as categories with subcategories or organizational hierarchies.

```csharp
[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    // Self-referencing relationship
    public int? ParentCategoryId { get; set; }
    public Category? ParentCategory { get; set; }
    
    // Navigation to child categories
    public ICollection<Category> SubCategories { get; set; } = new List<Category>();
    
    // Navigation to books in this category
    public ICollection<Book> Books { get; set; } = new List<Book>();
    
    // Computed properties
    [NotMapped]
    public bool IsRootCategory => ParentCategoryId == null;
    
    [NotMapped]
    public bool HasSubCategories => SubCategories.Any();
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<Category>()
        .HasOne(c => c.ParentCategory)
        .WithMany(c => c.SubCategories)
        .HasForeignKey(c => c.ParentCategoryId)
        .OnDelete(DeleteBehavior.Restrict);
}
```

##### **Section 2.1.3:** Data Transfer Objects (DTOs) and why use them

Data Transfer Objects (DTOs) serve as a crucial layer between your internal data models and external interfaces. They provide a way to control exactly what data is exposed by your API, enable versioning strategies, and protect against over-posting attacks. DTOs also allow you to optimize data transfer by including only the necessary fields for specific operations.

The separation between entities and DTOs becomes particularly important as applications grow in complexity. Entities are designed for persistence and domain logic, while DTOs are optimized for data transfer and API contracts. This separation provides flexibility in evolving both your internal models and external interfaces independently.

**Why DTOs Matter:**
1. **Security**: Prevent over-posting and exposure of sensitive data
2. **Performance**: Transfer only necessary data
3. **Versioning**: Maintain API contracts while evolving internal models
4. **Validation**: Apply operation-specific validation rules
5. **Documentation**: Clear API contracts for consumers

**Basic DTO Patterns:**
```csharp
// DTOs/BookDtos.cs
namespace BookStoreApi.DTOs
{
    // DTO for reading book data
    public class BookDto
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public string ISBN { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public DateTime PublishedDate { get; set; }
        public string? Description { get; set; }
        public int StockQuantity { get; set; }
        public bool IsInStock => StockQuantity > 0;
        
        // Related data
        public CategoryDto Category { get; set; } = null!;
        public PublisherDto Publisher { get; set; } = null!;
        public List<AuthorDto> Authors { get; set; } = new();
    }
    
    // DTO for creating books
    public class CreateBookDto
    {
        [Required(ErrorMessage = "Title is required")]
        [StringLength(200, MinimumLength = 1)]
        public string Title { get; set; } = string.Empty;
        
        [Required(ErrorMessage = "At least one author is required")]
        public List<int> AuthorIds { get; set; } = new();
        
        [Required(ErrorMessage = "ISBN is required")]
        [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$",
            ErrorMessage = "Invalid ISBN format")]
        public string ISBN { get; set; } = string.Empty;
        
        [Range(0.01, 9999.99)]
        public decimal Price { get; set; }
        
        [Required]
        public DateTime PublishedDate { get; set; }
        
        [StringLength(1000)]
        public string? Description { get; set; }
        
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        [Required]
        public int CategoryId { get; set; }
        
        [Required]
        public int PublisherId { get; set; }
    }
    
    // DTO for updating books
    public class UpdateBookDto
    {
        [Required]
        [StringLength(200, MinimumLength = 1)]
        public string Title { get; set; } = string.Empty;
        
        [Required]
        public List<int> AuthorIds { get; set; } = new();
        
        [Required]
        [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$",
            ErrorMessage = "Invalid ISBN format")]
        public string ISBN { get; set; } = string.Empty;
        
        [Range(0.01, 9999.99)]
        public decimal Price { get; set; }
        
        public DateTime PublishedDate { get; set; }
        
        [StringLength(1000)]
        public string? Description { get; set; }
        
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        public int CategoryId { get; set; }
        public int PublisherId { get; set; }
    }
    
    // Minimal DTO for lists and search results
    public class BookSummaryDto
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public bool IsInStock { get; set; }
        public string Category { get; set; } = string.Empty;
    }
    
    // Detailed DTO for single book views
    public class BookDetailDto : BookDto
    {
        public List<ReviewDto> RecentReviews { get; set; } = new();
        public decimal AverageRating { get; set; }
        public int ReviewCount { get; set; }
        public DateTime CreatedAt { get; set; }
        public DateTime? UpdatedAt { get; set; }
        
        // Additional details that might be expensive to load
        public BookDetailsDto? Details { get; set; }
    }
}

// Supporting DTOs
public class CategoryDto
{
    public int Id { get; set; }
    public string Name { get; set; } = string.Empty;
    public string? Description { get; set; }
}

public class PublisherDto
{
    public int Id { get; set; }
    public string Name { get; set; } = string.Empty;
    public string? Website { get; set; }
}

public class AuthorDto
{
    public int Id { get; set; }
    public string FirstName { get; set; } = string.Empty;
    public string LastName { get; set; } = string.Empty;
    public string FullName { get; set; } = string.Empty;
    public string? Nationality { get; set; }
}

public class ReviewDto
{
    public int Id { get; set; }
    public int Rating { get; set; }
    public string? Comment { get; set; }
    public string ReviewerName { get; set; } = string.Empty;
    public DateTime CreatedAt { get; set; }
}

public class BookDetailsDto
{
    public int PageCount { get; set; }
    public string? Language { get; set; }
    public string? Format { get; set; }
    public decimal Weight { get; set; }
    public string? Dimensions { get; set; }
}
```

**DTO Conversion Patterns:**
```csharp
// Extensions/BookExtensions.cs
public static class BookExtensions
{
    public static BookDto ToDto(this Book book)
    {
        return new BookDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            ISBN = book.ISBN,
            Price = book.Price,
            PublishedDate = book.PublishedDate,
            Description = book.Description,
            StockQuantity = book.StockQuantity,
            Category = book.Category.ToDto(),
            Publisher = book.Publisher.ToDto(),
            Authors = book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.ToDto())
                .ToList()
        };
    }
    
    public static BookSummaryDto ToSummaryDto(this Book book)
    {
        return new BookSummaryDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            Price = book.Price,
            IsInStock = book.StockQuantity > 0,
            Category = book.Category.Name
        };
    }
    
    public static BookDetailDto ToDetailDto(this Book book)
    {
        var dto = new BookDetailDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            ISBN = book.ISBN,
            Price = book.Price,
            PublishedDate = book.PublishedDate,
            Description = book.Description,
            StockQuantity = book.StockQuantity,
            Category = book.Category.ToDto(),
            Publisher = book.Publisher.ToDto(),
            Authors = book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.ToDto())
                .ToList(),
            CreatedAt = book.CreatedAt,
            UpdatedAt = book.UpdatedAt,
            RecentReviews = book.Reviews
                .OrderByDescending(r => r.CreatedAt)
                .Take(5)
                .Select(r => r.ToDto())
                .ToList(),
            AverageRating = book.Reviews.Any() 
                ? book.Reviews.Average(r => r.Rating) 
                : 0,
            ReviewCount = book.Reviews.Count,
            Details = book.Details?.ToDto()
        };
        
        return dto;
    }
    
    public static Book ToEntity(this CreateBookDto dto)
    {
        return new Book
        {
            Title = dto.Title,
            ISBN = dto.ISBN,
            Price = dto.Price,
            PublishedDate = dto.PublishedDate,
            Description = dto.Description,
            StockQuantity = dto.StockQuantity,
            CategoryId = dto.CategoryId,
            PublisherId = dto.PublisherId,
            CreatedAt = DateTime.UtcNow,
            CreatedBy = "System" // This would come from the current user context
        };
    }
    
    public static void UpdateEntity(this UpdateBookDto dto, Book book)
    {
        book.Title = dto.Title;
        book.ISBN = dto.ISBN;
        book.Price = dto.Price;
        book.PublishedDate = dto.PublishedDate;
        book.Description = dto.Description;
        book.StockQuantity = dto.StockQuantity;
        book.CategoryId = dto.CategoryId;
        book.PublisherId = dto.PublisherId;
        book.UpdatedAt = DateTime.UtcNow;
        book.UpdatedBy = "System" // This would come from the current user context
    }
}
```

##### **Section 2.1.4:** AutoMapper for object mapping

While manual DTO conversion works well for simple scenarios, AutoMapper provides a powerful, convention-based approach to object mapping that can significantly reduce boilerplate code and maintenance overhead. AutoMapper excels in complex scenarios with deep object graphs, conditional mapping, and custom transformation logic.

AutoMapper uses convention-based mapping by default but provides extensive configuration options for customizing the mapping behavior. Understanding how to leverage AutoMapper effectively can make your code cleaner and more maintainable while reducing the likelihood of mapping errors.

**Setting Up AutoMapper:**
```csharp
// Install AutoMapper NuGet packages
// AutoMapper
// AutoMapper.Extensions.Microsoft.DependencyInjection

// Profiles/BookProfile.cs
using AutoMapper;
using BookStoreApi.Entities;
using BookStoreApi.DTOs;

namespace BookStoreApi.Profiles
                        .Select(ba => ba.Author.FullName))))
                .ForMember(dest => dest.Category, opt => opt.MapFrom(src => src.Category.Name))
                .ForMember(dest => dest.IsInStock, opt => opt.MapFrom(src => src.StockQuantity > 0));
            
            CreateMap<Book, BookDetailDto>()
                .IncludeBase<Book, BookDto>()
                .ForMember(dest => dest.AverageRating, opt => opt.MapFrom(src => 
                    src.Reviews.Any() ? src.Reviews.Average(r => r.Rating) : 0))
                .ForMember(dest => dest.ReviewCount, opt => opt.MapFrom(src => src.Reviews.Count))
                .ForMember(dest => dest.RecentReviews, opt => opt.MapFrom(src => 
                    src.Reviews
                        .OrderByDescending(r => r.CreatedAt)
                        .Take(5)));
            
            // DTO to Entity mappings
            CreateMap<CreateBookDto, Book>()
                .ForMember(dest => dest.Id, opt => opt.Ignore())
                .ForMember(dest => dest.CreatedAt, opt => opt.MapFrom(src => DateTime.UtcNow))
                .ForMember(dest => dest.CreatedBy, opt => opt.MapFrom(src => "System"))
                .ForMember(dest => dest.UpdatedAt, opt => opt.Ignore())
                .ForMember(dest => dest.UpdatedBy, opt => opt.Ignore())
                .ForMember(dest => dest.Category, opt => opt.Ignore())
                .ForMember(dest => dest.Publisher, opt => opt.Ignore())
                .ForMember(dest => dest.BookAuthors, opt => opt.Ignore())
                .ForMember(dest => dest.Reviews, opt => opt.Ignore())
                .ForMember(dest => dest.OrderItems, opt => opt.Ignore());
            
            CreateMap<UpdateBookDto, Book>()
                .ForMember(dest => dest.Id, opt => opt.Ignore())
                .ForMember(dest => dest.CreatedAt, opt => opt.Ignore())
                .ForMember(dest => dest.CreatedBy, opt => opt.Ignore())
                .ForMember(dest => dest.UpdatedAt, opt => opt.MapFrom(src => DateTime.UtcNow))
                .ForMember(dest => dest.UpdatedBy, opt => opt.MapFrom(src => "System"))
                .ForMember(dest => dest.Category, opt => opt.Ignore())
                .ForMember(dest => dest.Publisher, opt => opt.Ignore())
                .ForMember(dest => dest.BookAuthors, opt => opt.Ignore())
                .ForMember(dest => dest.Reviews, opt => opt.Ignore())
                .ForMember(dest => dest.OrderItems, opt => opt.Ignore());
            
            // Supporting entity mappings
            CreateMap<Category, CategoryDto>();
            CreateMap<Publisher, PublisherDto>();
            CreateMap<Author, AuthorDto>()
                .ForMember(dest => dest.FullName, opt => opt.MapFrom(src => $"{src.FirstName} {src.LastName}"));
            CreateMap<Review, ReviewDto>()
                .ForMember(dest => dest.ReviewerName, opt => opt.MapFrom(src => src.User.UserName));
            CreateMap<BookDetails, BookDetailsDto>();
        }
    }
}

// Profiles/CategoryProfile.cs
public class CategoryProfile : Profile
{
    public CategoryProfile()
    {
        CreateMap<Category, CategoryDto>();
        CreateMap<Category, CategoryWithBooksDto>()
            .ForMember(dest => dest.BookCount, opt => opt.MapFrom(src => src.Books.Count));
        
        CreateMap<CreateCategoryDto, Category>()
            .ForMember(dest => dest.Id, opt => opt.Ignore())
            .ForMember(dest => dest.IsActive, opt => opt.MapFrom(src => true))
            .ForMember(dest => dest.Books, opt => opt.Ignore());
    }
}
```

**Registering AutoMapper in Program.cs:**
```csharp
var builder = WebApplication.CreateBuilder(args);

// Add services
builder.Services.AddControllers();
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen();

// Add AutoMapper
builder.Services.AddAutoMapper(typeof(BookProfile));

var app = builder.Build();
```

**Using AutoMapper in Services:**
```csharp
// Services/BookService.cs
using AutoMapper;
using AutoMapper.QueryableExtensions;

public class BookService : IBookService
{
    private readonly IBookRepository _bookRepository;
    private readonly IMapper _mapper;
    private readonly ILogger<BookService> _logger;
    
    public BookService(
        IBookRepository bookRepository, 
        IMapper mapper,
        ILogger<BookService> logger)
    {
        _bookRepository = bookRepository;
        _mapper = mapper;
        _logger = logger;
    }
    
    public async Task<List<BookSummaryDto>> GetBooksAsync()
    {
        _logger.LogInformation("Retrieving all books");
        
        var books = await _bookRepository.GetAllAsync();
        return _mapper.Map<List<BookSummaryDto>>(books);
    }
    
    public async Task<BookDetailDto?> GetBookByIdAsync(int id)
    {
        _logger.LogInformation("Retrieving book with ID: {BookId}", id);
        
        var book = await _bookRepository.GetByIdWithDetailsAsync(id);
        if (book == null)
        {
            return null;
        }
        
        return _mapper.Map<BookDetailDto>(book);
    }
    
    public async Task<BookDto> CreateBookAsync(CreateBookDto bookDto)
    {
        _logger.LogInformation("Creating new book: {Title}", bookDto.Title);
        
        // Map DTO to entity
        var book = _mapper.Map<Book>(bookDto);
        
        // Create the book
        var createdBook = await _bookRepository.CreateAsync(book);
        
        // Handle many-to-many relationship for authors
        await _bookRepository.UpdateBookAuthorsAsync(createdBook.Id, bookDto.AuthorIds);
        
        // Retrieve the created book with all related data
        var bookWithDetails = await _bookRepository.GetByIdWithDetailsAsync(createdBook.Id);
        
        return _mapper.Map<BookDto>(bookWithDetails);
    }
    
    public async Task<BookDto> UpdateBookAsync(int id, UpdateBookDto bookDto)
    {
        _logger.LogInformation("Updating book with ID: {BookId}", id);
        
        var existingBook = await _bookRepository.GetByIdAsync(id);
        if (existingBook == null)
        {
            throw new NotFoundException($"Book with ID {id} not found");
        }
        
        // Map DTO properties to existing entity
        _mapper.Map(bookDto, existingBook);
        
        // Update the book
        await _bookRepository.UpdateAsync(existingBook);
        
        // Update many-to-many relationships
        await _bookRepository.UpdateBookAuthorsAsync(id, bookDto.AuthorIds);
        
        // Retrieve updated book with details
        var updatedBook = await _bookRepository.GetByIdWithDetailsAsync(id);
        
        return _mapper.Map<BookDto>(updatedBook);
    }
    
    // Optimized query using ProjectTo for large datasets
    public async Task<PagedResult<BookSummaryDto>> GetBooksPagedAsync(int page, int pageSize, string? search = null)
    {
        _logger.LogInformation("Retrieving paged books: page {Page}, size {PageSize}", page, pageSize);
        
        var query = _bookRepository.GetQueryable();
        
        if (!string.IsNullOrEmpty(search))
        {
            query = query.Where(b => b.Title.Contains(search) || 
                                   b.BookAuthors.Any(ba => ba.Author.FirstName.Contains(search) || 
                                                          ba.Author.LastName.Contains(search)));
        }
        
        var totalCount = await query.CountAsync();
        
        // Use ProjectTo for efficient mapping at the database level
        var books = await query
            .OrderBy(b => b.Title)
            .Skip((page - 1) * pageSize)
            .Take(pageSize)
            .ProjectTo<BookSummaryDto>(_mapper.ConfigurationProvider)
            .ToListAsync();
        
        return new PagedResult<BookSummaryDto>
        {
            Data = books,
            TotalCount = totalCount,
            Page = page,
            PageSize = pageSize,
            TotalPages = (int)Math.Ceiling((double)totalCount / pageSize)
        };
    }
}
```

**Advanced AutoMapper Configuration:**
```csharp
// Profiles/AdvancedMappingProfile.cs
public class AdvancedMappingProfile : Profile
{
    public AdvancedMappingProfile()
    {
        // Conditional mapping
        CreateMap<Book, BookDto>()
            .ForMember(dest => dest.Description, opt => opt.MapFrom((src, dest, destMember, context) =>
            {
                // Only include description if user has permission
                var includeDescription = context.Items.ContainsKey("IncludeDescription") && 
                                       (bool)context.Items["IncludeDescription"];
                return includeDescription ? src.Description : null;
            }));
        
        // Custom value resolvers
        CreateMap<Book, BookDto>()
            .ForMember(dest => dest.Author, opt => opt.MapFrom<AuthorNameResolver>());
        
        // After mapping actions
        CreateMap<CreateBookDto, Book>()
            .AfterMap((src, dest, context) =>
            {
                // Set audit fields
                dest.CreatedAt = DateTime.UtcNow;
                dest.CreatedBy = context.Items.ContainsKey("CurrentUser") 
                    ? context.Items["CurrentUser"].ToString() 
                    : "System";
            });
    }
}

// Custom value resolver
public class AuthorNameResolver : IValueResolver<Book, BookDto, string>
{
    public string Resolve(Book source, BookDto destination, string destMember, ResolutionContext context)
    {
        if (!source.BookAuthors?.Any() == true)
            return "Unknown Author";
        
        var authors = source.BookAuthors
            .OrderBy(ba => ba.Order)
            .Select(ba => ba.Author.FullName)
            .ToList();
        
        return authors.Count switch
        {
            1 => authors[0],
            2 => $"{authors[0]} and {authors[1]}",
            _ => $"{authors[0]} et al."
        };
    }
}
```

---

#### **Challenge 2.1: Design your task management data model**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Create a comprehensive data model for a task management system that demonstrates entity relationships, DTOs, and AutoMapper configuration. This challenge brings together everything you've learned about data modeling.

**What You'll Learn:**
- Complex entity relationship design
- DTO creation for different scenarios
- AutoMapper profile configuration
- Data validation strategies

</div>

**Challenge Requirements:**
1. Design entities for a task management system:
   - `Task` - Main task entity
   - `User` - Users who can create and be assigned tasks
   - `Project` - Tasks belong to projects
   - `Category` - Tasks can be categorized
   - `Comment` - Tasks can have comments
   - `TaskAssignment` - Many-to-many relationship between tasks and users

2. Create appropriate DTOs for:
   - Creating tasks
   - Updating tasks
   - Viewing task details
   - Task summaries for lists

3. Set up AutoMapper profiles for all mappings

4. Implement proper validation using data annotations

**Expected Output:**
By the end of this challenge, you should have a complete data model that could power a task management application like Todoist or Asana.

**Solution Approach:**

**Step 1: Entity Design**
```csharp
// Entities/Task.cs
[Table("Tasks")]
public class Task
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(200)]
    public string Title { get; set; } = string.Empty;
    
    [MaxLength(2000)]
    public string? Description { get; set; }
    
    public TaskStatus Status { get; set; } = TaskStatus.NotStarted;
    
    public TaskPriority Priority { get; set; } = TaskPriority.Medium;
    
    public DateTime? DueDate { get; set; }
    
    public DateTime CreatedAt { get; set; }
    public DateTime? UpdatedAt { get; set; }
    public DateTime? CompletedAt { get; set; }
    
    // Foreign keys
    public int CreatedById { get; set; }
    public int ProjectId { get; set; }
    public int? CategoryId { get; set; }
    
    // Navigation properties
    public User CreatedBy { get; set; } = null!;
    public Project Project { get; set; } = null!;
    public Category? Category { get; set; }
    
    public ICollection<TaskAssignment> TaskAssignments { get; set; } = new List<TaskAssignment>();
    public ICollection<Comment> Comments { get; set; } = new List<Comment>();
}

// Entities/User.cs
[Table("Users")]
public class User
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string FirstName { get; set; } = string.Empty;
    
    [Required]
    [MaxLength(50)]
    public string LastName { get; set; } = string.Empty;
    
    [Required]
    [MaxLength(100)]
    public string Email { get; set; } = string.Empty;
    
    [MaxLength(100)]
    public string? JobTitle { get; set; }
    
    public bool IsActive { get; set; } = true;
    
    public DateTime CreatedAt { get; set; }
    
    [NotMapped]
    public string FullName => $"{FirstName} {LastName}";
    
    // Navigation properties
    public ICollection<Task> CreatedTasks { get; set; } = new List<Task>();
    public ICollection<TaskAssignment> TaskAssignments { get; set; } = new List<TaskAssignment>();
    public ICollection<Comment> Comments { get; set; } = new List<Comment>();
    public ICollection<Project> OwnedProjects { get; set; } = new List<Project>();
}

// Supporting entities...
public enum TaskStatus
{
    NotStarted = 0,
    InProgress = 1,
    Completed = 2,
    Cancelled = 3
}

public enum TaskPriority
{
    Low = 1,
    Medium = 2,
    High = 3,
    Critical = 4
}
```

**Step 2: DTOs**
```csharp
// DTOs/TaskDtos.cs
public class TaskDto
{
    public int Id { get; set; }
    public string Title { get; set; } = string.Empty;
    public string? Description { get; set; }
    public TaskStatus Status { get; set; }
    public TaskPriority Priority { get; set; }
    public DateTime? DueDate { get; set; }
    public DateTime CreatedAt { get; set; }
    public string CreatedBy { get; set; } = string.Empty;
    public string Project { get; set; } = string.Empty;
    public string? Category { get; set; }
    public List<UserDto> AssignedUsers { get; set; } = new();
    public bool IsOverdue => DueDate.HasValue && DueDate < DateTime.Now && Status != TaskStatus.Completed;
}

public class CreateTaskDto
{
    [Required(ErrorMessage = "Title is required")]
    [StringLength(200, MinimumLength = 1)]
    public string Title { get; set; } = string.Empty;
    
    [StringLength(2000)]
    public string? Description { get; set; }
    
    public TaskPriority Priority { get; set; } = TaskPriority.Medium;
    
    public DateTime? DueDate { get; set; }
    
    [Required(ErrorMessage = "Project is required")]
    public int ProjectId { get; set; }
    
    public int? CategoryId { get; set; }
    
    public List<int> AssignedUserIds { get; set; } = new();
}
```

**Step 3: AutoMapper Profile**
```csharp
// Profiles/TaskProfile.cs
public class TaskProfile : Profile
{
    public TaskProfile()
    {
        CreateMap<Task, TaskDto>()
            .ForMember(dest => dest.CreatedBy, opt => opt.MapFrom(src => src.CreatedBy.FullName))
            .ForMember(dest => dest.Project, opt => opt.MapFrom(src => src.Project.Name))
            .ForMember(dest => dest.Category, opt => opt.MapFrom(src => src.Category != null ? src.Category.Name : null))
            .ForMember(dest => dest.AssignedUsers, opt => opt.MapFrom(src => 
                src.TaskAssignments.Select(ta => ta.User)));
        
        CreateMap<CreateTaskDto, Task>()
            .ForMember(dest => dest.Id, opt => opt.Ignore())
            .ForMember(dest => dest.Status, opt => opt.MapFrom(src => TaskStatus.NotStarted))
            .ForMember(dest => dest.CreatedAt, opt => opt.MapFrom(src => DateTime.UtcNow))
            .ForMember(dest => dest.CreatedById, opt => opt.Ignore()) // Set from current user
            .ForMember(dest => dest.CreatedBy, opt => opt.Ignore())
            .ForMember(dest => dest.Project, opt => opt.Ignore())
            .ForMember(dest => dest.Category, opt => opt.Ignore())
            .ForMember(dest => dest.TaskAssignments, opt => opt.Ignore())
            .ForMember(dest => dest.Comments, opt => opt.Ignore());
    }
}
```

<div style="page-break-after: always;"></div>

---

#### Module 2.2: Entity Framework Core Setup

Entity Framework Core setup is where your carefully designed data models come to life as actual database structures. This process involves configuring database connections, creating your DbContext, and setting up the infrastructure that EF Core needs to manage your data persistence.

The setup phase is crucial because decisions made here affect performance, security, and maintainability throughout your application's lifecycle. Modern EF Core provides excellent tooling for database creation and management through migrations, but understanding the underlying concepts helps you troubleshoot issues and optimize performance.

##### **Section 2.2.1:** Setting up SQL Server (LocalDB for development)

SQL Server LocalDB provides an excellent development environment that closely mirrors production SQL Server while being lightweight and easy to set up. It's perfect for development because it requires no administrative configuration and runs as a user process, making it ideal for individual developers and CI/CD scenarios.

Understanding how to configure LocalDB properly sets you up for smooth development workflows and easy transitions to full SQL Server instances in staging and production environments. The connection string configuration and database initialization patterns you learn here apply directly to production scenarios.

**Installing SQL Server LocalDB:**

LocalDB typically comes with Visual Studio installations, but you can also install it separately:

```bash
# Check if LocalDB is already installed
sqllocaldb info

# If not installed, download from Microsoft:
# https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/sql-server-express-localdb

# Create a LocalDB instance (optional - default instance is created automatically)
sqllocaldb create "BookStoreDB" -s
```

**Understanding LocalDB Connection Strings:**

LocalDB connection strings follow specific patterns that differ from full SQL Server instances. Understanding these patterns helps you configure your application correctly and troubleshoot connection issues.

```csharp
// appsettings.json - Development configuration
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB;Trusted_Connection=true;MultipleActiveResultSets=true;TrustServerCertificate=true",
    "LocalDBWithInstance": "Server=(localdb)\\BookStoreInstance;Database=BookStoreDB;Trusted_Connection=true",
    "LocalDBWithDataDirectory": "Data Source=(LocalDB)\\mssqllocaldb;AttachDbFilename=|DataDirectory|\\BookStore.mdf;Integrated Security=True;Connect Timeout=30"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning",
      "Microsoft.EntityFrameworkCore.Database.Command": "Information"
    }
  }
}

// appsettings.Development.json - Override for development
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB_Dev;Trusted_Connection=true;MultipleActiveResultSets=true;TrustServerCertificate=true"
  },
  "Logging": {
    "LogLevel": {
      "Microsoft.EntityFrameworkCore": "Information"
    }
  }
}
```

**Installing Entity Framework Core:**

EF Core requires several NuGet packages depending on your database provider and the features you need:

```bash
# Core Entity Framework packages
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

# Optional but recommended packages
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Analyzers
```

**Creating the DbContext:**

The DbContext is the primary class responsible for interacting with the database. It represents a session with the database and can be used to query and save instances of your entities.

```csharp
// Data/BookStoreDbContext.cs
using Microsoft.EntityFrameworkCore;
using BookStoreApi.Entities;

namespace BookStoreApi.Data
{
    public class BookStoreDbContext : DbContext
    {
        public BookStoreDbContext(DbContextOptions<BookStoreDbContext> options) : base(options)
        {
        }
        
        // DbSets represent tables in the database
        public DbSet<Book> Books { get; set; }
        public DbSet<Author> Authors { get; set; }
        public DbSet<Category> Categories { get; set; }
        public DbSet<Publisher> Publishers { get; set; }
        public DbSet<BookAuthor> BookAuthors { get; set; }
        public DbSet<Review> Reviews { get; set; }
        public DbSet<User> Users { get; set; }
        public DbSet<Order> Orders { get; set; }
        public DbSet<OrderItem> OrderItems { get; set; }
        
        protected override void OnModelCreating(ModelBuilder modelBuilder)
        {
            base.OnModelCreating(modelBuilder);
            
            // Configure entity relationships and constraints
            ConfigureBookEntity(modelBuilder);
            ConfigureAuthorEntity(modelBuilder);
            ConfigureCategoryEntity(modelBuilder);
            ConfigurePublisherEntity(modelBuilder);
            ConfigureBookAuthorEntity(modelBuilder);
            ConfigureReviewEntity(modelBuilder);
            ConfigureUserEntity(modelBuilder);
            ConfigureOrderEntities(modelBuilder);
            
            // Apply configurations from separate files
            modelBuilder.ApplyConfigurationsFromAssembly(typeof(BookStoreDbContext).Assembly);
        }
        
        private void ConfigureBookEntity(ModelBuilder modelBuilder)
        {
            modelBuilder.Entity<Book>(entity =>
            {
                // Table configuration
                entity.ToTable("Books");
                entity.HasKey(e => e.Id);
                
                // Property configurations
                entity.Property(e => e.Title)
                    .IsRequired()
                    .HasMaxLength(200);
                
                entity.Property(e => e.Author)
                    .IsRequired()
                    .HasMaxLength(100);
                
                entity.Property(e => e.ISBN)
                    .IsRequired()
                    .HasMaxLength(20)
                    .HasColumnName("ISBN");
                
                entity.Property(e => e.Price)
                    .HasColumnType("decimal(10,2)")
                    .IsRequired();
                
                entity.Property(e => e.PublishedDate)
                    .HasColumnName("PublicationDate");
                
                entity.Property(e => e.Description)
                    .HasMaxLength(1000);
                
                entity.Property(e => e.CreatedAt)
                    .IsRequired()
                    .HasDefaultValueSql("GETUTCDATE()");
                
                entity.Property(e => e.CreatedBy)
                    .IsRequired()
                    .HasMaxLength(100);
                
                entity.Property(e => e.UpdatedBy)
                    .HasMaxLength(100);
                
                // Indexes
                entity.HasIndex(e => e.ISBN)
                    .IsUnique()
                    .HasDatabaseName("IX_Books_ISBN");
                
                entity.HasIndex(e => e.Title)
                    .HasDatabaseName("IX_Books_Title");
                
                entity.HasIndex(e => new { e.CategoryId, e.PublishedDate })
                    .HasDatabaseName("IX_Books_Category_PublicationDate");
                
                // Relationships
                entity.HasOne(e => e.Category)
                    .WithMany(c => c.Books)
                    .HasForeignKey(e => e.CategoryId)
                    .OnDelete(DeleteBehavior.Restrict)
                    .HasConstraintName("FK_Books_Categories");
                
                entity.HasOne(e => e.Publisher)
                    .WithMany(p => p.Books)
                    .HasForeignKey(e => e.PublisherId)
                    .OnDelete(DeleteBehavior.Restrict)
                    .HasConstraintName("FK_Books_Publishers");
            });
        }
        
        private void ConfigureBookAuthorEntity(ModelBuilder modelBuilder)
        {
            modelBuilder.Entity<BookAuthor>(entity =>
            {
                entity.ToTable("BookAuthors");
                
                // Composite primary key
                entity.HasKey(e => new { e.BookId, e.AuthorId });
                
                entity.Property(e => e.Role)
                    .IsRequired()
                    .HasMaxLength(50)
                    .HasDefaultValue("Author");
                
                entity.Property(e => e.Order)
                    .HasDefaultValue(1);
                
                entity.Property(e => e.ContributedAt)
                    .HasDefaultValueSql("GETUTCDATE()");
                
                // Relationships
                entity.HasOne(e => e.Book)
                    .WithMany(b => b.BookAuthors)
                    .HasForeignKey(e => e.BookId)
                    .OnDelete(DeleteBehavior.Cascade);
                
                entity.HasOne(e => e.Author)
                    .WithMany(a => a.BookAuthors)
                    .HasForeignKey(e => e.AuthorId)
                    .OnDelete(DeleteBehavior.Cascade);
                
                // Indexes
                entity.HasIndex(e => new { e.AuthorId, e.Order })
                    .HasDatabaseName("IX_BookAuthors_Author_Order");
            });
        }
        
        // Override SaveChanges to automatically set audit fields
        public override int SaveChanges()
        {
            UpdateAuditFields();
            return base.SaveChanges();
        }
        
        public override Task<int> SaveChangesAsync(CancellationToken cancellationToken = default)
        {
            UpdateAuditFields();
            return base.SaveChangesAsync(cancellationToken);
        }
        
        private void UpdateAuditFields()
        {
            var entries = ChangeTracker.Entries()
                .Where(e => e.State == EntityState.Added || e.State == EntityState.Modified);
            
            foreach (var entry in entries)
            {
                if (entry.State == EntityState.Added)
                {
                    if (entry.Property("CreatedAt").CurrentValue == null)
                        entry.Property("CreatedAt").CurrentValue = DateTime.UtcNow;
                    
                    if (entry.Property("CreatedBy").CurrentValue == null)
                        entry.Property("CreatedBy").CurrentValue = "System"; // Get from current user context
                }
                
                if (entry.State == EntityState.Modified)
                {
                    entry.Property("UpdatedAt").CurrentValue = DateTime.UtcNow;
                    entry.Property("UpdatedBy").CurrentValue = "System"; // Get from current user context
                }
            }
        }
    }
}
```

##### **Section 2.2.2:** Connection strings and configuration

Connection string configuration is more than just providing database credentials—it involves understanding security implications, environment-specific settings, and performance optimizations. Modern .NET applications use the configuration system to manage these settings in a secure, flexible way.

Understanding the various connection string options helps you optimize for different scenarios, from development environments with relaxed security to production systems with stringent requirements for encryption and connection pooling.

**Secure Connection String Management:**

```csharp
// Program.cs - Connection string configuration
var builder = WebApplication.CreateBuilder(args);

// Add services to the container
builder.Services.AddControllers();
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen();

// Configure Entity Framework
builder.Services.AddDbContext<BookStoreDbContext>(options =>
{
    var connectionString = builder.Configuration.GetConnectionString("DefaultConnection");
    
    options.UseSqlServer(connectionString, sqlServerOptions =>
    {
        // Enable retry on failure for connection resiliency
        sqlServerOptions.EnableRetryOnFailure(
            maxRetryCount: 3,
            maxRetryDelay: TimeSpan.FromSeconds(30),
            errorNumbersToAdd: null);
        
        // Set command timeout
        sqlServerOptions.CommandTimeout(30);
        
        // Configure migrations assembly (useful for separate migration projects)
        sqlServerOptions.MigrationsAssembly(typeof(BookStoreDbContext).Assembly.FullName);
    });
    
    // Configure EF Core options
    if (builder.Environment.IsDevelopment())
    {
        // Enable sensitive data logging in development
        options.EnableSensitiveDataLogging();
        options.EnableDetailedErrors();
    }
    
    // Configure query behavior
    options.ConfigureWarnings(warnings =>
    {
        warnings.Default(WarningBehavior.Log);
        warnings.Log(CoreEventId.FirstWithoutOrderByAndFilterWarning);
    });
});

var app = builder.Build();

// Ensure database is created and migrated
using (var scope = app.Services.CreateScope())
{
    var dbContext = scope.ServiceProvider.GetRequiredService<BookStoreDbContext>();
    
    if (app.Environment.IsDevelopment())
    {
        // Create database if it doesn't exist
        dbContext.Database.EnsureCreated();
        
        // Or apply migrations
                 // dbContext.Database.Migrate();
     }
 }
 ```

**Environment-Specific Configuration:**

```json
// appsettings.json - Base configuration
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB;Trusted_Connection=true"
  }
}

// appsettings.Development.json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB_Dev;Trusted_Connection=true;MultipleActiveResultSets=true"
  },
  "Logging": {
    "LogLevel": {
      "Microsoft.EntityFrameworkCore.Database.Command": "Information"
    }
  }
}

// appsettings.Production.json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=prod-sql-server;Database=BookStoreDB;User Id=app_user;Password=#{DB_PASSWORD}#;Encrypt=true;TrustServerCertificate=false"
  }
}
```

**Using User Secrets for Development:**

```bash
# Initialize user secrets
dotnet user-secrets init

# Set connection string
dotnet user-secrets set "ConnectionStrings:DefaultConnection" "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB_Local;Trusted_Connection=true"

# Set other sensitive data
dotnet user-secrets set "JwtSettings:SecretKey" "your-super-secret-key-here"
```

**Connection String Options Explained:**

```csharp
// Connection string parameters and their purposes
var connectionStringBuilder = new SqlConnectionStringBuilder
{
    // Basic connection parameters
    DataSource = "(localdb)\\mssqllocaldb",      // SQL Server instance
    InitialCatalog = "BookStoreDB",               // Database name
    IntegratedSecurity = true,                    // Use Windows authentication
    
    // Performance and reliability
    MultipleActiveResultSets = true,             // Allow multiple result sets
    ConnectTimeout = 30,                         // Connection timeout in seconds
    CommandTimeout = 60,                         // Command execution timeout
    Pooling = true,                              // Enable connection pooling
    MinPoolSize = 5,                             // Minimum connections in pool
    MaxPoolSize = 100,                           // Maximum connections in pool
    
    // Security (for non-development environments)
    Encrypt = true,                              // Encrypt connection
    TrustServerCertificate = false,              // Validate server certificate
    
    // Application specific
    ApplicationName = "BookStore API",           // Application identifier
    Workstation = Environment.MachineName       // Client machine name
};

var connectionString = connectionStringBuilder.ConnectionString;
```

##### **Section 2.2.3:** Your first database migration

Database migrations are EF Core's way of managing database schema changes over time. They provide a version-controlled, repeatable way to evolve your database structure as your application requirements change. Understanding migrations is crucial for maintaining databases across different environments and deployments.

Migrations capture the differences between your current entity models and the existing database schema, generating the necessary SQL commands to update the database. This approach ensures that database changes are applied consistently across development, testing, and production environments.

**Creating Your First Migration:**

```bash
# Add the first migration (this creates the initial database schema)
dotnet ef migrations add InitialCreate

# Review the generated migration files before applying
# They will be in the Migrations folder

# Apply the migration to create the database
dotnet ef database update

# Check migration status
dotnet ef migrations list
```

**Understanding Migration Files:**

When you create a migration, EF Core generates three files:

```csharp
// Migrations/20241201120000_InitialCreate.cs
using Microsoft.EntityFrameworkCore.Migrations;

#nullable disable

namespace BookStoreApi.Migrations
{
    /// <inheritdoc />
    public partial class InitialCreate : Migration
    {
        /// <inheritdoc />
        protected override void Up(MigrationBuilder migrationBuilder)
        {
            migrationBuilder.CreateTable(
                name: "Categories",
                columns: table => new
                {
                    Id = table.Column<int>(type: "int", nullable: false)
                        .Annotation("SqlServer:Identity", "1, 1"),
                    Name = table.Column<string>(type: "nvarchar(50)", maxLength: 50, nullable: false),
                    Description = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: true),
                    IsActive = table.Column<bool>(type: "bit", nullable: false, defaultValue: true)
                },
                constraints: table =>
                {
                    table.PrimaryKey("PK_Categories", x => x.Id);
                });

            migrationBuilder.CreateTable(
                name: "Publishers",
                columns: table => new
                {
                    Id = table.Column<int>(type: "int", nullable: false)
                        .Annotation("SqlServer:Identity", "1, 1"),
                    Name = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: false),
                    Address = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: true),
                    Email = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: true),
                    Phone = table.Column<string>(type: "nvarchar(20)", maxLength: 20, nullable: true),
                    Website = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: true),
                    CreatedAt = table.Column<DateTime>(type: "datetime2", nullable: false, defaultValueSql: "GETUTCDATE()")
                },
                constraints: table =>
                {
                    table.PrimaryKey("PK_Publishers", x => x.Id);
                });

            migrationBuilder.CreateTable(
                name: "Authors",
                columns: table => new
                {
                    Id = table.Column<int>(type: "int", nullable: false)
                        .Annotation("SqlServer:Identity", "1, 1"),
                    FirstName = table.Column<string>(type: "nvarchar(50)", maxLength: 50, nullable: false),
                    LastName = table.Column<string>(type: "nvarchar(50)", maxLength: 50, nullable: false),
                    Biography = table.Column<string>(type: "nvarchar(1000)", maxLength: 1000, nullable: true),
                    BirthDate = table.Column<DateTime>(type: "datetime2", nullable: true),
                    DeathDate = table.Column<DateTime>(type: "datetime2", nullable: true),
                    Nationality = table.Column<string>(type: "nvarchar(50)", maxLength: 50, nullable: true),
                    Email = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: true),
                    Website = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: true)
                },
                constraints: table =>
                {
                    table.PrimaryKey("PK_Authors", x => x.Id);
                });

            migrationBuilder.CreateTable(
                name: "Books",
                columns: table => new
                {
                    Id = table.Column<int>(type: "int", nullable: false)
                        .Annotation("SqlServer:Identity", "1, 1"),
                    Title = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: false),
                    Author = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: false),
                    ISBN = table.Column<string>(type: "nvarchar(20)", maxLength: 20, nullable: false),
                    Price = table.Column<decimal>(type: "decimal(10,2)", nullable: false),
                    PublicationDate = table.Column<DateTime>(type: "datetime2", nullable: false),
                    Description = table.Column<string>(type: "nvarchar(1000)", maxLength: 1000, nullable: true),
                    StockQuantity = table.Column<int>(type: "int", nullable: false),
                    CreatedAt = table.Column<DateTime>(type: "datetime2", nullable: false, defaultValueSql: "GETUTCDATE()"),
                    UpdatedAt = table.Column<DateTime>(type: "datetime2", nullable: true),
                    CreatedBy = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: false),
                    UpdatedBy = table.Column<string>(type: "nvarchar(100)", maxLength: 100, nullable: true),
                    CategoryId = table.Column<int>(type: "int", nullable: false),
                    PublisherId = table.Column<int>(type: "int", nullable: false)
                },
                constraints: table =>
                {
                    table.PrimaryKey("PK_Books", x => x.Id);
                    table.ForeignKey(
                        name: "FK_Books_Categories",
                        column: x => x.CategoryId,
                        principalTable: "Categories",
                        principalColumn: "Id",
                        onDelete: ReferentialAction.Restrict);
                    table.ForeignKey(
                        name: "FK_Books_Publishers",
                        column: x => x.PublisherId,
                        principalTable: "Publishers",
                        principalColumn: "Id",
                        onDelete: ReferentialAction.Restrict);
                });

            // Create indexes
            migrationBuilder.CreateIndex(
                name: "IX_Books_Category_PublicationDate",
                table: "Books",
                columns: new[] { "CategoryId", "PublicationDate" });

            migrationBuilder.CreateIndex(
                name: "IX_Books_ISBN",
                table: "Books",
                column: "ISBN",
                unique: true);

            migrationBuilder.CreateIndex(
                name: "IX_Books_Title",
                table: "Books",
                column: "Title");
        }

        /// <inheritdoc />
        protected override void Down(MigrationBuilder migrationBuilder)
        {
            migrationBuilder.DropTable(name: "Books");
            migrationBuilder.DropTable(name: "Authors");
            migrationBuilder.DropTable(name: "Publishers");
            migrationBuilder.DropTable(name: "Categories");
        }
    }
}
```

**Managing Migration Changes:**

```bash
# Add a new migration for entity changes
dotnet ef migrations add AddBookReviews

# Remove the last migration (if not applied yet)
dotnet ef migrations remove

# Reset database to a specific migration
dotnet ef database update InitialCreate

# Generate SQL script for a migration
dotnet ef migrations script InitialCreate AddBookReviews

# Reset database completely
dotnet ef database drop
dotnet ef database update
```

**Migration Best Practices:**

```csharp
// Custom migration for data transformation
public partial class UpdateBookAuthors : Migration
{
    protected override void Up(MigrationBuilder migrationBuilder)
    {
        // Add new column
        migrationBuilder.AddColumn<string>(
            name: "MainAuthor",
            table: "Books",
            type: "nvarchar(100)",
            maxLength: 100,
            nullable: true);

        // Custom SQL for data migration
        migrationBuilder.Sql(@"
            UPDATE Books 
            SET MainAuthor = Author 
            WHERE MainAuthor IS NULL");

        // Make column required after data migration
        migrationBuilder.AlterColumn<string>(
            name: "MainAuthor",
            table: "Books",
            type: "nvarchar(100)",
            maxLength: 100,
            nullable: false,
            oldClrType: typeof(string),
            oldType: "nvarchar(100)",
            oldMaxLength: 100,
            oldNullable: true);
    }

    protected override void Down(MigrationBuilder migrationBuilder)
    {
        migrationBuilder.DropColumn(
            name: "MainAuthor",
            table: "Books");
    }
}
```

##### **Section 2.2.4:** Seeding initial data

Database seeding is the process of populating your database with initial data that your application needs to function properly. This might include reference data like categories, initial user accounts, or sample data for development and testing. EF Core provides several approaches for seeding data, each suited to different scenarios.

Understanding when and how to seed data properly ensures your application can start up correctly in any environment, from local development to production deployment. Proper seeding strategies also make your database portable and your application more reliable.

**Seed Data in OnModelCreating:**

```csharp
// Data/BookStoreDbContext.cs - Add to OnModelCreating method
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    base.OnModelCreating(modelBuilder);
    
    // ... existing configuration ...
    
    // Seed reference data
    SeedReferenceData(modelBuilder);
    
    // Seed development data (only in development)
    if (_environment?.IsDevelopment() == true)
    {
        SeedDevelopmentData(modelBuilder);
    }
}

private void SeedReferenceData(ModelBuilder modelBuilder)
{
    // Seed Categories
    modelBuilder.Entity<Category>().HasData(
        new Category { Id = 1, Name = "Programming", Description = "Software development and programming books", IsActive = true },
        new Category { Id = 2, Name = "Technology", Description = "General technology and computing books", IsActive = true },
        new Category { Id = 3, Name = "Business", Description = "Business and management books", IsActive = true },
        new Category { Id = 4, Name = "Science", Description = "Science and research books", IsActive = true },
        new Category { Id = 5, Name = "Fiction", Description = "Fiction and literary works", IsActive = true }
    );

    // Seed Publishers
    modelBuilder.Entity<Publisher>().HasData(
        new Publisher 
        { 
            Id = 1, 
            Name = "O'Reilly Media", 
            Address = "1005 Gravenstein Highway North, Sebastopol, CA 95472",
            Email = "info@oreilly.com",
            Website = "https://www.oreilly.com",
            CreatedAt = new DateTime(2024, 1, 1)
        },
        new Publisher 
        { 
            Id = 2, 
            Name = "Addison-Wesley", 
            Address = "Boston, MA",
            Email = "info@addison-wesley.com",
            Website = "https://www.addison-wesley.com",
            CreatedAt = new DateTime(2024, 1, 1)
        },
        new Publisher 
        { 
            Id = 3, 
            Name = "Manning Publications", 
            Address = "20 Baldwin Road, Shelter Island, NY 11964",
            Email = "info@manning.com",
            Website = "https://www.manning.com",
            CreatedAt = new DateTime(2024, 1, 1)
        }
    );

    // Seed Authors
    modelBuilder.Entity<Author>().HasData(
        new Author 
        { 
            Id = 1, 
            FirstName = "Robert", 
            LastName = "Martin", 
            Biography = "Robert C. Martin is a software engineer and author best known for being one of the authors of the Agile Manifesto and for developing several software design principles.",
            BirthDate = new DateTime(1952, 12, 5),
            Nationality = "American",
            Email = "unclebob@objectmentor.com"
        },
        new Author 
        { 
            Id = 2, 
            FirstName = "Martin", 
            LastName = "Fowler", 
            Biography = "Martin Fowler is a British software developer, author and international public speaker on software development.",
            BirthDate = new DateTime(1963, 12, 18),
            Nationality = "British",
            Website = "https://martinfowler.com"
        },
        new Author 
        { 
            Id = 3, 
            FirstName = "Eric", 
            LastName = "Evans", 
            Biography = "Eric Evans is a software engineer and consultant who has written influential books on software design.",
            Nationality = "American"
        }
    );
}

private void SeedDevelopmentData(ModelBuilder modelBuilder)
{
    // Seed sample books for development
    modelBuilder.Entity<Book>().HasData(
        new Book
        {
            Id = 1,
            Title = "Clean Code: A Handbook of Agile Software Craftsmanship",
            Author = "Robert C. Martin", // This will be refactored later when we implement many-to-many
            ISBN = "978-0132350884",
            Price = 42.99m,
            PublishedDate = new DateTime(2008, 8, 1),
            Description = "Even bad code can function. But if code isn't clean, it can bring a development organization to its knees.",
            StockQuantity = 15,
            CategoryId = 1,
            PublisherId = 2,
            CreatedAt = new DateTime(2024, 1, 1),
            CreatedBy = "System"
        },
        new Book
        {
            Id = 2,
            Title = "Refactoring: Improving the Design of Existing Code",
            Author = "Martin Fowler",
            ISBN = "978-0134757599",
            Price = 54.99m,
            PublishedDate = new DateTime(2018, 11, 20),
            Description = "Refactoring is a controlled technique for improving the design of an existing code base.",
            StockQuantity = 8,
            CategoryId = 1,
            PublisherId = 2,
            CreatedAt = new DateTime(2024, 1, 1),
            CreatedBy = "System"
        },
        new Book
        {
            Id = 3,
            Title = "Domain-Driven Design: Tackling Complexity in the Heart of Software",
            Author = "Eric Evans",
            ISBN = "978-0321125217",
            Price = 59.99m,
            PublishedDate = new DateTime(2003, 8, 22),
            Description = "This book presents a top-down approach to understanding domain-driven design.",
            StockQuantity = 12,
            CategoryId = 1,
            PublisherId = 2,
            CreatedAt = new DateTime(2024, 1, 1),
            CreatedBy = "System"
        }
    );

    // Seed BookAuthor relationships
    modelBuilder.Entity<BookAuthor>().HasData(
        new BookAuthor { BookId = 1, AuthorId = 1, Role = "Author", Order = 1, ContributedAt = new DateTime(2024, 1, 1) },
        new BookAuthor { BookId = 2, AuthorId = 2, Role = "Author", Order = 1, ContributedAt = new DateTime(2024, 1, 1) },
        new BookAuthor { BookId = 3, AuthorId = 3, Role = "Author", Order = 1, ContributedAt = new DateTime(2024, 1, 1) }
    );
}
```

**Alternative Seeding with Data Service:**

```csharp
// Services/IDataSeedService.cs
public interface IDataSeedService
{
    Task SeedAsync();
}

// Services/DataSeedService.cs
public class DataSeedService : IDataSeedService
{
    private readonly BookStoreDbContext _context;
    private readonly ILogger<DataSeedService> _logger;

    public DataSeedService(BookStoreDbContext context, ILogger<DataSeedService> logger)
    {
        _context = context;
        _logger = logger;
    }

    public async Task SeedAsync()
    {
        try
        {
            await SeedCategoriesAsync();
            await SeedPublishersAsync();
            await SeedAuthorsAsync();
            await SeedBooksAsync();
            
            await _context.SaveChangesAsync();
            _logger.LogInformation("Database seeding completed successfully");
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "Error occurred while seeding database");
            throw;
        }
    }

    private async Task SeedCategoriesAsync()
    {
        if (await _context.Categories.AnyAsync()) return;

        var categories = new[]
        {
            new Category { Name = "Programming", Description = "Software development and programming books", IsActive = true },
            new Category { Name = "Technology", Description = "General technology and computing books", IsActive = true },
            new Category { Name = "Business", Description = "Business and management books", IsActive = true },
            new Category { Name = "Science", Description = "Science and research books", IsActive = true },
            new Category { Name = "Fiction", Description = "Fiction and literary works", IsActive = true }
        };

        await _context.Categories.AddRangeAsync(categories);
        _logger.LogInformation("Seeded {Count} categories", categories.Length);
    }

    private async Task SeedPublishersAsync()
    {
        if (await _context.Publishers.AnyAsync()) return;

        var publishers = new[]
        {
            new Publisher 
            { 
                Name = "O'Reilly Media", 
                Address = "1005 Gravenstein Highway North, Sebastopol, CA 95472",
                Email = "info@oreilly.com",
                Website = "https://www.oreilly.com",
                CreatedAt = DateTime.UtcNow
            },
            new Publisher 
            { 
                Name = "Addison-Wesley", 
                Address = "Boston, MA",
                Email = "info@addison-wesley.com",
                Website = "https://www.addison-wesley.com",
                CreatedAt = DateTime.UtcNow
            }
        };

        await _context.Publishers.AddRangeAsync(publishers);
        _logger.LogInformation("Seeded {Count} publishers", publishers.Length);
    }

    private async Task SeedAuthorsAsync()
    {
        if (await _context.Authors.AnyAsync()) return;

        var authors = new[]
        {
            new Author 
            { 
                FirstName = "Robert", 
                LastName = "Martin", 
                Biography = "Robert C. Martin is a software engineer and author best known for being one of the authors of the Agile Manifesto.",
                BirthDate = new DateTime(1952, 12, 5),
                Nationality = "American",
                Email = "unclebob@objectmentor.com"
            },
            new Author 
            { 
                FirstName = "Martin", 
                LastName = "Fowler", 
                Biography = "Martin Fowler is a British software developer, author and international public speaker on software development.",
                BirthDate = new DateTime(1963, 12, 18),
                Nationality = "British",
                Website = "https://martinfowler.com"
            }
        };

        await _context.Authors.AddRangeAsync(authors);
        _logger.LogInformation("Seeded {Count} authors", authors.Length);
    }

    private async Task SeedBooksAsync()
    {
        if (await _context.Books.AnyAsync()) return;

        // Get seeded data IDs
        var programmingCategory = await _context.Categories.FirstAsync(c => c.Name == "Programming");
        var addisonWesley = await _context.Publishers.FirstAsync(p => p.Name == "Addison-Wesley");
        var robertMartin = await _context.Authors.FirstAsync(a => a.LastName == "Martin");

        var books = new[]
        {
            new Book
            {
                Title = "Clean Code: A Handbook of Agile Software Craftsmanship",
                Author = "Robert C. Martin",
                ISBN = "978-0132350884",
                Price = 42.99m,
                PublishedDate = new DateTime(2008, 8, 1),
                Description = "Even bad code can function. But if code isn't clean, it can bring a development organization to its knees.",
                StockQuantity = 15,
                CategoryId = programmingCategory.Id,
                PublisherId = addisonWesley.Id,
                CreatedAt = DateTime.UtcNow,
                CreatedBy = "System"
            }
        };

        await _context.Books.AddRangeAsync(books);
        _logger.LogInformation("Seeded {Count} books", books.Length);
    }
}

// Register service in Program.cs
builder.Services.AddScoped<IDataSeedService, DataSeedService>();

// Use in Program.cs after building the app
using (var scope = app.Services.CreateScope())
{
    var dataSeedService = scope.ServiceProvider.GetRequiredService<IDataSeedService>();
    await dataSeedService.SeedAsync();
}
```

##### **Section 2.2.5:** Using SQL Server Management Studio

SQL Server Management Studio (SSMS) is a powerful integrated environment for managing SQL Server infrastructure. While not strictly necessary for .NET development (since you can accomplish most tasks through EF Core), SSMS provides invaluable insights into your database structure, performance, and data that can help you debug issues and optimize queries.

Understanding how to use SSMS effectively makes you a more complete developer by giving you direct access to your database, allowing you to run ad-hoc queries, examine execution plans, and understand exactly what your ORM is doing behind the scenes.

**Installing and Connecting to LocalDB:**

```bash
# Download SSMS from Microsoft:
# https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms

# Connect to LocalDB instance
# Server name: (localdb)\mssqllocaldb
# Authentication: Windows Authentication
```

**Useful SSMS Features for Development:**

**1. Viewing Generated Schema:**
After running your migrations, you can examine the actual database structure:

```sql
-- View all tables
SELECT TABLE_NAME, TABLE_SCHEMA 
FROM INFORMATION_SCHEMA.TABLES 
WHERE TABLE_TYPE = 'BASE TABLE'
ORDER BY TABLE_NAME;

-- View table structure
SELECT 
    COLUMN_NAME,
    DATA_TYPE,
    IS_NULLABLE,
    COLUMN_DEFAULT,
    CHARACTER_MAXIMUM_LENGTH
FROM INFORMATION_SCHEMA.COLUMNS
WHERE TABLE_NAME = 'Books'
ORDER BY ORDINAL_POSITION;

-- View foreign key relationships
SELECT 
    fk.name AS ForeignKey,
    tp.name AS ParentTable,
    cp.name AS ParentColumn,
    tr.name AS ReferencedTable,
    cr.name AS ReferencedColumn
FROM sys.foreign_keys fk
INNER JOIN sys.tables tp ON fk.parent_object_id = tp.object_id
INNER JOIN sys.tables tr ON fk.referenced_object_id = tr.object_id
INNER JOIN sys.foreign_key_columns fkc ON fkc.constraint_object_id = fk.object_id
INNER JOIN sys.columns cp ON fkc.parent_column_id = cp.column_id AND fkc.parent_object_id = cp.object_id
INNER JOIN sys.columns cr ON fkc.referenced_column_id = cr.column_id AND fkc.referenced_object_id = cr.object_id
ORDER BY tp.name, cp.name;
```

**2. Testing Queries:**
Use SSMS to test and optimize your queries before implementing them in code:

```sql
-- Test complex queries
SELECT 
    b.Id,
    b.Title,
    b.Price,
    c.Name AS Category,
    p.Name AS Publisher,
    STRING_AGG(CONCAT(a.FirstName, ' ', a.LastName), ', ') AS Authors
FROM Books b
INNER JOIN Categories c ON b.CategoryId = c.Id
INNER JOIN Publishers p ON b.PublisherId = p.Id
INNER JOIN BookAuthors ba ON b.Id = ba.BookId
INNER JOIN Authors a ON ba.AuthorId = a.Id
WHERE b.StockQuantity > 0
GROUP BY b.Id, b.Title, b.Price, c.Name, p.Name
ORDER BY b.Title;

-- Check query execution plan
-- Click "Include Actual Execution Plan" before running
-- This helps identify performance bottlenecks

-- View index usage
SELECT 
    i.name AS IndexName,
    i.type_desc AS IndexType,
    s.user_seeks,
    s.user_scans,
    s.user_lookups,
    s.user_updates
FROM sys.indexes i
LEFT JOIN sys.dm_db_index_usage_stats s ON i.object_id = s.object_id AND i.index_id = s.index_id
WHERE i.object_id = OBJECT_ID('Books')
ORDER BY s.user_seeks + s.user_scans + s.user_lookups DESC;
```

**3. Database Maintenance:**
```sql
-- Check database size
SELECT 
    DB_NAME() AS DatabaseName,
    SUM(size * 8) / 1024 AS SizeMB
FROM sys.database_files;

-- View migration history
SELECT * FROM __EFMigrationsHistory ORDER BY MigrationId;

-- Backup database for development
BACKUP DATABASE BookStoreDB_Dev 
TO DISK = 'C:\Temp\BookStoreDB_Dev_Backup.bak'
WITH FORMAT, INIT;

-- Restore database
RESTORE DATABASE BookStoreDB_Dev_Copy
FROM DISK = 'C:\Temp\BookStoreDB_Dev_Backup.bak'
WITH MOVE 'BookStoreDB_Dev' TO 'C:\Temp\BookStoreDB_Dev_Copy.mdf',
          MOVE 'BookStoreDB_Dev_Log' TO 'C:\Temp\BookStoreDB_Dev_Copy.ldf';
 ```

---

#### **Challenge 2.2: Set up your database**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Set up a complete Entity Framework Core environment with LocalDB, create your first migration, seed data, and verify everything works correctly. This challenge consolidates all the database setup concepts you've learned.

**What You'll Learn:**
- Complete EF Core configuration
- Migration creation and management
- Data seeding strategies
- Database verification using SSMS
- Troubleshooting common setup issues

</div>

**Challenge Requirements:**

1. **Configure Entity Framework:**
   - Install required NuGet packages
   - Configure DbContext with LocalDB connection
   - Set up proper logging for development

2. **Create and Apply Migration:**
   - Create initial migration for your book store entities
   - Apply migration to create database
   - Verify migration was applied successfully

3. **Implement Data Seeding:**
   - Seed at least 3 categories, 2 publishers, and 3 authors
   - Seed 5 sample books with proper relationships
   - Ensure seeded data is properly related

4. **Verify Database Setup:**
   - Connect using SSMS or similar tool
   - Run queries to verify data integrity
   - Check that indexes were created correctly

5. **Test CRUD Operations:**
   - Create a simple test to add, read, update, and delete a book
   - Verify operations work correctly

**Expected Output:**
When complete, you should have a fully functional database with seeded data that you can query and manipulate through your application.

**Solution:**

**Step 1: Package Installation**
```bash
# Navigate to your project directory
cd BookStoreApi

# Install required packages
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Design

# Verify packages are installed
dotnet list package
```

**Step 2: Configure Connection String**
```json
// appsettings.json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=BookStoreDB_Challenge;Trusted_Connection=true;MultipleActiveResultSets=true;TrustServerCertificate=true"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning",
      "Microsoft.EntityFrameworkCore.Database.Command": "Information"
    }
  },
  "AllowedHosts": "*"
}
```

**Step 3: Complete DbContext Implementation**
```csharp
// Data/BookStoreDbContext.cs
using Microsoft.EntityFrameworkCore;
using BookStoreApi.Entities;

namespace BookStoreApi.Data
{
    public class BookStoreDbContext : DbContext
    {
        public BookStoreDbContext(DbContextOptions<BookStoreDbContext> options) : base(options)
        {
        }
        
        public DbSet<Book> Books { get; set; }
        public DbSet<Author> Authors { get; set; }
        public DbSet<Category> Categories { get; set; }
        public DbSet<Publisher> Publishers { get; set; }
        public DbSet<BookAuthor> BookAuthors { get; set; }
        public DbSet<Review> Reviews { get; set; }
        public DbSet<User> Users { get; set; }
        public DbSet<Order> Orders { get; set; }
        public DbSet<OrderItem> OrderItems { get; set; }
        
        protected override void OnModelCreating(ModelBuilder modelBuilder)
        {
            base.OnModelCreating(modelBuilder);
            
            ConfigureEntities(modelBuilder);
            SeedData(modelBuilder);
        }
        
        private void ConfigureEntities(ModelBuilder modelBuilder)
        {
            // Book configuration
            modelBuilder.Entity<Book>(entity =>
            {
                entity.HasKey(e => e.Id);
                entity.Property(e => e.Title).IsRequired().HasMaxLength(200);
                entity.Property(e => e.ISBN).IsRequired().HasMaxLength(20);
                entity.Property(e => e.Price).HasColumnType("decimal(10,2)");
                entity.HasIndex(e => e.ISBN).IsUnique();
                
                entity.HasOne(e => e.Category)
                    .WithMany(c => c.Books)
                    .HasForeignKey(e => e.CategoryId)
                    .OnDelete(DeleteBehavior.Restrict);
                    
                entity.HasOne(e => e.Publisher)
                    .WithMany(p => p.Books)
                    .HasForeignKey(e => e.PublisherId)
                    .OnDelete(DeleteBehavior.Restrict);
            });
            
            // BookAuthor many-to-many configuration
            modelBuilder.Entity<BookAuthor>(entity =>
            {
                entity.HasKey(e => new { e.BookId, e.AuthorId });
                
                entity.HasOne(e => e.Book)
                    .WithMany(b => b.BookAuthors)
                    .HasForeignKey(e => e.BookId);
                    
                entity.HasOne(e => e.Author)
                    .WithMany(a => a.BookAuthors)
                    .HasForeignKey(e => e.AuthorId);
            });
        }
        
        private void SeedData(ModelBuilder modelBuilder)
        {
            // Seed Categories
            modelBuilder.Entity<Category>().HasData(
                new Category { Id = 1, Name = "Programming", Description = "Software development books", IsActive = true },
                new Category { Id = 2, Name = "Technology", Description = "Technology and computing books", IsActive = true },
                new Category { Id = 3, Name = "Business", Description = "Business and management books", IsActive = true }
            );
            
            // Seed Publishers
            modelBuilder.Entity<Publisher>().HasData(
                new Publisher 
                { 
                    Id = 1, 
                    Name = "O'Reilly Media", 
                    Email = "info@oreilly.com",
                    Website = "https://www.oreilly.com",
                    CreatedAt = DateTime.UtcNow
                },
                new Publisher 
                { 
                    Id = 2, 
                    Name = "Addison-Wesley", 
                    Email = "info@addison-wesley.com",
                    Website = "https://www.addison-wesley.com",
                    CreatedAt = DateTime.UtcNow
                }
            );
            
            // Seed Authors
            modelBuilder.Entity<Author>().HasData(
                new Author 
                { 
                    Id = 1, 
                    FirstName = "Robert", 
                    LastName = "Martin", 
                    Nationality = "American",
                    Email = "unclebob@objectmentor.com"
                },
                new Author 
                { 
                    Id = 2, 
                    FirstName = "Martin", 
                    LastName = "Fowler", 
                    Nationality = "British",
                    Website = "https://martinfowler.com"
                },
                new Author 
                { 
                    Id = 3, 
                    FirstName = "Eric", 
                    LastName = "Evans", 
                    Nationality = "American"
                }
            );
            
            // Seed Books
            modelBuilder.Entity<Book>().HasData(
                new Book
                {
                    Id = 1,
                    Title = "Clean Code",
                    Author = "Robert C. Martin",
                    ISBN = "978-0132350884",
                    Price = 42.99m,
                    PublishedDate = new DateTime(2008, 8, 1),
                    Description = "A handbook of agile software craftsmanship",
                    StockQuantity = 15,
                    CategoryId = 1,
                    PublisherId = 2,
                    CreatedAt = DateTime.UtcNow,
                    CreatedBy = "System"
                },
                new Book
                {
                    Id = 2,
                    Title = "Refactoring",
                    Author = "Martin Fowler",
                    ISBN = "978-0134757599",
                    Price = 54.99m,
                    PublishedDate = new DateTime(2018, 11, 20),
                    Description = "Improving the design of existing code",
                    StockQuantity = 8,
                    CategoryId = 1,
                    PublisherId = 2,
                    CreatedAt = DateTime.UtcNow,
                    CreatedBy = "System"
                },
                new Book
                {
                    Id = 3,
                    Title = "Domain-Driven Design",
                    Author = "Eric Evans",
                    ISBN = "978-0321125217",
                    Price = 59.99m,
                    PublishedDate = new DateTime(2003, 8, 22),
                    Description = "Tackling complexity in software",
                    StockQuantity = 12,
                    CategoryId = 1,
                    PublisherId = 2,
                    CreatedAt = DateTime.UtcNow,
                    CreatedBy = "System"
                },
                new Book
                {
                    Id = 4,
                    Title = "The Lean Startup",
                    Author = "Eric Ries",
                    ISBN = "978-0307887894",
                    Price = 29.99m,
                    PublishedDate = new DateTime(2011, 9, 13),
                    Description = "How constant innovation creates radically successful businesses",
                    StockQuantity = 20,
                    CategoryId = 3,
                    PublisherId = 1,
                    CreatedAt = DateTime.UtcNow,
                    CreatedBy = "System"
                },
                new Book
                {
                    Id = 5,
                    Title = "JavaScript: The Good Parts",
                    Author = "Douglas Crockford",
                    ISBN = "978-0596517748",
                    Price = 34.99m,
                    PublishedDate = new DateTime(2008, 5, 1),
                    Description = "Unearthing the excellence in JavaScript",
                    StockQuantity = 7,
                    CategoryId = 1,
                    PublisherId = 1,
                    CreatedAt = DateTime.UtcNow,
                    CreatedBy = "System"
                }
            );
            
            // Seed BookAuthor relationships
            modelBuilder.Entity<BookAuthor>().HasData(
                new BookAuthor { BookId = 1, AuthorId = 1, Role = "Author", Order = 1, ContributedAt = DateTime.UtcNow },
                new BookAuthor { BookId = 2, AuthorId = 2, Role = "Author", Order = 1, ContributedAt = DateTime.UtcNow },
                new BookAuthor { BookId = 3, AuthorId = 3, Role = "Author", Order = 1, ContributedAt = DateTime.UtcNow }
            );
        }
    }
}
```

**Step 4: Configure Services in Program.cs**
```csharp
// Program.cs
var builder = WebApplication.CreateBuilder(args);

// Add services to the container
builder.Services.AddControllers();
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen();

// Configure Entity Framework
builder.Services.AddDbContext<BookStoreDbContext>(options =>
{
    options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection"));
    
    if (builder.Environment.IsDevelopment())
    {
        options.EnableSensitiveDataLogging();
        options.EnableDetailedErrors();
    }
});

var app = builder.Build();

// Configure the HTTP request pipeline
if (app.Environment.IsDevelopment())
{
    app.UseSwagger();
    app.UseSwaggerUI();
}

app.UseHttpsRedirection();
app.UseAuthorization();
app.MapControllers();

app.Run();
```

**Step 5: Create and Apply Migration**
```bash
# Create the initial migration
dotnet ef migrations add InitialCreateChallenge

# Apply the migration
dotnet ef database update

# Verify migration was created
dotnet ef migrations list
```

**Step 6: Create Test Controller**
```csharp
// Controllers/TestController.cs
[ApiController]
[Route("api/[controller]")]
public class TestController : ControllerBase
{
    private readonly BookStoreDbContext _context;
    
    public TestController(BookStoreDbContext context)
    {
        _context = context;
    }
    
    [HttpGet("verify-setup")]
    public async Task<ActionResult> VerifySetup()
    {
        try
        {
            var categoryCount = await _context.Categories.CountAsync();
            var publisherCount = await _context.Publishers.CountAsync();
            var authorCount = await _context.Authors.CountAsync();
            var bookCount = await _context.Books.CountAsync();
            
            var result = new
            {
                DatabaseConnected = true,
                Categories = categoryCount,
                Publishers = publisherCount,
                Authors = authorCount,
                Books = bookCount,
                Message = "Database setup verified successfully!"
            };
            
            return Ok(result);
        }
        catch (Exception ex)
        {
            return BadRequest(new { Error = ex.Message });
        }
    }
    
    [HttpGet("sample-data")]
    public async Task<ActionResult> GetSampleData()
    {
        var books = await _context.Books
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .Include(b => b.BookAuthors)
                .ThenInclude(ba => ba.Author)
            .Select(b => new
            {
                b.Id,
                b.Title,
                b.Price,
                Category = b.Category.Name,
                Publisher = b.Publisher.Name,
                Authors = b.BookAuthors.Select(ba => $"{ba.Author.FirstName} {ba.Author.LastName}"),
                b.StockQuantity
            })
            .ToListAsync();
            
        return Ok(books);
    }
}
```

**Step 7: Verification Queries (Run in SSMS)**
```sql
-- Connect to (localdb)\mssqllocaldb and run these queries

-- Verify tables were created
SELECT name FROM sys.tables ORDER BY name;

-- Check seeded data
SELECT COUNT(*) AS CategoryCount FROM Categories;
SELECT COUNT(*) AS PublisherCount FROM Publishers;
SELECT COUNT(*) AS AuthorCount FROM Authors;
SELECT COUNT(*) AS BookCount FROM Books;

-- Verify relationships
SELECT 
    b.Title,
    c.Name AS Category,
    p.Name AS Publisher,
    STRING_AGG(CONCAT(a.FirstName, ' ', a.LastName), ', ') AS Authors
FROM Books b
INNER JOIN Categories c ON b.CategoryId = c.Id
INNER JOIN Publishers p ON b.PublisherId = p.Id
LEFT JOIN BookAuthors ba ON b.Id = ba.BookId
LEFT JOIN Authors a ON ba.AuthorId = a.Id
GROUP BY b.Title, c.Name, p.Name
ORDER BY b.Title;

-- Check indexes
SELECT 
    i.name AS IndexName,
    t.name AS TableName,
    c.name AS ColumnName
FROM sys.indexes i
INNER JOIN sys.index_columns ic ON i.object_id = ic.object_id AND i.index_id = ic.index_id
INNER JOIN sys.columns c ON ic.object_id = c.object_id AND ic.column_id = c.column_id
INNER JOIN sys.tables t ON i.object_id = t.object_id
WHERE t.name IN ('Books', 'Categories', 'Publishers', 'Authors')
ORDER BY t.name, i.name;
```

**Step 8: Test Your Setup**
```bash
# Run your application
dotnet run

# Test the verification endpoint
# Navigate to: https://localhost:xxxx/api/test/verify-setup
# You should see a JSON response with counts of your seeded data

# Test the sample data endpoint
# Navigate to: https://localhost:xxxx/api/test/sample-data
# You should see your books with related data
```

**Expected Results:**
- ✅ Database created successfully
- ✅ All tables created with proper constraints
- ✅ Seeded data populated correctly
- ✅ Relationships working properly
- ✅ Indexes created for performance
- ✅ Test endpoints returning expected data

 <div style="page-break-after: always;"></div>

---

#### Module 2.3: CRUD Operations with Entity Framework

Now that you have a properly configured database with Entity Framework Core, it's time to learn how to perform Create, Read, Update, and Delete (CRUD) operations effectively. These operations form the backbone of most business applications and understanding how to implement them correctly with EF Core is crucial for building robust, performant applications.

CRUD operations in EF Core go beyond simple data manipulation. They involve understanding entity tracking, performance optimization, transaction management, and handling complex relationships. Modern applications also require asynchronous operations to maintain responsiveness and scalability.

Throughout this module, we'll explore not just how to perform CRUD operations, but how to do them well—following best practices that ensure your application performs well under load, handles errors gracefully, and maintains data integrity.

##### **Section 2.3.1:** Reading data - Find, Where, Include

Reading data efficiently is fundamental to any application's performance. Entity Framework Core provides multiple ways to query data, each optimized for different scenarios. Understanding when to use Find vs. Where, how to properly load related data, and how to optimize queries can make the difference between a responsive application and one that struggles under load.

The key to effective data reading lies in understanding EF Core's query execution model, entity tracking behavior, and the various loading strategies available. Making the right choices here impacts not just performance, but also the user experience of your application.

**Basic Data Reading Patterns:**

```csharp
// Services/BookService.cs
using Microsoft.EntityFrameworkCore;
using BookStoreApi.Data;
using BookStoreApi.Entities;
using BookStoreApi.DTOs;

namespace BookStoreApi.Services
{
    public interface IBookService
    {
        Task<IEnumerable<BookSummaryDto>> GetAllBooksAsync();
        Task<BookDetailDto?> GetBookByIdAsync(int id);
        Task<IEnumerable<BookSummaryDto>> SearchBooksAsync(string searchTerm);
        Task<PagedResult<BookSummaryDto>> GetBooksPagedAsync(int page, int pageSize, string? category = null);
        Task<BookDto> CreateBookAsync(CreateBookDto bookDto);
        Task<BookDto> UpdateBookAsync(int id, UpdateBookDto bookDto);
        Task<bool> DeleteBookAsync(int id);
    }
    
    public class BookService : IBookService
    {
        private readonly BookStoreDbContext _context;
        private readonly IMapper _mapper;
        private readonly ILogger<BookService> _logger;
        
        public BookService(BookStoreDbContext context, IMapper mapper, ILogger<BookService> logger)
        {
            _context = context;
            _mapper = mapper;
            _logger = logger;
        }
        
        // Find vs FirstOrDefault - when to use which
        public async Task<BookDetailDto?> GetBookByIdAsync(int id)
        {
            _logger.LogInformation("Retrieving book with ID: {BookId}", id);
            
            // Use Find for primary key lookups - checks tracking cache first
            var book = await _context.Books.FindAsync(id);
            
            if (book == null)
            {
                _logger.LogWarning("Book with ID {BookId} not found", id);
                return null;
            }
            
            // For detailed view, we need related data
            // Load related data explicitly since Find doesn't support Include
            await _context.Entry(book)
                .Reference(b => b.Category)
                .LoadAsync();
                
            await _context.Entry(book)
                .Reference(b => b.Publisher)
                .LoadAsync();
                
            await _context.Entry(book)
                .Collection(b => b.BookAuthors)
                .Query()
                .Include(ba => ba.Author)
                .LoadAsync();
                
            await _context.Entry(book)
                .Collection(b => b.Reviews)
                .Query()
                .Include(r => r.User)
                .OrderByDescending(r => r.CreatedAt)
                .Take(5)
                .LoadAsync();
            
            return _mapper.Map<BookDetailDto>(book);
        }
        
        // Alternative approach using Where with Include for complex queries
        public async Task<BookDetailDto?> GetBookByIdWithIncludeAsync(int id)
        {
            _logger.LogInformation("Retrieving book with includes for ID: {BookId}", id);
            
            var book = await _context.Books
                .Include(b => b.Category)
                .Include(b => b.Publisher)
                .Include(b => b.BookAuthors)
                    .ThenInclude(ba => ba.Author)
                .Include(b => b.Reviews
                    .OrderByDescending(r => r.CreatedAt)
                    .Take(5))
                    .ThenInclude(r => r.User)
                .FirstOrDefaultAsync(b => b.Id == id);
            
            if (book == null)
            {
                _logger.LogWarning("Book with ID {BookId} not found", id);
                return null;
            }
            
            return _mapper.Map<BookDetailDto>(book);
        }
        
        // Efficient reading for lists - minimal data loading
        public async Task<IEnumerable<BookSummaryDto>> GetAllBooksAsync()
        {
            _logger.LogInformation("Retrieving all books summary");
            
            var books = await _context.Books
                .Include(b => b.Category)
                .Include(b => b.Publisher)
                .AsNoTracking() // Performance optimization for read-only scenarios
                .OrderBy(b => b.Title)
                .ToListAsync();
            
            return _mapper.Map<IEnumerable<BookSummaryDto>>(books);
        }
        
        // Complex queries with filtering
        public async Task<IEnumerable<BookSummaryDto>> SearchBooksAsync(string searchTerm)
        {
            _logger.LogInformation("Searching books with term: {SearchTerm}", searchTerm);
            
            if (string.IsNullOrWhiteSpace(searchTerm))
            {
                return await GetAllBooksAsync();
            }
            
            var books = await _context.Books
                .Include(b => b.Category)
                .Include(b => b.Publisher)
                .Include(b => b.BookAuthors)
                    .ThenInclude(ba => ba.Author)
                .Where(b => 
                    b.Title.Contains(searchTerm) ||
                    b.Description.Contains(searchTerm) ||
                    b.BookAuthors.Any(ba => 
                        ba.Author.FirstName.Contains(searchTerm) ||
                        ba.Author.LastName.Contains(searchTerm)) ||
                    b.Category.Name.Contains(searchTerm))
                .AsNoTracking()
                .OrderBy(b => b.Title)
                .ToListAsync();
            
            return _mapper.Map<IEnumerable<BookSummaryDto>>(books);
        }
        
        // Pagination with filtering
        public async Task<PagedResult<BookSummaryDto>> GetBooksPagedAsync(
            int page, 
            int pageSize, 
            string? category = null)
        {
            _logger.LogInformation("Retrieving paged books: page {Page}, size {PageSize}, category {Category}", 
                page, pageSize, category);
            
            var query = _context.Books
                .Include(b => b.Category)
                .Include(b => b.Publisher)
                .AsQueryable();
            
            // Apply category filter if specified
            if (!string.IsNullOrEmpty(category))
            {
                query = query.Where(b => b.Category.Name.Equals(category, StringComparison.OrdinalIgnoreCase));
            }
            
            // Get total count for pagination
            var totalCount = await query.CountAsync();
            
            // Apply pagination
            var books = await query
                .AsNoTracking()
                .OrderBy(b => b.Title)
                .Skip((page - 1) * pageSize)
                .Take(pageSize)
                .ToListAsync();
            
            var bookDtos = _mapper.Map<List<BookSummaryDto>>(books);
            
            return new PagedResult<BookSummaryDto>
            {
                Data = bookDtos,
                TotalCount = totalCount,
                Page = page,
                PageSize = pageSize,
                TotalPages = (int)Math.Ceiling((double)totalCount / pageSize)
            };
        }
    }
}

// DTOs/PagedResult.cs
public class PagedResult<T>
{
    public List<T> Data { get; set; } = new();
    public int TotalCount { get; set; }
    public int Page { get; set; }
    public int PageSize { get; set; }
    public int TotalPages { get; set; }
    public bool HasPreviousPage => Page > 1;
    public bool HasNextPage => Page < TotalPages;
}
```

**Performance Considerations:**

```csharp
// Performance-optimized reading patterns
public class OptimizedBookService
{
    private readonly BookStoreDbContext _context;
    
    public OptimizedBookService(BookStoreDbContext context)
    {
        _context = context;
    }
    
    // Use projection for better performance when you don't need full entities
    public async Task<IEnumerable<BookSummaryDto>> GetBookSummariesOptimized()
    {
        return await _context.Books
            .Select(b => new BookSummaryDto
            {
                Id = b.Id,
                Title = b.Title,
                Author = string.Join(", ", b.BookAuthors
                    .OrderBy(ba => ba.Order)
                    .Select(ba => ba.Author.FirstName + " " + ba.Author.LastName)),
                Price = b.Price,
                IsInStock = b.StockQuantity > 0,
                Category = b.Category.Name
            })
            .AsNoTracking()
            .ToListAsync();
    }
    
    // Compiled queries for frequently executed queries
    private static readonly Func<BookStoreDbContext, int, Task<Book?>> GetBookByIdCompiled =
        EF.CompileAsyncQuery((BookStoreDbContext context, int id) =>
            context.Books
                .Include(b => b.Category)
                .Include(b => b.Publisher)
                .FirstOrDefault(b => b.Id == id));
    
    public async Task<Book?> GetBookByIdCompiledAsync(int id)
    {
        return await GetBookByIdCompiled(_context, id);
    }
    
    // Splitting queries for better performance with multiple includes
    public async Task<BookDetailDto?> GetBookWithSplitQueryAsync(int id)
    {
        var book = await _context.Books
            .AsSplitQuery() // Splits into multiple SQL queries to avoid cartesian explosion
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .Include(b => b.BookAuthors)
                .ThenInclude(ba => ba.Author)
            .Include(b => b.Reviews)
                .ThenInclude(r => r.User)
            .FirstOrDefaultAsync(b => b.Id == id);
        
        return book == null ? null : _mapper.Map<BookDetailDto>(book);
    }
    
    // Raw SQL for complex queries that are hard to express in LINQ
    public async Task<IEnumerable<BookSalesDto>> GetBookSalesStatsAsync()
    {
        return await _context.Database
            .SqlQueryRaw<BookSalesDto>(@"
                SELECT 
                    b.Id,
                    b.Title,
                    COUNT(oi.Id) as TotalSales,
                    SUM(oi.Quantity) as TotalQuantitySold,
                    SUM(oi.Price * oi.Quantity) as TotalRevenue
                FROM Books b
                LEFT JOIN OrderItems oi ON b.Id = oi.BookId
                GROUP BY b.Id, b.Title
                ORDER BY TotalRevenue DESC")
            .ToListAsync();
    }
}

public class BookSalesDto
{
    public int Id { get; set; }
    public string Title { get; set; } = string.Empty;
    public int TotalSales { get; set; }
    public int TotalQuantitySold { get; set; }
    public decimal TotalRevenue { get; set; }
}
```

##### **Section 2.3.2:** Creating new records and handling relationships

Creating records in Entity Framework Core involves more than just adding data to a single table. Modern applications typically involve complex object graphs with relationships that need to be managed correctly. Understanding how EF Core handles entity states, relationship management, and cascade behaviors is crucial for building reliable data persistence layers.

When creating entities with relationships, you need to consider whether related entities already exist, how to handle validation across the object graph, and how to ensure data consistency. EF Core provides several strategies for managing these scenarios effectively.

**Basic Entity Creation:**

```csharp
// Services/BookService.cs - Create operations
public async Task<BookDto> CreateBookAsync(CreateBookDto bookDto)
{
    _logger.LogInformation("Creating new book: {Title}", bookDto.Title);
    
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Validate that referenced entities exist
        await ValidateReferencesAsync(bookDto);
        
        // Create the main entity
        var book = _mapper.Map<Book>(bookDto);
        
        // Handle many-to-many relationships
        await HandleBookAuthorsAsync(book, bookDto.AuthorIds);
        
        // Add to context and save
        _context.Books.Add(book);
        await _context.SaveChangesAsync();
        
        // Commit transaction
        await transaction.CommitAsync();
        
        _logger.LogInformation("Book created successfully with ID: {BookId}", book.Id);
        
        // Return the created book with all related data
        return await GetBookByIdAsync(book.Id);
    }
    catch (Exception ex)
    {
        await transaction.RollbackAsync();
        _logger.LogError(ex, "Error creating book: {Title}", bookDto.Title);
        throw;
    }
}

private async Task ValidateReferencesAsync(CreateBookDto bookDto)
{
    // Validate category exists
    var categoryExists = await _context.Categories
        .AnyAsync(c => c.Id == bookDto.CategoryId && c.IsActive);
    if (!categoryExists)
    {
        throw new ValidationException($"Category with ID {bookDto.CategoryId} not found or inactive");
    }
    
    // Validate publisher exists
    var publisherExists = await _context.Publishers
        .AnyAsync(p => p.Id == bookDto.PublisherId);
    if (!publisherExists)
    {
        throw new ValidationException($"Publisher with ID {bookDto.PublisherId} not found");
    }
    
    // Validate all authors exist
    var existingAuthorIds = await _context.Authors
        .Where(a => bookDto.AuthorIds.Contains(a.Id))
        .Select(a => a.Id)
        .ToListAsync();
    
    var missingAuthorIds = bookDto.AuthorIds.Except(existingAuthorIds).ToList();
    if (missingAuthorIds.Any())
    {
        throw new ValidationException($"Authors not found: {string.Join(", ", missingAuthorIds)}");
    }
    
    // Validate ISBN uniqueness
    var isbnExists = await _context.Books
        .AnyAsync(b => b.ISBN == bookDto.ISBN);
    if (isbnExists)
    {
        throw new ValidationException($"Book with ISBN {bookDto.ISBN} already exists");
    }
}

private async Task HandleBookAuthorsAsync(Book book, List<int> authorIds)
{
    // Create BookAuthor relationships
    for (int i = 0; i < authorIds.Count; i++)
    {
        var bookAuthor = new BookAuthor
        {
            Book = book,
            AuthorId = authorIds[i],
            Role = i == 0 ? "Primary Author" : "Co-Author",
            Order = i + 1,
            ContributedAt = DateTime.UtcNow
        };
        
        book.BookAuthors.Add(bookAuthor);
    }
}
```

**Creating Related Entities:**

```csharp
// Creating entities with new related data
public async Task<BookDto> CreateBookWithNewAuthorAsync(CreateBookWithNewAuthorDto bookDto)
{
    _logger.LogInformation("Creating book with new author: {Title}", bookDto.Title);
    
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Create new author if provided
        Author? newAuthor = null;
        if (bookDto.NewAuthor != null)
        {
            newAuthor = new Author
            {
                FirstName = bookDto.NewAuthor.FirstName,
                LastName = bookDto.NewAuthor.LastName,
                Biography = bookDto.NewAuthor.Biography,
                Nationality = bookDto.NewAuthor.Nationality,
                Email = bookDto.NewAuthor.Email
            };
            
            _context.Authors.Add(newAuthor);
            await _context.SaveChangesAsync(); // Save to get the ID
        }
        
        // Create the book
        var book = new Book
        {
            Title = bookDto.Title,
            ISBN = bookDto.ISBN,
            Price = bookDto.Price,
            PublishedDate = bookDto.PublishedDate,
            Description = bookDto.Description,
            StockQuantity = bookDto.StockQuantity,
            CategoryId = bookDto.CategoryId,
            PublisherId = bookDto.PublisherId,
            CreatedAt = DateTime.UtcNow,
            CreatedBy = "System" // Get from current user context
        };
        
        // Add existing authors
        var existingAuthors = await _context.Authors
            .Where(a => bookDto.ExistingAuthorIds.Contains(a.Id))
            .ToListAsync();
        
        int order = 1;
        
        // Add new author as primary if exists
        if (newAuthor != null)
        {
            book.BookAuthors.Add(new BookAuthor
            {
                Book = book,
                Author = newAuthor,
                Role = "Primary Author",
                Order = order++,
                ContributedAt = DateTime.UtcNow
            });
        }
        
        // Add existing authors
        foreach (var author in existingAuthors)
        {
            book.BookAuthors.Add(new BookAuthor
            {
                Book = book,
                Author = author,
                Role = order == 1 ? "Primary Author" : "Co-Author",
                Order = order++,
                ContributedAt = DateTime.UtcNow
            });
        }
        
        _context.Books.Add(book);
        await _context.SaveChangesAsync();
        
        await transaction.CommitAsync();
        
        _logger.LogInformation("Book with new author created successfully: {BookId}", book.Id);
        
        return await GetBookByIdAsync(book.Id);
    }
    catch (Exception ex)
    {
        await transaction.RollbackAsync();
        _logger.LogError(ex, "Error creating book with new author");
        throw;
    }
}
```

**Bulk Insert Operations:**

```csharp
// Efficient bulk creation
public async Task<List<BookDto>> CreateBooksAsync(List<CreateBookDto> bookDtos)
{
    _logger.LogInformation("Creating {Count} books in bulk", bookDtos.Count);
    
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Validate all books before creating any
        await ValidateBulkBooksAsync(bookDtos);
        
        var books = new List<Book>();
        
        foreach (var bookDto in bookDtos)
        {
            var book = _mapper.Map<Book>(bookDto);
            
            // Handle relationships
            await HandleBookAuthorsAsync(book, bookDto.AuthorIds);
            
            books.Add(book);
        }
        
        // Add all books at once
        _context.Books.AddRange(books);
        await _context.SaveChangesAsync();
        
        await transaction.CommitAsync();
        
        _logger.LogInformation("Successfully created {Count} books", books.Count);
        
        // Return created books
        var createdBookIds = books.Select(b => b.Id).ToList();
        var createdBooks = await _context.Books
            .Where(b => createdBookIds.Contains(b.Id))
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .Include(b => b.BookAuthors)
                .ThenInclude(ba => ba.Author)
            .ToListAsync();
        
        return _mapper.Map<List<BookDto>>(createdBooks);
    }
    catch (Exception ex)
    {
        await transaction.RollbackAsync();
        _logger.LogError(ex, "Error in bulk book creation");
        throw;
    }
}

private async Task ValidateBulkBooksAsync(List<CreateBookDto> bookDtos)
{
    // Check for duplicate ISBNs within the batch
    var duplicateISBNs = bookDtos
        .GroupBy(b => b.ISBN)
        .Where(g => g.Count() > 1)
        .Select(g => g.Key)
        .ToList();
    
    if (duplicateISBNs.Any())
    {
        throw new ValidationException($"Duplicate ISBNs in batch: {string.Join(", ", duplicateISBNs)}");
    }
    
    // Check for existing ISBNs in database
    var isbnsToCheck = bookDtos.Select(b => b.ISBN).ToList();
    var existingISBNs = await _context.Books
        .Where(b => isbnsToCheck.Contains(b.ISBN))
        .Select(b => b.ISBN)
        .ToListAsync();
    
    if (existingISBNs.Any())
    {
        throw new ValidationException($"ISBNs already exist: {string.Join(", ", existingISBNs)}");
    }
    
    // Validate all referenced entities exist
    var categoryIds = bookDtos.Select(b => b.CategoryId).Distinct().ToList();
    var publisherIds = bookDtos.Select(b => b.PublisherId).Distinct().ToList();
    var authorIds = bookDtos.SelectMany(b => b.AuthorIds).Distinct().ToList();
    
    var existingCategoryIds = await _context.Categories
        .Where(c => categoryIds.Contains(c.Id) && c.IsActive)
        .Select(c => c.Id)
        .ToListAsync();
    
    var missingCategoryIds = categoryIds.Except(existingCategoryIds).ToList();
    if (missingCategoryIds.Any())
    {
        throw new ValidationException($"Categories not found: {string.Join(", ", missingCategoryIds)}");
    }
    
    // Similar validation for publishers and authors...
}
```

##### **Section 2.3.3:** Updating existing records (tracking vs non-tracking)

Updating records in Entity Framework Core is more nuanced than it might first appear. EF Core's change tracking system provides powerful capabilities for detecting and persisting changes, but understanding how it works is crucial for building efficient update operations. The choice between tracked and non-tracked scenarios significantly impacts both performance and the complexity of your update logic.

Understanding entity states, concurrency handling, and partial updates helps you build robust applications that handle real-world scenarios like concurrent updates, optimistic locking, and complex business rules that span multiple entities.

**Basic Update Operations:**

```csharp
// Tracked entity updates - EF Core automatically detects changes
public async Task<BookDto> UpdateBookAsync(int id, UpdateBookDto bookDto)
{
    _logger.LogInformation("Updating book with ID: {BookId}", id);
    
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Find entity (this puts it in the tracking context)
        var book = await _context.Books
            .Include(b => b.BookAuthors)
            .FirstOrDefaultAsync(b => b.Id == id);
        
        if (book == null)
        {
            throw new NotFoundException($"Book with ID {id} not found");
        }
        
        // Validate references before updating
        await ValidateUpdateReferencesAsync(bookDto, id);
        
        // Update simple properties - EF Core will track these changes
        book.Title = bookDto.Title;
        book.ISBN = bookDto.ISBN;
        book.Price = bookDto.Price;
        book.PublishedDate = bookDto.PublishedDate;
        book.Description = bookDto.Description;
        book.StockQuantity = bookDto.StockQuantity;
        book.CategoryId = bookDto.CategoryId;
        book.PublisherId = bookDto.PublisherId;
        book.UpdatedAt = DateTime.UtcNow;
        book.UpdatedBy = "System"; // Get from current user context
        
        // Handle many-to-many relationship updates
        await UpdateBookAuthorsAsync(book, bookDto.AuthorIds);
        
        // SaveChanges will automatically detect and persist all changes
        await _context.SaveChangesAsync();
        await transaction.CommitAsync();
        
        _logger.LogInformation("Book updated successfully: {BookId}", id);
        
        return await GetBookByIdAsync(id);
    }
    catch (Exception ex)
    {
        await transaction.RollbackAsync();
        _logger.LogError(ex, "Error updating book: {BookId}", id);
        throw;
    }
}

private async Task ValidateUpdateReferencesAsync(UpdateBookDto bookDto, int excludeBookId)
{
    // Check ISBN uniqueness (excluding current book)
    var isbnExists = await _context.Books
        .AnyAsync(b => b.ISBN == bookDto.ISBN && b.Id != excludeBookId);
    if (isbnExists)
    {
        throw new ValidationException($"Book with ISBN {bookDto.ISBN} already exists");
    }
    
    // Validate category exists and is active
    var categoryExists = await _context.Categories
        .AnyAsync(c => c.Id == bookDto.CategoryId && c.IsActive);
    if (!categoryExists)
    {
        throw new ValidationException($"Category with ID {bookDto.CategoryId} not found or inactive");
    }
    
    // Validate publisher exists
    var publisherExists = await _context.Publishers
        .AnyAsync(p => p.Id == bookDto.PublisherId);
    if (!publisherExists)
    {
        throw new ValidationException($"Publisher with ID {bookDto.PublisherId} not found");
    }
    
    // Validate all authors exist
    var existingAuthorIds = await _context.Authors
        .Where(a => bookDto.AuthorIds.Contains(a.Id))
        .Select(a => a.Id)
        .ToListAsync();
    
    var missingAuthorIds = bookDto.AuthorIds.Except(existingAuthorIds).ToList();
    if (missingAuthorIds.Any())
    {
        throw new ValidationException($"Authors not found: {string.Join(", ", missingAuthorIds)}");
    }
}

private async Task UpdateBookAuthorsAsync(Book book, List<int> newAuthorIds)
{
    // Remove existing relationships that are no longer needed
    var currentAuthorIds = book.BookAuthors.Select(ba => ba.AuthorId).ToList();
    var authorsToRemove = book.BookAuthors
        .Where(ba => !newAuthorIds.Contains(ba.AuthorId))
        .ToList();
    
    foreach (var authorToRemove in authorsToRemove)
    {
        book.BookAuthors.Remove(authorToRemove);
    }
    
    // Add new relationships
    var authorsToAdd = newAuthorIds
        .Where(id => !currentAuthorIds.Contains(id))
        .ToList();
    
    for (int i = 0; i < authorsToAdd.Count; i++)
    {
        var authorId = authorsToAdd[i];
        var maxOrder = book.BookAuthors.Any() ? book.BookAuthors.Max(ba => ba.Order) : 0;
        
        book.BookAuthors.Add(new BookAuthor
        {
            BookId = book.Id,
            AuthorId = authorId,
            Role = maxOrder == 0 ? "Primary Author" : "Co-Author",
            Order = maxOrder + 1,
            ContributedAt = DateTime.UtcNow
        });
    }
    
    // Update order for remaining authors
    var remainingAuthors = book.BookAuthors.OrderBy(ba => ba.Order).ToList();
    for (int i = 0; i < remainingAuthors.Count; i++)
    {
        remainingAuthors[i].Order = i + 1;
        remainingAuthors[i].Role = i == 0 ? "Primary Author" : "Co-Author";
    }
}
```

**Non-Tracking Updates for Performance:**

```csharp
// Non-tracking updates for better performance when you don't need change tracking
public async Task<bool> UpdateBookPriceAsync(int id, decimal newPrice)
{
    _logger.LogInformation("Updating price for book {BookId} to {NewPrice}", id, newPrice);
    
    // Use ExecuteUpdate for efficient single-field updates
    var rowsAffected = await _context.Books
        .Where(b => b.Id == id)
        .ExecuteUpdateAsync(setters => setters
            .SetProperty(b => b.Price, newPrice)
            .SetProperty(b => b.UpdatedAt, DateTime.UtcNow)
            .SetProperty(b => b.UpdatedBy, "System"));
    
    if (rowsAffected == 0)
    {
        _logger.LogWarning("No book found with ID {BookId} for price update", id);
        return false;
    }
    
    _logger.LogInformation("Successfully updated price for book {BookId}", id);
    return true;
}

// Bulk updates using ExecuteUpdate
public async Task<int> UpdateBooksCategoryAsync(List<int> bookIds, int newCategoryId)
{
    _logger.LogInformation("Bulk updating category for {Count} books", bookIds.Count);
    
    // Validate category exists
    var categoryExists = await _context.Categories
        .AnyAsync(c => c.Id == newCategoryId && c.IsActive);
    if (!categoryExists)
    {
        throw new ValidationException($"Category with ID {newCategoryId} not found or inactive");
    }
    
    var rowsAffected = await _context.Books
        .Where(b => bookIds.Contains(b.Id))
        .ExecuteUpdateAsync(setters => setters
            .SetProperty(b => b.CategoryId, newCategoryId)
            .SetProperty(b => b.UpdatedAt, DateTime.UtcNow)
            .SetProperty(b => b.UpdatedBy, "System"));
    
    _logger.LogInformation("Updated category for {Count} books", rowsAffected);
    return rowsAffected;
}

// Disconnected entity updates (useful for web APIs)
public async Task<BookDto> UpdateBookDisconnectedAsync(int id, UpdateBookDto bookDto)
{
    _logger.LogInformation("Updating book using disconnected approach: {BookId}", id);
    
    // Create entity instance without tracking
    var book = new Book
    {
        Id = id,
        Title = bookDto.Title,
        ISBN = bookDto.ISBN,
        Price = bookDto.Price,
        PublishedDate = bookDto.PublishedDate,
        Description = bookDto.Description,
        StockQuantity = bookDto.StockQuantity,
        CategoryId = bookDto.CategoryId,
        PublisherId = bookDto.PublisherId,
        UpdatedAt = DateTime.UtcNow,
        UpdatedBy = "System"
    };
    
    // Attach entity and mark as modified
    _context.Books.Attach(book);
    _context.Entry(book).State = EntityState.Modified;
    
    // Specify which properties should not be updated
    _context.Entry(book).Property(b => b.CreatedAt).IsModified = false;
    _context.Entry(book).Property(b => b.CreatedBy).IsModified = false;
    
    try
    {
        await _context.SaveChangesAsync();
        _logger.LogInformation("Successfully updated book using disconnected approach: {BookId}", id);
        
        return await GetBookByIdAsync(id);
    }
    catch (DbUpdateConcurrencyException)
    {
        _logger.LogWarning("Concurrency conflict when updating book: {BookId}", id);
        throw new ConcurrencyException($"Book with ID {id} was modified by another user");
    }
}
```

**Concurrency Handling:**

```csharp
// Entity with concurrency token
public class Book
{
    // ... other properties ...
    
    [Timestamp]
    public byte[] RowVersion { get; set; } = Array.Empty<byte>();
}

// Update with optimistic concurrency control
public async Task<BookDto> UpdateBookWithConcurrencyAsync(int id, UpdateBookDto bookDto, byte[] rowVersion)
{
    _logger.LogInformation("Updating book with concurrency check: {BookId}", id);
    
    var book = await _context.Books
        .FirstOrDefaultAsync(b => b.Id == id);
    
    if (book == null)
    {
        throw new NotFoundException($"Book with ID {id} not found");
    }
    
    // Check if the row version matches (optimistic concurrency)
    if (!book.RowVersion.SequenceEqual(rowVersion))
    {
        throw new ConcurrencyException("Book was modified by another user. Please refresh and try again.");
    }
    
    // Update properties
    book.Title = bookDto.Title;
    book.Price = bookDto.Price;
    // ... other properties ...
    
    try
    {
        await _context.SaveChangesAsync();
        return await GetBookByIdAsync(id);
    }
    catch (DbUpdateConcurrencyException ex)
    {
        _logger.LogWarning(ex, "Concurrency exception when updating book: {BookId}", id);
        throw new ConcurrencyException("Concurrency conflict occurred. Please refresh and try again.");
    }
}
```

##### **Section 2.3.4:** Deleting records and cascade behaviors

Deleting records in a relational database involves understanding the implications of relationships and ensuring data integrity. Entity Framework Core provides several strategies for handling deletions, from simple single-record deletions to complex cascade scenarios and soft deletes for audit trails.

Understanding cascade behaviors, handling orphaned records, and implementing soft deletes are crucial for building applications that maintain data integrity while providing the flexibility that business requirements demand.

**Basic Delete Operations:**

```csharp
// Simple delete operation
public async Task<bool> DeleteBookAsync(int id)
{
    _logger.LogInformation("Deleting book with ID: {BookId}", id);
    
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        var book = await _context.Books
            .Include(b => b.BookAuthors)
            .Include(b => b.Reviews)
            .Include(b => b.OrderItems)
            .FirstOrDefaultAsync(b => b.Id == id);
        
        if (book == null)
        {
            _logger.LogWarning("Book with ID {BookId} not found for deletion", id);
            return false;
        }
        
        // Check if book can be deleted (business rules)
        await ValidateBookDeletionAsync(book);
        
        // EF Core will handle cascade deletes based on relationship configuration
        _context.Books.Remove(book);
        await _context.SaveChangesAsync();
        
        await transaction.CommitAsync();
        
        _logger.LogInformation("Successfully deleted book: {BookId}", id);
        return true;
    }
    catch (Exception ex)
    {
        await transaction.RollbackAsync();
        _logger.LogError(ex, "Error deleting book: {BookId}", id);
        throw;
    }
}

private async Task ValidateBookDeletionAsync(Book book)
{
    // Check if book has been ordered - might want to prevent deletion
    if (book.OrderItems.Any())
    {
        throw new BusinessRuleViolationException(
            $"Cannot delete book '{book.Title}' because it has been included in orders. Consider marking it as discontinued instead.");
    }
    
    // Other business rules for deletion...
}

// Bulk delete operations
public async Task<int> DeleteBooksByCategoryAsync(int categoryId)
{
    _logger.LogInformation("Bulk deleting books in category: {CategoryId}", categoryId);
    
    // Use ExecuteDelete for efficient bulk operations
    var deletedCount = await _context.Books
        .Where(b => b.CategoryId == categoryId)
        .ExecuteDeleteAsync();
    
    _logger.LogInformation("Deleted {Count} books from category {CategoryId}", deletedCount, categoryId);
    return deletedCount;
}

// Cascade delete configuration example
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Configure cascade behaviors
    modelBuilder.Entity<Book>()
        .HasMany(b => b.BookAuthors)
        .WithOne(ba => ba.Book)
        .OnDelete(DeleteBehavior.Cascade); // Delete BookAuthors when Book is deleted
    
    modelBuilder.Entity<Book>()
        .HasMany(b => b.Reviews)
        .WithOne(r => r.Book)
        .OnDelete(DeleteBehavior.Cascade); // Delete Reviews when Book is deleted
    
    modelBuilder.Entity<Book>()
        .HasMany(b => b.OrderItems)
        .WithOne(oi => oi.Book)
        .OnDelete(DeleteBehavior.Restrict); // Prevent deletion if OrderItems exist
}
```

**Soft Delete Implementation:**

```csharp
// Add soft delete properties to entities
public class Book
{
    // ... existing properties ...
    
    public bool IsDeleted { get; set; } = false;
    public DateTime? DeletedAt { get; set; }
    public string? DeletedBy { get; set; }
}

// Soft delete service implementation
public async Task<bool> SoftDeleteBookAsync(int id, string deletedBy)
{
    _logger.LogInformation("Soft deleting book with ID: {BookId}", id);
    
    var book = await _context.Books.FindAsync(id);
    if (book == null)
    {
        _logger.LogWarning("Book with ID {BookId} not found for soft deletion", id);
        return false;
    }
    
    if (book.IsDeleted)
    {
        _logger.LogWarning("Book with ID {BookId} is already soft deleted", id);
        return false;
    }
    
    book.IsDeleted = true;
    book.DeletedAt = DateTime.UtcNow;
    book.DeletedBy = deletedBy;
    
    await _context.SaveChangesAsync();
    
    _logger.LogInformation("Successfully soft deleted book: {BookId}", id);
    return true;
}

// Restore soft deleted entity
public async Task<bool> RestoreBookAsync(int id)
{
    _logger.LogInformation("Restoring soft deleted book: {BookId}", id);
    
    var book = await _context.Books
        .IgnoreQueryFilters() // Include soft deleted entities
        .FirstOrDefaultAsync(b => b.Id == id);
    
    if (book == null)
    {
        _logger.LogWarning("Book with ID {BookId} not found", id);
        return false;
    }
    
    if (!book.IsDeleted)
    {
        _logger.LogWarning("Book with ID {BookId} is not deleted", id);
        return false;
    }
    
    book.IsDeleted = false;
    book.DeletedAt = null;
    book.DeletedBy = null;
    book.UpdatedAt = DateTime.UtcNow;
    book.UpdatedBy = "System";
    
    await _context.SaveChangesAsync();
    
    _logger.LogInformation("Successfully restored book: {BookId}", id);
    return true;
}

// Configure global query filter for soft deletes
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Global query filter to exclude soft deleted entities
    modelBuilder.Entity<Book>()
        .HasQueryFilter(b => !b.IsDeleted);
}

// Get soft deleted entities
public async Task<IEnumerable<BookSummaryDto>> GetDeletedBooksAsync()
{
    var deletedBooks = await _context.Books
        .IgnoreQueryFilters()
        .Where(b => b.IsDeleted)
        .Include(b => b.Category)
        .Include(b => b.Publisher)
        .AsNoTracking()
        .ToListAsync();
    
    return _mapper.Map<IEnumerable<BookSummaryDto>>(deletedBooks);
}
```

##### **Section 2.3.5:** Async/await patterns with EF Core

Asynchronous programming is essential for building scalable web applications. Entity Framework Core's async support allows your application to handle more concurrent requests by freeing up threads while waiting for database operations to complete. Understanding how to use async/await effectively with EF Core can significantly improve your application's performance and responsiveness.

The key to effective async programming with EF Core lies in understanding when to use async operations, how to handle async enumeration, and how to avoid common pitfalls like blocking async operations or creating sync-over-async scenarios.

**Async Best Practices:**

```csharp
// Service implementation with proper async patterns
public class BookService : IBookService
{
    private readonly BookStoreDbContext _context;
    private readonly ILogger<BookService> _logger;
    
    public BookService(BookStoreDbContext context, ILogger<BookService> logger)
    {
        _context = context;
        _logger = logger;
    }
    
    // Proper async enumeration with IAsyncEnumerable
    public async IAsyncEnumerable<BookSummaryDto> GetBooksStreamAsync(
        [EnumeratorCancellation] CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Streaming books data");
        
        await foreach (var book in _context.Books
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .AsAsyncEnumerable()
            .WithCancellation(cancellationToken))
        {
            cancellationToken.ThrowIfCancellationRequested();
            
            yield return new BookSummaryDto
            {
                Id = book.Id,
                Title = book.Title,
                Price = book.Price,
                Category = book.Category.Name,
                IsInStock = book.StockQuantity > 0
            };
        }
    }
    
    // Async operations with cancellation support
    public async Task<BookDetailDto?> GetBookByIdAsync(int id, CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Retrieving book with ID: {BookId}", id);
        
        var book = await _context.Books
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .Include(b => b.BookAuthors)
                .ThenInclude(ba => ba.Author)
            .Include(b => b.Reviews.Take(5))
                .ThenInclude(r => r.User)
            .FirstOrDefaultAsync(b => b.Id == id, cancellationToken);
        
        if (book == null)
        {
            _logger.LogWarning("Book with ID {BookId} not found", id);
            return null;
        }
        
        return _mapper.Map<BookDetailDto>(book);
    }
    
    // Async batch processing
    public async Task<BatchResult<BookDto>> ProcessBooksAsync(
        List<CreateBookDto> bookDtos,
        CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Processing {Count} books in batch", bookDtos.Count);
        
        var result = new BatchResult<BookDto>();
        
        using var transaction = await _context.Database.BeginTransactionAsync(cancellationToken);
        
        try
        {
            foreach (var bookDto in bookDtos)
            {
                cancellationToken.ThrowIfCancellationRequested();
                
                try
                {
                    var createdBook = await CreateBookInternalAsync(bookDto, cancellationToken);
                    result.SuccessfulItems.Add(createdBook);
                }
                catch (Exception ex)
                {
                    _logger.LogError(ex, "Failed to create book: {Title}", bookDto.Title);
                    result.FailedItems.Add(new FailedItem<CreateBookDto>
                    {
                        Item = bookDto,
                        Error = ex.Message
                    });
                }
            }
            
            await transaction.CommitAsync(cancellationToken);
            _logger.LogInformation("Batch processing completed: {Success} successful, {Failed} failed", 
                result.SuccessfulItems.Count, result.FailedItems.Count);
        }
        catch (Exception ex)
        {
            await transaction.RollbackAsync(cancellationToken);
            _logger.LogError(ex, "Batch processing failed, transaction rolled back");
            throw;
        }
        
        return result;
    }
    
    // Async aggregation operations
    public async Task<BookStatisticsDto> GetBookStatisticsAsync(CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Calculating book statistics");
        
        var statistics = await _context.Books
            .GroupBy(b => 1) // Group all books together
            .Select(g => new BookStatisticsDto
            {
                TotalBooks = g.Count(),
                TotalValue = g.Sum(b => b.Price * b.StockQuantity),
                AveragePrice = g.Average(b => b.Price),
                BooksInStock = g.Count(b => b.StockQuantity > 0),
                BooksOutOfStock = g.Count(b => b.StockQuantity == 0),
                CategoryBreakdown = _context.Books
                    .GroupBy(b => b.Category.Name)
                    .Select(cg => new CategoryStatDto
                    {
                        CategoryName = cg.Key,
                        BookCount = cg.Count(),
                        TotalValue = cg.Sum(b => b.Price * b.StockQuantity)
                    })
                    .ToList()
            })
            .FirstOrDefaultAsync(cancellationToken);
        
        return statistics ?? new BookStatisticsDto();
    }
}

// Supporting DTOs and classes
public class BatchResult<T>
{
    public List<T> SuccessfulItems { get; set; } = new();
    public List<FailedItem<CreateBookDto>> FailedItems { get; set; } = new();
    public int TotalProcessed => SuccessfulItems.Count + FailedItems.Count;
    public int SuccessCount => SuccessfulItems.Count;
    public int FailureCount => FailedItems.Count;
    public double SuccessRate => TotalProcessed > 0 ? (double)SuccessCount / TotalProcessed * 100 : 0;
}

public class FailedItem<T>
{
    public T Item { get; set; } = default!;
    public string Error { get; set; } = string.Empty;
}

public class BookStatisticsDto
{
    public int TotalBooks { get; set; }
    public decimal TotalValue { get; set; }
    public decimal AveragePrice { get; set; }
    public int BooksInStock { get; set; }
    public int BooksOutOfStock { get; set; }
    public List<CategoryStatDto> CategoryBreakdown { get; set; } = new();
}

public class CategoryStatDto
{
    public string CategoryName { get; set; } = string.Empty;
    public int BookCount { get; set; }
    public decimal TotalValue { get; set; }
}
```

**Async Error Handling and Timeouts:**

```csharp
// Service with timeout and retry policies
public class ResilientBookService
{
    private readonly BookStoreDbContext _context;
    private readonly ILogger<ResilientBookService> _logger;
    
    public ResilientBookService(BookStoreDbContext context, ILogger<ResilientBookService> logger)
    {
        _context = context;
        _logger = logger;
    }
    
    // Operation with timeout
    public async Task<BookDto?> GetBookWithTimeoutAsync(int id, TimeSpan timeout = default)
    {
        timeout = timeout == default ? TimeSpan.FromSeconds(30) : timeout;
        
        using var cancellationTokenSource = new CancellationTokenSource(timeout);
        
        try
        {
            return await GetBookByIdAsync(id, cancellationTokenSource.Token);
        }
        catch (OperationCanceledException ex) when (cancellationTokenSource.Token.IsCancellationRequested)
        {
            _logger.LogWarning("Operation timed out after {Timeout} seconds for book ID: {BookId}", 
                timeout.TotalSeconds, id);
            throw new TimeoutException($"Operation timed out after {timeout.TotalSeconds} seconds", ex);
        }
    }
    
    // Async operation with retry
    public async Task<BookDto> CreateBookWithRetryAsync(
        CreateBookDto bookDto, 
        int maxRetries = 3,
        CancellationToken cancellationToken = default)
    {
        var attempt = 0;
        
        while (attempt <= maxRetries)
        {
            try
            {
                return await CreateBookAsync(bookDto, cancellationToken);
            }
            catch (DbUpdateException ex) when (attempt < maxRetries)
            {
                attempt++;
                var delay = TimeSpan.FromMilliseconds(Math.Pow(2, attempt) * 1000); // Exponential backoff
                
                _logger.LogWarning(ex, "Attempt {Attempt} failed, retrying in {Delay}ms", attempt, delay.TotalMilliseconds);
                
                await Task.Delay(delay, cancellationToken);
            }
        }
        
        throw new InvalidOperationException($"Failed to create book after {maxRetries} retries");
    }
}
```

---

#### **Challenge 2.3: Build your data access layer**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Build a complete data access layer that demonstrates all CRUD operations with Entity Framework Core. This challenge brings together everything you've learned about reading, creating, updating, and deleting data while handling relationships and implementing best practices.

**What You'll Learn:**
- Complete CRUD implementation
- Relationship management
- Async programming patterns
- Error handling and validation
- Performance optimization techniques

</div>

**Challenge Requirements:**

1. **Implement Complete BookService:**
   - All CRUD operations for books
   - Proper relationship handling (many-to-many with authors)
   - Async/await throughout
   - Comprehensive error handling and logging

2. **Add Advanced Features:**
   - Search functionality with multiple criteria
   - Pagination with filtering
   - Bulk operations for create and update
   - Soft delete implementation

3. **Create Supporting Services:**
   - CategoryService with basic CRUD
   - AuthorService with book association management
   - PublisherService with book relationship handling

4. **Implement Performance Optimizations:**
   - Use AsNoTracking for read-only scenarios
   - Implement projection for lists
   - Add compiled queries for frequently used operations

5. **Add Validation and Business Rules:**
   - ISBN uniqueness validation
   - Stock quantity business rules
   - Category active status validation
   - Proper error responses

**Expected Output:**
A fully functional data access layer that can handle all aspects of book management with proper relationships, validation, and error handling.

**Solution Implementation:**

**Step 1: Complete IBookService Interface**
```csharp
// Services/IBookService.cs
public interface IBookService
{
    // Read operations
    Task<PagedResult<BookSummaryDto>> GetBooksAsync(int page, int pageSize, string? category = null, string? search = null);
    Task<BookDetailDto?> GetBookByIdAsync(int id);
    Task<IEnumerable<BookSummaryDto>> SearchBooksAsync(string searchTerm);
    Task<BookStatisticsDto> GetBookStatisticsAsync();
    
    // Create operations
    Task<BookDto> CreateBookAsync(CreateBookDto bookDto);
    Task<List<BookDto>> CreateBooksAsync(List<CreateBookDto> bookDtos);
    
    // Update operations
    Task<BookDto> UpdateBookAsync(int id, UpdateBookDto bookDto);
    Task<bool> UpdateBookPriceAsync(int id, decimal newPrice);
    Task<int> UpdateBooksCategoryAsync(List<int> bookIds, int newCategoryId);
    
    // Delete operations
    Task<bool> DeleteBookAsync(int id);
    Task<bool> SoftDeleteBookAsync(int id, string deletedBy);
    Task<bool> RestoreBookAsync(int id);
    Task<IEnumerable<BookSummaryDto>> GetDeletedBooksAsync();
}
```

**Step 2: Implement Complete BookService**
```csharp
// Services/BookService.cs
public class BookService : IBookService
{
    private readonly BookStoreDbContext _context;
    private readonly IMapper _mapper;
    private readonly ILogger<BookService> _logger;
    
    public BookService(
        BookStoreDbContext context, 
        IMapper mapper, 
        ILogger<BookService> logger)
    {
        _context = context;
        _mapper = mapper;
        _logger = logger;
    }
    
    public async Task<PagedResult<BookSummaryDto>> GetBooksAsync(
        int page, 
        int pageSize, 
        string? category = null, 
        string? search = null)
    {
        _logger.LogInformation("Getting books: page {Page}, size {PageSize}, category {Category}, search {Search}", 
            page, pageSize, category, search);
        
        var query = _context.Books
            .Include(b => b.Category)
            .Include(b => b.Publisher)
            .AsQueryable();
        
        // Apply filters
        if (!string.IsNullOrEmpty(category))
        {
            query = query.Where(b => b.Category.Name.Contains(category));
        }
        
        if (!string.IsNullOrEmpty(search))
        {
            query = query.Where(b => 
                b.Title.Contains(search) ||
                b.Description.Contains(search) ||
                b.BookAuthors.Any(ba => 
                    ba.Author.FirstName.Contains(search) ||
                    ba.Author.LastName.Contains(search)));
        }
        
        var totalCount = await query.CountAsync();
        
        var books = await query
            .AsNoTracking()
            .OrderBy(b => b.Title)
            .Skip((page - 1) * pageSize)
            .Take(pageSize)
            .ProjectTo<BookSummaryDto>(_mapper.ConfigurationProvider)
            .ToListAsync();
        
        return new PagedResult<BookSummaryDto>
        {
            Data = books,
            TotalCount = totalCount,
            Page = page,
            PageSize = pageSize,
            TotalPages = (int)Math.Ceiling((double)totalCount / pageSize)
        };
    }
    
    // ... implement all other interface methods following the patterns shown above
}
```

**Expected Test Results:**
- ✅ All CRUD operations working correctly
- ✅ Relationships properly maintained
- ✅ Validation errors handled gracefully
- ✅ Performance optimizations in place
- ✅ Async operations throughout
- ✅ Comprehensive logging implemented

---

## **Part 3: Authentication & Authorization**
### *Building Secure .NET Applications with ASP.NET Core Identity*

<div style="background-color: #e3f2fd; padding: 20px; border-left: 4px solid #2196f3; margin: 20px 0;">

Welcome to **Part 3** of our comprehensive .NET tutorial! In this section, we'll dive deep into one of the most critical aspects of modern web development: **Authentication and Authorization**.

**What makes this part special:**
- 🔐 **Industry-standard security practices** with ASP.NET Core Identity
- 🎯 **Real-world authentication flows** including registration, login, and logout
- 🛡️ **Advanced authorization patterns** with roles, policies, and claims
- 🔑 **JWT token-based authentication** for modern applications
- 🚀 **Production-ready security features** including 2FA, password policies, and account lockout

**By the end of this part, you'll be able to:**
- Set up ASP.NET Core Identity with Entity Framework
- Implement secure user registration and authentication flows
- Create role-based and policy-based authorization
- Generate and validate JWT tokens for API authentication
- Implement advanced security features like two-factor authentication
- Handle security best practices and common vulnerabilities

</div>

### **Why Authentication & Authorization Matter**

In today's digital landscape, security isn't optional—it's essential. Every application that handles user data needs robust authentication (who you are) and authorization (what you can do) systems.

**Real-world scenarios we'll address:**
- **E-commerce platforms** needing customer accounts and admin access
- **Content management systems** with different user roles
- **API services** requiring secure token-based authentication
- **Enterprise applications** with complex permission structures

Let's build security the right way from the start!

---

#### **Module 3.1: ASP.NET Core Identity Setup**

ASP.NET Core Identity is Microsoft's comprehensive membership system that provides a robust foundation for authentication and user management. It handles the complex aspects of user security so you can focus on your application's business logic.

**What you'll learn in this module:**
- Understanding ASP.NET Core Identity architecture
- Setting up Identity with Entity Framework Core
- Configuring Identity services and options
- Creating custom user and role entities
- Database schema and migrations for Identity

#### **Section 3.1.1: Understanding ASP.NET Core Identity**

ASP.NET Core Identity is a complete membership system that provides:

**Core Components:**
- **UserManager\<TUser\>**: Manages users (create, update, delete, find)
- **SignInManager\<TUser\>**: Handles sign-in operations and authentication
- **RoleManager\<TRole\>**: Manages roles and role-based operations
- **IdentityDbContext**: Entity Framework context for Identity data

**Key Features:**
- Secure password hashing and storage
- Account confirmation via email/SMS
- Two-factor authentication support
- Account lockout protection
- Password reset functionality
- External login providers (Google, Facebook, etc.)

**Identity Architecture:**

```csharp
// Core Identity Services Flow
public class IdentityFlow
{
    /*
    User Registration Flow:
    1. UserManager validates user data
    2. Password is hashed using secure algorithms
    3. User entity is created in database
    4. Optional: Email confirmation token generated
    5. User can sign in (if email confirmed)
    
    Authentication Flow:
    1. SignInManager validates credentials
    2. Password hash is verified
    3. Authentication cookie/token is created
    4. User identity is established in request context
    
    Authorization Flow:
    1. ClaimsPrincipal contains user identity
    2. Authorization policies evaluate claims/roles
    3. Access is granted or denied
    */
}
```

**Identity Data Model:**

```csharp
// Built-in Identity entities
public class ApplicationUser : IdentityUser
{
    // IdentityUser provides:
    // - Id, UserName, Email
    // - PasswordHash, SecurityStamp
    // - PhoneNumber, EmailConfirmed
    // - LockoutEnd, AccessFailedCount
    // - And more...
    
    // Add custom properties
    public string FirstName { get; set; } = string.Empty;
    public string LastName { get; set; } = string.Empty;
    public DateTime CreatedAt { get; set; } = DateTime.UtcNow;
    public DateTime? LastLoginAt { get; set; }
    public bool IsActive { get; set; } = true;
    
    // Navigation properties
    public virtual ICollection<ApplicationUserRole> UserRoles { get; set; } = new List<ApplicationUserRole>();
}

public class ApplicationRole : IdentityRole
{
    // IdentityRole provides:
    // - Id, Name, NormalizedName
    // - ConcurrencyStamp
    
    // Add custom properties
    public string Description { get; set; } = string.Empty;
    public DateTime CreatedAt { get; set; } = DateTime.UtcNow;
    public bool IsActive { get; set; } = true;
    
    // Navigation properties
    public virtual ICollection<ApplicationUserRole> UserRoles { get; set; } = new List<ApplicationUserRole>();
}

public class ApplicationUserRole : IdentityUserRole<string>
{
    // Junction table for many-to-many User-Role relationship
    public virtual ApplicationUser User { get; set; } = null!;
    public virtual ApplicationRole Role { get; set; } = null!;
    public DateTime AssignedAt { get; set; } = DateTime.UtcNow;
    public string AssignedBy { get; set; } = string.Empty;
}
```

#### **Section 3.1.2: Installing and Configuring Identity Packages**

Let's set up ASP.NET Core Identity step by step.

**Step 1: Install Required Packages**

```xml
<!-- Add to your .csproj file -->
<PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="9.0.0" />
<PackageReference Include="Microsoft.AspNetCore.Identity.UI" Version="9.0.0" />
<PackageReference Include="Microsoft.AspNetCore.Authentication.JwtBearer" Version="9.0.0" />
```

Or via Package Manager Console:
```powershell
Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore
Install-Package Microsoft.AspNetCore.Identity.UI  
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer
```

**Step 2: Create Custom Identity Context**

```csharp
// Data/ApplicationDbContext.cs
public class ApplicationDbContext : IdentityDbContext<ApplicationUser, ApplicationRole, string>
{
    public ApplicationDbContext(DbContextOptions<ApplicationDbContext> options)
        : base(options)
    {
    }
    
    // Your existing DbSets
    public DbSet<Book> Books { get; set; }
    public DbSet<Author> Authors { get; set; }
    public DbSet<Category> Categories { get; set; }
    public DbSet<Publisher> Publishers { get; set; }
    
    protected override void OnModelCreating(ModelBuilder builder)
    {
        base.OnModelCreating(builder); // Critical: Call base first for Identity tables
        
        // Configure Identity relationships
        builder.Entity<ApplicationUser>(entity =>
        {
            entity.Property(e => e.FirstName).HasMaxLength(50).IsRequired();
            entity.Property(e => e.LastName).HasMaxLength(50).IsRequired();
            entity.HasIndex(e => e.Email).IsUnique();
            
            // Configure user-role relationship
            entity.HasMany(e => e.UserRoles)
                  .WithOne(e => e.User)
                  .HasForeignKey(ur => ur.UserId)
                  .IsRequired();
        });
        
        builder.Entity<ApplicationRole>(entity =>
        {
            entity.Property(e => e.Description).HasMaxLength(200);
            
            // Configure role-user relationship
            entity.HasMany(e => e.UserRoles)
                  .WithOne(e => e.Role)
                  .HasForeignKey(ur => ur.RoleId)
                  .IsRequired();
        });
        
        builder.Entity<ApplicationUserRole>(entity =>
        {
            entity.Property(e => e.AssignedBy).HasMaxLength(100);
        });
        
        // Configure your existing entities
        ConfigureBookEntities(builder);
    }
    
    private void ConfigureBookEntities(ModelBuilder builder)
    {
        // Your existing entity configurations
        builder.Entity<Book>(entity =>
        {
            entity.Property(e => e.Title).HasMaxLength(200).IsRequired();
            entity.Property(e => e.ISBN).HasMaxLength(13).IsRequired();
            entity.HasIndex(e => e.ISBN).IsUnique();
            // ... other configurations
        });
    }
}
```

**Step 3: Configure Identity Services**

```csharp
// Program.cs - Complete Identity configuration
var builder = WebApplication.CreateBuilder(args);

// Database configuration
builder.Services.AddDbContext<ApplicationDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection")));

// Identity configuration
builder.Services.AddIdentity<ApplicationUser, ApplicationRole>(options =>
{
    // Password settings
    options.Password.RequiredLength = 8;
    options.Password.RequireDigit = true;
    options.Password.RequireLowercase = true;
    options.Password.RequireUppercase = true;
    options.Password.RequireNonAlphanumeric = true;
    options.Password.RequiredUniqueChars = 1;
    
    // Lockout settings
    options.Lockout.DefaultLockoutTimeSpan = TimeSpan.FromMinutes(15);
    options.Lockout.MaxFailedAccessAttempts = 5;
    options.Lockout.AllowedForNewUsers = true;
    
    // User settings
    options.User.AllowedUserNameCharacters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789-._@+";
    options.User.RequireUniqueEmail = true;
    
    // Sign-in settings
    options.SignIn.RequireConfirmedEmail = false; // Set to true in production
    options.SignIn.RequireConfirmedPhoneNumber = false;
    options.SignIn.RequireConfirmedAccount = false;
})
.AddEntityFrameworkStores<ApplicationDbContext>()
.AddDefaultTokenProviders();

// Configure application cookie
builder.Services.ConfigureApplicationCookie(options =>
{
    options.AccessDeniedPath = "/Account/AccessDenied";
    options.Cookie.Name = "BookStoreAuth";
    options.Cookie.HttpOnly = true;
    options.Cookie.SameSite = SameSiteMode.Strict;
    options.ExpireTimeSpan = TimeSpan.FromDays(30);
    options.LoginPath = "/Account/Login";
    options.LogoutPath = "/Account/Logout";
    options.ReturnUrlParameter = CookieAuthenticationDefaults.ReturnUrlParameter;
    options.SlidingExpiration = true;
});

// Add other services
builder.Services.AddControllersWithViews();
builder.Services.AddRazorPages();

var app = builder.Build();

// Configure pipeline
if (!app.Environment.IsDevelopment())
{
    app.UseExceptionHandler("/Home/Error");
    app.UseHsts();
}

app.UseHttpsRedirection();
app.UseStaticFiles();
app.UseRouting();

// Authentication & Authorization middleware (order matters!)
app.UseAuthentication(); // First: Establish identity
app.UseAuthorization();  // Second: Check permissions

app.MapControllerRoute(
    name: "default",
    pattern: "{controller=Home}/{action=Index}/{id?}");
app.MapRazorPages();

app.Run();
```

#### **Section 3.1.3: Creating Identity Database Migration**

With Identity configured, let's create the database migration to set up all the necessary tables.

**Step 1: Create Identity Migration**

```powershell
# Add migration for Identity tables
Add-Migration AddIdentityTables -Context ApplicationDbContext

# Review the generated migration file
# It should include tables for:
# - AspNetUsers, AspNetRoles
# - AspNetUserRoles, AspNetUserClaims, AspNetRoleClaims
# - AspNetUserLogins, AspNetUserTokens
```

**Step 2: Review Generated Migration**

```csharp
// Migrations/[Timestamp]_AddIdentityTables.cs
public partial class AddIdentityTables : Migration
{
    protected override void Up(MigrationBuilder migrationBuilder)
    {
        // Creates comprehensive Identity schema
        migrationBuilder.CreateTable(
            name: "AspNetRoles",
            columns: table => new
            {
                Id = table.Column<string>(type: "nvarchar(450)", nullable: false),
                Name = table.Column<string>(type: "nvarchar(256)", maxLength: 256, nullable: true),
                NormalizedName = table.Column<string>(type: "nvarchar(256)", maxLength: 256, nullable: true),
                ConcurrencyStamp = table.Column<string>(type: "nvarchar(max)", nullable: true),
                Description = table.Column<string>(type: "nvarchar(200)", maxLength: 200, nullable: false),
                CreatedAt = table.Column<DateTime>(type: "datetime2", nullable: false),
                IsActive = table.Column<bool>(type: "bit", nullable: false)
            });
        
        // ... many more tables for complete Identity system
    }
}
```

**Step 3: Apply Migration and Verify**

```powershell
# Apply the migration
Update-Database -Context ApplicationDbContext

# Verify in SQL Server Management Studio
# You should see all Identity tables created
```

#### **Section 3.1.4: Seeding Default Roles and Admin User**

Let's create a robust data seeding system for our Identity setup.

**Step 1: Create Identity Seed Service**

```csharp
// Services/IdentitySeedService.cs
public class IdentitySeedService
{
    private readonly UserManager<ApplicationUser> _userManager;
    private readonly RoleManager<ApplicationRole> _roleManager;
    private readonly ILogger<IdentitySeedService> _logger;
    
    public IdentitySeedService(
        UserManager<ApplicationUser> userManager,
        RoleManager<ApplicationRole> roleManager,
        ILogger<IdentitySeedService> logger)
    {
        _userManager = userManager;
        _roleManager = roleManager;
        _logger = logger;
    }
    
    public async Task SeedAsync()
    {
        try
        {
            await SeedRolesAsync();
            await SeedAdminUserAsync();
            await SeedTestUsersAsync();
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "An error occurred while seeding Identity data");
            throw;
        }
    }
    
    private async Task SeedRolesAsync()
    {
        var roles = new[]
        {
            new ApplicationRole 
            { 
                Name = "Admin", 
                Description = "Full system access and management capabilities",
                IsActive = true 
            },
            new ApplicationRole 
            { 
                Name = "Manager", 
                Description = "Content management and user oversight capabilities",
                IsActive = true 
            },
            new ApplicationRole 
            { 
                Name = "User", 
                Description = "Standard user access to application features",
                IsActive = true 
            },
            new ApplicationRole 
            { 
                Name = "Customer", 
                Description = "Customer-specific features and purchasing capabilities",
                IsActive = true 
            }
        };
        
        foreach (var role in roles)
        {
            if (!await _roleManager.RoleExistsAsync(role.Name))
            {
                var result = await _roleManager.CreateAsync(role);
                if (result.Succeeded)
                {
                    _logger.LogInformation("Created role: {RoleName}", role.Name);
                }
                else
                {
                    _logger.LogError("Failed to create role {RoleName}: {Errors}", 
                        role.Name, string.Join(", ", result.Errors.Select(e => e.Description)));
                }
            }
        }
    }
    
    private async Task SeedAdminUserAsync()
    {
        const string adminEmail = "admin@bookstore.com";
        const string adminPassword = "Admin123!";
        
        var adminUser = await _userManager.FindByEmailAsync(adminEmail);
        if (adminUser == null)
        {
            adminUser = new ApplicationUser
            {
                UserName = adminEmail,
                Email = adminEmail,
                EmailConfirmed = true,
                FirstName = "System",
                LastName = "Administrator",
                IsActive = true,
                CreatedAt = DateTime.UtcNow
            };
            
            var result = await _userManager.CreateAsync(adminUser, adminPassword);
            if (result.Succeeded)
            {
                await _userManager.AddToRoleAsync(adminUser, "Admin");
                _logger.LogInformation("Created admin user: {Email}", adminEmail);
            }
            else
            {
                _logger.LogError("Failed to create admin user: {Errors}", 
                    string.Join(", ", result.Errors.Select(e => e.Description)));
            }
        }
    }
    
    private async Task SeedTestUsersAsync()
    {
        var testUsers = new[]
        {
            new { Email = "manager@bookstore.com", FirstName = "John", LastName = "Manager", Role = "Manager" },
            new { Email = "user@bookstore.com", FirstName = "Jane", LastName = "User", Role = "User" },
            new { Email = "customer@bookstore.com", FirstName = "Bob", LastName = "Customer", Role = "Customer" }
        };
        
        foreach (var userData in testUsers)
        {
            var user = await _userManager.FindByEmailAsync(userData.Email);
            if (user == null)
            {
                user = new ApplicationUser
                {
                    UserName = userData.Email,
                    Email = userData.Email,
                    EmailConfirmed = true,
                    FirstName = userData.FirstName,
                    LastName = userData.LastName,
                    IsActive = true,
                    CreatedAt = DateTime.UtcNow
                };
                
                var result = await _userManager.CreateAsync(user, "TestUser123!");
                if (result.Succeeded)
                {
                    await _userManager.AddToRoleAsync(user, userData.Role);
                    _logger.LogInformation("Created test user: {Email} with role {Role}", 
                        userData.Email, userData.Role);
                }
            }
        }
    }
}
```

**Step 2: Register and Call Seed Service**

```csharp
// Program.cs - Add after building the app
// ... existing code ...

var app = builder.Build();

// Seed Identity data
using (var scope = app.Services.CreateScope())
{
    var services = scope.ServiceProvider;
    try
    {
        var identitySeedService = new IdentitySeedService(
            services.GetRequiredService<UserManager<ApplicationUser>>(),
            services.GetRequiredService<RoleManager<ApplicationRole>>(),
            services.GetRequiredService<ILogger<IdentitySeedService>>());
        
        await identitySeedService.SeedAsync();
    }
    catch (Exception ex)
    {
        var logger = services.GetRequiredService<ILogger<Program>>();
        logger.LogError(ex, "An error occurred while seeding Identity data");
    }
}

// ... rest of pipeline configuration
```

---

#### **Challenge 3.1: Set up your Identity foundation**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Set up a complete ASP.NET Core Identity system with custom user and role entities, proper configuration, and data seeding. This foundational challenge prepares your application for secure user management.

**What You'll Learn:**
- Complete Identity setup and configuration
- Custom user and role entity creation
- Database migration and schema management
- Identity data seeding strategies
- Security configuration best practices

</div>

**Challenge Requirements:**

1. **Set Up Identity Infrastructure:**
   - Install required Identity packages
   - Create custom ApplicationUser and ApplicationRole classes
   - Configure ApplicationDbContext with Identity
   - Create and apply Identity migrations

2. **Configure Identity Services:**
   - Set up Identity with comprehensive password policies
   - Configure account lockout settings
   - Set up authentication cookies with security options
   - Add proper middleware configuration

3. **Implement Data Seeding:**
   - Create roles: Admin, Manager, User, Customer
   - Seed admin user with secure credentials
   - Add test users for each role
   - Implement proper error handling and logging

4. **Verify Security Configuration:**
   - Test password validation rules
   - Verify role assignments
   - Confirm database schema creation
   - Test user creation and authentication

**Solution Implementation:**

**Step 1: Package Installation and Project Setup**
```xml
<!-- Verify these packages in your .csproj -->
<PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="9.0.0" />
<PackageReference Include="Microsoft.AspNetCore.Identity.UI" Version="9.0.0" />
<PackageReference Include="Microsoft.AspNetCore.Authentication.JwtBearer" Version="9.0.0" />
```

**Step 2: Complete Entity Definitions**
```csharp
// Models/ApplicationUser.cs
public class ApplicationUser : IdentityUser
{
    [Required]
    [MaxLength(50)]
    public string FirstName { get; set; } = string.Empty;
    
    [Required]
    [MaxLength(50)]
    public string LastName { get; set; } = string.Empty;
    
    public DateTime CreatedAt { get; set; } = DateTime.UtcNow;
    public DateTime? LastLoginAt { get; set; }
    public bool IsActive { get; set; } = true;
    
    [NotMapped]
    public string FullName => $"{FirstName} {LastName}";
    
    public virtual ICollection<ApplicationUserRole> UserRoles { get; set; } = new List<ApplicationUserRole>();
}
```

**Step 3: Database Configuration and Migration**
```powershell
# Create the migration
Add-Migration AddIdentitySystem -Context ApplicationDbContext

# Apply the migration
Update-Database -Context ApplicationDbContext

# Verify tables created:
# - AspNetUsers, AspNetRoles, AspNetUserRoles
# - AspNetUserClaims, AspNetRoleClaims
# - AspNetUserLogins, AspNetUserTokens
```

**Step 4: Service Configuration Verification**
```csharp
// Program.cs verification checklist
// ✅ Identity services registered with proper options
// ✅ ApplicationDbContext configured with connection string
// ✅ Authentication and authorization middleware in correct order
// ✅ Cookie configuration for security
// ✅ Password policies configured
```

**Expected Test Results:**
- ✅ Identity database tables created successfully
- ✅ Admin user account created with email: admin@bookstore.com
- ✅ All four roles (Admin, Manager, User, Customer) created
- ✅ Test users created and assigned to roles
- ✅ Password policies enforced (8+ chars, mixed case, numbers, symbols)
- ✅ Account lockout configured (5 failed attempts, 15-minute lockout)

**Verification Commands:**
```sql
-- Check tables were created
SELECT name FROM sys.tables WHERE name LIKE 'AspNet%' ORDER BY name;

-- Verify roles
SELECT Id, Name, Description FROM AspNetRoles;

-- Check users and their roles
SELECT u.Email, u.FirstName, u.LastName, r.Name as Role
FROM AspNetUsers u
JOIN AspNetUserRoles ur ON u.Id = ur.UserId
JOIN AspNetRoles r ON ur.RoleId = r.Id;
```

<div style="page-break-after: always;"></div>

---

## 🎓 Course Content

Now that we've covered the essential C# concepts, let's dive into building real-world web applications. The following modules will take you from setting up your development environment to deploying a production-ready application with authentication, data persistence, and modern UI components.

<div style="background-color: #e3f2fd; padding: 20px; border-left: 4px solid #2196f3; margin: 20px 0;">

**Learning Philosophy:** This course follows a hands-on, project-based approach. Each module builds upon the previous one, and by the end, you'll have created a complete, industry-standard web application. Don't just read the code—type it out, experiment with it, and make it your own.

</div>

### **Part 1: ASP.NET Core Web API Fundamentals**

Web APIs are the backbone of modern web applications, serving as the communication layer between frontend interfaces and backend data. ASP.NET Core's Web API framework provides a robust, scalable foundation for building HTTP services that can serve various clients—from web browsers and mobile apps to other services and third-party integrations.

Understanding how to build well-designed APIs is crucial in today's development landscape. Modern applications are increasingly distributed, with frontend and backend often developed and deployed separately. This architectural approach, known as the "API-first" strategy, allows for greater flexibility, easier testing, and better separation of concerns.

Throughout Part 1, we'll explore the fundamental concepts that make ASP.NET Core Web APIs powerful and developer-friendly. We'll start with the basics—setting up your environment and creating your first API—then progressively add complexity as we introduce controllers, dependency injection, and data models. By the end of this part, you'll understand not just how to build APIs, but how to build them well, following industry best practices and modern .NET conventions.

#### Module 1.1: Getting Started with ASP.NET Core

Setting up a proper development environment is the foundation of productive software development. With .NET 9, Microsoft has streamlined the development experience significantly, but there are still important considerations for tooling, extensions, and project configuration that can make the difference between a frustrating experience and a smooth, productive workflow.

The modern .NET development experience centers around the .NET CLI (Command Line Interface), which provides powerful scaffolding, building, and deployment capabilities. Even if you prefer working in Visual Studio or Visual Studio Code, understanding the CLI commands will make you more versatile and help you automate development tasks.

##### **Section 1.1.1:** Setting up your development environment (Visual Studio/VS Code)

The choice of development environment significantly impacts your productivity and debugging capabilities. Visual Studio offers the most comprehensive development experience with advanced debugging, integrated testing tools, and sophisticated project management features. Visual Studio Code, while lighter, provides excellent .NET support through extensions and offers superior performance for many development scenarios.

Regardless of your IDE choice, certain extensions and configurations are essential for .NET development. IntelliSense, debugging support, integrated terminal access, and proper syntax highlighting form the foundation of any good .NET development setup. Additionally, modern development practices like GitLens for source control visualization, REST Client for API testing, and various productivity extensions can significantly enhance your workflow.

**Installing .NET 9 SDK:**
```bash
# Verify your installation
dotnet --version
# Should show 9.0.xxx

# List installed SDKs
dotnet --list-sdks

# List available project templates
dotnet new list
```

**Essential VS Code Extensions for .NET Development:**
If you choose Visual Studio Code, these extensions will provide a development experience comparable to Visual Studio for most scenarios:

- **C# Dev Kit** - Comprehensive C# and .NET support
- **C#** - Basic C# language support and debugging
- **NuGet Gallery** - Browse and install NuGet packages
- **REST Client** - Test APIs directly from VS Code
- **GitLens** - Enhanced Git capabilities
- **Bracket Pair Colorizer** - Visual bracket matching
- **Auto Rename Tag** - Automatically rename paired HTML/XML tags
- **Thunder Client** - API testing tool (alternative to Postman)

**Project Configuration Best Practices:**
Modern .NET projects use SDK-style project files that are much cleaner and more maintainable than their predecessors. Understanding how to configure these files properly ensures your projects work well in different environments and with various deployment scenarios.

```xml
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>net9.0</TargetFramework>
    <Nullable>enable</Nullable>
    <ImplicitUsings>enable</ImplicitUsings>
    <TreatWarningsAsErrors>true</TreatWarningsAsErrors>
    <WarningsAsErrors />
    <WarningsNotAsErrors>CS1591</WarningsNotAsErrors>
  </PropertyGroup>

  <PropertyGroup Condition="'$(Configuration)' == 'Debug'">
    <DefineConstants>DEBUG;TRACE</DefineConstants>
  </PropertyGroup>
</Project>
```

##### **Section 1.1.2:** Creating your first ASP.NET Core Web API project

The `dotnet new` command provides several templates for creating ASP.NET Core applications. For API development, the `webapi` template creates a minimal but complete starting point that follows current best practices. Understanding what this template provides and why helps you make informed decisions about project structure and configuration.

Modern ASP.NET Core applications use a streamlined approach compared to earlier versions. The traditional `Startup.cs` file has been consolidated into `Program.cs`, making the application bootstrap process more straightforward while maintaining all the configuration flexibility of previous versions.

**Creating the Project:**
```bash
# Create a new directory for your project
mkdir BookStoreApi
cd BookStoreApi

# Create the Web API project
dotnet new webapi --name BookStoreApi --framework net9.0

# Navigate into the project directory
cd BookStoreApi

# Restore dependencies
dotnet restore

# Build the project
dotnet build

# Run the project
dotnet run
```

**Understanding the Generated Project Structure:**
When you create a new Web API project, the template generates a specific folder structure designed to promote good organization and separation of concerns:

```
BookStoreApi/
├── Controllers/
│   └── WeatherForecastController.cs    # Sample controller
├── Properties/
│   └── launchSettings.json             # Development settings
├── appsettings.json                    # Application configuration
├── appsettings.Development.json        # Development-specific config
├── BookStoreApi.csproj                 # Project file
├── Program.cs                          # Application entry point
└── WeatherForecast.cs                  # Sample model
```

Each component serves a specific purpose:

- **Controllers/**: Contains your API controllers that handle HTTP requests
- **Properties/launchSettings.json**: Defines how your application launches in different environments
- **appsettings.json**: Configuration for different application aspects (connection strings, API keys, etc.)
- **Program.cs**: The application's entry point where services are configured and the request pipeline is built

##### **Section 1.1.3:** Understanding the project structure and startup configuration

The `Program.cs` file in .NET 9 represents a significant evolution in how ASP.NET Core applications are configured. This minimal hosting model reduces boilerplate code while maintaining full control over application behavior. Understanding this file is crucial because it's where you'll configure services, middleware, and application behavior.

**Examining Program.cs:**
```csharp
var builder = WebApplication.CreateBuilder(args);

// Add services to the container.
builder.Services.AddControllers();
// Learn more about configuring Swagger/OpenAPI at https://aka.ms/aspnetcore/swashbuckle
builder.Services.AddEndpointsApiExplorer();
builder.Services.AddSwaggerGen();

var app = builder.Build();

// Configure the HTTP request pipeline.
if (app.Environment.IsDevelopment())
{
    app.UseSwagger();
    app.UseSwaggerUI();
}

app.UseHttpsRedirection();
app.UseAuthorization();
app.MapControllers();

app.Run();
```

This seemingly simple file accomplishes several important tasks:

1. **Service Configuration**: The `builder.Services` section is where you register services for dependency injection
2. **Application Building**: `builder.Build()` creates the application instance with all configured services
3. **Middleware Pipeline**: The series of `app.Use...` calls define how HTTP requests are processed
4. **Controller Mapping**: `app.MapControllers()` sets up routing to your controller actions

**The Request Pipeline:**
Understanding the middleware pipeline is fundamental to ASP.NET Core development. Each piece of middleware can examine, modify, or respond to HTTP requests and responses. The order of middleware registration is crucial—each middleware component processes requests in the order they're added and processes responses in reverse order.

```csharp
// Middleware executes in this order for requests:
// 1. HTTPS Redirection - Ensures secure connections
// 2. Authorization - Validates user permissions
// 3. Controller routing - Matches URLs to controller actions

// And in reverse order for responses:
// 3. Controller routing generates response
// 2. Authorization may modify response headers
// 1. HTTPS Redirection ensures response is secure
```
##### **Section 1.1.4:** Running and testing your first API endpoint

Testing your API endpoints is an integral part of development, not an afterthought. Modern ASP.NET Core applications come with Swagger/OpenAPI integration by default, providing an interactive documentation and testing interface. This tool not only helps you test endpoints during development but also serves as living documentation for your API.

**Running Your Application:**
```bash
# Run with hot reload (recommended for development)
dotnet watch run

# Or run normally
dotnet run
```

When you run the application, you'll see output similar to:
```
info: Microsoft.Hosting.Lifetime[14]
      Now listening on: https://localhost:7173
info: Microsoft.Hosting.Lifetime[14]  
      Now listening on: http://localhost:5173
```

**Testing with Swagger UI:**
Navigate to `https://localhost:7173/swagger` (adjust port as needed) to access the Swagger UI. This interface shows all available endpoints, their parameters, and allows you to test them directly from your browser. The generated WeatherForecast endpoint demonstrates the basic structure of an API controller.

**Understanding the Sample WeatherForecast Controller:**
```csharp
[ApiController]
[Route("[controller]")]
public class WeatherForecastController : ControllerBase
{
    private static readonly string[] Summaries = new[]
    {
        "Freezing", "Bracing", "Chilly", "Cool", "Mild", "Warm", "Balmy", "Hot", "Sweltering", "Scorching"
    };

    private readonly ILogger<WeatherForecastController> _logger;

    public WeatherForecastController(ILogger<WeatherForecastController> logger)
    {
        _logger = logger;
    }

    [HttpGet(Name = "GetWeatherForecast")]
    public IEnumerable<WeatherForecast> Get()
    {
        return Enumerable.Range(1, 5).Select(index => new WeatherForecast
        {
            Date = DateOnly.FromDateTime(DateTime.Now.AddDays(index)),
            TemperatureC = Random.Shared.Next(-20, 55),
            Summary = Summaries[Random.Shared.Next(Summaries.Length)]
        })
        .ToArray();
    }
}
```

This controller demonstrates several important concepts:
- **Attribute routing** with `[Route("[controller]")]`
- **Dependency injection** with the logger parameter
- **HTTP verb mapping** with `[HttpGet]`
- **Data generation and transformation** in the action method

**Testing with REST Client Tools:**
While Swagger UI is convenient for quick testing, professional API development often requires more sophisticated testing tools. Here are examples using different approaches:

*Using curl:*
```bash
curl -X GET "https://localhost:7173/WeatherForecast" -H "accept: text/plain"
```

*Using PowerShell:*
```powershell
Invoke-RestMethod -Uri "https://localhost:7173/WeatherForecast" -Method GET
```

*Using VS Code REST Client extension:*
```http
### Get Weather Forecast
GET https://localhost:7173/WeatherForecast
Accept: application/json
```

---

#### **Challenge 1.1: Create a "Hello World" API with custom routing**

<div style="background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0;">

**Challenge Objective:** Create a simple API controller that demonstrates custom routing and returns personalized greetings. This challenge reinforces basic controller concepts while introducing route customization.

**What You'll Learn:**
- Custom route configuration
- Action method naming conventions
- Basic parameter handling
- HTTP status code responses

</div>

**Challenge Requirements:**
1. Create a new controller called `GreetingController`
2. Implement the following endpoints:
   - `GET /api/hello` - Returns "Hello, World!"
   - `GET /api/hello/{name}` - Returns "Hello, {name}!"
   - `GET /api/greet/{name}/{time}` - Returns appropriate greeting based on time of day
3. Add proper HTTP status codes and response types
4. Test all endpoints using Swagger UI

**Solution Approach:**
Think about how routes are structured and how parameters are passed to action methods. Consider what constitutes appropriate HTTP responses for different scenarios (successful responses, validation errors, etc.).

```csharp
// Starter template - complete the implementation
[ApiController]
[Route("api/[controller]")]
public class GreetingController : ControllerBase
{
    [HttpGet("/api/hello")]
    public ActionResult<string> SayHello()
    {
        // TODO: Return "Hello, World!"
    }

    [HttpGet("/api/hello/{name}")]
    public ActionResult<string> SayHelloToName(string name)
    {
        // TODO: Return personalized greeting
        // Consider validation - what if name is null or empty?
    }

    [HttpGet("/api/greet/{name}/{time}")]
    public ActionResult<string> GreetByTime(string name, string time)
    {
        // TODO: Return time-appropriate greeting
        // Handle different time values: morning, afternoon, evening
        // Consider validation for both parameters
    }
}
```

**Expected Output Examples:**
- `GET /api/hello` → `"Hello, World!"`
- `GET /api/hello/John` → `"Hello, John!"`
- `GET /api/greet/Sarah/morning` → `"Good morning, Sarah!"`
- `GET /api/greet/Mike/invalid` → Appropriate error response

<div style="page-break-after: always;"></div>

#### Module 1.2: Controllers and Routing in Depth

Controllers are the heart of any ASP.NET Core Web API, serving as the entry points for HTTP requests and coordinating the flow of data between clients and your application's business logic. Understanding how to design controllers effectively is crucial for building maintainable, testable, and scalable APIs.

Modern controller design emphasizes thin controllers with focused responsibilities. Rather than containing complex business logic, controllers should primarily handle HTTP concerns—request validation, response formatting, and coordination between services. This approach, known as the "thin controller, fat service" pattern, promotes better separation of concerns and makes your code easier to test and maintain.

##### **Section 1.2.1:** What are controllers and why do we need them?

Controllers serve as the bridge between the HTTP protocol and your application's domain logic. They handle the translation of HTTP requests into method calls on your business services, and then translate the results back into appropriate HTTP responses. This abstraction layer is essential because it allows your business logic to remain independent of HTTP concerns, making it more reusable and testable.

In the context of web APIs, controllers define the contract between your API and its consumers. Each controller typically represents a related group of operations on a specific resource or domain concept. For example, a `BooksController` would handle all HTTP operations related to books—creating, reading, updating, and deleting book records.

**The Role of Controllers in Modern APIs:**
Controllers in ASP.NET Core Web APIs have several key responsibilities:

1. **Request Routing**: Matching incoming HTTP requests to appropriate action methods
2. **Parameter Binding**: Converting HTTP request data into .NET objects
3. **Validation**: Ensuring incoming data meets your application's requirements
4. **Service Coordination**: Calling appropriate business services to fulfill requests
5. **Response Formatting**: Converting service results into HTTP responses
6. **Error Handling**: Gracefully managing exceptions and returning appropriate error responses

**Controller Design Principles:**
Effective controller design follows several important principles that promote maintainability and testability:

- **Single Responsibility**: Each controller should handle operations for one resource type
- **Thin Controllers**: Business logic should reside in services, not controllers
- **Consistent Naming**: Follow RESTful conventions for predictable APIs
- **Proper HTTP Usage**: Use appropriate HTTP verbs and status codes
- **Validation**: Validate input early and return meaningful error messages

##### **Section 1.2.2:** Creating your first controller and action methods

Let's create a practical controller for managing books in our bookstore API. This controller will demonstrate the fundamental patterns you'll use throughout your API development career.

**Creating the Book Model:**
Before building our controller, we need a model to represent our data. In a real application, this would likely correspond to a database entity, but for now, we'll use a simple class.

```csharp
// Models/Book.cs
namespace BookStoreApi.Models
{
    public class Book
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public string ISBN { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public DateTime PublishedDate { get; set; }
        public string Description { get; set; } = string.Empty;
        public int StockQuantity { get; set; }
    }
}
```

**Creating the Books Controller:**
```csharp
// Controllers/BooksController.cs
using Microsoft.AspNetCore.Mvc;
using BookStoreApi.Models;

namespace BookStoreApi.Controllers
{
    [ApiController]
    [Route("api/[controller]")]
    public class BooksController : ControllerBase
    {
        // In-memory storage for demonstration
        // In a real application, this would be injected as a service
        private static readonly List<Book> _books = new()
        {
            new Book 
            { 
                Id = 1, 
                Title = "Clean Code", 
                Author = "Robert C. Martin",
                ISBN = "978-0132350884",
                Price = 42.99m,
                PublishedDate = new DateTime(2008, 8, 1),
                Description = "A handbook of agile software craftsmanship",
                StockQuantity = 15
            },
            new Book 
            { 
                Id = 2, 
                Title = "The Pragmatic Programmer", 
                Author = "David Thomas",
                ISBN = "978-0201616224",
                Price = 39.99m,
                PublishedDate = new DateTime(1999, 10, 20),
                Description = "Your journey to mastery",
                StockQuantity = 8
            }
        };

        // GET: api/books
        [HttpGet]
        public ActionResult<IEnumerable<Book>> GetBooks()
        {
            return Ok(_books);
        }

        // GET: api/books/5
        [HttpGet("{id}")]
        public ActionResult<Book> GetBook(int id)
        {
            var book = _books.FirstOrDefault(b => b.Id == id);
            
            if (book == null)
            {
                return NotFound($"Book with ID {id} was not found.");
            }
            
            return Ok(book);
        }
    }
}
```

**Understanding Action Method Structure:**
Each action method in a controller follows a consistent pattern that makes APIs predictable and easy to understand:

1. **HTTP Verb Attribute**: `[HttpGet]`, `[HttpPost]`, etc., specify which HTTP method triggers this action
2. **Route Template**: Optional parameter in the attribute defines URL patterns
3. **Method Signature**: Parameters are automatically bound from the request
4. **Return Type**: `ActionResult<T>` allows returning both data and HTTP status codes
5. **Implementation**: Business logic or service calls to fulfill the request

##### **Section 1.2.3:** Understanding HTTP verbs (GET, POST, PUT, DELETE)

HTTP verbs (also called methods) define the type of operation being requested. RESTful APIs use these verbs consistently to create predictable, intuitive interfaces. Understanding when and how to use each verb is fundamental to good API design.

**GET - Retrieving Data:**
GET requests are used to retrieve data without modifying server state. They should be safe (no side effects) and idempotent (multiple identical requests have the same effect as a single request).

```csharp
// GET: api/books
[HttpGet]
public ActionResult<IEnumerable<Book>> GetBooks(
    [FromQuery] string? search = null,
    [FromQuery] int page = 1,
    [FromQuery] int pageSize = 10)
{
    var query = _books.AsQueryable();
    
    // Apply search filter if provided
    if (!string.IsNullOrEmpty(search))
    {
        query = query.Where(b => 
            b.Title.Contains(search, StringComparison.OrdinalIgnoreCase) ||
            b.Author.Contains(search, StringComparison.OrdinalIgnoreCase));
    }
    
    // Apply pagination
    var books = query
        .Skip((page - 1) * pageSize)
        .Take(pageSize)
        .ToList();
    
    return Ok(books);
}

// GET: api/books/5
[HttpGet("{id}")]
public ActionResult<Book> GetBook(int id)
{
    if (id <= 0)
    {
        return BadRequest("ID must be a positive number.");
    }
    
    var book = _books.FirstOrDefault(b => b.Id == id);
    return book == null ? NotFound() : Ok(book);
}
```

**POST - Creating New Resources:**
POST requests create new resources. They are neither safe nor idempotent—each request typically creates a new resource with a new identifier.

```csharp
// POST: api/books
[HttpPost]
public ActionResult<Book> CreateBook([FromBody] CreateBookDto bookDto)
{
    // Validate the model
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    // Check for duplicate ISBN
    if (_books.Any(b => b.ISBN == bookDto.ISBN))
    {
        return Conflict($"A book with ISBN {bookDto.ISBN} already exists.");
    }
    
    // Create new book
    var book = new Book
    {
        Id = _books.Count > 0 ? _books.Max(b => b.Id) + 1 : 1,
        Title = bookDto.Title,
        Author = bookDto.Author,
        ISBN = bookDto.ISBN,
        Price = bookDto.Price,
        PublishedDate = bookDto.PublishedDate,
        Description = bookDto.Description ?? string.Empty,
        StockQuantity = bookDto.StockQuantity
    };
    
    _books.Add(book);
    
    // Return 201 Created with location header
    return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
}

// DTO for creating books
public class CreateBookDto
{
    [Required]
    [StringLength(200)]
    public string Title { get; set; } = string.Empty;
    
    [Required]
    [StringLength(100)]
    public string Author { get; set; } = string.Empty;
    
    [Required]
    [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$", 
        ErrorMessage = "Invalid ISBN format")]
    public string ISBN { get; set; } = string.Empty;
    
    [Range(0.01, 9999.99)]
    public decimal Price { get; set; }
    
    public DateTime PublishedDate { get; set; }
    
    [StringLength(1000)]
    public string? Description { get; set; }
    
    [Range(0, int.MaxValue)]
    public int StockQuantity { get; set; }
}

// Handling duplicate ISBN conflict
public class BookService
{
    public ActionResult<Book> CreateBook(CreateBookDto bookDto)
    {
        // Check for duplicate ISBN
        if (_books.Any(b => b.ISBN == bookDto.ISBN))
        {
            return Conflict($"A book with ISBN {bookDto.ISBN} already exists.");
        }
        
        // Create new book
        var book = new Book
        {
            Id = _books.Count > 0 ? _books.Max(b => b.Id) + 1 : 1,
            Title = bookDto.Title,
            Author = bookDto.Author,
            ISBN = bookDto.ISBN,
            Price = bookDto.Price,
            PublishedDate = bookDto.PublishedDate,
            Description = bookDto.Description ?? string.Empty,
            StockQuantity = bookDto.StockQuantity
        };
        
        _books.Add(book);
        
        return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
    }
}
```

**PUT - Updating Resources:**
PUT requests replace entire resources. They should be idempotent—multiple identical requests should have the same effect as a single request.

```csharp
// PUT: api/books/5
[HttpPut("{id}")]
public ActionResult<Book> UpdateBook(int id, [FromBody] UpdateBookDto bookDto)
{
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        return NotFound($"Book with ID {id} was not found.");
    }
    
    // Check for ISBN conflicts with other books
    if (_books.Any(b => b.Id != id && b.ISBN == bookDto.ISBN))
    {
        return Conflict($"Another book with ISBN {bookDto.ISBN} already exists.");
    }
    
    // Update book properties
    book.Title = bookDto.Title;
    book.Author = bookDto.Author;
    book.ISBN = bookDto.ISBN;
    book.Price = bookDto.Price;
    book.PublishedDate = bookDto.PublishedDate;
    book.Description = bookDto.Description ?? string.Empty;
    book.StockQuantity = bookDto.StockQuantity;
    
    return Ok(book);
}
```

**DELETE - Removing Resources:**
DELETE requests remove resources. They should be idempotent—deleting a resource multiple times should have the same effect as deleting it once.

```csharp
// DELETE: api/books/5
[HttpDelete("{id}")]
public ActionResult DeleteBook(int id)
{
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        // Idempotent: returning 204 even if already deleted
        return NoContent();
    }
    
    _books.Remove(book);
    return NoContent(); // 204 No Content
}
```

**PATCH - Partial Updates:**
PATCH requests update specific fields of a resource. While more complex to implement correctly, they're useful for APIs where clients need to update individual properties without sending the entire resource.

```csharp
// PATCH: api/books/5
[HttpPatch("{id}")]
public ActionResult<Book> PatchBook(int id, [FromBody] JsonPatchDocument<Book> patchDoc)
{
    var book = _books.FirstOrDefault(b => b.Id == id);
    if (book == null)
    {
        return NotFound();
    }
    
    // Apply the patch
    patchDoc.ApplyTo(book, ModelState);
    
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }
    
    return Ok(book);
}
```

##### **Section 1.2.4:** Route parameters and query strings

Routing in ASP.NET Core Web APIs provides flexible ways to capture data from URLs and query strings. Understanding the different binding sources and how to use them effectively is crucial for building intuitive, RESTful APIs.

**Route Parameters:**
Route parameters are captured from the URL path and are typically used for resource identifiers. They're defined in the route template using curly braces.

```csharp
[ApiController]
[Route("api/[controller]")]
public class BooksController : ControllerBase
{
    // Single parameter: /api/books/5
    [HttpGet("{id}")]
    public ActionResult<Book> GetBook(int id)
    {
        // TODO: Implement get by ID
    }
    
    // Multiple parameters: /api/books/5/reviews/10
    [HttpGet("{bookId}/reviews/{reviewId}")]
    public ActionResult<Review> GetBookReview(int bookId, int reviewId)
    {
        // Both parameters are captured from the URL
        var book = _books.FirstOrDefault(b => b.Id == bookId);
        if (book == null) return NotFound("Book not found");
        
        // Logic to find review...
        return Ok(/* review */);
    }
    
    // Optional parameters: /api/books/search/programming or /api/books/search
    [HttpGet("search/{term?}")]
    public ActionResult<IEnumerable<Book>> SearchBooks(string? term = null)
    {
        if (string.IsNullOrEmpty(term))
        {
            return Ok(_books.Take(10)); // Return first 10 books
        }
        
        var results = _books.Where(b => 
            b.Title.Contains(term, StringComparison.OrdinalIgnoreCase) ||
            b.Author.Contains(term, StringComparison.OrdinalIgnoreCase));
            
        return Ok(results);
    }
    
    // Route constraints: /api/books/123 (only numeric IDs)
    [HttpGet("{id:int:min(1)}")]
    public ActionResult<Book> GetBookWithConstraints(int id)
    {
        // id is guaranteed to be a positive integer
        var book = _books.FirstOrDefault(b => b.Id == id);
        return book == null ? NotFound() : Ok(book);
    }
}
```

**Query String Parameters:**
Query strings are ideal for optional parameters, filtering, sorting, and pagination. They appear after the `?` in URLs and can be bound automatically to action method parameters.

```csharp
// GET: /api/books?category=programming&minPrice=20&maxPrice=50&sort=title&order=asc&page=2&pageSize=10
[HttpGet]
public ActionResult<IEnumerable<Book>> GetBooks(
    [FromQuery] string? category = null,
    [FromQuery] decimal? minPrice = null,
    [FromQuery] decimal? maxPrice = null,
    [FromQuery] string? sort = "title",
    [FromQuery] string order = "asc",
    [FromQuery] int page = 1,
    [FromQuery] int pageSize = 10)
{
    var query = _books.AsQueryable();
    
    // Apply filters
    if (!string.IsNullOrEmpty(category))
    {
        query = query.Where(b => b.Category?.Equals(category, StringComparison.OrdinalIgnoreCase) == true);
    }
    
    if (minPrice.HasValue)
    {
        query = query.Where(b => b.Price >= minPrice.Value);
    }
    
    if (maxPrice.HasValue)
    {
        query = query.Where(b => b.Price <= maxPrice.Value);
    }
    
    // Apply sorting
    query = sort?.ToLower() switch
    {
        "title" => order.ToLower() == "desc" 
            ? query.OrderByDescending(b => b.Title)
            : query.OrderBy(b => b.Title),
        "author" => order.ToLower() == "desc"
            ? query.OrderByDescending(b => b.Author)
            : query.OrderBy(b => b.Author),
        "price" => order.ToLower() == "desc"
            ? query.OrderByDescending(b => b.Price)
            : query.OrderBy(b => b.Price),
        _ => query.OrderBy(b => b.Title)
    };
    
    // Apply pagination
    var totalCount = query.Count();
    var books = query
        .Skip((page - 1) * pageSize)
        .Take(pageSize)
        .ToList();
    
    // Return with pagination metadata in headers
    Response.Headers.Add("X-Total-Count", totalCount.ToString());
    Response.Headers.Add("X-Page", page.ToString());
    Response.Headers.Add("X-Page-Size", pageSize.ToString());
    
    return Ok(books);
}
```

**Complex Query Parameters:**
For more complex scenarios, you can bind query parameters to custom objects:

```csharp
public class BookSearchCriteria
{
    public string? Title { get; set; }
    public string? Author { get; set; }
    public string? Category { get; set; }
    public decimal? MinPrice { get; set; }
    public decimal? MaxPrice { get; set; }
    public DateTime? PublishedAfter { get; set; }
    public DateTime? PublishedBefore { get; set; }
    public bool? InStock { get; set; }
    public string Sort { get; set; } = "title";
    public string Order { get; set; } = "asc";
    public int Page { get; set; } = 1;
    public int PageSize { get; set; } = 10;
}

[HttpGet("search")]
public ActionResult<IEnumerable<Book>> SearchBooks([FromQuery] BookSearchCriteria criteria)
{
    var query = _books.AsQueryable();
    
    // Apply all filters based on criteria properties
    if (!string.IsNullOrEmpty(criteria.Title))
    {
        query = query.Where(b => b.Title.Contains(criteria.Title, StringComparison.OrdinalIgnoreCase));
    }
    
    if (!string.IsNullOrEmpty(criteria.Author))
    {
        query = query.Where(b => b.Author.Contains(criteria.Author, StringComparison.OrdinalIgnoreCase));
    }
    
    if (criteria.MinPrice.HasValue)
    {
        query = query.Where(b => b.Price >= criteria.MinPrice.Value);
    }
    
    if (criteria.MaxPrice.HasValue)
    {
        query = query.Where(b => b.Price <= criteria.MaxPrice.Value);
    }
    
    if (criteria.PublishedAfter.HasValue)
    {
        query = query.Where(b => b.PublishedDate >= criteria.PublishedAfter.Value);
    }
    
    if (criteria.PublishedBefore.HasValue)
    {
        query = query.Where(b => b.PublishedDate <= criteria.PublishedBefore.Value);
    }
    
    return Ok(query.ToList());
}
```

##### **Section 1.2.5:** Model binding and validation

Model binding is the process by which ASP.NET Core automatically converts HTTP request data into .NET objects. This powerful feature eliminates much of the manual work involved in parsing request data, while validation ensures that incoming data meets your application's requirements before it reaches your business logic.

Understanding how model binding works and how to configure it properly is essential for building robust APIs. Poor validation can lead to security vulnerabilities, data corruption, and poor user experience. Modern ASP.NET Core provides several validation approaches, from simple data annotations to complex custom validators.

**Automatic Model Binding:**

ASP.NET Core can bind data from multiple sources automatically:

```csharp
public class BookOrderController : ControllerBase
{
    // Binding from route, query, and body
    [HttpPost("orders/{customerId}")]
    public ActionResult<Order> CreateOrder(
        int customerId,                    // From route
        [FromQuery] string? promocode,     // From query string
        [FromBody] CreateOrderDto order,   // From request body
        [FromHeader] string userAgent)     // From headers
    {
        // All parameters are automatically bound
        var newOrder = new Order
        {
            CustomerId = customerId,
            PromoCode = promocode,
            UserAgent = userAgent,
            Items = order.Items
        };
        
        return CreatedAtAction(nameof(GetOrder), new { id = newOrder.Id }, newOrder);
    }
}
```

**Data Annotations for Validation:**

Data annotations provide a declarative way to specify validation rules directly on your model properties:

```csharp
public class CreateBookDto
{
    [Required(ErrorMessage = "Title is required")]
    [StringLength(200, MinimumLength = 1, ErrorMessage = "Title must be between 1 and 200 characters")]
    public string Title { get; set; } = string.Empty;
    
    [Required(ErrorMessage = "Author is required")]
    [StringLength(100, MinimumLength = 2, ErrorMessage = "Author name must be between 2 and 100 characters")]
    public string Author { get; set; } = string.Empty;
    
    [Required(ErrorMessage = "ISBN is required")]
    [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$", 
        ErrorMessage = "Invalid ISBN format")]
    public string ISBN { get; set; } = string.Empty;
    
    [Range(0.01, 9999.99, ErrorMessage = "Price must be between $0.01 and $9999.99")]
    public decimal Price { get; set; }
    
    public DateTime PublishedDate { get; set; }
    
    [StringLength(1000, ErrorMessage = "Description cannot exceed 1000 characters")]
    public string? Description { get; set; }
    
    [Range(0, int.MaxValue, ErrorMessage = "Stock quantity cannot be negative")]
    public int StockQuantity { get; set; }
    
    [EmailAddress(ErrorMessage = "Invalid email format")]
    public string? ContactEmail { get; set; }
    
    [Url(ErrorMessage = "Invalid URL format")]
    public string? PublisherWebsite { get; set; }
}
```

**Custom Validation Attributes:**

For more complex validation rules, you can create custom validation attributes:

```csharp
public class FutureDateAttribute : ValidationAttribute
{
    public override bool IsValid(object? value)
    {
        if (value is DateTime date)
        {
            return date <= DateTime.Now.AddYears(2); // Books can be published max 2 years in future
        }
        return true; // Let other validators handle non-DateTime values
    }
    
    public override string FormatErrorMessage(string name)
    {
        return $"{name} cannot be more than 2 years in the future.";
    }
}

// Usage in DTO
public class CreateBookDto
{
    // ...existing properties...
    
    [Required]
    [ISBNValidation(ErrorMessage = "Invalid ISBN format or checksum")]
    public string ISBN { get; set; } = string.Empty;
    
    [FutureDate(ErrorMessage = "Publication date cannot be more than 2 years in the future")]
    public DateTime PublishedDate { get; set; }
}
```

**Handling Validation in Controllers:**
```csharp
[HttpPost]
public ActionResult<Book> CreateBook([FromBody] CreateBookDto bookDto)
{
    // Check model validation
    if (!ModelState.IsValid)
    {
        // Return detailed validation errors
        var errors = ModelState
            .Where(x => x.Value?.Errors.Count > 0)
            .ToDictionary(
                kvp => kvp.Key,
                kvp => kvp.Value?.Errors.Select(e => e.ErrorMessage).ToArray()
            );
            
        return BadRequest(new { 
            Message = "Validation failed", 
            Errors = errors 
        });
    }
    
    // Additional business logic validation
    if (_books.Any(b => b.ISBN == bookDto.ISBN))
    {
        ModelState.AddModelError("ISBN", "A book with this ISBN already exists");
        return BadRequest(ModelState);
    }
    
    // Create and save the book
    var book = new Book
    {
        Id = GenerateNewId(),
        Title = bookDto.Title,
        Author = bookDto.Author,
        ISBN = bookDto.ISBN,
        Price = bookDto.Price,
        PublishedDate = bookDto.PublishedDate,
        Description = bookDto.Description ?? string.Empty,
        StockQuantity = bookDto.StockQuantity
    };
    
    _books.Add(book);
    
    return CreatedAtAction(nameof(GetBook), new { id = book.Id }, book);
}
```

<div style="page-break-after: always;"></div>

---

### **Part 2: Data Access and Entity Framework**

Moving from in-memory data storage to a proper database represents a crucial step in building production-ready applications. Entity Framework Core (EF Core) is Microsoft's modern object-relational mapping (ORM) framework that bridges the gap between object-oriented programming and relational databases. It enables developers to work with databases using .NET objects, eliminating the need for most of the data-access code that typically needs to be written.

Understanding EF Core is essential for modern .NET development because it provides a powerful, flexible way to interact with databases while maintaining type safety and leveraging LINQ for queries. EF Core supports multiple database providers, making it possible to switch between different database systems with minimal code changes.

Throughout Part 2, we'll explore how to design effective data models, establish relationships between entities, configure EF Core for your specific needs, and implement efficient data access patterns. We'll also cover advanced topics like query optimization, transaction management, and handling complex scenarios that arise in real-world applications.

#### Module 2.1: Data Models and DTOs
 
Proper data modeling is the foundation of any successful application. The way you design your entities and their relationships directly impacts performance, maintainability, and the overall architecture of your system. Entity Framework Core provides powerful tools for defining these models and relationships, but understanding the underlying principles is crucial for making informed decisions.

Modern data modeling in EF Core goes beyond simple property mapping. It involves understanding how your domain concepts translate to database structures, how to handle different types of relationships, and how to optimize for both development productivity and runtime performance.

##### **Section 2.1.1:** Designing your data models

Entity design in EF Core requires balancing several concerns: reflecting your domain accurately, optimizing for database performance, and maintaining clean, understandable code. The entities you create serve as both the foundation for your database schema and the objects your application logic works with.

When designing entities, it's important to consider not just the current requirements but also how your data model might evolve over time. EF Core's migration system makes schema changes manageable, but thoughtful initial design can prevent many future complications.

**Basic Entity Design Principles:**
```csharp
// Entities/Book.cs
using System.ComponentModel.DataAnnotations;
using System.ComponentModel.DataAnnotations.Schema;

namespace BookStoreApi.Entities
{
    [Table("Books")]
    public class Book
    {
        [Key]
        public int Id { get; set; }
        
        [Required]
        [MaxLength(200)]
        public string Title { get; set; } = string.Empty;
        
        [Required]
        [MaxLength(100)]
        public string Author { get; set; } = string.Empty;
        
        [Required]
        [MaxLength(20)]
        [Column("ISBN")]
        public string ISBN { get; set; } = string.Empty;
        
        [Column(TypeName = "decimal(10,2)")]
        public decimal Price { get; set; }
        
        [Column("PublicationDate")]
        public DateTime PublishedDate { get; set; }
        
        [MaxLength(1000)]
        public string? Description { get; set; }
        
        public int StockQuantity { get; set; }
        
        // Audit fields
        public DateTime CreatedAt { get; set; }
        public DateTime? UpdatedAt { get; set; }
        public string CreatedBy { get; set; } = string.Empty;
        public string? UpdatedBy { get; set; }
        
        // Navigation properties for relationships
        public int CategoryId { get; set; }
        public Category Category { get; set; } = null!;
        
        public int PublisherId { get; set; }
        public Publisher Publisher { get; set; } = null!;
        
        public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
        public ICollection<Review> Reviews { get; set; } = new List<Review>();
        public ICollection<OrderItem> OrderItems { get; set; } = new List<OrderItem>();
    }
}
```

**Supporting Entities:**
```csharp
// Entities/Category.cs
[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    [MaxLength(200)]
    public string? Description { get; set; }
    
    public bool IsActive { get; set; } = true;
    
    // Navigation properties
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

// Entities/Publisher.cs
[Table("Publishers")]
public class Publisher
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(100)]
    public string Name { get; set; } = string.Empty;
    
    [MaxLength(200)]
    public string? Address { get; set; }
    
    [MaxLength(100)]
    public string? Email { get; set; }
    
    [MaxLength(20)]
    public string? Phone { get; set; }
    
    [MaxLength(200)]
    public string? Website { get; set; }
    
    public DateTime CreatedAt { get; set; }
    
    // Navigation properties
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

// Entities/Author.cs
[Table("Authors")]
public class Author
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string FirstName { get; set; } = string.Empty;
    
    [Required]
    [MaxLength(50)]
    public string LastName { get; set; } = string.Empty;
    
    [MaxLength(1000)]
    public string? Biography { get; set; }
    
    }
    
    public DateTime? BirthDate { get; set; }
    public DateTime? DeathDate { get; set; }
    
    [MaxLength(50)]
    public string? Nationality { get; set; }
    
    [MaxLength(100)]
    public string? Email { get; set; }
    
    [MaxLength(200)]
    public string? Website { get; set; }
    
    // Computed property
    [NotMapped]
    public string FullName => $"{FirstName} {LastName}";
    
    [NotMapped]
    public bool IsLiving => !DeathDate.HasValue;
    
    // Navigation properties
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
}
```

##### **Section 2.1.2:** Entity relationships (One-to-Many, Many-to-Many)

Understanding and properly implementing entity relationships is crucial for building robust data models. EF Core supports all standard relationship types, and the way you configure these relationships affects both the generated database schema and how you can query and manipulate your data.

Relationships in EF Core are discovered by convention in many cases, but explicit configuration often provides better control and clearer intent. The choice between different relationship patterns also affects performance and the complexity of your queries.

**One-to-Many Relationships:**

One-to-many relationships are the most common in relational databases. They represent scenarios where one entity can be related to multiple instances of another entity, but each instance of the second entity relates to only one instance of the first.

```csharp
// One-to-Many: Category -> Books
// One category can have many books, but each book belongs to one category

[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    // Navigation property - one category has many books
    public ICollection<Book> Books { get; set; } = new List<Book>();
}

[Table("Books")]
public class Book
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(200)]
    public string Title { get; set; } = string.Empty;
    
    // Foreign key property
    public int CategoryId { get; set; }
    
    // Navigation property - many books belong to one category
    public Category Category { get; set; } = null!;
}

// Fluent API configuration in DbContext
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<Book>()
        .HasOne(b => b.Category)
        .WithMany(c => c.Books)
        .HasForeignKey(b => b.CategoryId)
        .OnDelete(DeleteBehavior.Restrict); // Prevent cascade delete
}
```

**Many-to-Many Relationships:**

Many-to-many relationships occur when multiple instances of one entity can relate to multiple instances of another entity. In EF Core 5+, this can be configured automatically, but explicit join entities often provide better control.

```csharp
// Many-to-Many: Books <-> Authors
// A book can have multiple authors, and an author can write multiple books

// Explicit join entity approach (recommended for complex scenarios)
[Table("BookAuthors")]
public class BookAuthor
{
    public int BookId { get; set; }
    public Book Book { get; set; } = null!;
    
    public int AuthorId { get; set; }
    public Author Author { get; set; } = null!;
    
    // Additional properties for the relationship
    public string Role { get; set; } = "Author"; // Author, Co-Author, Editor, etc.
    public int Order { get; set; } = 1; // Order of authors for display
    public DateTime ContributedAt { get; set; }
}

// Updated Book entity
public class Book
{
    // ...existing properties...
    
    // Navigation to join entity
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
    
    // Computed property for easy access to authors
    [NotMapped]
    public IEnumerable<Author> Authors => BookAuthors.Select(ba => ba.Author);
}

// Updated Author entity
public class Author
{
    // ...existing properties...
    
    // Navigation to join entity
    public ICollection<BookAuthor> BookAuthors { get; set; } = new List<BookAuthor>();
    
    // Computed property for easy access to books
    [NotMapped]
    public IEnumerable<Book> Books => BookAuthors.Select(ba => ba.Book);
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<BookAuthor>()
        .HasKey(ba => new { ba.BookId, ba.AuthorId });
    
    modelBuilder.Entity<BookAuthor>()
        .HasOne(ba => ba.Book)
        .WithMany(b => b.BookAuthors)
        .HasForeignKey(ba => ba.BookId);
    
    modelBuilder.Entity<BookAuthor>()
        .HasOne(ba => ba.Author)
        .WithMany(a => a.BookAuthors)
        .HasForeignKey(ba => ba.AuthorId);
}
```

**One-to-One Relationships:**

One-to-one relationships are less common but useful for scenarios like splitting large entities or representing optional detailed information.

```csharp
// One-to-One: Book -> BookDetails
// Each book has one set of detailed information

[Table("Books")]
public class Book
{
    [Key]
    public int Id { get; set; }
    
    // ...basic properties...
    
    // Navigation property for one-to-one relationship
    public BookDetails? Details { get; set; }
}

[Table("BookDetails")]
public class BookDetails
{
    [Key]
    public int BookId { get; set; } // Same as the Book's primary key
    
    public int PageCount { get; set; }
    public string? Language { get; set; }
    public string? Format { get; set; } // Hardcover, Paperback, etc.
    public decimal Weight { get; set; }
    public string? Dimensions { get; set; }
    
    [MaxLength(2000)]
    public string? DetailedDescription { get; set; }
    
    [MaxLength(500)]
    public string? TableOfContents { get; set; }
    
    // Navigation property back to Book
    public Book Book { get; set; } = null!;
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<BookDetails>()
        .HasOne(bd => bd.Book)
        .WithOne(b => b.Details)
        .HasForeignKey<BookDetails>(bd => bd.BookId);
}
```

**Self-Referencing Relationships:**

Sometimes entities need to relate to other instances of the same type, such as categories with subcategories or organizational hierarchies.

```csharp
[Table("Categories")]
public class Category
{
    [Key]
    public int Id { get; set; }
    
    [Required]
    [MaxLength(50)]
    public string Name { get; set; } = string.Empty;
    
    // Self-referencing relationship
    public int? ParentCategoryId { get; set; }
    public Category? ParentCategory { get; set; }
    
    // Navigation to child categories
    public ICollection<Category> SubCategories { get; set; } = new List<Category>();
    
    // Navigation to books in this category
    public ICollection<Book> Books { get; set; } = new List<Book>();
    
    // Computed properties
    [NotMapped]
    public bool IsRootCategory => ParentCategoryId == null;
    
    [NotMapped]
    public bool HasSubCategories => SubCategories.Any();
}

// Fluent API configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity<Category>()
        .HasOne(c => c.ParentCategory)
        .WithMany(c => c.SubCategories)
        .HasForeignKey(c => c.ParentCategoryId)
        .OnDelete(DeleteBehavior.Restrict);
}
```

##### **Section 2.1.3:** Data Transfer Objects (DTOs) and why use them

Data Transfer Objects (DTOs) serve as a crucial layer between your internal data models and external interfaces. They provide a way to control exactly what data is exposed by your API, enable versioning strategies, and protect against over-posting attacks. DTOs also allow you to optimize data transfer by including only the necessary fields for specific operations.

The separation between entities and DTOs becomes particularly important as applications grow in complexity. Entities are designed for persistence and domain logic, while DTOs are optimized for data transfer and API contracts. This separation provides flexibility in evolving both your internal models and external interfaces independently.

**Why DTOs Matter:**
1. **Security**: Prevent over-posting and exposure of sensitive data
2. **Performance**: Transfer only necessary data
3. **Versioning**: Maintain API contracts while evolving internal models
4. **Validation**: Apply operation-specific validation rules
5. **Documentation**: Clear API contracts for consumers

**Basic DTO Patterns:**
```csharp
// DTOs/BookDtos.cs
namespace BookStoreApi.DTOs
{
    // DTO for reading book data
    public class BookDto
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public string ISBN { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public DateTime PublishedDate { get; set; }
        public string? Description { get; set; }
        public int StockQuantity { get; set; }
        public bool IsInStock => StockQuantity > 0;
        
        // Related data
        public CategoryDto Category { get; set; } = null!;
        public PublisherDto Publisher { get; set; } = null!;
        public List<AuthorDto> Authors { get; set; } = new();
    }
    
    // DTO for creating books
    public class CreateBookDto
    {
        [Required(ErrorMessage = "Title is required")]
        [StringLength(200, MinimumLength = 1)]
        public string Title { get; set; } = string.Empty;
        
        [Required(ErrorMessage = "At least one author is required")]
        public List<int> AuthorIds { get; set; } = new();
        
        [Required(ErrorMessage = "ISBN is required")]
        [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$",
            ErrorMessage = "Invalid ISBN format")]
        public string ISBN { get; set; } = string.Empty;
        
        [Range(0.01, 9999.99)]
        public decimal Price { get; set; }
        
        [Required]
        public DateTime PublishedDate { get; set; }
        
        [StringLength(1000)]
        public string? Description { get; set; }
        
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        [Required]
        public int CategoryId { get; set; }
        
        [Required]
        public int PublisherId { get; set; }
    }
    
    // DTO for updating books
    public class UpdateBookDto
    {
        [Required]
        [StringLength(200, MinimumLength = 1)]
        public string Title { get; set; } = string.Empty;
        
        [Required]
        public List<int> AuthorIds { get; set; } = new();
        
        [Required]
        [RegularExpression(@"^(?=(?:\D*\d){10}(?:(?:\D*\d){3})?$)[\d-]+$",
            ErrorMessage = "Invalid ISBN format")]
        public string ISBN { get; set; } = string.Empty;
        
        [Range(0.01, 9999.99)]
        public decimal Price { get; set; }
        
        public DateTime PublishedDate { get; set; }
        
        [StringLength(1000)]
        public string? Description { get; set; }
        
        [Range(0, int.MaxValue)]
        public int StockQuantity { get; set; }
        
        public int CategoryId { get; set; }
        public int PublisherId { get; set; }
    }
    
    // Minimal DTO for lists and search results
    public class BookSummaryDto
    {
        public int Id { get; set; }
        public string Title { get; set; } = string.Empty;
        public string Author { get; set; } = string.Empty;
        public decimal Price { get; set; }
        public bool IsInStock { get; set; }
        public string Category { get; set; } = string.Empty;
    }
    
    // Detailed DTO for single book views
    public class BookDetailDto : BookDto
    {
        public List<ReviewDto> RecentReviews { get; set; } = new();
        public decimal AverageRating { get; set; }
        public int ReviewCount { get; set; }
        public DateTime CreatedAt { get; set; }
        public DateTime? UpdatedAt { get; set; }
        
        // Additional details that might be expensive to load
        public BookDetailsDto? Details { get; set; }
    }
}

// Supporting DTOs
public class CategoryDto
{
    public int Id { get; set; }
    public string Name { get; set; } = string.Empty;
    public string? Description { get; set; }
}

public class PublisherDto
{
    public int Id { get; set; }
    public string Name { get; set; } = string.Empty;
    public string? Website { get; set; }
}

public class AuthorDto
{
    public int Id { get; set; }
    public string FirstName { get; set; } = string.Empty;
    public string LastName { get; set; } = string.Empty;
    public string FullName { get; set; } = string.Empty;
    public string? Nationality { get; set; }
}

public class ReviewDto
{
    public int Id { get; set; }
    public int Rating { get; set; }
    public string? Comment { get; set; }
    public string ReviewerName { get; set; } = string.Empty;
    public DateTime CreatedAt { get; set; }
}

public class BookDetailsDto
{
    public int PageCount { get; set; }
    public string? Language { get; set; }
    public string? Format { get; set; }
    public decimal Weight { get; set; }
    public string? Dimensions { get; set; }
}
```

**DTO Conversion Patterns:**
```csharp
// Extensions/BookExtensions.cs
public static class BookExtensions
{
    public static BookDto ToDto(this Book book)
    {
        return new BookDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            ISBN = book.ISBN,
            Price = book.Price,
            PublishedDate = book.PublishedDate,
            Description = book.Description,
            StockQuantity = book.StockQuantity,
            Category = book.Category.ToDto(),
            Publisher = book.Publisher.ToDto(),
            Authors = book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.ToDto())
                .ToList()
        };
    }
    
    public static BookSummaryDto ToSummaryDto(this Book book)
    {
        return new BookSummaryDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            Price = book.Price,
            IsInStock = book.StockQuantity > 0,
            Category = book.Category.Name
        };
    }
    
    public static BookDetailDto ToDetailDto(this Book book)
    {
        var dto = new BookDetailDto
        {
            Id = book.Id,
            Title = book.Title,
            Author = string.Join(", ", book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.FullName)),
            ISBN = book.ISBN,
            Price = book.Price,
            PublishedDate = book.PublishedDate,
            Description = book.Description,
            StockQuantity = book.StockQuantity,
            Category = book.Category.ToDto(),
            Publisher = book.Publisher.ToDto(),
            Authors = book.BookAuthors
                .OrderBy(ba => ba.Order)
                .Select(ba => ba.Author.ToDto())
                .ToList(),
            CreatedAt = book.CreatedAt,
            UpdatedAt = book.UpdatedAt,
            RecentReviews = book.Reviews
                .OrderByDescending(r => r.CreatedAt)
                .Take(5)
                .Select(r => r.ToDto())
                .ToList(),
            AverageRating = book.Reviews.Any() 
                ? book.Reviews.Average(r => r.Rating) 
                : 0,
            ReviewCount = book.Reviews.Count,
            Details = book.Details?.ToDto()
        };
        
        return dto;
    }
    
    public static Book ToEntity(this CreateBookDto dto)
    {
        return new Book
        {
            Title = dto.Title,
            ISBN = dto.ISBN,
            Price = dto.Price,
            PublishedDate = dto.PublishedDate,
            Description = dto.Description,
            StockQuantity = dto.StockQuantity,
            CategoryId = dto.CategoryId,
            PublisherId = dto.PublisherId,
            CreatedAt = DateTime.UtcNow,
            CreatedBy = "System" // This would come from the current user context
        };
    }
    
    public static void UpdateEntity(this UpdateBookDto dto, Book book)
    {
        book.Title = dto.Title;
        book.ISBN = dto.ISBN;
        book.Price = dto.Price;
        book.PublishedDate = dto.PublishedDate;
        book.Description = dto.Description;
        book.StockQuantity = dto.StockQuantity;
        book.CategoryId = dto.CategoryId;
        book.PublisherId = dto.PublisherId;
        book.UpdatedAt = DateTime.UtcNow;
        book.UpdatedBy = "System" // This would come from the current user context
    }
}
```

##### **Section 2.1.4:** AutoMapper for object mapping

While manual DTO conversion works well for simple scenarios,