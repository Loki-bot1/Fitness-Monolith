🏋️ Fitness Monolith

A production-ready Fitness Management REST API built with Spring Boot following a monolithic architecture. The application provides secure authentication using JWT, role-based authorization with Spring Security, and RESTful APIs for managing fitness-related operations.

Designed with clean architecture principles, the project separates business logic into Controller, Service, Repository, DTO, and Security layers for scalability and maintainability.

🚀 Features
🔐 JWT Authentication & Authorization
👥 Role-Based Access Control (Admin/User)
🛡️ Spring Security Integration
📦 RESTful API Architecture
📝 CRUD Operations
📄 DTO-Based Request & Response Models
✅ Bean Validation
⚠️ Global Exception Handling
💾 PostgreSQL Database Integration
🔄 Spring Data JPA & Hibernate
📚 Swagger/OpenAPI Documentation
🐳 Docker Support
🔧 Environment Variable Configuration
📂 Layered Architecture
🛠️ Tech Stack
Backend
Java 22
Spring Boot
Spring Security
JWT (JSON Web Token)
Spring Data JPA
Hibernate
Database
PostgreSQL (Neon DB Compatible)
Documentation
Swagger / OpenAPI
DevOps
Docker
Tools
Maven
Postman
Git & GitHub
📂 Project Structure
src/
├── controller/
├── service/
├── repository/
├── entity/
├── dto/
├── security/
├── config/
├── exception/
├── util/
└── resources/
⚙️ Installation
Clone Repository
git clone https://github.com/Loki-bot1/Fitness-Monolith.git

cd Fitness-Monolith
Configure Environment Variables
DB_URL=your_database_url

DB_USER=your_username

DB_PWD=your_password

JWT_SECRET=your_secret_key
Run the Project

Using Maven

mvn spring-boot:run

Or using Docker

docker build -t fitness-monolith .

docker run -p 8081:8081 fitness-monolith
🔐 Authentication

Authentication is implemented using JWT (JSON Web Token).

The application supports:

User Registration
User Login
JWT Token Generation
Protected APIs
Role-Based Authorization
Password Encryption
📚 API Documentation

Swagger UI

http://localhost:8081/swagger-ui.html

OpenAPI JSON

http://localhost:8081/v3/api-docs
🏗️ Architecture
Client
   │
REST Controller
   │
Service Layer
   │
Repository Layer
   │
PostgreSQL Database
📌 Highlights
Production-ready backend architecture
Secure authentication using JWT
Clean layered design
DTO-based API responses
Global exception handling
Validation for incoming requests
Dockerized application
OpenAPI documentation
PostgreSQL support
Environment-based configuration
🚀 Future Improvements
Refresh Token Support
Email Verification
Password Reset
Unit & Integration Testing
GitHub Actions CI/CD
Flyway Database Migration
Cloud Deployment
Workout & Diet Tracking Modules
👨‍💻 Author

Lokesh Jahure

GitHub: https://github.com/Loki-bot1

⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub
