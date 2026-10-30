# Containerization & Kubernetes Deployment Challenge

## Project Overview
A web application containerized using Docker and deployed on Kubernetes (K3s) on AWS EC2.

## Technologies Used
- AWS EC2
- Ubuntu
- Docker
- Kubernetes (K3s)
- Nginx
- HTML and CSS

## Project Structure
- index.html - Web application
- Dockerfile - Docker image configuration
- deployment.yaml - Kubernetes Deployment
- service.yaml - Kubernetes NodePort Service

## Docker Build
sudo docker build -t cnd-web-app:v1 .

## Kubernetes Deployment
sudo kubectl apply -f deployment.yaml
sudo kubectl apply -f service.yaml

## Verification
- Kubernetes replicas: 2/2 available
- Application pods: 2 Running
- Service type: NodePort
- NodePort: 30080

## Application URL
http://3.26.171.122:30080

## Student Details
Name: Satish Swami
Roll Number: 202301070055
Branch: E&TC
Semester: 7
Subject: Cloud Native DevOps (MDM)
