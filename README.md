# Library Platform Parent

## Mandatory Information

- **Student Name**: [Harsha Nimeda]
- **Student Number**: [2301691058]
- **Slack Handle**: [@Harsha Nimeda]
- **GCP Project ID**: [indigo-splice-491917-q2]

## Project Description

This repository is the parent Maven project for the **Library Management System** platform services. It aggregates three core microservices as Git submodules:

- `config-server` – Centralized configuration server
- `eureka-server` – Service registry and discovery
- `api-gateway` – Single entry point for all backend requests

The parent POM manages shared dependencies and Spring Boot / Spring Cloud versions, ensuring consistency across platform components.

## Technology Stack

- Java 25
- Spring Boot 3.4.5
- Spring Cloud 2024.0.1
- Maven
- Git Submodules

## Setup / Getting Started Instructions

### Prerequisites
- Git
- Java 25
- Maven 3.8+

### Clone and Initialize Submodules

```bash
git clone https://github.com/your-username/library-platform-parent.git
cd library-platform-parent
git submodule update --init --recursive
