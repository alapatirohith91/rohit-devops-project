# 🚀 Automated Dockerized Web Deployment on AWS

## 📌 Project Overview
This project demonstrates an automated cloud deployment pipeline using Docker, AWS EC2, and GitHub Actions.

The application is containerized using Docker and deployed on an AWS EC2 instance. A CI/CD pipeline is implemented to automatically build and deploy the application whenever code is pushed to GitHub.

---

## 🏗️ Architecture

Developer → GitHub → GitHub Actions → AWS EC2 → Docker Container → Live Application

---

## ⚙️ Technologies Used

- Docker
- AWS EC2 (Ubuntu)
- GitHub Actions (CI/CD)
- Linux
- Git & SSH

---

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions workflow is triggered.
3. SSH connection is established with EC2.
4. Docker image is rebuilt on EC2.
5. Old container is stopped and replaced.
6. Updated application goes live automatically.

---

## 🛠️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/rohit-devops-project.git

2️⃣ Build Docker Image

docker build -t rohit-devops .

3️⃣ Run Container

docker run -d -p 8080:80 rohit-devops


🔐 Security Features

SSH key-based authentication

Restricted security group access

Secure automated deployment

📈 Key Learnings

Containerization using Docker

Cloud deployment on AWS

CI/CD automation using GitHub Actions

Secure remote deployment via SSH

Infrastructure and security management
