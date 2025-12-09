# Expense Tracker Application

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A robust, production-grade microservices-based application for tracking personal expenses. This system leverages modern Java 21 features, Spring Boot 3, and utilizes Kong as an API Gateway for secure and efficient request routing.

## 🏗 Architecture

The application is built using a microservices architecture pattern:

- **API Gateway (Kong)**: Central entry point for all client requests, handling routing, rate limiting, and basic security policies.
- **Auth Service**: Manages user authentication and issues JWT tokens for secure access.
- **User Service**: Handles user profile management and data.
- **Expense Service**: Core domain service for tracking and managing user expenses.

## 🚀 Key Features

- **Microservices Architecture**: Decoupled services for independent scalability and maintenance.
- **Centralized API Gateway**: Simplifies client integration and manages cross-cutting concerns.
- **Secure Authentication**: robust JWT-based stateless authentication.
- **Modern Tech Stack**: Built with the latest Java LTS (21) and Spring Boot 3 standards.

## 🛠 Tech Stack

- **Language**: Java 21+
- **Framework**: Spring Boot 3.x
- **Build Tool**: Maven
- **Gateway**: Kong API Gateway
- **Security**: Spring Security, JWT (JSON Web Tokens)
- **Database**: (Configure as per service, e.g., PostgreSQL/MySQL)

## 📋 Prerequisites

Ensure you have the following installed:

- [Java Development Kit (JDK) 21](https://adoptium.net/)
- [Maven](https://maven.apache.org/)
- [Docker](https://www.docker.com/) (Recommended for running Kong and Databases)

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/expense-tracker.git
cd expence-tracker
```

### 2. Build the Services

Navigate to each service directory and build the application:

```bash
cd auth-module
mvn clean install
```

_(Repeat for other modules as they are added)_

### 3. Run the Services

```bash
mvn spring-boot:run
```

## 🤝 Contribution

Contributions are welcome! Please fork the repository and submit a pull request.
