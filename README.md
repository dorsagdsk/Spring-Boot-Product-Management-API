##Spring Boot Product Management API

A RESTful backend application developed using Java and Spring Boot to manage products. The application provides REST APIs for product management, including creating, retrieving, updating, deleting, searching products, and handling product images.

##Features

Product Management (CRUD)

Create new products

Retrieve all products

Retrieve a product by ID

Update existing products

Delete products

Product Search

Search products by name

Search by description

Search by brand

Search by category

Image Management

Upload product images

Store image data in the database

Retrieve product images

##Technologies Used

Java 21

Spring Boot

Spring Web MVC

Spring Data JPA

Hibernate

H2 Database

Maven

Lombok

RESTful APIs

##Project Architecture

The project follows a layered architecture:

Controller: Handles HTTP requests and API responses.

Service: Contains business logic.

Repository: Handles database operations using Spring Data JPA.

Model: Defines the Product entity.
