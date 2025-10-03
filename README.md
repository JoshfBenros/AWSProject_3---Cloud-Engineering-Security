# AWS EC2 Project – Cloud Engineering & Security

## Objective
The goal of this project was to learn the fundamentals of cloud engineering and cloud security by launching and configuring an AWS EC2 instance, securing it with SSH keys, and hosting a simple web server.

## Steps Completed
1. **Created EC2 Instance** using Amazon Linux 2023 (t3.micro).  
2. **Generated & used PEM key** securely to SSH into the instance.  
3. **Configured Security Groups**:
   - SSH (port 22) → restricted to my IP  
   - HTTP (port 80) → open to 0.0.0.0/0 for testing
4. **Installed Apache** (`httpd`) and started the service.  
5. **Verified Access** by visiting the Public IPv4 address in the browser and receiving the Apache "It works!" page.  

## Security Considerations
- Keys were stored locally and locked down with correct permissions.  
- Security groups limited inbound access where possible.  
- Keys are never uploaded to GitHub.  

## Screenshots
- EC2 setup and specs  
- SSH session installing Apache  
- Browser verification ("It works!" page)  

---
This project demonstrated both the **engineering side (deployment)** and the **security side (SSH keys & security groups)** of working in the cloud.
