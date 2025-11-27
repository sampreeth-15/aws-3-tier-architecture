# AWS 3-Tier Web Application Architecture

## Overview

This project is a production-like 3-Tier Web Application deployed on Amazon Web Services (AWS).  
It follows a classic layered architecture:

- Presentation Tier (Web): Accessed through an Application Load Balancer (ALB).
- Application Tier: Web servers running on EC2 inside an Auto Scaling Group.
- Database Tier: Amazon RDS MySQL inside private subnets.

## Architecture Diagram (Description)

User → Internet → Application Load Balancer → EC2 (Private Subnets) → RDS MySQL  

All components are inside a custom VPC.

## AWS Services Used

- VPC  
- Public & Private Subnets  
- Internet Gateway  
- Route Tables  
- Security Groups  
- EC2  
- Launch Template  
- Auto Scaling Group  
- Application Load Balancer  
- RDS MySQL  
- CloudWatch  
- S3 (optional)

## App Info

A simple HTML application is deployed on EC2 instances.

## Folder Structure
aws-3-tier-architecture/
│── README.md
│── app/
│    └── index.html
└── .gitignore

## Author

- Sampreeth B S  
- GitHub: https://github.com/sampreeth-15  
- LinkedIn: https://www.linkedin.com/in/sampreeth-bs-5380b11a0  
