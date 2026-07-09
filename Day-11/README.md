# Day 11 - Attach Elastic Network Interface (ENI) to EC2 Instance

Today I learned how to attach an Elastic Network Interface (ENI) to an Amazon EC2 instance.

An Elastic Network Interface (ENI) is a virtual network adapter for an EC2 instance. It enables communication between the EC2 instance and the Virtual Private Cloud (VPC). An ENI contains networking information such as private IP addresses, security groups, MAC address, and subnet details. A secondary ENI can be detached from one EC2 instance and attached to another within the same Availability Zone.

In DevOps, ENIs are used for network management, high availability, disaster recovery, traffic separation, and maintaining consistent network configurations across EC2 instances.

## Steps Performed

- Logged in to the AWS Management Console.
- Opened the EC2 Dashboard.
- Navigated to **Network Interfaces**.
- Selected the existing network interface **devops-eni**.
- Clicked **Actions → Attach**.
- Selected the EC2 instance **devops-ec2**.
- Clicked **Attach**.
- Verified that the network interface was successfully attached to the EC2 instance.

## What I Learned

- ENI is a virtual network interface for an EC2 instance.
- Every EC2 instance requires a primary network interface.
- Additional ENIs can be attached depending on the instance type.
- ENIs contain private IP addresses, security groups, MAC address, and subnet information.
- A secondary ENI can be detached and attached to another EC2 instance within the same Availability Zone.
- ENIs provide flexible networking and simplify infrastructure management.

## Components of an ENI

- Private IPv4 Address
- Secondary Private IP Addresses
- Security Groups
- MAC Address
- Subnet
- Elastic IP Association (Optional)

## Benefits

- Flexible network management.
- Supports high availability.
- Simplifies disaster recovery.
- Enables multiple network interfaces.
- Easy migration of network settings.

## Difference Between ENI and Elastic IP

| Elastic Network Interface (ENI) | Elastic IP (EIP) |
|---------------------------------|------------------|
| Virtual network adapter | Static public IPv4 address |
| Stores network configuration | Provides a fixed public IP |
| Can contain private IPs and security groups | Can be associated with only one EC2 instance at a time |
| Can be detached and reattached | Can be disassociated and reassociated |

## DevOps Use Cases

- Multi-tier application architecture.
- High availability.
- Disaster recovery.
- Traffic isolation.
- Network migration.
- Production server networking.

## Lab Status

✅ Successfully attached the Elastic Network Interface (**devops-eni**) to the EC2 instance (**devops-ec2**) and verified the attachment.<img width="1906" height="956" alt="Screenshot 2026-07-09 222918" src="https://github.com/user-attachments/assets/57e79ca9-418d-4040-9010-aaed42682109" />
