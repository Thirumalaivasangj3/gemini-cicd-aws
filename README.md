# Gemini CI/CD AWS Pipeline

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### Automated DevOps Deployment using GitHub, Jenkins, Docker, and AWS

---

## Project Overview

This project demonstrates a **secure, scalable, and fully automated CI/CD pipeline** for a Gemini Bot Clone web application. The pipeline integrates **GitHub, Jenkins, Docker, and AWS** to automate the entire deployment lifecycle, enabling fast, reliable, and production-ready deployments with minimal manual intervention.

---

## Key Features

| Feature |
|---|
| GitHub webhook-triggered Jenkins CI/CD pipeline |
| Docker containerized application deployment |
| AWS EC2 hosting for production deployment |
| Artifact and build log storage using AWS S3 |
| Automated container lifecycle management and cleanup |
| Secure infrastructure using IAM roles and security groups |
| Production-ready DevOps workflow |

---

## System Architecture

```
GitHub Repository
       ↓
Jenkins Pipeline
       ↓
Docker Image Build
       ↓
AWS EC2 Deployment
       ↓
Artifact Storage in AWS S3
```

---

## Technologies Used

| Category | Technology |
|---|---|
| **Frontend** | HTML, CSS, JavaScript |
| **Version Control** | Git & GitHub |
| **CI/CD Tool** | Jenkins |
| **Containerization** | Docker |
| **Cloud Platform** | AWS EC2, AWS S3, IAM |
| **Web Server** | Nginx (Docker container) |

---

## Repository Structure

```
gemini-cicd-aws/
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

## Automated Deployment Workflow

| Step | Action |
|---|---|
| 1 | Developer pushes code to GitHub |
| 2 | GitHub webhook automatically triggers Jenkins pipeline |
| 3 | Jenkins builds Docker image and deploys container to AWS EC2 |
| 4 | Build artifacts and logs are uploaded to AWS S3 |
| 5 | Old containers and images are automatically cleaned |

> Average deployment time: **~2–3 minutes**

---

## Run Locally

```bash
git clone https://github.com/Thirumalaivasangj3/gemini-cicd-aws.git
cd gemini-cicd-aws
docker build -t gemini-bot .
docker run -p 8081:80 gemini-bot
```

Open in browser:
```
http://localhost:8081
```

---

## Security Measures

- IAM role-based secure AWS access
- Encrypted S3 artifact storage
- Jenkins credential vault for secrets management
- Controlled EC2 access using security groups

---

## Project Outcomes

| Metric | Result |
|---|---|
| Deployment Time | Reduced from 30–45 mins to **~2 minutes** |
| Manual Steps | Eliminated |
| Scalability | Improved deployment reliability |
| Standard | Enterprise-level DevOps automation |

---

## Authors

**Thirumalaivasan GJ**

---

## License

MIT License
