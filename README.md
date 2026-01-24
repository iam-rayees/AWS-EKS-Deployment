# Production-Grade Kubernetes Deployment on AWS

## Overview

This repository captures a real-world DevOps implementation focused on running containerized applications **reliably at scale** on AWS using Kubernetes.

The goal of this project is not just to deploy workloads, but to design an architecture that reflects **production expectations** including scalability, traffic management, security, and operational stability.

Every step in this repository is documented with clarity so the setup can be reproduced, understood, and improved.

---

## Tech Stack

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=for-the-badge&logo=amazon-eks&logoColor=white)
![ALB](https://img.shields.io/badge/AWS%20ALB-8C4FFF?style=for-the-badge&logo=amazon-aws&logoColor=white)
![NLB](https://img.shields.io/badge/AWS%20NLB-8C4FFF?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Route53](https://img.shields.io/badge/Route%2053-8C4FFF?style=for-the-badge&logo=amazon-route53&logoColor=white)
![ACM](https://img.shields.io/badge/AWS%20ACM-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)

---

## What This Project Covers

- End-to-end Kubernetes cluster setup using Amazon EKS  
- Container image management with Amazon ECR  
- Deployment of multiple services including web apps, workers, Redis, and PostgreSQL  
- Service exposure using Application Load Balancer and Network Load Balancer  
- Traffic routing and service discovery through Kubernetes Services and Ingress  
- Secure DNS based access using Route53 and ACM  
- Realistic production considerations around networking, scaling, and observability  

---

## Architecture Highlights

- EKS cluster with managed node groups
- Stateless and stateful workloads deployed via Kubernetes Deployments
- Internal and external service exposure patterns
- Load balancer integration with Kubernetes
- Cloud native traffic flow and certificate management

This setup closely mirrors how modern teams operate Kubernetes workloads in real production environments.

---

## Why This Repository Exists

Most examples stop at “pods running successfully”.

This project goes a step further by focusing on:
- How traffic reaches the cluster
- How services communicate internally
- How external users access applications securely
- How scalability and reliability are achieved in practice

It is built to reflect **how things are actually done**, not just how they are demonstrated.

---

## Who This Is For

- DevOps and Cloud Engineers
- Kubernetes learners moving beyond basics
- Engineers preparing for real production environments
- Anyone wanting hands-on exposure to AWS EKS architectures

---

## Final Note

This repository represents practical learning through implementation.

Kubernetes is powerful  
AWS makes it scalable  
Architecture makes it production ready  

Still building. Still learning. Always improving.
