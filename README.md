📌 Overview

This project demonstrates the deployment of a highly available and scalable web application across AWS, GCP, and Azure.
The assignment required setting up custom networking, compute, load balancing, and auto-scaling policies to ensure redundancy, security, and fault tolerance.

🚀 Cloud Deployments
🔹 AWS

Custom VPC with public/private subnets

EC2 instances running Apache with a personal website

Application Load Balancer (ALB) for distributing traffic

Auto Scaling Group (min 2, desired 2, max 5)

Scaling policy: scale out at >60% CPU, scale in at <40% CPU

Security Groups enforcing least-privilege rules

🔹 GCP

Custom VPC network with firewall rules

VM instances deployed in Managed Instance Group

HTTP Load Balancer for traffic distribution

Auto Scaling policy configured for CPU thresholds

Verified redundancy across zones

🔹 Azure

Custom Virtual Network (VNet) with subnets

VM Scale Set with load balancer

Auto-scaling rules based on CPU utilization

Network Security Groups (NSGs) for access control

Demonstrated failover and redundancy

📂 Deliverables

📑 Assignment Questions (PDF/DOCX)

📝 My Completed Report

🖼️ Evidence

Screenshots of:

ALB distributing traffic

Minimum 2 instances running

Auto-scaling policy test (termination/restart)

VPC/VNet configuration

Security settings

🧑‍💻 Author

Kowshal Sugunarajah
Postgraduate Student – Cloud Computing @ Durham College
Ex-Amazon QA | Cloud & Database Enthusiast
