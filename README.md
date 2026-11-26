# Online Shopping Application (REST API)

## Project Description
An end-to-end e-commerce backend built with Java 17 and Spring Boot following clean Controller-Service-DAO layered architecture, supporting customer onboarding, session-based authentication, catalog browsing, cart management, and order placement.

## Tech Stack Used
- **Language:** Java 17
- **Frameworks:** Spring Boot, Spring Web, Spring Data JPA, Hibernate
- **Database:** MySQL
- **Build & Tools:** Maven, Jakarta Bean Validation, REST API, Postman

## Key Features & Modules
- **7 REST Controllers:** `User`, `Customer`, `Product`, `Cart`, `Order`, `Address`, and `Bank`.
- **Session-Based Authentication:** Login/logout session token validation separating customer and admin workflows.
- **Relational Domain Modeling:** 9 JPA/Hibernate entities mapped in MySQL.
- **Centralized Exception Handling:** `@RestControllerAdvice` (`GlobalExceptionHandler`) returning structured `MyError` responses.

## Setup & Installation
1. Clone: `git clone https://github.com/Lrssrrb/Online-shopping-application.git && cd Online-shopping-application`
2. Update MySQL credentials in `src/main/resources/application.properties`.
3. Run: `mvn clean install && mvn spring-boot:run`