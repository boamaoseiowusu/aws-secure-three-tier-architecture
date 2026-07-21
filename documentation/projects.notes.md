# Project Notes

## AWS Services Used

- Amazon EC2
- Amazon VPC
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Elastic IP
- Amazon Linux 2023

---

## Security Design

- Bastion Host located in Public Subnet
- Apache Server located in Private Subnet
- SSH access restricted through Security Groups
- Private server not publicly accessible

---

## Improvements

Future enhancements include:

- Application Load Balancer
- Auto Scaling
- CloudWatch Monitoring
- AWS WAF
- HTTPS using ACM
