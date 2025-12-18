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

## 📸 Project Screenshots

### 🔐 AWS ECR Login
![ECR Login](screenshots/01-aws-ecr-login.png.jpeg)

### 🏷️ Docker Image Tagging
![Docker Tagging](screenshots/02-docker-image-tagging.png.jpeg)

### 🚀 Docker Image Push to ECR
![Docker Push](screenshots/03-docker-push-ecr.png.jpeg)

### 📦 Image Stored in ECR
![ECR Registry](screenshots/04-ecr-registry-stored.png.jpeg)

### 🧩 ECS Task Definition
![Task Definition](screenshots/05-ecs-task-definition.png.jpeg)

### 🌐 Network Port Mapping
![Port Mapping](screenshots/06-network-port-mapping.png.jpeg)

### 🟢 ECS Cluster Running
![Cluster Running](screenshots/07-ecs-cluster-running.png.jpeg)

### 📊 ECS Task Metadata
![Task Metadata](screenshots/08-ecs-task-metadata.png.jpeg)

### 🔍 Container Runtime Details
![Container Runtime](screenshots/08b-ecs-container-runtime-json.png.jpeg)

### 📜 CloudWatch Logs
![CloudWatch Logs](screenshots/09-cloudwatch-logs.png.jpeg)

### ✅ Application Live
![Live App](screenshots/10-final-app-live-ui.png.jpeg)

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

⭐ If you find this project useful, feel free to star the repository!

