# Automated CI/CD Pipeline for Containerized Web Application 🚀


## Overview

- This project implements an end-to-end CI/CD pipeline for a containerized web application.
- The application is developed using Python Flask.
- GitHub is used for source code management and version control.
- Jenkins automates the continuous integration and continuous deployment process.
- Docker is used to build and deploy the application as a container.
- The pipeline automatically builds, tests, and deploys the application.
- The project demonstrates a real-world DevOps workflow from code commit to application deployment.


## Architecture

Developer
    |
    ↓
GitHub Repository
    |
    ↓
Jenkins CI/CD Pipeline
    |
    ↓
Docker Image Build
    |
    ↓
Docker Container
    |
    ↓
Web Application Deployment


## Technologies Used

- Python Flask
- Git
- GitHub
- Docker
- Jenkins
- Ubuntu Linux

## Features

- Automated source code management using GitHub
- Docker containerization
- Jenkins CI/CD automation
- Continuous application deployment
- Reproducible deployment environment

## Project Structure

docker-cicd-project

├── app.py
├── Dockerfile
├── Jenkinsfile
├── requirements.txt
└── README.md

## How to Run Application

### Build Docker Image

docker build -t docker-cicd-app .

### Run Docker Container

docker run -d -p 5000:5000 docker-cicd-app

### Access Application

http://localhost:5000

## Author

Megha Ganesh Gurikar


