# Real-Time Supply Tracker 🚚📦

![GitHub release](https://img.shields.io/github/release/jefrinurmukti/real-time-supply-tracker.svg) ![Java](https://img.shields.io/badge/Java-11-blue.svg) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.5.4-green.svg) ![Docker](https://img.shields.io/badge/Docker-20.10.7-blue.svg)

Welcome to the **Real-Time Supply Tracker** repository! This project showcases a Spring Boot microservices ecosystem that integrates various technologies to provide a production-ready demo for supply chain management. 

You can find the latest releases of the project [here](https://github.com/jefrinurmukti/real-time-supply-tracker/releases). Make sure to download and execute the necessary files for a seamless experience.

## Table of Contents

1. [Introduction](#introduction)
2. [Architecture Overview](#architecture-overview)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [Setup Instructions](#setup-instructions)
6. [Running the Application](#running-the-application)
7. [API Documentation](#api-documentation)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Introduction

The **Real-Time Supply Tracker** is designed to manage supply chain operations effectively. This system uses microservices to ensure scalability and resilience. By utilizing technologies like Kafka for messaging and Eureka for service discovery, this project exemplifies modern cloud-native application development.

## Architecture Overview

![Architecture Diagram](https://example.com/architecture-diagram.png)

The architecture consists of several key components:

- **API Gateway**: Acts as a single entry point for all client requests, routing them to the appropriate microservice.
- **Microservices**: Each microservice handles a specific business capability, such as inventory management, order processing, and shipment tracking.
- **Eureka**: Provides service discovery, allowing microservices to find each other dynamically.
- **Kafka**: Manages real-time data streaming between services.
- **Zipkin**: Implements distributed tracing, helping to monitor and troubleshoot microservices.
- **Circuit Breakers**: Enhances system resilience by preventing cascading failures.

## Technologies Used

- **Java**: The primary programming language for building microservices.
- **Spring Boot**: Simplifies the development of Java applications by providing a set of conventions and defaults.
- **Spring Cloud**: Provides tools for building cloud-native applications.
- **Kafka**: A distributed streaming platform that enables real-time data processing.
- **Eureka**: A service registry for locating services in a microservices architecture.
- **Zipkin**: A distributed tracing system for monitoring and troubleshooting.
- **Docker**: Containerizes applications for consistent deployment across environments.

## Features

- **Real-Time Tracking**: Monitor supply chain activities as they happen.
- **Microservices Architecture**: Each component is independently deployable and scalable.
- **Resilience**: Circuit breakers prevent failures from affecting the entire system.
- **Service Discovery**: Eureka allows dynamic service registration and discovery.
- **Data Streaming**: Kafka ensures reliable data flow between services.
- **Distributed Tracing**: Zipkin provides insights into system performance.

## Setup Instructions

To set up the **Real-Time Supply Tracker**, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jefrinurmukti/real-time-supply-tracker.git
   cd real-time-supply-tracker
   ```

2. **Build the Project**:
   Use Maven to build the project.
   ```bash
   mvn clean install
   ```

3. **Docker Setup**:
   Ensure you have Docker installed. Build the Docker images.
   ```bash
   docker-compose build
   ```

4. **Environment Configuration**:
   Update the `application.yml` file with your specific configurations, such as database credentials and Kafka settings.

5. **Start the Services**:
   Use Docker Compose to start all services.
   ```bash
   docker-compose up
   ```

## Running the Application

After setting up the application, you can access the API Gateway at `http://localhost:8080`. The API Gateway will route requests to the appropriate microservices.

For detailed instructions on each microservice, refer to the respective folders in the repository.

## API Documentation

The API documentation is available through Swagger UI. You can access it at `http://localhost:8080/swagger-ui.html` after running the application. This documentation provides detailed information on available endpoints, request parameters, and response formats.

## Contributing

We welcome contributions to enhance the **Real-Time Supply Tracker**. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your forked repository.
5. Create a pull request detailing your changes.

Please ensure your code adheres to the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, please reach out to the project maintainer:

- **Name**: Jefrin Urmukti
- **Email**: jefrin@example.com
- **GitHub**: [jefrinurmukti](https://github.com/jefrinurmukti)

You can also check the [Releases](https://github.com/jefrinurmukti/real-time-supply-tracker/releases) section for updates and new features. 

Thank you for your interest in the **Real-Time Supply Tracker**!