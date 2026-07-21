# ☁️ AWS Secure Three-Tier Architecture

![Architecture](architecture/aws-three-tier-architecture.png)

---

## 📌 Project Overview

This project demonstrates the design and deployment of a secure AWS Three-Tier Architecture following cloud networking and security best practices.

The environment consists of a custom Amazon VPC with public and private subnets. Administrative access is provided through a Bastion Host located in the public subnet, while the Apache web server resides securely in a private subnet. Internet connectivity for private resources is enabled through a NAT Gateway, and traffic is controlled using Route Tables and Security Groups.

This project showcases practical AWS infrastructure deployment, Linux administration, secure networking, and troubleshooting skills.

---

## 🎯 Project Objectives

- Design a secure Virtual Private Cloud (VPC)
- Implement public and private subnet segmentation
- Deploy a Bastion Host for secure administration
- Install and configure Apache on Amazon Linux 2023
- Restrict direct internet access to private resources
- Configure outbound internet access through a NAT Gateway
- Apply least-privilege security using Security Groups
- Document the deployment process for future reference

---

# 🏗️ Architecture Diagram

![AWS Architecture](architecture/aws-three-tier-architecture.png)

---

# ☁️ AWS Services Used

| Service | Purpose |
|----------|---------|
| Amazon VPC | Private Cloud Network |
| EC2 | Virtual Servers |
| Internet Gateway | Public Internet Access |
| NAT Gateway | Outbound Internet for Private Subnet |
| Route Tables | Traffic Routing |
| Security Groups | Instance Firewall |
| Elastic IP | Public Address |
| Amazon Linux 2023 | Operating System |
| Apache HTTP Server | Web Hosting |

---

# 🌐 Architecture Components

- Virtual Private Cloud (VPC)
- Public Subnet
- Private Subnet
- Internet Gateway
- NAT Gateway
- Bastion Host
- Private Apache Web Server
- Route Tables
- Security Groups

---

# 🔄 Network Traffic Flow

```text
Internet
     │
     ▼
Internet Gateway
     │
     ▼
Public Subnet
     │
     ├─────────────┐
     ▼             ▼
Bastion Host   NAT Gateway
                     │
                     ▼
             Private Subnet
                     │
                     ▼
          Apache Web Server
```

---

# 📸 Project Gallery

## 🌍 VPC Overview

![VPC](screenshots/01-vpc-overview.png)

---

## 🌐 Public & Private Subnets

![Subnets](screenshots/02-public-private-subnets.png)

---

## 🚪 Internet Gateway

![Internet Gateway](screenshots/03-internet-gateway.png)

---

## 🛣️ Public Route Table

![Public Route Table](screenshots/04-public-route-table.png)

---

## 🔒 Private Route Table

![Private Route Table](screenshots/06-private-route-table.png)

---

## 🌍 NAT Gateway

![NAT Gateway](screenshots/08-nat-gateway.png)

---

## 💻 EC2 Instances

![EC2](screenshots/09-ec2-instances.png)

---

## 🛡️ Security Groups

![Security Groups](screenshots/10-security-groups.png)

---

## ⚙️ Apache Running

![Apache](screenshots/11-apache-running.png)

---

## 🌐 Custom Web Page

![Website](screenshots/12-custom-webpage.png)

---

# 🚀 Deployment Steps

1. Created a custom Amazon VPC.
2. Configured public and private subnets.
3. Attached an Internet Gateway.
4. Configured public route table.
5. Created and configured a NAT Gateway.
6. Configured the private route table.
7. Launched a Bastion Host in the public subnet.
8. Launched a private EC2 instance.
9. Configured Security Groups.
10. Connected to the private server through the Bastion Host using SSH.
11. Installed Apache HTTP Server.
12. Created a custom HTML landing page.
13. Verified Apache functionality.

---

# 🔐 Security Best Practices

- Bastion Host used for secure administration
- Private server isolated from direct internet access
- Least privilege Security Group rules
- Public and private subnet separation
- Controlled outbound traffic using NAT Gateway
- Secure SSH access

---

# 🛠️ Troubleshooting

Challenges encountered during this project included:

- SSH connection failures
- EC2 Instance Connect limitations
- Private subnet connectivity
- Route Table configuration
- Security Group configuration
- Apache installation on Amazon Linux 2023

Each issue was successfully resolved through AWS documentation and Linux troubleshooting.

---

# 📚 Skills Demonstrated

- AWS Cloud Infrastructure
- Amazon EC2
- Amazon VPC
- Linux Administration
- Bash Commands
- SSH
- Apache HTTP Server
- Cloud Networking
- Network Troubleshooting
- Security Groups
- Route Tables
- NAT Gateway
- Bastion Host
- Infrastructure Documentation

---

# 📈 Future Improvements

- Application Load Balancer
- Auto Scaling Group
- CloudWatch Monitoring
- SNS Notifications
- AWS WAF
- HTTPS using ACM
- Infrastructure as Code (Terraform)

---

# 👨‍💻 About Me

**Boama Osei-Owusu**

Cloud & Infrastructure Professional

- CompTIA Security+
- CompTIA Cloud+
- U.S. Army Reserve (92A Automated Logistical Specialist)
- Secret Security Clearance
- Hands-on AWS Cloud Projects

### Connect with me

**LinkedIn**

https://www.linkedin.com/in/boama-osei-owusu-526628b5

**GitHub**

https://github.com/boamaoseiowusu
