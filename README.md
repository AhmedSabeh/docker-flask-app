# Dockerized Flask App

This project demonstrates how to Dockerize a simple **Flask** web application.

## 🚀 Overview

A basic Flask web app is wrapped in a Docker container. The app responds with "Hello, World! I am inside a Docker container!" when you visit the app’s root URL.

## 🔧 Prerequisites

- Docker installed on your machine.

## 🛠 Getting Started

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/AhmedSabeh/docker-flask-app.git
cd docker-flask-app
```

2. Build the Docker Image
Run the following command to build the Docker image:
```
docker build -t docker-flask-app .
```
3. Run the Docker Container
Start the container with the following command:
```
docker run -d -p 5000:5000 --name flask-container docker-flask-app
```
This maps port 5000 on your machine to port 5000 inside the container.

4. Visit the Application
Open your browser and visit:

http://localhost:5000

You should see:

"Hello, World! I am inside a Docker container!"
