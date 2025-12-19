Tender & Bidding Management System
A robust backend system built with .NET 8 designed to manage the full lifecycle of corporate tenders and competitive bidding. This project implements Domain-Driven Design (DDD) and Clean Architecture principles to ensure high maintainability and scalability.

🏗 Architecture & Design Patterns
To meet the high standards of enterprise software, the system is structured into distinct layers following DDD principles:


Domain Layer: Contains core business logic, Aggregate Roots, Entities, and Value Objects.


Application Layer: Implements use cases via the CQRS (Command Query Responsibility Segregation) pattern to optimize read/write performance.


Infrastructure Layer: Handles data persistence with EF Core and SQL Server, utilizing the Repository pattern.


API Layer: Exposes secure RESTful endpoints documented via Swagger.


🌟 Key Features

User Management & RBAC: Secure registration and authentication with JWT, featuring Role-Based Access Control for Procurement Officers, Bidders, and Evaluators.


Tender Lifecycle Management: Full CRUD operations for tenders, including document upload support and categorization by industry/type.


Secure Bid Submission: Online submission with automatic requirement validation and secure attachment handling.


Automated Evaluation: Criteria-based scoring system for bid comparisons and transparent awarding mechanisms.


Audit Trails: Compliance-focused logging of tender amendments and evaluation actions.


🛠 Tech Stack

Language/Framework: C#, .NET 8 (ASP.NET Core Web API).


Database: SQL Server with Entity Framework Core.


Security: JWT-based Authentication & Authorization.


Documentation: Swagger/OpenAPI.
