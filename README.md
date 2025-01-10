# Spring Boot Demo Project

This is a simple Spring Boot project demonstrating basic REST API functionality with OpenAPI documentation.

## Features

- Spring Boot 3.2.2 (Latest LTS)
- Java 21
- Gradle build system
- OpenAPI 3.0 documentation
- Integration tests

## Getting Started

### Prerequisites

- Java 21 JDK
- Gradle (Wrapper included)

### Running the Application

```bash
./gradlew bootRun
```

### Running Tests

```bash
./gradlew test
```

### API Documentation

Once the application is running, you can access the OpenAPI documentation at:
- Swagger UI: http://localhost:8080/swagger-ui.html
- OpenAPI JSON: http://localhost:8080/v3/api-docs

## Endpoints

- GET /hello - Returns a greeting message

## Built With

- [Spring Boot](https://spring.io/projects/spring-boot)
- [SpringDoc OpenAPI](https://springdoc.org/)
- [Gradle](https://gradle.org/)