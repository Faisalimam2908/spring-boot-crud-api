# Spring Boot CRUD REST API

This is a simple **Spring Boot RESTful API** application demonstrating basic **CRUD (Create, Read, Update, Delete)** operations using:

- Spring Boot
- Spring Web (REST API)
- Spring Data JPA
- H2 in-memory database

## 📌 Features

- RESTful endpoints for managing `Employee` entities
- Full CRUD support (`GET`, `POST`, `PUT`, `DELETE`)
- H2 in-memory database (no setup required)
- Project structured using best practices: controller → repository → entity
- Ready-to-run using Maven and Spring Boot

## 🧪 Endpoints

| Method | URL                     | Description           |
|--------|-------------------------|-----------------------|
| GET    | `/api/employees`        | Get all employees     |
| GET    | `/api/employees/{id}`   | Get employee by ID    |
| POST   | `/api/employees`        | Create new employee   |
| PUT    | `/api/employees/{id}`   | Update employee       |
| DELETE | `/api/employees/{id}`   | Delete employee       |

## ⚙️ How to Run

```bash
# Step 1: Clone the repo
git clone https://github.com/your-username/spring-boot-crud-api.git
cd spring-boot-crud-api

# Step 2: Run using Maven
./mvnw spring-boot:run
