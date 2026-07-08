Day 10 - Attach Elastic IP to EC2 Instance
Today I learned how to attach an Elastic IP (EIP) to an Amazon EC2 instance.
An Elastic IP (EIP) is a static public IPv4 address provided by AWS. Unlike a regular public IP, an Elastic IP remains the same even if the EC2 instance is stopped and started. It can also be detached from one instance and associated with another, making it ideal for production workloads that require a consistent public IP address.
In DevOps, Elastic IPs are commonly used for web servers, application servers, bastion hosts, and disaster recovery because they ensure uninterrupted access to services.
Steps Performed
Logged in to the AWS Management Console.
Opened the EC2 Dashboard.
Navigated to Elastic IPs.
Selected the existing Elastic IP devops-ec2-eip.
Clicked Actions → Associate Elastic IP address.
Selected the EC2 instance devops-ec2.
Associated the Elastic IP with the instance.
Verified that the Elastic IP was successfully attached.
What I Learned
Elastic IP is a static public IPv4 address.
It does not change after stopping and starting an EC2 instance.
Elastic IPs can be moved between EC2 instances.
They provide a permanent public endpoint for applications.
Elastic IPs improve availability and simplify DNS management.
AWS may charge for Elastic IPs that are allocated but not associated with a running instance.
Difference Between Public IP and Elastic IP
Public IP
Elastic IP
Assigned automatically
Allocated manually
Changes after stop/start
Remains the same
Temporary
Static and reusable
DevOps Use Cases
Hosting production web applications.
Maintaining a fixed public IP address.
Disaster recovery and failover.
Bastion (Jump) servers.
High availability architectures.
Lab Status
✅ Successfully attached the Elastic IP devops-ec2-eip to the EC2 instance devops-ec2 and verified the association.<img width="1891" height="973" alt="Screenshot 2026-07-08 223523" src="https://github.com/user-attachments/assets/4551faa9-0287-4fe8-aa15-56e27cade2a4" />
