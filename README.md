# ⚡ Cloud & DevOps Portfolio — Muhammad Ibraheem (FA23-BAI-055)

![CI/CD Pipeline](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Container-Docker_Nginx-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Status](https://img.shields.io/badge/Status-Production_Ready-10B981?style=for-the-badge)

## 👨‍💻 Developer Profile
- **Name:** Muhammad Ibraheem
- **Roll Number:** FA23-BAI-055
- **GitHub:** [@muhammad-ibraheem-dextro](https://github.com/muhammad-ibraheem-dextro)
- **Docker Hub:** `ibraheem11/devops-a2`

## 🚀 Architecture & Containerization
This repository hosts a modern, glassmorphic developer portfolio packaged into an Alpine-based **Nginx** Docker image and automated via a **GitHub Actions** CI/CD workflow.

```bash
docker build -t ibraheem11/devops-a2:manual .
docker run -d -p 8080:80 --name page ibraheem11/devops-a2:manual