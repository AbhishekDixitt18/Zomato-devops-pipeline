# 🍔 FoodHub – Full Stack DevOps Pipeline 🚀

<p align="center">
  <b>A complete food delivery platform with end-to-end DevOps automation</b>
</p>

---

## ✨ Project Overview

FoodHub is a **full-stack food delivery application** built with modern DevOps practices.  
It demonstrates how real-world applications are **built, containerized, deployed, and automated** in the cloud.

---

## 🧱 Tech Stack

### 🖥 Frontend
- React.js (Vite)
- Responsive UI
- JWT Authentication

### ⚙ Backend
- Node.js + Express.js
- REST APIs
- OpenAI-powered chatbot

### 🗄 Database
- PostgreSQL
- Auto-seeded restaurant & menu data

---

## 🐳 Containerization

- Docker for application packaging
- Docker Compose for multi-container orchestration
- Isolated services with shared networking

---

## ☁ Infrastructure as Code (Terraform)

- AWS EC2
- VPC, Subnets, Internet Gateway
- Security Groups
- Elastic IPs

---

## 🔧 Configuration Management (Ansible)

- Automated server setup
- Docker installation
- Application deployment
- Zero manual SSH work

---

## 🚀 CI/CD Pipeline (Jenkins)

✔ Triggered on every GitHub push  
✔ Automated build & deployment  
✔ Docker image creation  
✔ Ansible-based rollout  
✔ Health checks  

---

## 🔐 Security Features

- JWT authentication
- Environment-based secrets
- AWS firewall rules
- Encrypted storage
- Ansible Vault ready

---

## 🔄 Workflow Diagram

```text
Developer
   ↓
GitHub (Push)
   ↓
Jenkins CI/CD
   ↓
Docker Build
   ↓
Ansible Deploy
   ↓
AWS EC2
   ↓
Users Access App
