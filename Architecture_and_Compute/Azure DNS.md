## 🌐 Azure DNS — AZ-900

**Definition:**
Azure DNS is a cloud-based DNS hosting service that provides domain name resolution using Microsoft’s global Azure infrastructure.<br>

---

## ☁ Key Benefits of Azure DNS

• High availability and resiliency<br>
• Fast performance using global Azure network<br>
• Secure management using Azure tools<br>
• Easy integration with other Azure services<br>
• Supports public and private DNS domains<br>
• Automated record management via APIs and CLI<br>

---

### 🔁 AWS Mapping

Azure DNS ↔ AWS Route 53<br>

---

## ⚡ Reliability & Performance

• Hosted on Azure’s worldwide DNS servers<br>
• Uses anycast networking<br>
• Routes DNS queries to nearest server<br>
• Provides low latency and high uptime<br>

---

📌 Exam Line:<br>
Azure DNS uses anycast for fast and reliable name resolution.<br>

---

## 🔐 Security Features

• Azure RBAC for access control<br>
• Activity logs for auditing changes<br>
• Resource locks to prevent accidental deletion<br>

---

## 🧑‍💻 Ease of Use

• Managed via Azure Portal<br>
• Supports Azure CLI and PowerShell<br>
• REST APIs for automation<br>
• Unified billing and credentials with Azure services<br>

---

## 🏠 Private DNS Domains

• Create custom domain names inside VNets<br>
• Use internal DNS for private resources<br>
• Avoid default Azure naming schemes<br>

---

## 🔗 Alias Records (Exam Favorite)

• DNS records that point to Azure resources directly<br>
• Automatically update if resource IP changes<br>
• Can reference:<br>
– Public IP addresses<br>
– Traffic Manager profiles<br>
– CDN endpoints<br>

---

📌 Benefit:<br>
No manual DNS updates when IP changes.<br>

---

## ⚠ Important Limitation

• Azure DNS does NOT sell domain names<br>
• Domains must be purchased from third-party registrar or App Service domains<br>
• Azure DNS hosts and manages DNS records only<br>

---

## 🧠 AZ-900 Exam Keywords

• DNS hosting service<br>
• Anycast networking<br>
• High availability<br>
• Private DNS zones<br>
• Alias records<br>
• RBAC security<br>

---

## 📒 Quick Notebook Summary

> Azure DNS is a scalable and secure DNS hosting service that uses Azure’s global network for fast name resolution. It supports public and private domains, alias records for Azure resources, and centralized management using Azure tools.

---

### 🎯 AWS Memory Shortcut

Azure DNS = Route 53<br>
Alias record = AWS Alias record<br>
Private DNS = internal hosted zones<br>

---
