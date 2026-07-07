# Sauda-CV-Assistant-multi-cloud
# Sauda CV Assistant 

An AI-driven platform designed to generate professional, ATS-friendly CVs through an interactive chatbot interface. 

## Architectural Overview
This project showcases a highly available Active-Active Multi-Cloud Architecture blueprint designed to bridge AWS and GCP environments, ensuring zero single points of failure, high scalability, and seamless cloud failover.

>  Implementation Note: While the cross-cloud architecture was fully designed and mapped in the infrastructure blueprint, the live deployment, provisioning, and simulation were entirely executed on AWS due to individual account constraints on the GCP platform.

## Infrastructure & Tech Stack
- Infrastructure as Code (IaC): Environment automated and provisioned utilizing Terraform.
- Containerization & Orchestration: Microservices containerized with Docker and deployed via AWS ECS Fargate (Serverless application management).
- Traffic Management & High Availability: Architected via AWS Route 53 utilizing weighted routing and active health checks for cross-cloud failover simulation.
- CI/CD Pipeline: Automated code validation and deployment workflows using GitHub Actions.

## Key Engineering Focus
- Eliminating Vendor Lock-in through multi-cloud design concepts.
- Implementing Secure Networking architectures.
- Ensuring Serverless efficiency to optimize computing resource costs.
