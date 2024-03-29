# Student CRUD API

This repository contains a simple CRUD (Create, Read, Update, Delete) API for managing student records. The project is built using Spring Boot, and it provides RESTful endpoints for performing various operations on a Student entity.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Exception Handling](#exception-handling)

## Introduction

The Student CRUD API allows users to perform basic CRUD operations on student records. It includes endpoints for retrieving all students, getting a student by ID, creating a new student, updating an existing student, and deleting a student.

## Features

- **Get All Students:** Retrieve a list of all students.
- **Get Student by ID:** Retrieve details of a specific student by providing the student ID.
- **Create Student:** Add a new student to the database.
- **Update Student:** Modify the details of an existing student.
- **Delete Student:** Remove a student from the database.

## Technologies Used

- [Spring Boot](https://spring.io/projects/spring-boot): Framework for building Java-based applications.
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa): Data access framework for Java applications.
- [MySQL Database](https://www.MySQL.com/):  database for development and testing.
- [Maven](https://maven.apache.org/): Dependency management and build tool.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/student-crud-api.git
   cd student-crud-api
mvn spring-boot:run
Access the API:
The API will be accessible at http://localhost:8080/api/students.

## API Endpoints

- **Get All Students:**
  - Endpoint: `GET /api/students`

- **Get Student by ID:**
  - Endpoint: `GET /api/students/{id}`

- **Create Student:**
  - Endpoint: `POST /api/students`

- **Update Student:**
  - Endpoint: `PUT /api/students/{id}`

- **Delete Student:**
  - Endpoint: `DELETE /api/students/{id}`
 
##  Exception Handling
The API handles exceptions gracefully and returns appropriate HTTP status codes along with error messages. Common exceptions include StudentNotFoundException when a requested student is not found
