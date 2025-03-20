#  Deploying a Containerized Application on AWS Using Docker and ECS  

## Overview  
This project demonstrates how to **containerize an application** using **Docker** and deploy it on **AWS ECS (Elastic Container Service)** with a secure and scalable architecture. The workflow involves setting up a **GitHub repository**, building and pushing a **Docker container** to **Docker Hub** and **Amazon Elastic Container Registry (ECR)**, and configuring an **AWS infrastructure** that includes **VPC, Security Groups, ECS Cluster, Load Balancer, and Route 53**.  

By following this guide, I was be able to:  
✅ Build and manage **Docker containers**  
✅ Push and store container images in **Docker Hub** and **AWS ECR**  
✅ Set up a **secure AWS environment** with **VPC, Security Groups, and Load Balancer**  
✅ Deploy and scale your application using **AWS ECS Fargate**  
✅ Secure your domain and web communications using **Route 53** and **AWS Certificate Manager**  

---

## Prerequisites  
Before starting, I ensure to installe on my computer:  
- **Git** and **Visual Studio Code**  
- **GitHub account** (Create a Key Pair and add the **Public SSH Key** to GitHub)  
- **Docker Hub account**  
- **Docker**  
- **AWS CLI** (Create **IAM User** and Named Profile)  

---

## Steps to Deploy a Containerized Application on AWS  

### 1. Local Setup  
1. **Create a GitHub Repository** to store the Dockerfile  
2. **Clone the GitHub Repository** on my computer  
3. **Sign up for a Docker Hub account**  
4. **Download and Install Docker** on my computer  
5. **Create a Dockerfile**  
6. **Build the Container Image**  
7. **Start the Container**  
8. **Create a Repository in your Docker Hub account**  
9. **Push the Image to your Docker Hub repository**  

---

### 2. AWS Setup  
10. **Install AWS CLI**, create an **IAM User**, and set up a **Named Profile**  
11. **Create an Amazon ECR Repository** to store the image  
12. **Push the Image to your ECR repository**  

---

### 3. Network Configuration  
13. **Set up a Virtual Private Cloud (VPC)** with public and private subnets in **two availability zones**  
14. **Create necessary resources**, including NAT Gateway, Internet Gateway, Target Group, and Application Load Balancer using Public Subnets  
15. **Create Security Groups**  

---

### 4. Application Deployment  
16. **Set up an Application Load Balancer** to distribute web traffic to containers  
17. **Create an ECS Cluster**  
18. **Define an ECS Task Definition**  
19. **Create a Service** within the ECS Cluster  

---

### 5. Domain and Security  
20. **Use Route 53** to register a domain name and create a record set  
21. **Use AWS Certificate Manager** to secure web communications  

---

## Summary  
This deployment leverages **Docker** and **AWS ECS Fargate** to manage containerized applications efficiently. The architecture includes a **VPC with subnets**, an **application load balancer**, **Amazon ECR**, **Amazon ECS** and **security best practices** with AWS **Certificate Manager** and **Route 53**.  



---
