### Hotel Management System

This project was developed as a mandatory assignment for the **Programming 3** course within the Information Technology Analyst program at **Universidad ORT Uruguay**. 

The system provides a comprehensive full-stack solution for managing cabin reservations, featuring a decoupled architecture that separates business logic from user interaction.

## Project Overview
The project is built as a dual-system architecture:
1.  **Web API Backend:** Acting as the robust business logic engine and handling data persistence.
2.  **MVC Web Client:** A Model-View-Controller application that serves as the primary interface for user interaction.

## Technical Implementation & Core Concepts
The development focused on modern .NET techniques and software architecture standards:

* **Clean Architecture:** Implementation of clear layer division (Domain, Application, Infrastructure), separating business logic from UI and data access to ensure maintainability and scalability.
* **Advanced OOP:** Leveraged Object-Oriented Programming principles such as inheritance and polymorphism to create modular and reusable code.
* **Entity Framework (ORM):** Used as the primary ORM to simplify database interaction, leveraging object-to-table mapping and minimizing data access complexity.
* **Dependency Injection:** Applied to enhance flexibility and promote loose coupling between classes.
* **Core Patterns:** Implementation of the **Repository Pattern** through Interfaces and strict **Exception Handling** to ensure a robust and stable user experience.
* **UML Modeling:** Initial planning phase included class diagrams to effectively map out the application flow and architecture.

## Tech Stack
* **Language:** C#
* **Frameworks:** .NET Core / .NET 7
* **Architecture:** Clean Architecture / MVC / Web API
* **Database:** SQL Server
* **ORM:** Entity Framework Core

## Related Repositories
This project is part of a dual-system solution. You can access the corresponding web client part here:
* **[MVC Web Application Client](https://github.com/Ulx7/Hotel-Management-System-MVC.git)**
