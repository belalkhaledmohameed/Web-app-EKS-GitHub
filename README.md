📌 Project Overview
This project is a Task Management Application that allows users to authenticate, create accounts, and track task statuses through a RESTful API.
The application is fully containerized and deployed using DevOps best practices on AWS EKS with a complete CI/CD pipeline.
=====================================================================================================================================================
🧩 Application Features
User authentication & signup
Task creation and status tracking
REST API to fetch task status
Secure database integration
Fully automated deployment pipeline
======================================================================================================================================================
🛠️ Tech Stack
🔹 Backend & Application
RESTful API
Database for authentication & user data
======================================================================================================================================================
🔹 DevOps & Infrastructure
Docker – Containerizing the application
Kubernetes (EKS) – Container orchestration
Helm – Kubernetes package management
Sealed Secrets – Secure secret encryption (instead of plain base64)
GitHub Actions – CI/CD pipeline automation
AWS – Cloud infrastructure (EKS Cluster)
======================================================================================================================================================
🔐 Security Implementation
Kubernetes Secrets are encrypted using Sealed Secrets
Prevents exposing sensitive data in Git repositories
Secrets are safely decrypted only inside the Kubernetes cluster
======================================================================================================================================================
🔄 CI/CD Pipeline
The project uses GitHub Actions to automate:
Code checkout
Docker image build
Image push to container registry
Helm chart update
Automatic deployment to AWS EKS via Kubernetes
======================================================================================================================================================
☁️ Cloud Infrastructure
AWS EKS for Kubernetes cluster
Managed Kubernetes nodes
Secure networking and IAM integration
======================================================================================================================================================
📦 Deployment Flow
Copy code
Text
Developer → GitHub Repo
        → GitHub Actions (CI/CD)
        → Docker Build & Push
        → Helm Deployment
        → AWS EKS Cluster
        → Running Application
======================================================================================================================================================
🚀 Why This Project?
This project demonstrates:
Real-world DevOps workflow
Secure Kubernetes deployments
CI/CD automation
Cloud-native application deployment
Best practices for production-ready systems
======================================================================================================================================================
🧠 Skills Demonstrated
DevOps Engineering
Kubernetes & Helm
AWS EKS
CI/CD Pipelines
Secure Secret Management
Containerization
======================================================================================================================================================
complete photos of all Steps of Project
![Project Logo](F:\Project Photos\Project_Steps.png)

