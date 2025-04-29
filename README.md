# Health-Care-Booking
This Healthcare Booking Application is a backend system developed using Microservices architecture with Spring Boot. It provides a secure and scalable solution for managing healthcare services such as user registration, doctor scheduling, and appointment booking. 

🔧 Tech Stack
Java, Spring Boot, Maven
Spring Security with JWT for authentication and authorization
Spring Cloud Gateway, Eureka Server for API routing and service discovery
MySQL for persistent data storage
Spring Data JPA, Hibernate for ORM
Lombok for reducing boilerplate code
Postman for API testing

📦 Microservices Overview
User Service: Manages user registration, login, and roles (Admin, Doctor, Patient).
Doctor Service: Handles doctor profiles, availability, and schedules.
Appointment Service: Facilitates appointment booking, updating, and cancellation.
API Gateway: Routes incoming client requests to appropriate microservices.
Eureka Discovery Server: Enables dynamic service registration and discovery.
