# Serozet Architecture Base

![Branch](https://img.shields.io/badge/branch-main-green)
![Framework](https://img.shields.io/badge/.NET-9.0-purple)
![License](https://img.shields.io/badge/license-MIT-blue)

## 🎯 Vision
Serozet Base is the foundational boilerplate for all Serozet ecosystem services. It implements **Clean Architecture** principles to ensure high maintainability, scalability, and performance.

## 🛠 Tech Stack
- **Language:** C# 13
- **Framework:** .NET 9.0 (ASP.NET Core)
- **Database:** PostgreSQL (via Entity Framework Core)
- **Observability:** Serilog + Seq
- **Validation:** FluentValidation
- **Docs:** Swagger/OpenAPI

## 🏗 Project Structure
- `Serozet.Api`: Entry point & Controllers.
- `Serozet.Domain`: Enterprise entities & Value objects.
- `Serozet.Application`: Business logic & Use cases.
- `Serozet.Persistence`: Database context & Migrations.

## 🚀 Getting Started
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/serozet/serozet-base.git](https://github.com/serozet/serozet-base.git)
