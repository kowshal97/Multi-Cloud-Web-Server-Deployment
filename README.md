# 🌐 Multi-Cloud Web Application Deployment – Assignment 2  

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)  
![Cloud](https://img.shields.io/badge/Cloud-AWS%20%7C%20GCP%20%7C%20Azure-orange)  
![Architecture](https://img.shields.io/badge/Design-High%20Availability-blue)  
![Scaling](https://img.shields.io/badge/AutoScaling-Enabled-success)  
![Database](https://img.shields.io/badge/Database-PostgreSQL-lightblue)  

---

## 📌 Overview  
This project demonstrates the deployment of a **highly available and scalable web application** across **AWS, GCP, and Azure**.  
The project required setting up **custom networking, compute, load balancing, and auto-scaling policies** to ensure **redundancy, security, and fault tolerance**.  

---

## 🚀 Cloud Deployments  

### 🔹 AWS  
- Custom **VPC** with public/private subnets  
- **EC2 instances** running Apache with a personal website  
- **Application Load Balancer (ALB)** for distributing traffic  
- **Auto Scaling Group** (min: 2, desired: 2, max: 5)  
- Scaling policy: **scale out at >60% CPU, scale in at <40% CPU**  
- **Security Groups** enforcing least-privilege rules  

### 🔹 GCP  
- Custom **VPC network** with firewall rules  
- **VM instances** deployed in Managed Instance Group  
- **HTTP Load Balancer** for traffic distribution  
- **Auto Scaling policy** configured for CPU thresholds  
- Verified **redundancy across zones**  

### 🔹 Azure  
- Custom **Virtual Network (VNet)** with subnets  
- **VM Scale Set** with load balancer  
- **Auto-scaling rules** based on CPU utilization  
- **Network Security Groups (NSGs)** for access control  
- Demonstrated **failover and redundancy**  

---

## 📂 Repository Contents  
→ Detailed documentation with steps and screenshots  
📝 [Multi Cloud](https://github.com/kowshal97/Multi-Cloud-Web-Server-Deployment/raw/main/Multi%20Cloud.docx)  

---

## 🧰 Technologies Used  
- ☁️ **AWS** → VPC, EC2, ALB, RDS, Auto Scaling  
- ☁️ **GCP** → VPC, Instance Groups, HTTP Load Balancer, Cloud SQL  
- ☁️ **Azure** → VNet, VMSS, Load Balancer, Azure Database  
- 🗄️ **PostgreSQL**  
- 🐧 **Linux (Ubuntu / Amazon Linux 2)**  

---

## 🎯 Key Learnings  
- ✅ Learned **multi-cloud deployment practices**  
- ✅ Implemented **load balancing + auto-scaling** on 3 providers  
- ✅ Practiced **redundancy and high availability**  
- ✅ Gained **hands-on experience with AWS, GCP, and Azure**  

---

## 👤 Author  
**Kowshal Sugunarajah**  
🎓 Postgraduate Student – Cloud Computing @ Durham College  
💼 Ex-QA at Amazon | ☁️ Cloud Enthusiast | 🗄️ Database & Automation Tester  
