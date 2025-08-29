# User Management Service

Spring Boot 3 application providing REST endpoints for managing users. It uses Spring Data JPA with a MySQL database.

## Endpoints
- `POST /users` - create user
- `GET /users` - list all users
- `GET /users/{id}` - get user by id
- `PUT /users/{id}` - update user
- `DELETE /users/{id}` - delete user

## Database configuration
Database connection is configured in `src/main/resources/application.properties`.
