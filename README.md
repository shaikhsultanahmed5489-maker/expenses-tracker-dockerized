# Expenses Tracker Dockerized

A Docker practice project where an open-source Spring Boot + MySQL Expenses Tracker application was containerized using Docker and Docker Compose, and deployed on AWS EC2.

## My Contributions

* Created a multi-stage Dockerfile
* Created Docker Compose configuration
* Containerized Spring Boot and MySQL services
* Configured Docker networking and volumes
* Deployed and tested the application on AWS EC2

## Tech Stack

* Spring Boot
* MySQL
* Docker
* Docker Compose
* AWS EC2
* Ubuntu Linux

## Run the Application

Build and start the containers:

```bash
docker compose up -d
```

Check running containers:

```bash
docker ps
```

Access the application:

```text
http://<EC2-PUBLIC-IP>:8080
```

## Screenshots

### Application Running

(screenshots/application-homepage.png)

### Docker Containers

(screenshots/docker-ps.png)

### AWS EC2 Deployment

(screenshots/ec2.png)

## Note

The original Expenses Tracker application was developed by its original author(https://github.com/mohamed0sawy/Expenses-Tracker-WebApp.git). This repository focuses on Dockerization and AWS deployment for DevOps learning and practice.
