# 🌐 Bar-Port Projects

Welcome to the official repository of **Bar-Port**.  
This repository hosts our projects built with **ASP.NET Core**, **Blazor**, and modern .NET technologies.  
We focus on delivering scalable, maintainable, and high-quality software solutions.

---

## 🚀 Overview

At **Bar-Port**, our mission is to build enterprise-grade applications with:
- Robust **backends** using ASP.NET Core.
- Interactive **UI experiences** powered by Blazor.
- Clean and maintainable architecture aligned with **Clean Architecture** and **Domain-Driven Design (DDD)**.
- Cross-platform support with **.NET 8**.

---

## 🛠 Tech Stack

- **Backend:** ASP.NET Core, Entity Framework Core  
- **Frontend:** Blazor Server / Blazor WebAssembly  
- **Database:** SQL Server / PostgreSQL  
- **Authentication & Authorization:** ASP.NET Core Identity + JWT  
- **Architecture:** Clean Architecture, Modular Monolith  
- **DevOps & CI/CD:** GitHub Actions / Azure DevOps Pipelines  
- **Others:** Swagger, MediatR, FluentValidation, Serilog  

---

## 📂 Project Structure

```bash
src/
 ├── Application/         # Business logic, CQRS handlers, validators
 ├── Domain/              # Entities, Aggregates, Value Objects
 ├── Infrastructure/      # EF Core, external services, repositories
 ├── Web/                 # ASP.NET Core + Blazor UI
 └── Tests/               # Unit and Integration Tests
