# Item REST API (Spring Boot)

This is a simple Java Spring Boot backend application that provides REST APIs to manage items.

## Tech Stack
- Java 17
- Spring Boot
- Maven

## How to Run

1. Open project
2. Run:

   mvnw spring-boot:run

3. Server runs on:
   http://localhost:8080

## API Endpoints

### Add Item
POST /items

Request Body:
{
  "name": "Laptop",
  "description": "Gaming laptop",
  "price": 75000
}

### Get Item by ID
GET /items/{id}

Example:
GET /items/1

## Data Storage
Items are stored in-memory using ArrayList.
Data resets when server restarts.
