# Dockerized Flask Web Application

This project demonstrates how to containerize a simple Python Flask web application using Docker, and how to publish the Docker image to a public container registry (Docker Hub).

---

## 🚀 Project Overview

The goal of this project is to build, containerize, and deploy a lightweight web application using modern DevOps practices. The application is built with Python and Flask, packaged into a Docker container, and pushed to Docker Hub for portability and deployment readiness.

---

## 🎯 Purpose

This project was created as part of my learning journey to become a Cloud/DevOps Engineer. It covers foundational skills such as containerization, dependency management, and image distribution using Docker and Docker Hub.

---

## 🧠 What I Learned

Through this project, I gained practical experience with:

- Creating a Flask-based web application
- Writing and structuring a `Dockerfile`
- Building and running Docker images locally
- Publishing Docker images to Docker Hub
- Understanding image tagging, versioning, and portability
- Verifying the image by pulling and running it from another system

---

## 🛠️ Skills I Acquired

- **Docker**: Image creation, tagging, running containers, pushing to registries  
- **Flask**: Setting up a minimal web server using Python  
- **DevOps Fundamentals**: Packaging and distributing software using containers  
- **Version Control**: Using Git and GitHub for code management and collaboration  
- **Container Registries**: Working with Docker Hub to host and distribute images  

---

## 🧪 How to Run the Application Locally

```
# Build the Docker image
docker build -t flask-docker-app .

# Run the container
docker run -p 5000:5000 flask-docker-app

```

## 📤 How to Push to Docker Hub

```
# Tag the image using your Docker Hub username
docker tag flask-docker-app akshaykashyap74/flask-docker-app:latest

# Push the image to Docker Hub
docker push akshaykashyap74/flask-docker-app:latest

```

## 📥 How to Pull and Run Anywhere

```
# Pull the image from Docker Hub
docker pull akshaykashyap74/flask-docker-app:latest

# Run the image
docker run -p 5000:5000 akshaykashyap74/flask-docker-app:latest

```
## ✅ Output

Hello from Dockerized Flask App!

## 📚 Future Improvements

    1. Add CI/CD with GitHub Actions Or Jenkins

    2. Deploy the container to AWS EC2 or ECS

    3. Automate image versioning and testing
