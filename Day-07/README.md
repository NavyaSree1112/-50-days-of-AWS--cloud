Day 07 - Change EC2 Instance Type

Today I learned how to change the instance type of an Amazon EC2 instance.

An EC2 instance type determines the CPU, memory, storage, and networking capacity of a virtual machine. AWS allows us to change the instance type based on application requirements. If an instance is underutilized, switching to a smaller instance type helps reduce costs, while upgrading to a larger instance type improves performance when more resources are needed.

In this lab, I changed the instance type of an existing EC2 instance from t2.micro to t2.nano. Before making the change, I ensured the instance status checks were completed, stopped the instance, modified the instance type, started it again, and verified that it was running successfully.

What I Learned
EC2 instance types define the hardware configuration of a virtual machine.
An instance must be stopped before changing its instance type.
Status checks should be completed before making infrastructure changes.
Choosing the appropriate instance type helps optimize cloud costs and application performance.
AWS allows instance types to be changed whenever application requirements change.
Lab Status

✅ Successfully changed the EC2 instance type from t2.micro to t2.nano and verified that the instance was running successfully.
