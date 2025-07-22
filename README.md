# ec2-cloudwatch-monitoring
 Flask app hosted on AWS EC2 with CloudWatch agent setup for system metrics monitoring

# 🚀 EC2 + CloudWatch Monitoring

This project demonstrates how to deploy a Python Flask application on an AWS EC2 instance and configure Amazon CloudWatch Agent to monitor system-level metrics like CPU, memory, and disk.

## 📌 Project Goal

- Host a basic Python web app on EC2
- Install and configure the CloudWatch agent
- Collect system metrics and trigger alarms
- Send email alerts using Amazon SNS

## 🛠️ Technologies Used

- Amazon EC2 (Amazon Linux 2)
- Amazon CloudWatch (Monitoring & Alarms)
- IAM (EC2 instance role)
- Python 3 + Flask
- SNS for notifications

## 📁 Project Structure
ec2-cloudwatch-monitoring/
├── app.py
├── config.json
└── README.md

# 📝 Steps Performed

1. Launched an EC2 instance with required ports (22, 80)
2. Installed Python and Flask
3. Created a basic web app (app.py)
4. Installed and configured the CloudWatch agent (config.json)
5. Verified metrics in CloudWatch Dashboard
6. Set an alarm on CPUUtilization > 60%
7. Created an SNS topic for alerts

## 🧠 Key Learnings

- Deploying and managing EC2 instances
- Monitoring real-time system performance
- Integrating CloudWatch with custom config
- Using Flask to run lightweight apps
- 
