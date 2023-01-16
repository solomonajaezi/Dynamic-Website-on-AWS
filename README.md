# Built and Deployed a Dynamic Website on AWS. The Project Features a 3-Tier AWS VPC Architecture.



I used AWS services and tools such as EC2, S3, RDS, Route-53, NAT Gateway, Bastion host, MySql, MySql Workbench, LAMP Stack, and Auto Scaling for this project.

This project involves creating one public subnet and two private subnets:
Tier-1: Public subnet, which will have a direct route to the internet through an internet gateway.
Tier-2: Private subnet that will host the webservers.
Tier-3: Private subnet host the database.

Steps for the project
Creating a VPC
Creating a NAT Gateway
Creating Security Groups
Starting RDS instances with MySql engine
Creating S3 bucket and uploading application file
Creating IAM role with S3 policy
Launched EC2 Instance in the public subnet
Launched setup server in the public subnet
Installed MySql workbench on my computer
Installed and configured the dynamic website on EC2 instance using LAMP stack
Register a new domain using Route 53
Register SSL certificate to secure the website
Created an auto scaling group

Final result: www.solomonsrental.com

This project aims to demonstrate an understanding and ability to design and implement scalable, fault-tolerant, and secure web applications on AWS.
