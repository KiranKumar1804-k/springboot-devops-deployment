# springboot-devops-deployment

## 📌 Project Overview
This repository demonstrates my **DevOps and Cloud contribution** to a Java Spring Boot web application (Boardgame Listing Web App).  
The focus of this project is on **application deployment, CI/CD automation, containerization, cloud infrastructure, and operational support**, rather than core feature development.

The application itself is a full-stack board game database system where users can view, add, and manage board games and reviews with role-based access control.

---

## 🎯 My DevOps Contribution

- Supported deployment and runtime operations of a Spring Boot application
- Built and maintained CI/CD pipelines using Jenkins
- Dockerized the application for consistent builds across environments
- Deployed the application on AWS EC2 (Linux)
- Performed Linux-level troubleshooting (services, ports, logs, permissions)
- Integrated GitHub webhook triggers for automated builds
- Worked with configuration files, builds, and environment issues
- Ensured application availability and smooth deployments

---

## 🛠 Technologies Used

### Application Stack
- Java
- Spring Boot
- Spring MVC
- Spring Security
- JDBC
- Thymeleaf
- HTML5, CSS, JavaScript
- Bootstrap
- H2 Database (In-memory)
- JUnit
- Maven

### DevOps & Cloud
- Linux
- AWS EC2
- Jenkins
- Docker
- Git & GitHub
- GitHub Webhooks
- CI/CD Pipelines

---

## ✨ Application Features (Context)

- Full-stack web application
- Role-based authentication and authorization
- Three roles: non-members, users, managers
- Non-members can view board game lists and reviews
- Users can add board games and submit reviews
- Managers can edit and delete reviews
- CRUD operations using JDBC
- Secure login using Spring Security
- UI built with Thymeleaf and styled with Bootstrap
- Schema.sql used for initial database setup
- Thymeleaf fragments for reusable UI components

---

## 🚀 CI/CD Workflow

1. Developer pushes code to GitHub
2. GitHub webhook triggers Jenkins pipeline
3. Jenkins performs:
   - Maven build
   - Dependency resolution
   - Docker image build
4. Application is deployed to AWS EC2
5. Logs and services are monitored on the Linux server

---

## ▶️ How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/springboot-devops-deployment.git
