# Employee Management System

A RESTful Employee Management System developed using Java, Spring Boot, Spring Data JPA, Hibernate, and MySQL.

## Project Overview

This project provides REST APIs to manage employee information. It supports creating, retrieving, updating, and deleting employee records using standard HTTP methods.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST APIs
- Postman
- Git and GitHub

## Features

- Create a new employee
- Retrieve all employees
- Retrieve an employee by ID
- Update employee details
- Delete an employee by ID
- Store employee information in MySQL

## Project Architecture

Client (Postman) → Controller → Service → Repository → JPA/Hibernate → MySQL

## REST API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| POST | `/employees` | Create employee |
| GET | `/employees` | Get all employees |
| GET | `/employees/{id}` | Get employee by ID |
| PUT | `/employees/{id}` | Update employee |
| DELETE | `/employees/{id}` | Delete employee |

## Sample Employee JSON

```json
{
  "name": "Tabish Shaikh",
  "email": "tabish@gmail.com",
  "department": "IT",
  "salary": 50000
}
```

## Database Configuration

1. Create a MySQL database named `employee_db`.
2. Configure your database URL, username, and password in `application.properties`.
3. Keep real credentials private. Use environment variables or a local configuration file rather than committing passwords to GitHub.

## How to Run the Project

1. Clone the repository.
2. Open the project in Eclipse or another Java IDE.
3. Configure your MySQL database.
4. Run `EmpMgmtApplication.java`.
5. The application starts on `http://localhost:8080`.

## API Testing

Use Postman to test all CRUD endpoints.

## Author

Tabish Shaikh
