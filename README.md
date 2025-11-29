# Product Management API

A simple RESTful API built with Spring Boot that performs CRUD operations for managing product data.  
This project demonstrates how to build clean, modular, and scalable backend applications using Controller–Service–Repository architecture.


##  Features
- Create new products  
- Get a product by ID  
- Update existing product information  
- Delete products  
- List all products  
- Error handling & validation basics  


## Architecture
This project uses layered Spring Boot design:
**ProductController** → Handles incoming HTTP requests  
**ProductRepository** → In-memory data access (can be replaced by DB)  
**Product** → Model (entity)  
**Main.java** → Spring Boot entry point  

## Technologies Used
- Java  
- Spring Boot  
- Spring Web  
- REST API  
- Maven (pom.xml)  
- OOP principles  


##  API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/products` | List all products |
| GET | `/products/{id}` | Get a product by ID |
| POST | `/products` | Create a new product |
| PUT | `/products/{id}` | Update product |
| DELETE | `/products/{id}` | Delete product |

