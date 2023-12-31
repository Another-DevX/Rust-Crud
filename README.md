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
git clone https://github.com/Another-DevX/Rust-Crud
```

2. Build and run the Docker container
```
docker-compose up -d db

docker-compose build

docker compose up rustapp
```

## API Endpoints

To use API endpoints call localhost:8080/ROUTE in postman with te given nomenclature

- POST /users: Create a new user
- GET /users: Retrieve all users
- GET /users/{id}: Retrieve a user by ID
- PUT /users/{id}: Update a user by ID
- DELETE /users/{id}: Delete a user by ID
