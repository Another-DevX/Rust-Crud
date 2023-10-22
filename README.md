# Rust CRUD Application with PostgreSQL and Docker

## Overview

This is a simple CRUD (Create, Read, Update, Delete) application written in Rust. The application uses PostgreSQL as its database and is designed to be run in a Docker container for easy deployment.

## Features

- CRUD operations for managing users
- Containerized application using Docker
- Uses Rust's asynchronous programming features

## Prerequisites

- Docker
- Rust

## Getting Started

1. Clone the repository
```
git clone https://github.com/your_username/your_repository.git
```

2. Build and run the Docker container
```
docker-compose up --build
```

## API Endpoints

- POST /users: Create a new user
- GET /users: Retrieve all users
- GET /users/{id}: Retrieve a user by ID
- PUT /users/{id}: Update a user by ID
- DELETE /users/{id}: Delete a user by ID

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
