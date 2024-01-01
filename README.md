# Currency Conversion Microservices Project

## Overview

This project is a Spring Boot Microservices implementation for currency conversion. It comprises several microservices, each serving a specific purpose, orchestrated using Docker.

## Project Structure

- **api-gateway**: Microservice acting as the API gateway for the project.
- **currency-conversion-service**: Microservice responsible for handling currency conversion requests.
- **currency-exchange-service**: Microservice providing currency exchange rates.
- **naming-server**: Eureka Naming Server for service discovery.
- **docker-compose.yaml**: Docker Compose file to orchestrate the deployment of microservices.

## Getting Started

1. Clone the repository.
   git clone <repository-url>

ChatGPT
Certainly! Based on the information you provided, here's a template for the README file for your Spring Boot Microservices project with Docker:

markdown
Copy code
# Currency Conversion Microservices Project

## Overview

This project is a Spring Boot Microservices implementation for currency conversion. It comprises several microservices, each serving a specific purpose, orchestrated using Docker.

## Project Structure

- **api-gateway**: Microservice acting as the API gateway for the project.
- **currency-conversion-service**: Microservice responsible for handling currency conversion requests.
- **currency-exchange-service**: Microservice providing currency exchange rates.
- **naming-server**: Eureka Naming Server for service discovery.
- **docker-compose.yaml**: Docker Compose file to orchestrate the deployment of microservices.

## Getting Started

1. Clone the repository.
   git clone <repository-url>
   cd <repository-folder>

2. Build and run the microservices using Docker
   docker-compose up

3. Access the services through the API gateway.
   API Gateway: http://localhost:8080

## Microservices Endpoints

**API Gateway**

  Endpoint: http://localhost:8080
  Routes requests to relevant microservices.

**Currency Conversion Service**

  Endpoint: http://localhost:8080/currency-conversion
  Handles currency conversion requests.

**Currency Exchange Service**
  
  Endpoint: http://localhost:8000
  Provides currency exchange rates.

**Eureka Naming Server**

  Endpoint: http://localhost:8761
  Service discovery for microservices.

**Docker Compose**

The project utilizes Docker Compose to streamline the deployment process. The docker-compose.yaml file defines the configuration for orchestrating the microservices.
  docker-compose up

**How to Contribute**

  If you want to contribute to this project, follow these steps:
  Fork the repository.
  Create a new branch.
  Make your changes and commit them.
  Push to your fork and submit a pull request.

**Support**

  If you encounter any issues or need assistance, please create an issue or contact [maheshmaahi67@gmail.com].


