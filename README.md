# 🚀 CI/CD Pipeline with GitHub Actions & Docker

![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Python](https://img.shields.io/badge/Python-Flask-green)

## 📌 Project Overview

This project demonstrates a **fully automated CI/CD pipeline** using GitHub Actions that automatically builds and deploys a Dockerized Flask application to AWS EC2 on every code push.

> Every time code is pushed to the `main` branch — it automatically builds, tests, and deploys to production! No manual steps needed.

---

## 🏗️ Architecture---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python Flask | Web application |
| Docker | Containerization |
| GitHub Actions | CI/CD automation |
| AWS EC2 | Cloud server |

---

## ✨ Features

- ✅ Automatic deployment on every push
- ✅ Dockerized application
- ✅ Zero manual deployment steps
- ✅ Health check endpoint
- ✅ AWS EC2 cloud hosting

---

## 📁 Project Structure
---

## 🚀 How CI/CD Works

1. Developer pushes code to `main` branch
2. GitHub Actions automatically triggers
3. Docker image is built
4. GitHub Actions SSHs into EC2
5. New container is deployed
6. App is live! 🌐

---

## ⚙️ Setup Guide

### Prerequisites
- AWS EC2 instance (Ubuntu 22.04)
- Docker installed on EC2
- GitHub repository secrets configured

### GitHub Secrets Required

| Secret | Description |
|---|---|
| `EC2_HOST` | EC2 Public IP address |
| `EC2_SSH_KEY` | EC2 private key (.pem content) |

### Run Locally

```bash
git clone https://github.com/vaishnavipatelj/devops-project03.git
cd devops-project03
docker build -t devops-project03 .
docker run -p 5000:5000 devops-project03
```

Open browser: `http://localhost:5000`

---

## 📊 Pipeline Status

| Step | Status |
|---|---|
| Code Push | ✅ Triggers pipeline |
| Docker Build | ✅ Automated |
| EC2 Deploy | ✅ Automated |
| App Live | ✅ Running |

---

## 👩‍💻 Author

**Vaishnavi Patel** | Aspiring DevOps Engineer

[![GitHub](https://img.shields.io/badge/GitHub-vaishnavipatelj-black)](https://github.com/vaishnavipatelj)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/YOUR_PROFILE)

---

⭐ **Star this repo if you found it helpful!**
