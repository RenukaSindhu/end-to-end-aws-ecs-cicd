# 🚀 AWS ECS CI/CD Pipeline using Docker, Amazon ECS Fargate & AWS DevOps

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Docker](https://img.shields.io/badge/Docker-Container-blue?logo=docker)
![Amazon ECS](https://img.shields.io/badge/Amazon-ECS-orange?logo=amazonecs)
![Amazon ECR](https://img.shields.io/badge/Amazon-ECR-orange)
![CodePipeline](https://img.shields.io/badge/AWS-CodePipeline-blue)
![CodeBuild](https://img.shields.io/badge/AWS-CodeBuild-yellow)
![CloudWatch](https://img.shields.io/badge/AWS-CloudWatch-red)
![WAF](https://img.shields.io/badge/AWS-WAF-green)

## 📌 Project Overview

This project demonstrates an end-to-end production-style deployment of a containerized web application on AWS.

The application is first deployed manually using Docker, Amazon ECR and Amazon ECS Fargate to understand the complete deployment workflow.

The deployment process is then fully automated using AWS CodePipeline and AWS CodeBuild, enabling Continuous Integration and Continuous Deployment (CI/CD).

The infrastructure is secured using AWS WAF, HTTPS with AWS Certificate Manager, custom domain routing using Amazon Route 53, monitored using Amazon CloudWatch, configured with Amazon SNS notifications, and automatically scales using ECS Service Auto Scaling.

---

## ✨ Features

- Docker Containerization
- Amazon ECS Fargate Deployment
- Amazon Elastic Container Registry (ECR)
- AWS CodeBuild
- AWS CodePipeline
- Application Load Balancer
- Route 53 Custom Domain
- HTTPS using AWS Certificate Manager
- AWS WAF Protection
- CloudWatch Dashboard
- CloudWatch Logs
- CloudWatch Alarms
- Amazon SNS Email Notifications
- ECS Service Auto Scaling
- High Availability across Multiple Availability Zones

---

# 🏗 Architecture

## Complete Solution Architecture

> *(Insert your final architecture diagram here)*

```text
architecture/complete-architecture.png
```

## CI/CD Pipeline Architecture

> *(Insert CI/CD architecture here)*

```text
architecture/cicd-architecture.png
```

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Cloud | AWS |
| Compute | Amazon ECS Fargate, Amazon EC2 |
| Containerization | Docker |
| Registry | Amazon ECR |
| CI/CD | AWS CodePipeline, AWS CodeBuild |
| Networking | VPC, ALB, Route53, NAT Gateway |
| Security | IAM, ACM, WAF, Security Groups |
| Monitoring | CloudWatch, SNS |
| Languages | HTML, CSS, JavaScript |
| Operating System | Amazon Linux 2023 |
