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

### High Level Project Diagram:

<img width="968" height="393" alt="image" src="https://github.com/user-attachments/assets/01262e3e-1def-4926-a0e4-cb62ec3fc532" />

-------------------------------------------------------------------------------------------------------------------------------------

### High Level Tasks/Steps:

-	Fork the Application Source Code GitHub Repository.
-	Launch EC2 instance, install Docker and Build Docker image.
-	Create Amazon ECR Repository, Create IAM Role and Create User Access Key.
-	Login to Amazon ECR from CLI and Push Docker Image to ECR Repo.
-	Create ECS Cluster, Task Definition, Service, Load Balancer.
-	Validate the Deployment of Web App.

## Output Results Screenshots:

Build the docker image from Dockerfile present at App source code repository:

<img width="973" height="193" alt="image" src="https://github.com/user-attachments/assets/dda2a273-d0e3-4904-a724-61517a15fd8a" />

---------------------------------------------------------------------------------------------------------------------------------

<img width="960" height="135" alt="image" src="https://github.com/user-attachments/assets/0f429c4c-f04c-40bc-a0aa-2caf7668badb" />

----------------------------------------------------------------------------------------------------------------------------------

<img width="968" height="192" alt="image" src="https://github.com/user-attachments/assets/349be476-bd4e-4f11-b8c9-5ff8d8d3aae9" />

-----------------------------------------------------------------------------------------------------------------------------------

Create Amazon ECR Repository, Create IAM Role and Create User Access Key.

<img width="960" height="316" alt="image" src="https://github.com/user-attachments/assets/5c5b1d38-d76e-4391-a361-6e9569551a93" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="948" height="689" alt="image" src="https://github.com/user-attachments/assets/0f22e065-adc4-4ca2-8f58-bf64335071d3" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="956" height="257" alt="image" src="https://github.com/user-attachments/assets/a9dfe10b-c972-4d1b-9aff-10e37cbca78c" />

------------------------------------------------------------------------------------------------------------------------------------

The web-app image with tag: latest has been pushed to ECR repo from EC2 machine.

<img width="864" height="312" alt="image" src="https://github.com/user-attachments/assets/f3e461a8-f0d6-4159-aff7-c01a8fb28a90" />

------------------------------------------------------------------------------------------------------------------------------------

Create ECS Cluster, Task Definition, Service, Load Balancer:


<img width="957" height="341" alt="image" src="https://github.com/user-attachments/assets/f2653510-4ec1-4896-9a92-f7c65522b30d" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="962" height="356" alt="image" src="https://github.com/user-attachments/assets/ab0b4c1c-aa50-42f8-bb71-bdf57dfb46b2" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="957" height="364" alt="image" src="https://github.com/user-attachments/assets/648fe87e-224c-4cf2-bdad-d47eb10d0546" />

-------------------------------------------------------------------------------------------------------------------------------------

Under Amazon ECS, Service has been created and deployed successfully:


<img width="956" height="355" alt="image" src="https://github.com/user-attachments/assets/29962397-197d-4db1-8608-169f4276fc20" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="961" height="235" alt="image" src="https://github.com/user-attachments/assets/47605ef2-7c0f-46f7-9da4-e9f22003c28a" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="958" height="402" alt="image" src="https://github.com/user-attachments/assets/fe45a4c1-69a7-4e79-b018-4159353c3609" />

-------------------------------------------------------------------------------------------------------------------------------------

Copy the DNS name: alb-web-app-1955152254.us-east-1.elb.amazonaws.com

Final Web Application URL: http://alb-web-app-1955152254.us-east-1.elb.amazonaws.com:8080/LoginWebApp-1/

<img width="966" height="468" alt="image" src="https://github.com/user-attachments/assets/64c8c4b8-b0d1-4cb3-a032-1ff84f568271" />

------------------------------------------------------------------------------------------------------------------------------------

Open the Browser and hit the App URL to access the Web Application.

The Web-Application gets accesssed successfully,  Login page loaded on browser:

<img width="968" height="381" alt="image" src="https://github.com/user-attachments/assets/47de5cb6-e2f3-40ec-8a5b-c124b2b1952d" />

-----------------------------------------------------------------------------------------------------------------------------------

**By following the above steps, the Project successfully deploys the Dockerized Web-Application using AWS services, including Amazon ECS, Amazon ECR, AWS Fargate and Load Balancer. This deployment enables** **serverless operation, reducing infrastructure management while ensuring the application can handle fluctuating traffic demands seamlessly and securely.**



