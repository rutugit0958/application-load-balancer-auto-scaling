
# Application Load Balancer with Auto Scaling (CPU-Based)

## 📌 Project Overview
This project demonstrates how to deploy a highly available and scalable web application using AWS Application Load Balancer and Auto Scaling Group.

The infrastructure automatically scales EC2 instances based on CPU utilization using CloudWatch metrics.

## 🛠️ Technologies Used
- AWS EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- CloudWatch
- Amazon Linux 2

## 🏗️ Architecture
User traffic is routed through an Application Load Balancer to EC2 instances managed by an Auto Scaling Group. CloudWatch monitors CPU usage and automatically scales instances.

## ⚙️ Implementation Steps
1. Created EC2 Launch Template with Apache installed using User Data
2. Created Target Group with health checks
3. Configured Application Load Balancer
4. Attached Auto Scaling Group to ALB
5. Implemented CPU-based auto scaling policy

## 📈 Auto Scaling Policy
- Metric: Average CPU Utilization
- Target: 50%
- Min instances: 1
- Max instances: 3

## ✅ Outcome
- High availability
- Automatic scaling
- Load balanced traffic
- Production-ready AWS architecture

## 📷 Screenshots
Refer to the screenshots folder for implementation proof.

## 👨‍💻 Author
Rutuja Patil


