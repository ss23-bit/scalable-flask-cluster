# 🚀 High-Availability DevOps & AI Lab

This is my central repository tracking my transition into a Senior DevOps role. It features a production-ready microservice cluster and an automated AI security auditor.

## 🌟 Featured Project: Scalable Python Cluster
*A high-availability architecture designed for security and scale.*

### 🏗️ Architecture
- **Reverse Proxy:** Nginx (Load Balancer)
- **App Stack:** Flask + Gunicorn (Multi-worker)
- **Security:** Custom AI Auditor powered by Google Gemini (Integrated via GitHub Actions)
- **Infrastructure:** Docker Compose with automated health checks



### 🚀 Key Capabilities
- **Self-Healing:** Docker health checks automatically detect and bypass unhealthy containers.
- **Instant Scaling:** `docker compose up -d --scale web-app=10`
- **AI Governance:** Every commit is audited for security anti-patterns by an LLM-based gatekeeper.

---

## 🗺️ 90-Day Roadmap & Progress
- [x] **Month 1: Linux & Bash** (CS50 Foundations, OverTheWire)
- [x] **Month 2: Docker Orchestration** (Current Focus: Scaling, Proxies, Health)
- [/] **Month 3: Cloud & IaC** (Next: Terraform, AWS/GCP, Kubernetes)

## 📁 Repository Structure
- `app-cluster/`: Production Nginx/Flask/Gunicorn setup.
- `ai-auditor/`: Gemini-powered security auditing tools.
- `01-linux-basics/`: Shell scripts and CLI practice.
- `99-notes/`: Daily learning logs.

## 🛠️ Tech Stack
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)