# Student Management System (Cloud-Native)

A cloud-native Student Management System built using microservices architecture, designed for scalability and real-world deployment.

## 🚀 Features
- Manage students, courses, and enrollments
- Microservices-based architecture
- REST APIs for integration

## 🏗️ Tech Stack
- Java (Spring Boot)
- Node.js
- Kubernetes (KIND, planned migration to EKS)
- AWS (EC2, S3, Lambda - planned)
- Docker

## ☁️ Cloud & DevOps Goals
- Deploy on Amazon EKS
- Implement CI/CD pipelines
- Infrastructure as Code (Terraform - planned)
- Monitoring with CloudWatch

## 📦 Project Status
🚧 Currently under development

## 🎯 Purpose
This project is built to gain hands-on experience with cloud-native systems, Kubernetes, and AWS services.

## 🔗 Future Enhancements
- Add authentication & authorization
- Implement autoscaling (HPA)
- Introduce API Gateway



User → API → Microservices → Database
             ↓
         Kubernetes (EKS)
             ↓
           AWS