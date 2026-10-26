# Food Management System (Backend)

A REST API backend for managing restaurants and food items, with customer registration and email OTP verification.

## Tech Stack
- Java
- Spring Boot
- Hibernate / JPA
- PostgreSQL
- Maven
- Tools: Postman, Swagger, Git

## Features
- CRUD operations for restaurants
- CRUD operations for food items
- Customer registration
- Email OTP verification
- Exception handling and request validation

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /customers/register | Register a new customer |
| POST | /customers/verify-otp | Verify OTP sent to email |
| POST | /restaurants | Add a restaurant |
| GET | /restaurants | Get all restaurants |
| PUT | /restaurants/{id} | Update a restaurant |
| DELETE | /restaurants/{id} | Delete a restaurant |
| POST | /food-items | Add a food item |
| GET | /food-items | Get all food items |

(Replace these with your actual endpoints.)

## How to Run
1. Clone the repository:
   `git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git`
2. Create a PostgreSQL database.
3. Open `src/main/resources/application.properties` and update:
   - `spring.datasource.url` with your database name
   - `spring.datasource.username` and `spring.datasource.password`
   - `spring.mail.username` and `spring.mail.password` (use a Gmail App Password)
4. Run the application. It starts on `http://localhost:4020`.

## Project Status
- Completed: Backend REST APIs, database integration, OTP verification
- Planned: Frontend

## Author
Pratiksha Sawant