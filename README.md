# 🚀 End-to-End CI/CD Pipeline for Dockerized Kubernetes Application using Jenkins

![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5)
![Python](https://img.shields.io/badge/Python-Flask-yellow)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black)

## 📌 Project Overview

This project demonstrates a complete DevOps CI/CD workflow for deploying a containerized Python web application to Kubernetes using Jenkins.

The pipeline automatically builds a Docker image, pushes it to Docker Hub, and deploys the latest version to a Kubernetes cluster with zero-downtime rolling updates.

---

## 🏗️ Architecture

```
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ├── Checkout Source Code
    ├── Build Docker Image
    ├── Docker Hub Login
    ├── Push Image
    ├── Deploy to Kubernetes
    └── Verify Rollout
            │
            ▼
Docker Desktop Kubernetes
            │
            ▼
Python Web Application
```

---

## 🛠️ Tech Stack

- Jenkins
- Docker
- Docker Hub
- Kubernetes
- Python
- Git
- GitHub
- YAML
- Docker Desktop
- Linux (WSL)

---

## ✨ Features

- Fully automated CI/CD Pipeline
- Dockerized Python application
- Docker Hub image publishing
- Kubernetes Deployment
- Rolling Updates
- ConfigMaps
- Secrets Management
- Namespace Support
- Automated image deployment
- Jenkins Declarative Pipeline

---

## 📂 Project Structure

```
containerized-kubernetes-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── Jenkinsfile
├── README.md
│
└── k8s/
    ├── deployment.yaml
    ├── service.yaml
    ├── config.yaml
    └── secret.yaml
```

---

## ⚙️ CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins checks out the repository
3. Docker image is built
4. Jenkins authenticates with Docker Hub
5. Docker image is pushed to Docker Hub
6. Kubernetes Deployment image is updated
7. Rolling Update is performed
8. Deployment status is verified

---

## 🚀 Pipeline Stages

- Checkout
- Build Docker Image
- Docker Login
- Push Docker Image
- Deploy to Kubernetes
- Verify Rollout

---


## 📈 Key Learning Outcomes

- Building production-ready CI/CD pipelines
- Docker image lifecycle management
- Kubernetes deployments
- Rolling updates
- Jenkins Pipeline automation
- Docker Hub integration
- Kubernetes ConfigMaps & Secrets
- Container orchestration

---

## 👩‍💻 Author

Yamini Nelluru

