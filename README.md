# 🚀 CI/CD Pipeline: Docker + GitHub Actions + AWS EC2

An end-to-end automated deployment pipeline that builds a Docker image, pushes it to Docker Hub, and deploys it to a live AWS EC2 server — fully automated on every code push.

![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED)
![AWS](https://img.shields.io/badge/AWS-EC2-FF9900)

---

## 📌 Project Overview

This project demonstrates a complete CI/CD workflow used in real-world DevOps environments:

**Code Push → GitHub Actions Trigger → Docker Build → Push to Docker Hub → Auto-Deploy to AWS EC2 → Live Website**

Every time code is pushed to the `main` branch, the pipeline automatically rebuilds the Docker image and redeploys it to the production server — with zero manual steps.

---

## 🏗️ Architecture
