# Scalable-Node.js-Deployment-on-AWS-ECS-Fargate

This project demonstrates a professional-grade cloud-native deployment. I containerized a Node.js application using Docker, managed the images via Amazon ECR, and orchestrated the serverless deployment using Amazon ECS Fargate.

✍️ Author
Hina Atif Cloud & DevOps Enthusiast

🏗️ Architecture Overview
Containerization: Docker

Registry: Amazon Elastic Container Registry (ECR)

Orchestration: Amazon Elastic Container Service (ECS)

Compute: AWS Fargate (Serverless)

Monitoring: Amazon CloudWatch

🛠️ Step-by-Step Deployment Process
1. Registry Authentication & Image Build
Before pushing to the cloud, I authenticated the local terminal with the AWS ECR Public registry and tagged the local build for production.

ECR Login: Authenticated using the AWS CLI.

Docker Tagging: Prepared the image with the specific ECR Repository URI


2. Pushing to Amazon ECR
The container image was pushed to AWS. This ensures a secure, centralized location for deployment images.

3. ECS Task Definition & Resource Allocation
I configured a Task Definition to specify how the container should run.

Environment: Fargate (Serverless)

Networking: Set up Port Mapping for port 8000 to allow web traffic.

Compute: Allocated 2 vCPU (2048 units) and 8 GiB Memory.

## 📸 Project Screenshots

### 🔐 AWS ECR Authentication
![ECR Login](screenshots/01-aws-ecr-login.png.jpeg)

### 🏷️ Docker Image Tagging
![Docker Tagging](screenshots/02-docker-image-tagging.png.jpeg)

### 🚀 Docker Image Push to ECR
![Docker Push](screenshots/03-docker-push-ecr.png.jpeg)

### 📦 Image Stored in ECR
![ECR Registry](screenshots/04-ecr-registry-stored.png.jpeg)

### 🧩 ECS Task Definition
![Task Definition](screenshots/05-ecs-task-definition.png.jpeg)

### 🌐 Port Mapping Configuration
![Port Mapping](screenshots/06-network-port-mapping.png.jpeg)

### 🟢 ECS Cluster Running
![Cluster Running](screenshots/07-ecs-cluster-running.png.jpeg)

### 📊 ECS Task Metadata
![Task Metadata](screenshots/08-ecs-task-metadata.png.jpeg)

### 🔍 Container Runtime Details
![Container Runtime](screenshots/08b-ecs-container-runtime-json.png.jpeg)

### 📜 CloudWatch Logs
![CloudWatch Logs](screenshots/09-cloudwatch-logs.png.jpeg)

### ✅ Final Application Live
![Live App](screenshots/10-final-app-live-ui.png.jpeg)


🔍 Deep Dive: Container Runtime Metadata
To ensure the deployment met production specifications, I verified the internal container state. This technical metadata confirms:

Task ID: A unique identifier for this specific container instance.

Resource Allocation: Successfully reserved 2048 CPU units for the Node.js application.

Image Integrity: The container is running exactly the version pushed to ECR: public.ecr.aws/a6s2x7y5/node-app: latest.

4. Cluster Monitoring & Log Analysis
After launching the service in the node-app-cluster-hina cluster, I utilised Amazon CloudWatch to monitor real-time logs and verify that the application started successfully.


🏆 Final Result
The application is live and fully accessible. This project proves the ability to manage the entire lifecycle of a containerised application in a professional AWS environment.




🧠 Key Skills Demonstrated
Infrastructure as Code Concepts: Configuring Task Definitions and IAM Roles.

Network Security: Managing Port Mappings and Security Groups.

DevOps Workflow: Moving from local Docker builds to cloud orchestration.

Troubleshooting: Analyzing CloudWatch logs for deployment verification.
