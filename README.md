# DevOps First Project 🚀

A simple **static web application** built with **HTML & CSS**, containerized using **Docker**, and served using **Nginx**.  
This project is part of my **DevOps learning journey**, focusing on containerization and image management.

---

## 📌 Project Overview

This project demonstrates:
- How to containerize a static website using Docker
- How to serve static content using Nginx
- How to publish Docker images to Docker Hub

It serves as a **foundation project** before moving to CI/CD, Kubernetes, and cloud deployments.

---

## ✨ Features

- Static frontend (HTML & CSS)
- Lightweight Nginx web server
- Dockerized application
- Image pushed to Docker Hub

---

## 🧰 Tech Stack

- HTML
- CSS
- Nginx
- Docker
- Git & GitHub

---

## 🐳 Docker Image

The application image is publicly available on Docker Hub:

```bash
purvaawankhede/cloud-native-ecommerce:latest
```

---
## Run the application locally
Pull the docker image
```bash
docker pull purvaawankhede/cloud-native-ecommerce:latest
```
---
## Run the container
```bash
docker run -d -p 8080:80 --name devops-first-container \
purvaawankhede/cloud-native-ecommerce:latest
```
---
##Access the application
Open your browser and visit:
```
http://localhost:8090
```