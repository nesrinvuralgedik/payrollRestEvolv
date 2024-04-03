# Spring Boot Application
This application is built using the Spring Boot framework, simplifying Java-based application development.

## Description
Spring MVC + Spring HATEOAS app with HAL representations of each resource.  
Spring HATEOAS is used to define RESTful services by creating hypermedia-driven outputs, meaning adding links to relevant operations.


It is built with Maven and includes the following dependencies:
  - Web
  - JPA
  - H2

A simple payroll service that manages the employees of a company. It stores employee objects in a (H2 in-memory) database and accesses them via JPA.
Then it uses the Spring MVC as a web layer.

## Usage
Once the application is running, you can use the following endpoints to interact with the user data:

http://localhost:8080/
- `GET /employees`: Retrieve a list of all employees.
- `GET /employees/{id}`: Retrieve a specific employee by ID.
- `POST /employees`: Create a new employee.
- `PUT /employees/{id}`: Update an existing employee.
- `DELETE /employees/{id}`: Delete an employee by ID.
