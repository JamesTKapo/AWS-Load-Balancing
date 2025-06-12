# Apache Load Balancing in AWS

# Overview

This project demonstrates the configuration of a basic web server load balancing setup using iptables, Apache, and multiple synchronized virtual machines in an AWS environment. 
The goal was to gain hands-on experience with server cloning, secure file synchronization, and traffic distribution in a controlled lab environment.

# Key Features:
- Configured four Apache web servers using Amazon Machine Images (AMIs) for rapid deployment.

- Set up iptables rules to perform basic load balancing by randomly forwarding HTTP traffic across multiple servers.

- Synchronized website content between servers using rsync, SSH key authentication, and cron jobs.

- Validated load balancing using a custom Python script to simulate traffic and monitor request distribution.

# Diagram
![800px-AWSAsg1Overview](https://github.com/user-attachments/assets/b2435e29-295f-41c2-bd29-f968a2b145af)


# Completed Work

## AMIs
![asg1-ss01-amis](https://github.com/user-attachments/assets/17aebbaa-ade8-4a80-bb1a-b1bf2e55e98b)

## Elastic Block Store/Volumes
![asg1-ss02-ebs](https://github.com/user-attachments/assets/96dfc741-f8cd-4c07-ad2d-fb781ac404d6)

## Router's security group with the port numbers
![asg1-ss03-routers](https://github.com/user-attachments/assets/725064d6-cd13-4166-84b0-b9e816e0ff45)

## Access VIA SSH keys
![asg1-ss05-sshkeys](https://github.com/user-attachments/assets/3ab98f49-516d-48c5-a1ba-9ab133a5e02d)

## IP Tables Configuration
![asg1-ss04-iptables](https://github.com/user-attachments/assets/3e64de1a-7059-4393-b211-2166be3d3b35)

## Testing Rsync
![asg1-ss06-files png](https://github.com/user-attachments/assets/094b898f-2f51-4c73-8b63-cb7e7daed337)

## Crontab on the slave(s)
![asg1-ss07-crontab png](https://github.com/user-attachments/assets/c240cc02-6a8c-4f0d-8407-3ef8da400a3d)




