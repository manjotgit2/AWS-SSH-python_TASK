# AWS-SSH-python_TASK
this task is related  these three concepts .
# DevOps Project
####EC2 Setup and Instance Creation
Login to AWS Management Console
Open Amazon EC2 dashboard
Click Launch Instance
Enter instance name (e.g., My-DevOps-Server)
Select AMI: Ubuntu Server 22.04 LTS
Choose instance type: t2.micro
Create a new key pair and download .pem file
Configure security group:
Allow SSH (Port 22)
Allow HTTP (Port 80)
Allow HTTPS (Port 443)
Click Launch Instance
Connect to instance using SSH:
chmod 400 my-key.pem
ssh -i my-key.pem ubuntu@<public-ip>
