# AWS Gemini Bot CI/CD Pipeline

### Secure and Scalable DevOps Implementation using GitHub, Jenkins, Docker, and AWS

## 📌 Project Overview

This project demonstrates a **secure, automated, and scalable Continuous Integration and Continuous Deployment (CI/CD) pipeline** for a Gemini Bot Clone web application.

The system integrates **GitHub, Jenkins, Docker, and Amazon Web Services (AWS)** to automate the entire workflow — from code architecture to production deployment — ensuring faster releases, reduced manual effort, and high deployment reliability.

---

## 🚀 Key Features

* GitHub webhook-triggered automated Jenkins pipeline
* Docker-based containerized application deployment
* AWS EC2 infrastructure hosting the application
* Artifact storage and build log backup using AWS S3
* Automated container lifecycle management and cleanup
* Secure infrastructure using IAM roles and AWS security groups
* Production-ready DevOps automation workflow

---

## 🏗 System Architecture

Pipeline Flow:

GitHub Repository
→ Jenkins CI/CD Pipeline
→ Docker Image Build
→ AWS EC2 Container Deployment
→ Artifact & Log Storage in AWS S3

---

## 🛠 Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Version Control:** Git & GitHub
* **CI/CD Tool:** Jenkins
* **Containerization:** Docker
* **Cloud Platform:** AWS EC2, AWS S3, IAM
* **Web Server:** Nginx (Docker container)

---

## 📁 Repository Structure

```
aws-gemini-bot-cicd-pipeline/
│── index.html
│── style.css
│── script.js
│── Dockerfile
│── Jenkinsfile
│── README.md
│── download.png
│── download1.png
│── downloads.png
```

---

## ⚙️ Automated Deployment Workflow

1. Developer pushes code to GitHub repository.
2. GitHub webhook triggers Jenkins pipeline automatically.
3. Jenkins builds Docker image and deploys container to AWS EC2.
4. Build artifacts and logs are uploaded to AWS S3.
5. Old containers and images are automatically cleaned.

Average deployment time: **~2–3 minutes**

---

## 📦 Run Locally

```bash
git clone https://github.com/Thirumalaivasangj3/aws-gemini-bot-cicd-pipeline.git
cd aws-gemini-bot-cicd-pipeline
docker build -t gemini-bot .
docker run -p 8081:80 gemini-bot
```

Open in browser:

```
http://localhost:8081
```

---

## 🔐 Security Measures

* IAM role-based secure AWS access
* Encrypted AWS S3 artifact storage
* Jenkins credentials stored securely in credential vault
* Restricted EC2 access using security groups

---

## 📈 Project Outcomes

* Reduced deployment time from 30–45 minutes to ~2 minutes
* Eliminated manual deployment steps
* Improved scalability, automation, and deployment reliability
* Demonstrates enterprise-level DevOps CI/CD implementation

---

## 🔮 Future Enhancements

* Multi-environment deployment (Dev / Staging / Production)
* Kubernetes (AWS EKS) integration
* Monitoring with Prometheus and Grafana
* Infrastructure provisioning using Terraform
* Automated security vulnerability scanning

---

## 👨‍💻 Authors

* Thirumalaivasan GJ

---

## 📜 License

MIT License
