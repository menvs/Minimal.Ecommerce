# 🛒 Minimal E-Commerce Microservices

This project is a modular, scalable e-commerce backend built using **.NET 8**, **Clean Architecture**, **CQRS**, and **DDD principles**, split into 3 independent microservices:

- 🧱 **ProductService** – manages products and categories  
- 📦 **OrderService** – manages customer orders and cart (optional)  
- 🔐 **AuthService** – handles authentication, authorization, and user management

Each service is independently deployable, testable, and follows Clean Architecture.

---

## 📚 Roadmap Features Coverage

### ✅ Phase 1: C# & .NET Fundamentals
- C# OOP: classes, interfaces, abstraction, encapsulation  
- Exception handling with middleware  
- Delegates, events, collections, generics  
- .NET CLI for solution/project management  

---

### ✅ Phase 2: Data Access with EF Core
- `DbContext`, `DbSet`, EF Core Migrations  
- LINQ Queries, relationships (1-M, M-M)  
- Repository + Unit of Work patterns  
- Database seeding  

---

### ✅ Phase 3: ASP.NET Core Web API
- RESTful APIs using ASP.NET Core  
- Routing, Middleware, DI  
- DTOs, Model Binding, Validation  
- Swagger / OpenAPI integration  

---

### ✅ Secure Web Development
- Input validation (FluentValidation)  
- SQL Injection protection via EF Core  
- JWT-based authentication (AuthService)  
- Secure headers: CSP, HSTS  
- Logging with Serilog  
- Role-based authorization & claims  

---

### ✅ Phase 4: Advanced C# Topics
- Asynchronous programming with `async/await`  
- `CancellationToken` support  
- Concurrency handling (`lock`, `SemaphoreSlim`)  
- Memory management with `IDisposable`, `Span<T>`  
- Benchmarking with BenchmarkDotNet  
- Use of `StringBuilder`, pooling, etc.  

---

### ✅ Phase 5: Authentication & Authorization
- JWT authentication (AuthService)  
- Login, register, token refresh  
- Role-based & policy-based authorization  
- Token validation in other services via middleware  

---

### ✅ Phase 6: Architecture & Clean Code
- **Clean Architecture** (Domain, Application, Infrastructure, API)  
- **CQRS** with MediatR for commands/queries  
- **DDD** principles (Aggregates, Entities, ValueObjects)  
- SOLID principles, AutoMapper, layered structure  

---

### ✅ Phase 7: DevOps & Deployment
- Dockerized microservices  
- CI/CD with GitHub Actions  
- Deployable to Azure / Render  
- Logging with Serilog sinks (Console, File, etc.)  
- Environment-based config using `appsettings.{env}.json`  

---

### ✅ Phase 8: Testing
- xUnit + Moq unit tests for CQRS Handlers  
- Integration tests for endpoints using WebApplicationFactory  
- Test coverage for business logic and controllers  

---

### ✅ Phase 9: API Performance Optimization
- Caching with Redis (`IDistributedCache`)  
- Response compression (Gzip)  
- Pagination + filtering + data shaping  
- EF Core performance tuning (AsNoTracking, projections)  
- Rate limiting (AspNetCoreRateLimit)  
- Profiling with dotTrace / Application Insights  

---


