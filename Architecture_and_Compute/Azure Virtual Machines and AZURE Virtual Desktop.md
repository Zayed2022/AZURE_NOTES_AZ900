## 🖥 Azure Virtual Machines (VMs) — AZ-900

**Definition:**
Azure Virtual Machines provide Infrastructure as a Service (IaaS) in the form of virtualized servers that allow full control over the operating system and installed software.<br>

---

## ✅ Why Use Azure VMs

• Full control over the operating system<br>
• Ability to run custom software<br>
• Custom hosting configurations<br>
• No physical hardware maintenance<br>
• Flexible and scalable compute<br>

---

### 🔁 AWS Mapping

Azure VM ↔ AWS EC2<br>

(Same IaaS virtual server concept)<br>

---

## ⚠ Responsibility Reminder (IaaS)

• Azure manages physical hardware<br>
• You manage OS, patches, software, security inside VM<br>

---

## 📦 VM Images

• Preconfigured templates to create VMs quickly<br>
• Can include OS only or OS + software tools<br>
• Speeds up deployment<br>

---

### 🔁 AWS Mapping

Azure VM Image ↔ AWS AMI (Amazon Machine Image)<br>

---

## 📈 Scaling VMs in Azure

VMs can run individually or be grouped for availability and scalability.<br>

---

## ➕ Virtual Machine Scale Sets (VERY IMPORTANT)

**Definition:**
Scale sets manage groups of identical, load-balanced VMs that automatically scale based on demand or schedules.<br>

---

### ✅ Benefits

• Automatic scaling in/out<br>
• Centralized VM management<br>
• Built-in load balancer<br>
• Ideal for large workloads and high traffic apps<br>

---

### 🔁 AWS Mapping

Azure VM Scale Sets ↔ AWS Auto Scaling Groups<br>

---

## 🛡 Virtual Machine Availability Sets

**Definition:**
Availability sets improve VM reliability by distributing VMs across update domains and fault domains.<br>

---

### 🔄 Update Domains

• Groups of VMs updated together<br>
• Only one group rebooted at a time during maintenance<br>

---

### ⚡ Fault Domains

• Separate power and network sources<br>
• Protect against hardware failures<br>
• Typically up to 3 fault domains<br>

---

📌 No extra cost for availability sets (only pay for VMs).<br>

---

### 🔁 AWS Mapping

Azure Availability Sets ↔ AWS placement across multiple hardware (conceptually similar to multi-AZ resilience inside region)<br>

---

## 📦 Common VM Use Cases

• Testing and development environments<br>
• Running cloud applications with variable demand<br>
• Extending on-prem datacenter (hybrid cloud)<br>
• Disaster recovery setups<br>
• Lift-and-shift migrations from physical servers<br>

---

## ⚙ VM Configuration Options

When creating a VM you choose:<br>

• VM size (CPU, RAM, workload type)<br>
• Storage disks (HDD, SSD)<br>
• Networking (VNet, IPs, ports, security rules)<br>

---

## 🧠 AZ-900 Exam Keywords

• IaaS compute service<br>
• Full OS control<br>
• VM images<br>
• Scale sets for autoscaling<br>
• Availability sets for resiliency<br>
• Lift-and-shift workloads<br>

---

## 📒 Quick Notebook Summary

> Azure Virtual Machines are IaaS virtual servers that provide full control over OS and applications. They support rapid deployment using images, scaling through VM scale sets, and high availability through availability sets, making them ideal for flexible and resilient workloads.

---

### 🎯 AWS Memory Shortcut

Azure VM = EC2<br>
Image = AMI<br>
Scale set = Auto Scaling Group<br>
Availability set = fault isolation concept<br>

---

## 🖥 Azure Virtual Desktop (AVD) — AZ-900

**Definition:**
Azure Virtual Desktop is a cloud-based desktop and application virtualization service that provides users with a remote Windows desktop accessible from anywhere and on any device.<br>

---

## ☁ Key Features

• Cloud-hosted Windows desktops and applications<br>
• Access from browsers or remote desktop apps<br>
• Works across different devices and operating systems<br>
• Centralized desktop management in Azure<br>

---

### 🔁 AWS Mapping

Azure Virtual Desktop ↔ Amazon WorkSpaces<br>

(Cloud-hosted virtual desktops concept)<br>

---

## 🔐 Security Benefits

• Centralized identity management using Microsoft Entra ID<br>
• Multi-factor authentication (MFA) for secure logins<br>
• Role-based access control (RBAC) for permissions<br>
• Data and applications stay in the cloud (not on local devices)<br>
• Reduced risk of data leakage<br>
• Isolated user sessions for security<br>

---

## 👥 Multi-Session Windows Support (Exam Favorite)

• Supports Windows 10 & Windows 11 Enterprise multi-session<br>
• Multiple users can share a single VM securely<br>
• Lower cost per user compared to single-user desktops<br>
• Better app compatibility than server-based desktops<br>

---

## 📦 Why Use Azure Virtual Desktop

• Remote work solutions<br>
• Secure access to corporate desktops<br>
• Centralized IT management<br>
• Cost-effective multi-user environments<br>

---

## 🧠 AZ-900 Exam Keywords

• Desktop virtualization<br>
• Cloud-hosted Windows environment<br>
• Entra ID integration<br>
• MFA and RBAC security<br>
• Multi-session Windows 10/11<br>

---

## 📒 Quick Notebook Summary

> Azure Virtual Desktop provides secure, cloud-hosted Windows desktops and applications accessible from any device. It offers centralized security using Entra ID, supports multi-session Windows for cost efficiency, and keeps data securely in the cloud.

---

### 🎯 AWS Memory Shortcut

Azure Virtual Desktop = Amazon WorkSpaces<br>
Cloud desktops = secure remote work<br>
Multi-session = multiple users per VM<br>

---


