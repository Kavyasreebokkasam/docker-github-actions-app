
# Dockerized Web Application with GitHub Actions

## About
A beginner-friendly DevOps project that uses Docker
to containerize a web application and GitHub Actions
to automate Docker image builds.

## Technologies
- HTML
- CSS
- Docker
- Nginx
- Git
- GitHub Actions

## Features
- Simple web application
- Docker containerization
- Automated Docker image building
- Continuous Integration

## Run Locally

Build:
docker build -t my-devops-app .

Run:
docker run -d -p 8080:80 --name devops-app my-devops-app

Open:
http://localhost:8080
