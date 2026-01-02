# 🖥️ Windows Server 2019 Administration
> **Module 1: Introduction & Fundamentals**

![Windows Server](https://img.shields.io/badge/Windows_Server-2019-0078D6?style=for-the-badge&logo=windows-server&logoColor=white)
![Status](https://img.shields.io/badge/Status-Learning-brightgreen?style=for-the-badge)
![Category](https://img.shields.io/badge/Category-Infrastructure-orange?style=for-the-badge)

---
# 🖥️ Windows Server 2019  
## Module 1 – Introduction & Fundamentals (Basic)

> A beginner-friendly, professional guide to understanding Windows Server 2019 fundamentals, designed for students, system administrators, and IT professionals.

---

## 📌 Project Overview

**Windows Server 2019** is an enterprise-grade operating system used by organizations to manage users, computers, networks, and critical business services.  
This repository covers **Module 1 – Introduction & Fundamentals**, focusing on core concepts, editions, installation, and real-world usage.

This project is ideal for:
- Beginners learning Windows Server
- Students preparing for system administration roles
- Trainers and educators
- Interview and lab practice reference

---

## 📖 Module Contents

### 1️⃣ What Is Windows Server?
Windows Server is designed to:
- Manage users and computers centrally  
- Control and share network resources  
- Provide advanced security and authentication  
- Host applications, databases, and websites  

> Windows Server is **not for personal use**. It is used in **companies, data centers, and cloud environments**.

---

### 2️⃣ Windows Server vs Windows 10/11

| Feature | Windows Server | Windows 10/11 |
|------|---------------|--------------|
| Purpose | Enterprise / Company | Personal |
| Users | Multiple (Hundreds/Thousands) | Single |
| Server Roles | Yes (AD, DNS, DHCP) | No |
| Security | Advanced | Basic |
| Cost | High | Low |

---

### 3️⃣ What’s New in Windows Server 2019
- Improved security features  
- Hybrid cloud integration  
- Enhanced virtualization  
- Storage Spaces Direct  
- Windows Defender Advanced Threat Protection (ATP)  

---

### 4️⃣ Windows Server 2019 Editions

#### 🔹 Standard
- Small to medium businesses  
- Limited virtualization (2 VMs)

#### 🔹 Datacenter
- Large enterprises  
- Unlimited virtual machines  
- Advanced storage and security

#### 🔹 Essentials
- Small offices  
- Maximum 25 users / 50 devices  

> **Real-world usage:** Most organizations use **Standard** or **Datacenter** editions.

---

### 5️⃣ System Requirements

#### Minimum Requirements
- CPU: 1.4 GHz (64-bit)  
- RAM: 2 GB (GUI)  
- Disk: 32 GB  
- Network: 1 Gbps NIC  

#### Recommended for Lab / Office
- RAM: 8–16 GB  
- Disk: 100 GB  
- SSD recommended  

---

### 6️⃣ Installation Types

#### Desktop Experience (GUI)
- Graphical interface  
- Easy for beginners  
- Slightly higher resource usage  

#### Server Core
- No GUI  
- Command-line / PowerShell based  
- More secure and faster  
- Recommended for advanced administrators  

---

### 7️⃣ Hands-On: Windows Server 2019 Installation

**Installation Steps:**
1. Boot from Windows Server 2019 ISO  
2. Select Language, Time, and Keyboard  
3. Click **Install Now**  
4. Choose **Windows Server 2019 – Desktop Experience**  
5. Accept license agreement  
6. Select **Custom Installation**  
7. Create disk partitions  
8. Install the OS  
9. Set Administrator password  
10. Log in  

#### 🧪 Mandatory Practice Task
Install Windows Server 2019 on:
- VirtualBox  
- VMware  
- OR a physical machine  

---

### 8️⃣ First Login – Initial Configuration
After first login:
- Change computer name  
- Set correct time zone  
- Assign a static IP address  
- Enable Windows Updates  

---

### 9️⃣ Server Manager – Core Management Tool
**Server Manager** is the central console used to:
- Add and manage server roles  
- Configure services  
- Monitor server health  

Server Manager opens automatically after login.

---

### 🔟 Real-World Use Case
Organizations use Windows Server to:
- Control employee logins  
- Centralize and secure data  
- Protect the network  
- Run business-critical applications  

---

## 📂 Repository Structure (Recommended)

```text
Windows-Server-2019-Basics/
│
├── README.md
├── screenshots/
│   ├── installation.png
│   ├── server-manager.png
│   └── desktop.png
└── labs/
    └── module-1-installation.md

👤 Author
Anup kumar singh
Windows Server / System Administrator

