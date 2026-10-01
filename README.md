<h1 align="center">Hi, I'm Akhilesh 👋</h1>
<h3 align="center">Aspiring AWS Cloud & DevOps Engineer | Transitioning from Data Operations & Analytics</h3>

<p align="center">
  <a href="https://linkedin.com/in/gajula-akhilesh-cloud-engineer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:akhilesh.gajula.it@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <!-- Add your portfolio site link here -->
  <!-- <a href="https://yourportfolio.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"></a> -->
</p>

---

### 🚀 About Me

I'm a Cloud & DevOps Engineer in the making, transitioning from a 4-year background in MIS / Data Operations as a Research Associate (2022–2026). Alongside full-time work, I completed my B.Tech in Electrical & Electronics (2022–2025).

During my time in Data Operations, I developed a strong interest in infrastructure and automation — which led me into DevOps. Since then, I've built and deployed several production-style projects covering the full stack: containerized microservices, Kubernetes clusters, multi-environment CI/CD pipelines, and cloud infrastructure on AWS.

Currently looking for opportunities as a **Cloud / DevOps Engineer** where I can apply this hands-on foundation.

📄 [Resume](#) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/gajula-akhilesh-cloud-engineer)

---

### 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white">
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
</p>

---

### 📌 Hands-on Projects

**[Cloud-Native-E-Commerce-Deployment&CI/CD-on-AWS-EKS](https://github.com/akhileshgajulaa/Project-12-Cloud-Native-E-Commerce-Application-Deployment-CI-CD-on-AWS-EKS)**
A 3-tier e-commerce app (React, Spring Boot, MySQL) deployed to Amazon EKS with Helm, with Terraform provisioning the AWS infrastructure.
A GitHub Actions pipeline runs SonarQube and Trivy, pushes images to ECR, and deploys to EKS. Pods autoscale with HPA, and Prometheus and Grafana handle monitoring.

**[Production-Style-3-Tier-Employee-Management-System-on-Amazon-EKS](https://github.com/akhileshgajulaa/Project-11-Production-Style-3-Tier-Employee-Management-System-on-Amazon-EKS)**
A React, Spring Boot (JWT) and MySQL app deployed on EKS with hand-written Kubernetes manifests. The MySQL StatefulSet is backed by EBS, and an ALB Ingress routes / to the frontend and /api to the backend.
It also uses HPA, PodDisruptionBudgets and NetworkPolicies for production-style resilience.

**[Docker Microservices Project](https://github.com/akhileshgajulaa/Project-9-Docker_Microservices_Project)**
Three Spring Boot microservices (user, order, payment) run behind an Nginx reverse proxy. Multi-stage Docker builds and Docker Compose bring up the whole stack with one command.
Nginx is the only public entry point, and the services talk to each other over a custom Docker network using DNS names.

**[Multi-Environment CI/CD with GitHub Actions](https://github.com/akhileshgajulaa/Project-8-CI-CD-Pipeline-with-GitHub-Actions-SonarQube-Nexus-Tomcat)**
A GitHub Actions pipeline builds a Java/Maven WAR once and promotes the same artifact through DEV → TEST → PREPROD → PROD. Each environment is a Tomcat server on AWS EC2.
Each stage depends on the previous one, so a failure stops the pipeline before PROD. Deployment uses the Tomcat Manager API with environment-scoped GitHub secrets.

**[Java Web App on AWS EC2 with Apache Tomcat](https://github.com/akhileshgajulaa/Project-6-Java-Web-Application-on-AWS-EC2-using-Apache-Tomcat-/tree/master/java-maven-tomcat-deployment)**
A Java Maven web application deployed manually to an AWS EC2 instance running Apache Tomcat. It covers the basic EC2 setup, build, and WAR deployment workflow.

**[Terraform 3-Tier Architecture](https://github.com/akhileshgajulaa/Project-5-Terraform_3_tire_Architecture/tree/master/three-tier-aws-terraform)**
A three-tier AWS architecture (presentation, application and database layers) defined entirely as code with Terraform. It makes the infrastructure repeatable and version-controlled instead of console-built.

**[AWS Highly Available Java Web App](https://github.com/akhileshgajulaa/Project-4_aws_highly_available_java_webapp/tree/master/aws-highly-available-java-webapp/aws-highly-available-java-webapp)**
A Java web application deployed on AWS with a highly available design, most likely across multiple Availability Zones with load balancing and auto scaling. It shows how to avoid a single point of failure.

**[Serverless Employee App (AWS Lambda)](https://github.com/akhileshgajulaa/Project-2-Lambda_serverless)**
A serverless employee application built on AWS Lambda, so there are no servers to manage. It shows event-driven, pay-per-use architecture.

