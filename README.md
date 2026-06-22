# Expenses Tracker Dockerized

## Overview

This repository contains a Dockerized version of an open-source Spring Boot Expenses Tracker application.

The focus of this project is on containerization, orchestration, and deployment using Docker, Docker Compose, and AWS EC2.

## My Contributions

* Created a multi-stage Dockerfile for the Spring Boot application
* Created Docker Compose configuration
* Configured MySQL and Spring Boot containers
* Implemented persistent storage using Docker volumes
* Configured container networking
* Built and tested Docker images
* Deployed and verified the application on AWS EC2

## Tech Stack

* Java 17
* Spring Boot
* MySQL
* Maven
* Docker
* Docker Compose
* AWS EC2
* Ubuntu Linux

## Project Structure

```text
.
├── Dockerfile
├── docker-compose.yml
├── pom.xml
├── src/
├── screenshots/
└── README.md
```

## Docker Build

Build the Docker image:

```bash
docker build -t expensesapp .
```

Verify the image:

```bash
docker images
```

## Running with Docker Compose

Start the application:

```bash
docker compose up -d
```

Check running containers:

```bash
docker ps
```

Stop the application:

```bash
docker compose down
```

## AWS EC2 Deployment

### EC2 Configuration

* Launch Ubuntu EC2 instance
* Install Docker
* Install Docker Compose
* Clone the repository
* Build and run containers

### Clone Repository

```bash
git clone <repository-url>
cd expenses-tracker-dockerized
```

### Deploy Application

```bash
docker compose up -d
```

### Verify Deployment

```bash
docker ps
```

Application will be available at:

```text
http://<EC2-PUBLIC-IP>:8080
```

## Screenshots

### Application Running on AWS EC2

(screenshots/application-homepage.png)

### Running Containers

(screenshots/docker-ps.png)

### AWS EC2 Instance

(screenshots/ec2-instance.png)

## Learning Outcomes

Through this project I gained hands-on experience with:

* Docker Image Creation
* Multi-Stage Docker Builds
* Docker Compose
* Container Networking
* Volume Management
* Spring Boot Containerization
* MySQL Containerization
* AWS EC2 Deployment
* Linux Administration
* Troubleshooting Containerized Applications

## Disclaimer

The original Expenses Tracker application was developed by its original author(s).

This repository focuses on Dockerization, container orchestration, and AWS deployment for DevOps learning and practice purposes.
