# food-management-system

FoodOrderingSystem is a backend application developed using Java and Spring Boot that manages an online food ordering process. It provides REST APIs for user registration, email OTP verification, login, restaurant management, food items, food categories, shopping carts, orders, payments, delivery addresses, and reviews.

The application uses PostgreSQL to store and manage data and Spring Data JPA with Hibernate for database operations. It also includes input validation and exception handling to improve data consistency and reliability.

## Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate ORM
- PostgreSQL
- REST APIs
- Maven
- Jakarta Validation
- JavaMailSender for email OTP verification
- Swagger / OpenAPI for API documentation

## Key Features

- User registration, login, and email verification using OTP
- Restaurant and food item management
- Food category management
- Shopping cart management, including adding items, updating quantities, and removing items
- Order and order-item management
- Delivery address management
- Payment management
- Restaurant and user reviews
- Exception handling and request validation

## Database

PostgreSQL is used as the relational database to store users, restaurants, food items, categories, carts, cart items, orders, payments, addresses, and reviews.

## API Documentation

Swagger UI is available at:

`http://localhost:4020/swagger-ui/index.html`

## How to Run

1. Install Java 17, Maven, and PostgreSQL.
2. Create the `foodorderingsystem` database.
3. Configure the database URL, username, and password in `application.properties`.
4. Configure SMTP settings if email OTP verification is required.
5. Run the Spring Boot application.
6. Access the API documentation using the Swagger UI URL above.

