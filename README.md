# Real-Time-Analytics-Reporting-Dashboard
A Java Spring Boot Microservices-based platform for real-time analytics and automated reporting.
# Real-Time Analytics & Reporting Dashboard

A Microservices-Based Real-Time Analytics and Reporting Dashboard built using Java, Spring Boot, and Spring Cloud.

## Overview

This project is a distributed application designed to manage product data, process analytical information, and generate automated reports through independent microservices.

It follows a modular microservices architecture with centralized service discovery, API Gateway-based routing, and frontend integration.

## Architecture

The project consists of the following components:

- **Frontend:** User interface for interacting with the application.
- **API Gateway:** Central entry point for routing client requests to backend services.
- **Server / Service Registry:** Supports backend service registration and discovery.
- **Products Service:** Handles product-related operations.
- **Analytics Service:** Processes data and generates analytical insights.
- **Reports Service:** Handles analytical report generation.

## Technology Stack

- Java 17
- Spring Boot
- Spring Cloud
- Microservices Architecture
- Netflix Eureka
- Spring WebClient
- REST APIs
- Ehcache
- Maven

## Key Features

- Microservices-based architecture.
- Centralized API Gateway.
- Service registration and discovery.
- Inter-service communication using WebClient.
- Product data management.
- Analytics processing.
- Automated scheduled report generation.
- Caching for improved performance.
- Independent and modular backend services.

## Project Repositories

| Component | Repository |
|---|---|
| Server / Service Registry | [RealTime_Project_Server](https://github.com/vaibhavdhardwivedi6-netizen/RealTime_Project_Server) |
| Frontend | [Real-Time-Frontend](https://github.com/vaibhavdhardwived6-netizen/Real-Time-Frontend-) |
| Products Service | [Products-Service](https://github.com/vaibhavdhardwived6-netizen/products-service) |
| Analytics Service | [Analytics-Service](https://github.com/vaibhavdhardwived6-netizen/Analytics-Service) |
| Reports Service | [Reports-Service](https://github.com/vaibhavdhardwived6-netizen/Reports-Service) |
| API Gateway | [API-Gateway](https://github.com/vaibhavdhardwived6-netizen/Real-Time-API_GATEWAY-) |

## Architecture Flow

Frontend → API Gateway → Backend Microservices

Backend services communicate with each other and use service discovery for locating registered services.

## Author

**Vaibhav Dhar Dwivedi**

Java Backend Developer | Spring Boot | Microservices

GitHub: [vaibhavdhardwived6-netizen](https://github.com/vaibhavdhardwived6-netizen)
