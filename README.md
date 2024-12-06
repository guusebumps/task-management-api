# Task Management API

A simple RESTful API built with Go and Gin to manage tasks.

## Features
- Create, read, update, and delete tasks.
- Mark tasks as completed.
- Simple and lightweight.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/guusebumps/task-management-api.git
   cd task-management-api
   ```
2. Install dependencies:
   ```bash
   go mod tidy
   ```
3. Run the server:
   ```bash
   go run main.go
   ```

## Endpoints
| Method | Endpoint       | Description         |
|--------|----------------|---------------------|
| GET    | `/tasks`       | Get all tasks       |
| POST   | `/tasks`       | Create a new task   |
| PUT    | `/tasks/:id`   | Update a task       |
| DELETE | `/tasks/:id`   | Delete a task       |

## Dependencies
- [Gin](https://github.com/gin-gonic/gin)
