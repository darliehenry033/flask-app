# flask-app
# ☁️ Cloud-Native Flask App with CI/CD Pipeline

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 📖 Project Overview
This project demonstrates a complete **DevOps lifecycle** for a web application. It moves beyond simple development to include containerization, orchestration, and automated delivery.

The goal was to decouple the application from the infrastructure, ensuring it runs identically on a local machine, a developer's workstation, or a production Kubernetes cluster.

### 🏗 Architecture
1.  **Application:** A Python Flask web server.
2.  **Containerization:** Dockerized using a lightweight Alpine Linux image for security and speed.
3.  **Orchestration:** Managed via Kubernetes (k8s) deployments and services for high availability.
4.  **Automation:** A GitHub Actions pipeline triggers on every commit to build and push artifacts to Docker Hub.

---

## 🛠 Technologies Used

| Category | Technology | Usage |
| :--- | :--- | :--- |
| **Containerization** | Docker | Multi-stage builds, Image optimization |
| **Orchestration** | Kubernetes (Minikube) | Deployment sets, Services, Load Balancing |
| **CI/CD** | GitHub Actions | Automated build & push pipeline |
| **OS/Scripting** | Linux (Alpine), Bash | Base images, shell automation |
| **Backend** | Python (Flask) | REST API endpoints |

---

## 🚀 How to Run Locally

### Prerequisites
* Docker Desktop
* Minikube (or any local K8s cluster)
* `kubectl` CLI tool

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR-USERNAME/devops-intern-project.git](https://github.com/YOUR-USERNAME/devops-intern-project.git)
cd devops-intern-project
