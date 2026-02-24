# AWS-VPC-Architecture-Project
# AWS VPC Architecture Project with ALB and Nginx Deployment

## Overview

This project demonstrates a secure cloud infrastructure deployment using Amazon Web Services (AWS). The architecture includes Virtual Private Cloud (VPC) networking with public and private subnets, Application Load Balancer (ALB), NAT Gateway, and EC2 instances running Nginx web server.

## Architecture Components

- Virtual Private Cloud (VPC) setup  
- Internet Gateway (IGW) configuration  
- Public and Private Subnets  
- Application Load Balancer (ALB)  
- NAT Gateway for private subnet internet access  
- AWS Systems Manager Session Manager  
- Nginx web server deployment  

## AWS Services Used

- Amazon VPC  
- Application Load Balancer  
- NAT Gateway  
- EC2 Instances  
- Security Groups  
- Route Tables  
- AWS Systems Manager Session Manager  

## Project Workflow

Internet Users → Internet Gateway → Application Load Balancer → Target Group → EC2 Instances (Public and Private Subnets)

## Application Deployment

- Installed Nginx web server on both EC2 instances  
- Created simple HTML pages to verify load balancing  
- Verified traffic distribution using ALB DNS endpoint  

## Security Implementation

- Private EC2 instance is not directly accessible from the internet  
- Session Manager is used for secure instance access  
- Security groups restrict inbound traffic  
- NAT Gateway provides outbound internet connectivity

## Tools and Technologies

- AWS Cloud Platform  
- Linux Server Management  
- Nginx Web Server  
- Git Version Control  

## How to Run Project

1. Create AWS VPC architecture as described  
2. Launch EC2 instances in public and private subnets  
3. Configure Application Load Balancer  
4. Install and configure Nginx  
5. Access application using ALB DNS URL  

## Future Improvements

- Implement Auto Scaling Groups  
- Add HTTPS using SSL certificates  
- Automate deployment using CI/CD pipelines  
- Containerize application using Docker

## Author

Varun Madineni
