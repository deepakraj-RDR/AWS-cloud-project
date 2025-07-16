# AWS-cloud-project

# DevOps AWS Projects Portfolio

This repository contains a collection of hands-on DevOps projects implemented using Amazon Web Services (AWS). Each project focuses on a critical infrastructure setup or configuration task widely used in real-world cloud environments. These projects showcase my understanding of networking, load balancing, auto scaling, and secure file transfer in AWS.

---

## 📁 Projects Overview

### ✅ Project 1: Configure Elastic IP Address to Windows Web Server in AWS
- Launched a Windows EC2 instance.
- Installed IIS (Internet Information Services) to serve web content.
- Attached an **Elastic IP** for consistent access to the web server.
- Verified web access via static IP.

---

### ✅ Project 2: Configure Elastic IP Address to Linux Web Server in AWS
- Deployed a Linux EC2 instance (Amazon Linux 2).
- Installed Apache HTTP Server and configured firewall rules.
- Assigned an **Elastic IP** for persistent public connectivity.
- Hosted a sample webpage for testing.

---

### ✅ Project 3: Configure SFTP for Linux Web Server in AWS
- Configured a secure **SFTP server** using OpenSSH on a Linux EC2 instance.
- Created isolated user directories with restricted access.
- Implemented user-based authentication for secure file transfers.
- Verified file uploads/downloads through SFTP clients.

---

### ✅ Project 4: Configure Network Load Balancer (NLB) with 3 Web Servers
- Launched 3 backend EC2 instances configured with web services.
- Created a **Network Load Balancer** and registered all 3 instances.
- Set up listener rules to route TCP traffic on port 80.
- Ensured **high availability** and **low-latency** connections.

---

### ✅ Project 5: Configure Application Load Balancer (ALB) with 3 Web Servers
- Deployed 3 EC2 instances running a sample web app.
- Configured an **Application Load Balancer** to distribute HTTP requests.
- Used target groups for traffic routing and health checks.
- Verified load balancing based on HTTP requests.

---

### ✅ Project 6: Configure Auto Scaling with Fault Tolerance
- Designed an **Auto Scaling Group** with launch template.
- Configured scaling policies based on CPU utilization.
- Implemented health checks and **automatic instance replacement** on failure.
- Demonstrated **fault tolerance** and **cost optimization**.

---

## 🛠️ Technologies & Tools Used
- **AWS EC2**, **Elastic IP**
- **Apache**, **IIS**, **OpenSSH**
- **SFTP**, **Auto Scaling**
- **Network Load Balancer (NLB)**, **Application Load Balancer (ALB)**
- **IAM**, **Security Groups**, **CloudWatch**

---

## 📸 Screenshots & Outputs
Screenshots and configuration outputs are provided in PDF in the project folder.

---

## 📌 Author
**Deepak RDR**  
Cloud & DevOps Enthusiast | NPTEL Certified | Java | Databases  

---



