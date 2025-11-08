# 🟠 AWS Auto-Healing Scalable Web Server (Day-3 Project)

## 🎯 Objective
Create a self-healing, scalable EC2 web infrastructure with EBS persistence, Auto Scaling, Load Balancer, and CloudWatch monitoring.

## 🧱 Architecture
![Architecture Diagram](architecture-diagram.png)

## ⚙️ AWS Components Used
- EC2
- EBS
- AMI
- Launch Template
- Application Load Balancer
- Auto Scaling Group
- CloudWatch
- SNS

## 🚀 Step-by-Step Process
Detailed in the `notes.md` file and screenshots folder.

## 📸 Proofs
All steps captured in `/screenshots` directory with filenames.

## 💬 Key Learnings
- Persistent storage via EBS
- AMI reusability
- Elastic scaling with ASG
- Monitoring & alerting via CloudWatch
- Cost-effective automation setup

## 👨‍💻 Author
Mahesh — DevOps | Cloud Enthusiast


```yaml
aws-ec2-autoscaling-monitoring-project/
│
├── README.md                 # Full documentation (we’ll fill this)
├── screenshots/              # All proof images here
│   ├── 01-ec2-launch.png
│   ├── 02-webserver-running.png
│   ├── 03-ebs-attached.png
│   ├── 04-ebs-persistent.png
│   ├── 05-custom-ami.png
│   ├── 06-launch-template.png
│   ├── 07-alb-targetgroup.png
│   ├── 08-asg-created.png
│   ├── 09-cloudwatch-alarm.png
│   ├── 10-asg-scaleout.png
│   ├── 11-sns-alert.png
│   ├── 12-cloudwatch-agent.png
│
├── architecture-diagram.png  # Final AWS setup diagram (draw.io / Lucidchart)
└── notes.md                  # Personal commands & troubleshooting
```
