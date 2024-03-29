Project Overview
This Spring Boot application is designed to manage user registration and login for task management.

Features
User Management

User registration with validation for unique usernames.
User login with password validation.
JWT-based authentication for secure user sessions.
Task Management

CRUD operations for tasks, including creation, retrieval, update, and deletion.
Tasks are represented by the Task entity, with attributes like title, description, and status.
Exception Handling

Global exception handling for common exceptions.
Specific handling for MethodArgumentNotValidException to manage validation errors.
Components
Controllers
UserController

Manages user registration and login operations.
TaskController

Handles CRUD operations for tasks.
CentralExceptionHandler

Global exception handler to manage common exceptions.
Entities
User

Represents a user with attributes such as username, email, password, and role.
Task

Represents a task with attributes like title, description, and status.
Services
UserService

Handles user-related business logic, including registration and login.
TaskService

Manages task-related business logic, including CRUD operations.
Repositories
UserRepository

Interacts with the database for user-related operations.
TaskRepository

Communicates with the database for task-related operations.
Configuration
JwtService
Manages the generation and validation of JWT tokens for user authentication.