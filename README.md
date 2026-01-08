# Java Microservices Architecture Example

**GitHub:** https://github.com/farafatima44/java-microservices-examples

---

## Project Overview

This repository demonstrates a **Java microservices architecture** using modern Spring technologies.  
It includes multiple services communicating via service discovery and API gateway patterns, showcasing enterprise‑grade system design.

The project demonstrates:
- Modular backend services with **Spring Boot**
- Service discovery using **Eureka**
- API routing and management via **Spring Cloud Gateway**
- Event‑driven communication patterns
- Decoupled architecture for scalability and resilience

---

## Key Features

- **Modular Microservices:** Independent services for booking, inventory, and user management.  
- **Service Discovery:** Uses **Eureka Server** to register and locate services dynamically.  
- **API Gateway:** Central routing point for microservices using **Spring Cloud Gateway**.  
- **Resilience and Fault Tolerance:** Enables retry, timeout, and circuit breaker patterns.  
- **Event Messaging:** Microservices communicate using asynchronous messaging patterns.  
- **Config Server (Optional):** Centralized configuration for all microservices.

---

## Technologies Used

| Layer         | Technologies & Tools                           |
|---------------|------------------------------------------------|
| Backend       | Java 17, Spring Boot, Spring Cloud, REST APIs  |
| Service Mesh  | Eureka, Spring Cloud Gateway                   |
| Messaging     | Kafka or messaging patterns                    |
| Cloud/DevOps  | Docker, Kubernetes (EKS), AWS (optional)       |
| Testing       | JUnit, Mockito                                 |
| Version Control| Git/GitHub                                    |

---

## Enhancements & Contributions

- Refactored services into a **modular, scalable microservices environment**
- Integrated **Eureka service discovery** with API Gateway routing
- Added **unit and integration tests** using JUnit and Mockito
- Configured for **Docker containerization** and cloud deployment
- Demonstrated **event‑driven patterns** for inter‑service communication

---

## Setup / Installation

**Clone the project**
```bash
git clone https://github.com/farafatima44/java-microservices-examples.git
cd java-microservices-examples
