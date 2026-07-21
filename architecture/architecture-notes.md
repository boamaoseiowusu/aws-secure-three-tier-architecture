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


# Architecture Notes

## Components

- VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- NAT Gateway
- Bastion Host
- Apache Web Server

## Traffic Flow

Internet

↓

Internet Gateway

↓

Public Subnet

↓

Bastion Host

↓

Private Web Server

## Security

Only the Bastion Host accepts SSH from approved IP addresses.

The Private Web Server accepts SSH only from the Bastion Host Security Group.

Internet traffic reaches private resources only through the NAT Gateway for outbound communication.
