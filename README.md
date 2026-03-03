# Deployment of Web Application using AWS Serverless Stack: Amazon ECS, ECR, Fargate

**Objective:** To showcase the end-to-end process of containerizing a simple web application using AWS serverless stack and ensure reliable application deployment.

**Real-time Scenario:** CloudServ Solutions, a fast-growing tech startup, offers digital transformation solutions with a focus on serverless architecture for agile development.
To enhance client experiences and streamline operations, CloudServ Solutions is deploying a critical customer-facing web application. This application must support high availability, scalability, and efficient resource management as part of the company's commitment to adopting serverless technologies.
As a DevOps engineer at CloudServ Solutions, you are responsible for deploying this Dockerized application using AWS services, including Amazon ECS, Amazon ECR, and AWS Fargate. This deployment will enable serverless operation, reducing infrastructure management while ensuring the application can handle fluctuating traffic demands seamlessly and securely.

### Major Tools, Service, Environment Used in This Project:

- Amazon ECR (Elastic Container Registry)
- Amazon ECS (Elastic Container Service)
- AWS Fargate
- AWS Application Load Balancer
- Docker

### High Level Diagram:

<img width="968" height="393" alt="image" src="https://github.com/user-attachments/assets/01262e3e-1def-4926-a0e4-cb62ec3fc532" />

### High Level Tasks/Steps:

-	Fork the Application Source Code GitHub Repository.
-	Launch EC2 instance, install Docker and Build Docker image.
-	Create Amazon ECR Repository, Create IAM Role and Create User Access Key.
-	Login to Amazon ECR from CLI and Push Docker Image to ECR Repo.
-	Create ECS Cluster, Task Definition, Service, Load Balancer.
-	Validate the Deployment of Web App.









