# Configuring and Accessing a Linux Virtual Machine on AWS EC2 using AWS Free Tier

## 📌 Project Overview
This project demonstrates how to configure and access a Linux Virtual Machine on Amazon Web Services (AWS) using the EC2 service under the AWS Free Tier. The virtual machine is launched, configured with a security group, and accessed remotely using SSH.

This project is useful for beginners who want to learn cloud computing basics and understand how virtual machines work in AWS.

---

## 🎯 Aim
To configure and access a Linux Virtual Machine (EC2 Instance) using AWS Free Tier.

---

## 🛠️ Services Used
- Amazon EC2 (Elastic Compute Cloud)
- AWS Free Tier
- Security Groups
- Key Pair Authentication
- SSH Access

---

## 🖥️ System Requirements
- AWS Account (Free Tier Enabled)
- Web Browser (Chrome / Edge recommended)
- Internet Connection
- SSH Client (Optional if using EC2 Instance Connect)

---

## 📂 Project Steps

### Step 1: Login to AWS Console
- Open https://aws.amazon.com
- Login using AWS credentials.

### Step 2: Open EC2 Service
- Search for **EC2** in AWS Console.
- Open EC2 Dashboard.

### Step 3: Launch EC2 Instance
- Click **Launch Instance**
- Choose **Amazon Linux AMI**
- Select **t2.micro** (Free Tier eligible)

### Step 4: Create Key Pair
- Create a new key pair
- Download `.pem` file

### Step 5: Configure Security Group
- Allow **SSH (Port 22)**
- Select **Anywhere (0.0.0.0/0)**

### Step 6: Launch Instance
- Click **Launch**
- Wait until instance state becomes **Running**

### Step 7: Connect to Instance
- Click **Connect**
- Use **EC2 Instance Connect**
- Access the Linux terminal

### Step 8: Execute Linux Commands
Example commands:

```bash
ls
pwd
whoami
### 🎥 Project Demo Video
[![Watch the demo](https://img.youtube.com/vi/yGS-07uIB_M/0.jpg)](https://youtu.be/yGS-07uIB_M)


