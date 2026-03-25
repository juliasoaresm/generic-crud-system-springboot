# Generic CRUD System – Spring Boot

## About
This project is a backend application built with Spring Boot that implements a **generic CRUD system** capable of dynamically handling different entities using reflection.

Instead of creating separate controllers and forms for each entity, the system allows dynamic routing and form generation based on the entity name provided in the URL.

## Features
- Generic CRUD operations
- Dynamic entity handling using reflection
- Reusable controller for multiple entities
- Backend-driven form generation
- Integration with Thymeleaf templates

## Key Concept
The system uses Java Reflection (`Class.forName`) to dynamically resolve entity classes at runtime, allowing flexible and scalable CRUD operations without hardcoding each entity.

## Technologies
- Java
- Spring Boot
- Thymeleaf
- MVC Architecture

## Use Case
Originally developed as part of a fictional platform (“AirBnTruta”), this system demonstrates how backend logic can be abstracted and reused to support multiple entities dynamically.

## Example
Access different entities via URL:

/crud/servico  
/crud/fugitivo  

The system dynamically loads and renders the corresponding data and forms.

## Author
Julia Soares
