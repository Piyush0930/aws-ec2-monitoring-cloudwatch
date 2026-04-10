# AWS EC2 Monitoring & Alert System

This project demonstrates how to monitor an AWS EC2 instance using Amazon CloudWatch and set up automated alerts for system performance metrics.

---

## 🚀 Features

- Monitor CPU utilization
- Monitor Memory usage
- Monitor Disk usage
- Collect system logs (/var/log/syslog)
- Email alerts using SNS
- Real-time monitoring using CloudWatch Agent

---

## 🏗️ Architecture

EC2 Instance → CloudWatch Agent → CloudWatch Metrics → Alarm → SNS → Email Notification

---

## ⚙️ Tools Used

- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- CloudWatch Agent
- Ubuntu Linux

---

## 📦 Installation Steps

### 1. Install CloudWatch Agent
```bash
wget https://amazoncloudwatch-agent.s3.amazonaws.com/ubuntu/amd64/latest/amazon-cloudwatch-agent.deb
sudo dpkg -i amazon-cloudwatch-agent.deb
