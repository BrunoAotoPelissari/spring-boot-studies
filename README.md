# Spring Boot Learning Project

Welcome to the Spring Boot Learning Project! This is an Java-based project following the best practices aimed at helping individuals learn Spring Boot, a powerful framework for building microservices and standalone applications. This project serves as a practical guide to building production-ready Spring applications, covering various essential concepts and implementations.

## Table of Contents
- Introduction
- Getting Started
- Project Structure
- Missing Implementations
- Changelog
- API Overview
- Key Concepts Covered
- How to Contribute
- License

## Introduction
Spring Boot is a widely used Java framework that simplifies the development of robust and scalable applications. This project is designed to provide a hands-on experience with various Spring Boot features and best practices. Whether you're new to Spring or looking to enhance your skills, this project offers a great learning opportunity.

## Getting Started

### Requisites
1. Java 17 or higher
2. docker and docker-compose installed

To run this project locally, you need to have follow the following:

1. Clone the repository: `git clone https://github.com/BrunoAotoPelissari/spring-boot-studies`
2. Navigate to the project directory: `cd spring-boot-studies`
3. run in your terminal `docker-compose up -d`
4. run in your terminal `mvn spring-boot:run`

To check if everything is running fine, you can access `localhost:8080/api/v1/student` and it should return a proper json response.

## Project Structure

The project follows a structured architecture to promote modularity and maintainability. Here's an overview of the main components:

- `src/main/java/com/example/demo/`: Root package for the project.
- `api/`: API layer containing REST controllers.
- `business/`: Business logic layer.
- `data/`: Data access layer, including JPA entities and repositories.
- `config/`: Configuration classes for Spring Boot.
- `util/`: Utility classes for the project.

## Missing Implementations

While the project covers a wide range of Spring Boot concepts, there are a few implementations that are currently missing. Please refer to the Changelog section for updates on the ongoing development of these features.

## Changelog

[Unreleased]

- Added authentication and authorization.
- Integrated external service for data enrichment.
- Implemented caching for improved performance.
- Enhanced error handling and validation.

## API Overview

The project includes a simple API for managing student data. Here's a quick overview of the available endpoints:

- `GET /api/students`: Fetch a list of all students.
- `GET /api/students/{id}`: Fetch details of a specific student.
- `POST /api/students`: Create a new student.
- `PUT /api/students/{id}`: Update an existing student.
- `DELETE /api/students/{id}`: Delete a student.

## Key Concepts Covered

Throughout this project, you will gain hands-on experience with the following Spring Boot concepts:

- Dependency injection and inversion of control.
- Configuration using properties files.
- Creating and connecting to a database using JPA.
- Defining JPA entities and repositories.
- Implementing RESTful APIs using Spring MVC.
- Writing unit tests and integration tests.
- Business logic implementation and separation of concerns.

## How to Contribute

Contributions to this project are welcome and encouraged! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your fork.
4. Create a pull request detailing your changes and improvements.

Feel free to give suggestions and improvements, happy learning and coding!

- Maintainer: Bruno Aoto
- Contact: <bruno.aoto.pelissari@gmail.com>
- LinkedIn: <https://www.linkedin.com/in/bruno-aoto-pelissari-85095b229/>

## License

This project is licensed under the MIT License. See the LICENSE file for details.
