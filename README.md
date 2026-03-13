**Frontend Repository:
https://github.com/durgaprasad18-k/JobPortal-frontend**

# Job Portal Backend (Spring Boot)

## Overview
This project is the backend of a Job Portal application built using Spring Boot and MongoDB Atlas.  
It provides REST APIs for user registration, login authentication using JWT, and profile management.

## Tech Stack
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- MongoDB Atlas
- Maven

## Features
- User Registration
- User Login
- JWT Token Authentication
- MongoDB Cloud Database ( Atlas )
- RESTful APIs

## API Endpoints

### Register User
POST /users/register

### Login
POST /auth/login

## Example Request

Register User

{
"name": "Durga Prasad",
"email": "durga@gmail.com",
"password": "Durga@123"
}

## Example Response

{
"id": 1,
"name": "Durga Prasad",
"email": "durga@gmail.com"
}

## Run the Project

Clone the repository

Run:

./mvnw spring-boot:run

Server runs on:

http://localhost:8080

## Database
MongoDB Atlas

Collections:
- users
- profiles
- sequence
- 
## Backend Screenshots

### MongoDB Database
![MongoDB](screenshots/backend screenshots/mongodb.png)

### Users Collection
![Users](screenshots/backend screenshots/users.png)

### Profiles Collection
![Profiles](screenshots/backend screenshots/profiles.png)

### Register API
![Register API](screenshots/backend screenshots/postman-register.png)

### Login API
![Login API](screenshots/backend screenshots/postman-jwt.png)
