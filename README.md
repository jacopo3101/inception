# Inception

## Score
![project score](/assets/score.png)

## Description
Project Inception is a hands-on exercise in system administration, focusing on Docker virtualization. It involves setting up a small infrastructure of different services within a personal virtual machine environment.
The Docker image must be built from scratch, starting from the penultimate stable version of Debian or Alpine.

## Objectives
- Broaden knowledge and proficiency in system administration.
- Gain practical experience in Docker containerization.
- Learn to set up and manage a small infrastructure of services using Docker.
- Understand best practices for Dockerfile design and container orchestration.

## Project Structure
The project directory structure is organized as follows:
```
project_inception/
│
├── srcs/
│ ├── Makefile
│ ├── docker-compose.yml
│ ├── .env
│ ├── requirements/
│ │ ├── mariadb/
│ │ ├── nginx/
│ │ ├── tools/
│ │ └── wordpress/
│ └── [other necessary files and directories]
│
└── [other project files]
```
- **srcs/**: Contains all project configurations and Docker-related files.
  - **Makefile**: Automates the setup of the application.
  - **docker-compose.yml**: Defines the composition of Docker services.
  - **.env**: Stores environment variables and sensitive data locally.
  - **requirements/**: Directory for storing Dockerfiles and related configurations for each service.
