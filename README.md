# Farm Collector API

Farm Collector API is a Spring Boot-based application that manages farm data, such as crops, farm details, and seasons. This API is equipped with Flyway for database migrations and Swagger for API documentation.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Setup & Installation](#setup-installation)
4. [API Documentation with Swagger](#api-documentation-with-swagger)


## Overview
The `farm-collector-api` is a RESTful service built using Spring Boot. It allows the management of farm-related data and integrates Flyway for handling database migrations. Swagger is used to document and visualize the available API endpoints.

## Features
- CRUD operations for farm data, crops, and seasons.
- Flyway integration for database version control and migrations.
- Swagger UI for easy API documentation and testing.
- Unit and integration tests for the backend.


### Setup & Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/danvisrinivas/farm-collector-api.git
   cd farm-collector-api
2. **Run the application**:
   Run the below command for Running the application
   `mvn spring-boot:run`

### API Documentation with Swagger
    Access the Swagger URL at `http://localhost:8080/swagger-ui.html` to work woth endpoints.
