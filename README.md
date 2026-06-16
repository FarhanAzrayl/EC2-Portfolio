# EC2-Portfolio
Resume Showcase

# AWS EC2 Portfolio Website

## Overview
This project deploys a personal portfolio website on an AWS EC2 instance using Ubuntu and Nginx.

The goal was to simulate a real production-like deployment and learn core cloud fundamentals.

---

## Architecture

User
 |
Internet
 |
Security Group (Firewall
Rules)
 |
EC2 Ubuntu Instance
 |
Nginx Reverse Proxy / Web
Server
 |
Portfolio Website
(HTML/CSS/JS)

---

## AWS Services Used
- EC2 (Compute)
- Security Groups (Firewall rules)
- Ubuntu Linux
- Nginx Web Server

---

## Skills Demonstrated
- Linux server administration
- SSH access using key pairs
- Web server configuration (Nginx)
- AWS networking (Security Groups, public IP)
- File transfer using SCP
- Basic troubleshooting

---

## Deployment Steps
1. Launch EC2 instance (Ubuntu)
2. Configure Security Group (allow HTTP 80)
3. SSH into server
4. Install Nginx
5. Upload website files via SCP
6. Deploy to /var/www/html
7. Access via public IP

---

## Challenges Faced
- SSH key permission issues
- File transfer path issues in Windows SCP
- Security group misconfiguration blocking HTTP access

---

## Lessons Learned
- AWS Security Groups act as firewalls
- EC2 requires public IP for external access
- Nginx serves static content from /var/www/html
- Cloud troubleshooting is mostly networking-related
