## 🧱 Infrastructure as a Service (IaaS) — AZ-900

**Definition:**
Infrastructure as a Service (IaaS) provides virtualized computing resources over the internet, giving customers maximum control over their infrastructure while the cloud provider manages physical hardware.<br>

---

## ☁ Responsibilities in IaaS (Shared Responsibility Model)

### 🏢 Cloud Provider Handles:

• Physical datacenter<br>
• Servers (hardware)<br>
• Networking infrastructure<br>
• Power and cooling<br>
• Physical security<br>

---

### 👤 Customer Handles:

• Operating system installation and updates<br>
• VM configuration<br>
• Network configuration<br>
• Applications<br>
• Data and storage configuration<br>
• Security inside the VM<br>

---

### 🔁 AWS Mapping

Azure Virtual Machine ↔ AWS EC2<br>

Same responsibility split in both clouds<br>

---

## 📌 Exam Key Point

> IaaS offers the most control and also the most responsibility for the customer.

---

## 📦 Why Use IaaS (Common Scenarios)

---

### 🚚 Lift-and-Shift Migration

• Move on-prem servers directly to cloud VMs<br>
• Minimal application changes<br>
• Fast cloud adoption<br>

**AWS Mapping:**<br>
On-prem servers → EC2 ↔ Azure VM<br>

---

### 🧪 Testing & Development

• Quickly spin up environments<br>
• Shut down when not needed<br>
• Maintain full configuration control<br>

---

## 🧠 AZ-900 Exam Keywords

• Maximum flexibility<br>
• Customer manages OS & applications<br>
• Provider manages physical infrastructure<br>
• Lift-and-shift scenario<br>
• Virtual machines<br>

---

## 📒 Quick Notebook Summary

> IaaS provides virtualized infrastructure where the cloud provider manages hardware and physical facilities, while customers manage operating systems, applications, networking, and data. It offers maximum control and is ideal for lift-and-shift and testing environments.

---

### 🎯 AWS Memory Shortcut

IaaS = renting servers<br>
AWS EC2 = Azure VM<br>
More control = more responsibility<br>

---
