# 🚀 Dockerized Flask Web Application

A professional demonstration of **Containerization** using Docker and Python Flask. This project showcases the ability to package a web application with all its dependencies into a lightweight, portable, and production-ready container.

---

## 🛠️ Tech Stack
- **Language:** Python 3.9
- **Framework:** Flask (Lightweight Web Server)
- **Containerization:** Docker
- **Environment:** Linux / Google Cloud Shell

## 🌟 Key Features
- **Infrastructure as Code:** Fully automated environment setup via `Dockerfile`.
- **Port Mapping:** Seamlessly exposed container services to the host machine on port `8080`.
- **Slim Image Optimization:** Built using `python:3.9-slim` to reduce image size and improve deployment speed.

## 🚀 Getting Started

### Prerequisites
- Docker installed on your local machine or cloud environment.

### 1. Clone the Repository
```bash
git clone [https://github.com/VimukthiPrabath/docker-flask-web-app.git](https://github.com/VimukthiPrabath/docker-flask-web-app.git)
cd docker-flask-web-app
```

### 2. Build the Docker Image
```Bash
docker build -t my-web-app .
```
###3. Run the Container
```Bash
docker run -p 8080:8080 my-web-app
```
Once the container is running, access the application at http://localhost:8080.

## 🎓 Internship & Career Goals
This project serves as a key milestone in my Software Engineering & DevOps journey. It demonstrates my proficiency in:
 - Docker Lifecycle Management: Build, Run, and Port Mapping.
 - Version Control: Using Git/GitHub for collaborative development and source code management.
 - Deployment Readiness: Building scalable, isolated, and portable software environments.
