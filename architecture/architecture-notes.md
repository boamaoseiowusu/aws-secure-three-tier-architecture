# AWS Secure Three-Tier Architecture

## Overview

This project demonstrates a secure three-tier AWS architecture using:

- Amazon VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- NAT Gateway
- Bastion Host
- Private EC2 Web Server
- Security Groups

## Security Features

- Bastion Host for secure administration
- Private EC2 has no public IP
- NAT Gateway for outbound Internet access
- Security Groups enforce least-privilege access

## Traffic Flow

Internet
↓
Internet Gateway
↓
Public Subnet
↓
Bastion Host
↓
Private EC2 Web Server
