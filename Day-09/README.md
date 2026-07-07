# Day 09 - Enable Termination Protection for EC2 Instance

Today I learned how to enable **Termination Protection** for an Amazon EC2 instance.

Amazon EC2 (Elastic Compute Cloud) provides virtual servers in the AWS cloud. These instances can host applications, databases, websites, and other services. Since production servers are critical, AWS provides **Termination Protection** to prevent them from being accidentally deleted.

Termination Protection is an instance attribute that blocks accidental termination requests. If someone tries to terminate a protected EC2 instance, AWS denies the request until the protection is disabled.

In DevOps, protecting production infrastructure is an important best practice because accidental deletion of servers can cause application downtime, data loss, and service interruptions.

## AWS Service Used

- Amazon EC2

## Navigation Path

EC2 Dashboard
→ Instances
→ Select EC2 Instance
→ Actions
→ Instance Settings
→ Change Termination Protection
→ Enable
→ Save

## What I Learned

- Amazon EC2 provides scalable virtual servers in the cloud.
- Termination Protection prevents an EC2 instance from being accidentally terminated.
- It helps protect important production servers from accidental deletion.
- Termination Protection is different from Stop Protection.
- Stop Protection prevents an instance from being stopped.
- Termination Protection prevents an instance from being terminated (deleted).
- Protecting cloud resources is an important DevOps best practice.

## Why is it Important in DevOps?

- Prevents accidental deletion of production servers.
- Improves infrastructure reliability.
- Reduces the risk of downtime.
- Helps protect critical applications and services.
- Supports safe cloud infrastructure management.

## Lab Status

✅ Learned how to enable Termination Protection for an EC2 instance using the AWS Management Console.<img width="1888" height="972" alt="Screenshot 2026-07-07 233125" src="https://github.com/user-attachments/assets/ec07e6b8-5f64-4f4f-879c-38d6bfc1e600" />
