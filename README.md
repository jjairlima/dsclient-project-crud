# DSClient - Client Management REST API

Backend application developed with Java and Spring Boot for client management.

This project demonstrates the implementation of a RESTful CRUD API using a layered architecture, data persistence with JPA, validation, and relational databases.

## Features

- Create clients
- Retrieve client details
- List clients
- Update client information
- Delete clients
- Validate request data
- Persist data using JPA
- RESTful API architecture

## Technologies

- Java 11
- Spring Boot 2.4.4
- Spring Web
- Spring Data JPA
- Bean Validation
- PostgreSQL
- H2 Database
- Maven
- Spring Boot Test

## Architecture

The application follows a layered backend architecture with separation of responsibilities between:

- Controllers
- Services
- Repositories
- Entities
- DTOs

This structure helps improve maintainability, testability, and separation of business logic from persistence and API layers.

## Database

The project supports relational database persistence using:

- H2 for development and testing scenarios
- PostgreSQL for relational database environments

## Validation

Request and domain data validation is implemented using Spring Boot Validation.

## Build

The project uses Maven for dependency management and application build.

To run the application locally:

```bash
./mvnw spring-boot:run
