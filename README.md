# Data Validation Spring Boot App

A Spring Boot REST API that demonstrates data validation using Bean Validation and JPA.

## Technologies Used
- Java 17
- Spring Boot 4.0.5
- MySQL
- Spring Data JPA
- Bean Validation (JSR 380)

## Features
- Validate book data using annotations (@NotNull, @Size, @Min)
- Custom validation using Spring Validator interface
- Global exception handling with @ControllerAdvice

## API Endpoint
- POST `/addBook` - Add a new book with validation

## How to Run
1. Create a MySQL database called `bookstore`
2. Set environment variables:
   - `DB_USERNAME` = your mysql username
   - `DB_PASSWORD` = your mysql password
3. Run the application
4. Test using Postman
