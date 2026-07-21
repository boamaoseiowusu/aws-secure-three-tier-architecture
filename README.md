# aws-secure-three-tier-architecture
Built a secure three-tier AWS architecture using VPC, Public &amp; Private Subnets, Bastion Host, NAT Gateway, Apache Web Server, and Security Groups.
AWS Secure Three-Tier Architecture
Project Overview

This project demonstrates the deployment of a secure three-tier architecture in Amazon Web Services (AWS) using industry best practices.

The environment was designed to simulate a production-ready network where public-facing resources are separated from backend application servers through multiple security layers.

The architecture includes:

Virtual Private Cloud (VPC)
Public and Private Subnets
Internet Gateway
NAT Gateway
Bastion Host
Private EC2 Web Server
Route Tables
Security Groups
Apache Web Server
Architecture

(Insert your architecture diagram here once we create it.)

Technologies Used
Amazon EC2
Amazon VPC
Internet Gateway
NAT Gateway
Route Tables
Security Groups
Amazon Linux 2023
Apache HTTP Server
SSH
GitHub
Architecture Components
Public Tier
Bastion Host
Internet Gateway
Public Route Table

Purpose:

Provides secure administrative access to the private network.

Private Tier

Private EC2 Server

Apache Web Server

Purpose:

Hosts the application while remaining inaccessible from the Internet.

Networking
Custom VPC
Public Subnet
Private Subnet
NAT Gateway
Route Tables
Security

Implemented security best practices including:

SSH restricted through Security Groups
Private server inaccessible from the Internet
Bastion Host used as secure jump server
Private subnet outbound Internet through NAT Gateway
Principle of least privilege
Deployment Steps
Step 1

Created a custom VPC.

Step 2

Created Public and Private Subnets.

Step 3

Attached an Internet Gateway.

Step 4

Configured Route Tables.

Step 5

Created a NAT Gateway.

Step 6

Launched Bastion Host.

Step 7

Launched Private EC2 Instance.

Step 8

Configured Security Groups.

Step 9

Installed Apache.

Step 10

Verified application using localhost.

Screenshots
Step	Screenshot
VPC	screenshots/01-vpc-overview.png
Subnets	screenshots/02-public-private-subnets.png
Internet Gateway	screenshots/03-internet-gateway.png
Public Route Table	screenshots/04-public-route-table.png
Route Association	screenshots/05-public-route-association.png
Private Route Table	screenshots/06-private-route-table.png
Private Route Association	screenshots/07-private-route-association.png
NAT Gateway	screenshots/08-nat-gateway.png
EC2 Instances	screenshots/09-ec2-instances.png
Security Groups	screenshots/10-security-groups.png
Apache Running	screenshots/11-apache-running.png
Custom Web Page	screenshots/12-custom-webpage.png
Resource Map	screenshots/13-resource-map.png
Skills Demonstrated
AWS Networking
VPC Design
Cloud Security
EC2 Administration
Linux Administration
SSH
Apache Configuration
Infrastructure Design
Troubleshooting
Cloud Architecture
Learning Summary

During this project I learned how enterprise AWS environments isolate public and private workloads using VPC networking. I configured secure routing, deployed a Bastion Host for administrative access, implemented a NAT Gateway for outbound connectivity, and installed Apache on a private EC2 instance. This project strengthened my understanding of cloud networking, Linux administration, and AWS security best practices.

Future Improvements
Application Load Balancer
Auto Scaling Group
RDS Database
CloudWatch Monitoring
AWS Systems Manager
AWS WAF
Route53
SSL/TLS
CloudFront
Created By

Boama Osei-Owusu

AWS Cloud Portfolio

Dallas, Texas
