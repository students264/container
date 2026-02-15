# Containerized Portfolio App

## Project Overview

A responsive personal portfolio website built with **HTML, CSS, and Bootstrap**, containerized using **Docker**, and deployed on **AWS** using a scalable cloud architecture.


## Deployed Using

1. Amazon Elastic Container Registry (ECR)
2. Amazon Elastic Container Service (ECS)
3. AWS Fargate
4. AWS Application Load Balancer
5. IAM User 


## AWS Deployment Summary

- Created private ECR repository  
- Pushed Docker image to ECR with AWS CLI
- Created ECS Cluster (Fargate)  
- Defined Task Definition  
- Created ECS Service (Desired Count: 2)  
- Integrated Application Load Balancer  


## Architecture
User --> Application load balancer --> 2 ECS Farget Tasks --> Docker Container --> Portfolio App
