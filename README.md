# Scalable Node.js Deployment on AWS ECS Fargate

🚀 A production-style cloud-native deployment of a Dockerized Node.js application using AWS ECS Fargate.

This project demonstrates how to containerize a Node.js application, push images to Amazon ECR, and deploy them on AWS ECS using Fargate with proper networking, security, and monitoring.

---

## 👩‍💻 Author

**Hina Atif**  
Cloud & DevOps Engineer  

---

## 🏗️ Architecture Overview

- **Application:** Node.js (To-Do App)
- **Containerization:** Docker
- **Image Registry:** Amazon ECR
- **Orchestration:** Amazon ECS
- **Compute:** AWS Fargate (Serverless)
- **Monitoring & Logs:** Amazon CloudWatch
- **Networking:** VPC, Subnets, Security Groups

---

## 🛠️ Tech Stack

- AWS ECS (Fargate)
- Amazon ECR
- Docker
- Node.js
- AWS CloudWatch
- VPC & Security Groups
- Linux

---

## 🧩 Deployment Workflow

1. Built and containerized the Node.js application using Docker  
2. Authenticated Docker with Amazon ECR using AWS CLI  
3. Tagged and pushed the Docker image to Amazon ECR  
4. Created ECS Task Definition with CPU, memory, and port mappings  
5. Deployed the task on ECS Fargate in a public subnet  
6. Configured security groups to allow external traffic  
7. Verified logs and application health using CloudWatch  

---

## 🧠 Key Skills Demonstrated

- Containerization using Docker
- AWS ECS Fargate (Serverless Containers)
- Amazon ECR image management
- Cloud networking & security configuration
- Monitoring and log analysis with CloudWatch
- Real-world DevOps troubleshooting

---

## 🎯 Why This Project Matters

This project reflects real-world DevOps practices by covering the complete lifecycle of a cloud-native application — from local development to production deployment on AWS.

---

## 🚀 Future Enhancements

- Add Jenkins CI/CD pipeline
- Introduce Application Load Balancer (ALB)
- Enable HTTPS using ACM
- Infrastructure as Code with Terraform

---

## 📘 Project Blog

A detailed explanation of the architecture, design decisions, and learnings from this project is available on Medium:

🔗 [https://medium.com/@hinaatif/deploying-a-scalable-node-js-application-on-aws-ecs-fargate-with-docker](https://medium.com/@hinaatif355/deploying-a-scalable-node-js-application-on-aws-ecs-fargate-with-docker-a1fbddf9ec53)

---
⭐ If you find this project useful, feel free to star the repository!

