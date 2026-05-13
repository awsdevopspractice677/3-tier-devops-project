# 3-Tier DevOps Project

## 🚀 Project Overview
A production-ready 3-tier application (Frontend, Backend, Database) 
with complete DevOps pipeline implementation using Jenkins, Docker, 
and AWS — built for real-world retail domain use cases.

## 🏗️ Architecture
- **Frontend** — Web layer (containerized with Docker)
- **Backend** — Application/API layer
- **Database** — Data persistence layer

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Jenkins | CI/CD Pipeline Automation |
| Docker | Containerization |
| AWS EC2 | Cloud Hosting |
| GitHub | Source Code Management |
| SonarQube | Code Quality Analysis |
| Nexus | Artifact Repository |

## 📦 CI/CD Pipeline Flow
1. Code pushed to GitHub
2. Jenkins triggers pipeline automatically
3. SonarQube performs code quality check
4. Docker image built and pushed to registry
5. Application deployed to AWS EC2

## 🔧 How to Run
```bash
# Clone the repo
git clone https://github.com/awsdevopspractice677/3-tier-devops-project

# Build Docker images
docker-compose up --build
```

## 👨‍💻 Author
Rishi Kumar Tirumalasetti — AWS DevOps Engineer @ TCS
