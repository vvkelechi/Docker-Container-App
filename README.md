# Docker-Container-App
## 📌 Overview
This repository contains a simple backend application containerized using Docker.
The application is designed to be lightweight, portable, and deployment-ready.

---

## 🧰 Tech Stack
- Python (Flask)
- Docker
- Linux

---

## 🐳 Docker Build & Run

### Build Image
```bash
docker build -t docker-container-app .

Run Container
bash
Copy code
docker run -p 8080:8080 docker-container-app

🔍 Test Endpoints
/ → Application status

/health → Health check

🚀 Use Cases
Local development

CI/CD pipelines

Kubernetes deployments (EKS)

🧠 Key Learnings
Writing efficient Dockerfiles

Exposing application ports

Running containerized workloads

