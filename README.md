# Product Service Microservice

## Overview
This project is a Spring Boot microservice developed for DevOps Lab 3 in the SE4010 module.  
It provides REST APIs to manage product data using an H2 in-memory database.  
Swagger UI is integrated for easy API testing and documentation.

---

## Technologies Used
- Java 17
- Spring Boot 4
- Spring Data JPA
- H2 In-Memory Database
- Swagger (Springdoc OpenAPI)
- Maven

---

## Features
- Create a new product
- View all products
- View a product by ID
- Delete a product by ID
- Interactive API documentation using Swagger
- Database access using H2 Console

---

## How to Run the Application

### Step 1: Clone the repository

```
git clone https://github.com/JanudiAdhikari/ctse-lab3-product-service
```

### Step 2: Open the project in VS Code

### Step 3: Run the application
Run the main class:
```
ProductServiceApplication.java
```

---

## Access the Application

### Swagger UI
```
http://localhost:8081/swagger-ui/index.html
```

Use Swagger to test all API endpoints.

---

### H2 Database Console
```
http://localhost:8081/h2-console
```

Login details:
```
JDBC URL: jdbc:h2:mem:productdb
Username: sa
Password:
```

---