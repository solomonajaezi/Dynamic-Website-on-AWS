# Built and Deployed a Dynamic Website on AWS. The Project Features a 3-Tier AWS VPC Architecture.



I used AWS services and tools such as EC2, S3, RDS, Route-53, NAT Gateway, Bastion host, MySql, MySql Workbench, LAMP Stack, and Auto Scaling for this project.

This project involves creating one public subnet and two private subnets:

Tier-1: Public subnet that will have a direct route to the internet through an internet gateway.
Tier-2: Private subnet that hosts the webservers.
Tier-3: Private subnet that host the database.

Steps for the project
1. Creating a VPC
2. Creating a NAT Gateway
3. Creating Security Groups
4. Starting RDS instances with MySql engine
5. Creating S3 bucket and uploading application file
6. Creating IAM role with S3 policy
7. Launched EC2 Instance in the public subnet
8. Launched setup server in the public subnet
9. Installed MySql workbench on my computer
10. Installed and configured the dynamic website on EC2 instance using LAMP stack
11. Register a new domain using Route 53
12. Register SSL certificate to secure the website
13. Created an auto scaling group

Final result: www.solomonsrental.com

This project aims to demonstrate an understanding and ability to design and implement scalable, fault-tolerant, and secure web applications on AWS.
