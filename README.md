Ultimate CI/CD with Jenkins & ArgoCD 🚀

This repository demonstrates a complete CI/CD pipeline for a Spring Boot application using Jenkins, SonarQube, Docker, and ArgoCD.

📌 Pipeline Workflow

Checkout SCM – Pull source code from GitHub.

Build & Test – Compile and run unit tests using Maven.

Static Code Analysis – Run SonarQube scans and enforce quality gates.

Docker Build & Push – Build Docker image and push to Docker Hub.

Deployment (GitOps) – ArgoCD automatically syncs the updated manifests to Kubernetes.

⚡ Tech Stack

Jenkins – CI automation

SonarQube – Code quality & security

Docker & Docker Hub – Containerization & registry

Kubernetes – Deployment environment

ArgoCD – GitOps-based CD

🔧 Features

Automated build, test, and deploy pipeline

GitOps-driven Kubernetes deployments

Quality gates with SonarQube

Rollback & history tracking with ArgoCD

👉 This setup ensures faster feedback, high-quality code, and automated deployments with complete visibility into the workflow.
Hello, I have Implemented a CI/CD pipeline that automates the journey of a Spring Boot application from build → test → containerization → deployment on Kubernetes.
<img width="1366" height="768" alt="Jenkins" src="https://github.com/user-attachments/assets/a911602f-0572-4d0e-b797-7376185b44ca" />
<img width="1366" height="768" alt="ArgoCD" src="https://github.com/user-attachments/assets/2183aff9-89ac-4787-9d63-8c24fb15e056" />
<img width="1321" height="659" alt="Image" src="https://github.com/user-attachments/assets/826ff7f9-d90b-48ba-bcab-5af574033448" />
<img width="1366" height="768" alt="Sonarqube" src="https://github.com/user-attachments/assets/6c0aa506-a8ec-4671-af9f-590531ac813e" />
