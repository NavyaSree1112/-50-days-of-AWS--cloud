# Day 12 - Attach EBS Volume to EC2 Instance

Today I learned how to attach an Amazon Elastic Block Store (EBS) volume to an EC2 instance.

An Amazon EBS Volume is a virtual hard disk that provides persistent block storage for EC2 instances. It is used to store operating system files, applications, databases, logs, and other data. Additional EBS volumes can be attached to an EC2 instance whenever more storage is required.

In DevOps, EBS volumes are widely used to expand storage capacity, separate application data from the operating system, store databases, maintain logs, and provide reliable persistent storage for production workloads.

## Steps Performed

- Logged in to the AWS Management Console.
- Opened the **EC2 Dashboard**.
- Navigated to **Volumes** under Elastic Block Store.
- Selected the existing EBS volume.
- Clicked **Actions → Attach Volume**.
- Selected the EC2 instance **devops-ec2**.
- Used the default device name.
- Clicked **Attach Volume**.
- Verified that the volume status changed to **In-use**.

## What I Learned

- Amazon EBS provides persistent block storage for EC2 instances.
- An EBS volume acts like a virtual hard disk.
- Additional volumes can be attached to increase storage capacity.
- A volume must be in the same Availability Zone as the EC2 instance.
- Attached volumes can be detached and reattached to another EC2 instance within the same Availability Zone.
- EBS volumes support snapshots for backup and recovery.

## Difference Between EC2 and EBS

| EC2 Instance | EBS Volume |
|--------------|------------|
| Compute resource | Storage resource |
| Runs applications | Stores data |
| Uses CPU and RAM | Provides persistent storage |

## DevOps Use Cases

- Expanding server storage.
- Database storage.
- Application log storage.
- Backup and recovery.
- Persistent storage for production applications.

## Lab Status

✅ Successfully attached the EBS volume to the EC2 instance and verified that the volume status changed to **In-use**.<img width="1892" height="928" alt="Screenshot 2026-07-10 164733" src="https://github.com/user-attachments/assets/d092437a-39c8-48d4-be28-75edb5a2e522" />
