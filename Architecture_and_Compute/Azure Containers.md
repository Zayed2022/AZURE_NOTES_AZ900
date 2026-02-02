## 📦 Azure Containers — AZ-900

Containers provide a lightweight virtualization method to run multiple applications on a single host without managing separate operating systems.<br>

---

## 🧱 What Are Containers?

• Lightweight virtualization environments<br>
• Run multiple containers on one physical or virtual host<br>
• Do NOT require managing a full operating system per container<br>
• Faster startup and scaling than virtual machines<br>
• Designed for agility and dynamic workloads<br>
• Common engine: Docker (supported by Azure)<br>

---

### 🔁 AWS Mapping

Azure Containers ↔ AWS Containers (ECS, EKS, Fargate)<br>

Docker supported in both clouds<br>

---

## ⚔ Virtual Machines vs Containers (Exam Concept)

**Virtual Machines:**<br>
• Each VM has its own operating system<br>
• Heavier and slower to scale<br>
• Full OS management required<br>

**Containers:**<br>
• Share host OS<br>
• Lightweight and fast<br>
• No OS management<br>
• Ideal for microservices<br>

---

📌 Exam Line:<br>
Containers are lighter and more agile than VMs.<br>

---

## ☁ Azure Container Services

---

### 🚀 Azure Container Instances (ACI)

• Fastest way to run containers in Azure<br>
• No VM management required<br>
• PaaS offering<br>
• Upload container → Azure runs it<br>

---

### 🔄 Azure Container Apps

• PaaS container platform<br>
• Built-in load balancing<br>
• Automatic scaling<br>
• More elastic than ACI<br>

---

### ⚙ Azure Kubernetes Service (AKS)

• Container orchestration service<br>
• Manages deployment, scaling, and lifecycle of containers<br>
• Ideal for large container fleets<br>

---

### 🔁 AWS Mapping

ACI ↔ AWS Fargate<br>
Container Apps ↔ ECS with autoscaling (conceptually)<br>
AKS ↔ Amazon EKS (Kubernetes)<br>

---

## 🧩 Containers & Microservices

• Break applications into smaller independent services<br>
• Each component runs in its own container<br>
• Scale components independently<br>
• Easier updates and maintenance<br>

---

### 📌 Example

Front-end container<br>
Back-end container<br>
Database service container<br>

Scale only what’s under load.<br>

---

## 🧠 AZ-900 Exam Keywords

• Lightweight virtualization<br>
• No OS management<br>
• Docker containers<br>
• PaaS container services<br>
• AKS orchestration<br>
• Microservices architecture<br>

---

## 📒 Quick Notebook Summary

> Containers are lightweight environments that run applications without managing full operating systems. Azure offers container services such as Azure Container Instances, Container Apps, and Azure Kubernetes Service (AKS) to deploy and scale containerized workloads efficiently.

---

### 🎯 AWS Memory Shortcut

VM = heavy server<br>
Container = lightweight app box<br>
ACI = Fargate style<br>
AKS = EKS (Kubernetes)<br>

---
