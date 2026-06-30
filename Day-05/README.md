Day 05 - Create an Amazon EBS GP3 Volume

Today I learned how to create an Amazon Elastic Block Store (EBS) GP3 Volume for an EC2 instance.

Amazon EBS is a block storage service provided by AWS that offers persistent storage for EC2 instances. A GP3 (General Purpose SSD) volume delivers high performance, low latency, and cost-effective storage for a wide range of workloads. It is the recommended SSD volume type for most cloud applications.

In DevOps, EBS volumes are used to store operating systems, application files, databases, logs, backups, and other important data. Since EBS volumes are persistent, the data remains available even if an EC2 instance is stopped or restarted.

Steps Performed

- Logged into the AWS Management Console.
- Opened the Amazon EC2 service.
- Navigated to Elastic Block Store → Volumes.
- Clicked Create Volume.
- Entered the volume name as devops-volume.
- Selected the volume type as GP3 (General Purpose SSD).
- Set the volume size to 2 GiB.
- Chose the required Availability Zone.
- Created the volume.
- Verified that the volume status changed to Available.

What I Learned

- Amazon EBS provides persistent block storage for EC2 instances.
- GP3 is the latest General Purpose SSD volume type recommended for most workloads.
- A volume must be created in the same Availability Zone as the EC2 instance where it will be attached.
- Tags can be used to assign meaningful names to AWS resources.
- EBS volumes are commonly used for operating systems, application data, databases, backups, and log storage.
- Persistent storage ensures that data is retained even after an EC2 instance is stopped.

Commands Used

No Linux commands were required. The task was completed using the AWS Management Console.

Lab Status

✅ Successfully created a 2 GiB GP3 Amazon EBS Volume named devops-volume and verified that the volume was created successfully.
