# Secure and Scalable CI/CD Pipeline for Gemini Bot Clone

### Automated DevOps Implementation using GitHub, Jenkins, Docker, and AWS

## 📌 Project Overview

This project demonstrates a **secure and scalable Continuous Integration and Continuous Deployment (CI/CD) pipeline** for the **Gemini Bot Clone**, a web-based chatbot interface built using HTML, CSS, and JavaScript.

The pipeline automates the complete deployment workflow using **GitHub, Jenkins, Docker, and Amazon Web Services (AWS)**, ensuring fast, reliable, and production-ready deployments with minimal manual intervention.

---

## 🚀 Key Features

* Fully automated CI/CD pipeline triggered by GitHub commits
* Docker-based containerized deployment
* Jenkins pipeline automation for build and deployment
* AWS EC2 hosting for application deployment
* AWS S3 artifact storage and log management
* Automated container lifecycle management and cleanup
* Secure deployment using IAM roles and security groups

---

## 🏗 System Architecture

Pipeline Workflow:

GitHub → Jenkins Pipeline → Docker Image Build → AWS EC2 Deployment → Artifact Storage in AWS S3

---

## 🛠 Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript
* **Version Control:** Git, GitHub
* **CI/CD Automation:** Jenkins
* **Containerization:** Docker
* **Cloud Infrastructure:** AWS EC2, AWS S3, IAM
* **Web Server:** Nginx (Docker container)

---

## 📁 Repository Structure

```
gemini-bot-clone/
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

## ⚙️ Deployment Process

1. Developer pushes code to GitHub.
2. GitHub webhook triggers Jenkins pipeline.
3. Jenkins builds Docker image.
4. Docker container deployed automatically to AWS EC2.
5. Build artifacts and logs uploaded to AWS S3.
6. Old containers and images are cleaned automatically.

Average deployment time: **2–3 minutes**

---

## 📦 Run Locally

```bash
git clone https://github.com/yourusername/gemini-bot-clone.git
cd gemini-bot-clone
docker build -t gemini-bot .
docker run -p 8081:80 gemini-bot
```

Open:
http://localhost:8081

---

## 🔐 Security Measures

* IAM role-based secure access to AWS resources
* Encrypted S3 artifact storage
* Controlled EC2 security group access
* Jenkins credential vault for secrets management

---

## 📈 Project Outcomes

* Deployment time reduced from 30–45 minutes to ~2 minutes
* Automated error-free deployments
* Improved scalability and reliability
* Demonstrates real-world enterprise DevOps pipeline practices

---

## 🔮 Future Enhancements

* Multi-environment deployments (Dev / Staging / Production)
* Kubernetes (EKS) based container orchestration
* Monitoring using Prometheus and Grafana
* Infrastructure provisioning using Terraform
* Automated security and vulnerability scanning

---

## 👨‍💻 Authors

* Thirumalaivasan GJ
  
---

## 📜 License

This project is released under the MIT License.
