:rocket: App Web Distribuée
:page_facing_up: Project Description
App Web Distribuée is a distributed web application built with a microservices architecture. The project is Dockerized and utilizes Spring Boot for the backend services, Node.js for certain functionalities, Eureka for service discovery, and an API Gateway for routing requests. It’s designed to be scalable, flexible, and maintainable.

:star2: Features
Dockerized Microservices: Each microservice is packaged in a separate Docker container.
Spring Boot Services: Backend services built with Spring Boot and connected to H2 databases.
API Gateway: A central gateway for routing API requests to the correct microservice.
Eureka Service Discovery: Automatically registers and discovers services in the architecture.
Microservices Architecture: Modular, scalable, and fault-tolerant design.
:wrench: Tech Stack
Frontend: React (for future integration)
Backend:
Spring Boot (for backend microservices)
Node.js (for auxiliary services, like notifications)
Databases:
MongoDB (for user data)
H2 (for Spring Boot microservices)
Service Discovery: Eureka
API Gateway: Spring Cloud Gateway
Containerization: Docker & Docker Compose for orchestration
:package: Microservices
1. User Service
Handles user-related functions, such as registration and authentication, with MongoDB for data storage.

2. Authentication Service
Responsible for managing user authentication, including login and registration using JWT tokens.

3. API Gateway
The entry point for all client requests, routing them to the appropriate microservice.

4. Eureka Server
Provides service discovery by enabling microservices to register themselves and find each other in the system.

:floppy_disk: Setup and Installation
Prerequisites

Docker: Install Docker
Docker Compose: Install Docker Compose

Clone the Repository

git clone https://github.com/Nada-bkh/app-web-distribuee.git

cd app-web-distribuee

Build and Run the Application

Build and start all containers:

docker-compose up --build

Access the Services:

API Gateway: http://localhost:8080
Eureka Server: http://localhost:8761
Local Development Commands
Build the services:

docker-compose build

Start the services:

docker-compose up

Stop and remove the services:

docker-compose down

:dart: Contribution
Contributions are welcome! If you’d like to contribute, fork the repository and submit a pull request with your changes or improvements. Please ensure you have tested your changes locally before submitting.

:memo: License
This project is licensed under the MIT License.

Nada Ben Khalifa.
