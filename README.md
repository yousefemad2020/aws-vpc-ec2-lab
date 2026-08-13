# AWS Custom VPC & Automated EC2 Web Server Deployment

A hands-on cloud lab demonstrating the creation of a custom Amazon VPC, subnet configuration, Security Group rules, and deploying an Amazon Linux 2023 EC2 instance with an automated Apache Web Server using User Data script and IMDSv2.

## 🛠️ Infrastructure & Tech Stack
- **Cloud Provider:** Amazon Web Services (AWS)
- **Networking:** Custom VPC, Public Subnet, Route Tables
- **Compute:** EC2 (Amazon Linux 2023)
- **Security:** Security Groups (SSH Port 22, HTTP Port 80)
- **Automation:** Bash Scripting (User Data) & IMDSv2
- **Web Server:** Apache (httpd)

## 📐 Architecture & Key Steps
1. **Custom VPC Creation:** Provisioned CIDR block `172.16.0.0/16` with public subnet `172.16.0.0/20`.
2. **Security Group Configuration:** Allowed inbound HTTP (80) and SSH (22) traffic.
3. **Automated Server Provisioning:** Configured `user_data.sh` to install Apache, retrieve instance metadata via IMDSv2, and host a dynamic HTML test page.
4. **Remote Access & Verification:** Connected via SSH and verified web accessibility using the public IP.

## 📸 Screenshots
All lab execution screenshots are available in the [`/screenshots`](./screenshots) directory.

---
**Author:** Yousef Emad
