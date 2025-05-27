# DSList Backend API

This project was developed as part of my studies in Java and Spring Boot. It is a backend API that manages a list of games with CRUD operations and an additional feature to reorder items within a list.

## 🚀 Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL (Staging/Production)
- H2 Database (Development/Test)
- Maven
- Swagger (API Documentation)

## ⚙️ Project Profiles
- **Development/Test:** uses an H2 in-memory database.
- **Staging/Production:** uses PostgreSQL.

## 🏗️ How to Run
1. Clone this repository.
2. Configure your application properties or YAML file according to the desired profile (`dev`, `test`, or `prod`).
3. Run the application with:
./mvnw spring-boot:run

## 🗺️ API Documentation
After run, you can access the API documentation and test the endpoints through Swagger:
http://localhost:8080/swagger-ui.html
