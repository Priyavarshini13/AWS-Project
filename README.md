AWS Solution Architect Training – Capstone Projects

This repository contains practical tasks completed during AWS Solution Architect Training with AWS Cloud Practitioner Certification conducted by Nminds Academy.

Student: Priyavarshini V
Department: CSE – Artificial Intelligence & Machine Learning
College: Sri Eshwar College of Engineering, Coimbatore
Trainer: Aravindraj G (AWS Academy Certified Educator)

The project demonstrates basic cloud infrastructure setup using Amazon EC2, Elastic IP, IIS, Apache, and SFTP.

Technologies Used

Amazon Web Services (AWS)

Amazon EC2

Windows Server

Linux Server

Internet Information Services (IIS)

Apache Web Server

Elastic IP

SSH / SFTP

Task 1 – Create an EC2 Windows Instance
Objective

Create a Windows Server virtual machine using Amazon EC2 to run Windows-based applications in the cloud.

Key Steps

Login to AWS Management Console

Launch EC2 instance

Select Windows Server AMI

Choose instance type

Configure security group (RDP – Port 3389)

Connect using Remote Desktop

Use Cases

Hosting Windows applications

Running Microsoft SQL Server

Development and testing environments

Task 2 – Configure IIS Web Server on Windows Server
Objective

Install and configure Internet Information Services (IIS) on the Windows EC2 instance to host a website.

Key Steps

Connect to Windows instance via RDP

Open Server Manager

Install Web Server (IIS) Role

Start IIS Manager

Create or modify the default website

Access the website using the public IP

Result

A functional web server hosted on AWS Windows EC2 instance.

Task 3 – Configure Elastic IP for Windows Web Server
Objective

Assign a static public IP address to the Windows EC2 instance using Elastic IP.

Key Steps

Allocate Elastic IP from AWS

Associate it with the EC2 instance

Update DNS or access via Elastic IP

Benefits

Static IP for web servers

High availability

Easy failover

Task 4 – Create an EC2 Linux Instance
Objective

Launch a Linux-based virtual server using Amazon EC2.

Key Steps

Select Amazon Linux / Ubuntu AMI

Choose instance type

Configure security group (SSH – Port 22)

Connect using SSH

Use Cases

Hosting web applications

Development environments

Database servers

Task 5 – Configure Apache Web Server on Linux
Objective

Install and configure Apache HTTP Server to host web pages on the Linux EC2 instance.

Key Steps

Connect to Linux instance using SSH

Install Apache

sudo yum install httpd -y

Start Apache

sudo systemctl start httpd

Enable Apache

sudo systemctl enable httpd

Create a sample webpage

echo "Welcome to AWS Apache Server" > /var/www/html/index.html
Result

Web server accessible through EC2 public IP.

Task 6 – Configure Elastic IP for Linux Web Server
Objective

Assign an Elastic IP to the Linux EC2 instance to maintain a static public address.

Key Steps

Allocate Elastic IP

Associate it with Linux instance

Verify website access using Elastic IP

Task 7 – Configure SFTP for Linux Web Server
Objective

Set up Secure File Transfer Protocol (SFTP) to securely transfer files to the Linux server.

Key Steps

Enable SSH service

Create user for SFTP

Configure permissions

Transfer files securely using SFTP client (WinSCP / FileZilla)

Advantages

Secure encrypted file transfer

Remote file management

Firewall-friendly (Port 22)

Architecture Overview

The project architecture includes:

AWS EC2 Windows Instance

AWS EC2 Linux Instance

IIS Web Server

Apache Web Server

Elastic IP for static access

Secure file transfer using SFTP

Learning Outcomes

Through this project, the following AWS concepts were learned:

Cloud server deployment

Web server configuration

Static IP management

Linux and Windows server management

Secure file transfer protocols
