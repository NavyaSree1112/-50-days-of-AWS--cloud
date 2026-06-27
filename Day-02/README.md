# Day 2 - Create Security Group

## Objective
Create an AWS Security Group to control inbound traffic for EC2 instances.

## What is a Security Group?

A Security Group is a virtual firewall that controls the inbound and outbound traffic of an EC2 instance.

## Why Do We Use Security Groups?

- Protect EC2 instances from unauthorized access.
- Control which users or services can connect.
- Allow only required network traffic.
- Improve cloud security.

## Key Concepts

### Inbound Rules
Control traffic entering the EC2 instance.

### Outbound Rules
Control traffic leaving the EC2 instance.

## Ports Used

| Port | Service | Purpose |
|------|---------|---------|
| 22 | SSH | Remote login to Linux server |
| 80 | HTTP | Access websites |

## Task Performed

- Security Group Name: `devops-sg`
- Description: `Security group for Nautilus App Servers`
- VPC: Default VPC
- Added HTTP (Port 80) from `0.0.0.0/0`
- Added SSH (Port 22) from `0.0.0.0/0`

## Learning Outcome

- Learned how Security Groups protect EC2 instances.
- Understood inbound and outbound traffic.
- Learned the importance of ports 22 and 80.
