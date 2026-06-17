# Full-Stack Employee Management System

A full-stack Employee Management System built using Spring Boot, React.js, MySQL, Spring Security, and JWT Authentication. The application provides secure employee management with complete CRUD functionality through a responsive and user-friendly interface.

## Features

### Authentication
- User Registration
- User Login
- JWT Authentication
- Secure API Access using Spring Security

### Employee Management
- Add New Employee
- View All Employees
- Update Employee Details
- Delete Employee Records
- Responsive User Interface
- RESTful API Integration
- MySQL Database Connectivity
- Exception Handling and Validation

## Tech Stack

### Frontend
- React.js
- React Router
- Axios
- Bootstrap

### Backend
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- JWT Authentication
- REST APIs

### Database
- MySQL

### Tools
- Java 17+
- Maven
- Git & GitHub
- VS Code
- Postman

## Project Architecture

```text
React Frontend
       ↓
REST API Layer
       ↓
Spring Boot Backend
       ↓
Service Layer
       ↓
Repository Layer (JPA)
       ↓
MySQL Database
```

## Application Flow

```text
Register User
      ↓
Login User
      ↓
Generate JWT Token
      ↓
Access Dashboard
      ↓
View Employees
      ↓
Add Employee
      ↓
Update Employee
      ↓
Delete Employee
```

## API Endpoints

### Authentication APIs

| Method | Endpoint | Description |
|----------|----------|-------------|
| POST | /auth/register | Register a new user |
| POST | /auth/login | Login and generate JWT token |

### Employee APIs

| Method | Endpoint | Description |
|----------|----------|-------------|
| GET | /employees | Get all employees |
| GET | /employees/{id} | Get employee by ID |
| POST | /employees | Add new employee |
| PUT | /employees/{id} | Update employee |
| DELETE | /employees/{id} | Delete employee |

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/kirankothavale05-blip/Full-Stack-Employee-Mgt-System.git
```

### Backend Setup

1. Open the Spring Boot project.
2. Configure MySQL database in `application.properties`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employeedb
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

3. Run the Spring Boot application.

```bash
mvn spring-boot:run
```

Backend API will start at:

```text
http://localhost:8080
```

### Frontend Setup

```bash
cd emp-frontend
npm install
npm start
```

Frontend application will start at:

```text
http://localhost:3000
```

## Screenshots

### Register Page

![Register Page](https://github.com/user-attachments/assets/763b7653-8c18-42ec-9e37-3276305e4730)

### Login Page

![Login Page](https://github.com/user-attachments/assets/cac6fea7-e996-4156-b080-3db650ad10fd)

### Dashboard

![Dashboard](https://github.com/user-attachments/assets/264c75dc-1820-4d46-a0a8-1aeae041a656)

### Employee List

![Employee List](https://github.com/user-attachments/assets/528e1ad3-f2eb-44af-9362-a30e9098d0bd)

### Add Employee

![Add Employee](https://github.com/user-attachments/assets/faa02b53-34eb-4408-8245-66aca0a890db)

### Update Employee

![Update Employee](https://github.com/user-attachments/assets/9caa88d5-da8a-4e51-a454-a86d47035b4c)

### Delete Employee

![Delete Employee](https://github.com/user-attachments/assets/81668bd0-1b1d-42d6-ab56-4e64ad70e80a)

## Future Enhancements

- Role-Based Access Control
- Search and Filter Employees
- Pagination
- Email Notifications
- Docker Deployment
- Cloud Deployment (AWS)

## Learning Outcomes

- Spring Boot REST API Development
- React Frontend Development
- JWT Authentication & Authorization
- Spring Security Integration
- CRUD Operations
- MySQL Database Integration
- Full Stack Application Development
- Git & GitHub Version Control

## Author

### Kiran Kothavale

Java Full Stack Developer

GitHub: https://github.com/kirankothavale05-blip
