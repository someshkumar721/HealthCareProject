This is a **Healthcare Management System** built using **Spring Boot** framework that provides RESTful APIs to manage healthcare operations including patients, doctors, appointments, diseases, and visit records. The application demonstrates best practices in layered architecture, exception handling, logging, and data persistence with **MySQL**.

| Technology | Purpose |
|------------|---------|
| **Spring Boot** | Application framework |
| **Spring MVC** | REST API controllers |
| **Spring Data JPA** | Database operations (DAO layer) |
| **MySQL** | Relational database |
| **Hibernate** | ORM framework |
| **Maven** | Build and dependency management |
| **SLF4J + Logback** | Logging framework |
| **Apache POI** | Excel file processing |
| **Bean Validation (Hibernate Validator)** | Request validation |

**Application Flow Diagram**

Client Request
      ↓
[Controller Layer] ←→ Validation (@Valid)
      ↓
[Service Layer] ←→ Business Logic
      ↓
[DAO Layer] ←→ Spring Data JPA
      ↓
[Database] ←→ MySQL
