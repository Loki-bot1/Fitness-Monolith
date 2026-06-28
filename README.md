🏋️ Fitness Monolith

A production-ready Fitness Management REST API built using Spring Boot following a monolithic architecture. The application provides secure authentication using JWT, role-based authorization, and RESTful APIs for managing fitness-related data.

The project follows clean architecture principles with separate Controller, Service, Repository, DTO, and Security layers to ensure maintainability and scalability.

🚀 Features
🔐 JWT Authentication & Authorization
👥 Role-Based Access Control (Admin/User)
🛡️ Spring Security Integration
📦 RESTful API Design
📝 CRUD Operations
📄 DTO-Based Request & Response Models
✅ Bean Validation
⚠️ Global Exception Handling
💾 Database Integration with JPA & Hibernate
🐳 Docker Support
🔧 Environment Variable Configuration
📂 Layered Architecture
⚡ Maven Build System
🛠️ Tech Stack
Backend
Java 21
Spring Boot
Spring Security
JWT
Spring Data JPA
Hibernate
Database
MySQL
DevOps
Docker
Build Tool
Maven
API Testing
Postman
Version Control
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
⚙️ Getting Started
Clone the Repository
git clone https://github.com/Loki-bot1/Fitness-Monolith.git
cd Fitness-Monolith
Configure Environment Variables
DB_URL=your_database_url
DB_USER=your_database_username
DB_PWD=your_database_password
JWT_SECRET=your_jwt_secret
Run the Application

Using Maven:

mvn spring-boot:run

Or with Docker:

docker build -t fitness-monolith .
docker run -p 8081:8081 fitness-monolith

Application URL:

http://localhost:8081
🔐 Security

The application uses Spring Security with JWT authentication.

Features include:

User Registration
User Login
JWT Token Generation
Protected Endpoints
Role-Based Authorization
Password Encryption
📡 API Overview

Example endpoints:

Method	Endpoint	Description
POST	/auth/register	Register a new user
POST	/auth/login	Authenticate user
GET	/users	Get all users
GET	/users/{id}	Get user by ID
PUT	/users/{id}	Update user
DELETE	/users/{id}	Delete user

Replace these endpoints with the actual ones from your project.

🏗️ Architecture

The project follows a layered architecture:

Client
   │
REST Controller
   │
Service Layer
   │
Repository Layer
   │
Database
📌 Future Enhancements
Swagger / OpenAPI Documentation
Unit & Integration Testing
CI/CD Pipeline using GitHub Actions
Flyway Database Migration
Cloud Deployment
Performance Monitoring
👨‍💻 Author

Lokesh Jahure

GitHub: https://github.com/Loki-bot1
⭐ If you like this project

If you found this project helpful or learned something from it, please consider giving it a ⭐ on GitHub.
