# ☁ Cloud Deployment Models — AZ-900 Notes (Mapped to AWS)

## 📌 Definition (Exam Style)

> Cloud models describe how cloud resources are deployed and who owns/controls the infrastructure.

Main types:
✅ Private
✅ Public
✅ Hybrid
(+ Multi-cloud – bonus concept)

---

# 🏢 1) Private Cloud

### ✔ What it is:

Cloud used by **one organization only**

Can be:

* On-premises datacenter
* Or dedicated off-site datacenter

---

### 🔁 AWS Mapping:

| Azure Concept | AWS Equivalent                         |
| ------------- | -------------------------------------- |
| Private cloud | On-prem + VMware Cloud / private infra |

---

### ✅ Advantages:

✔ Full control
✔ High security
❌ High cost
❌ Less scalability than public cloud

---

📌 Exam line:

> Private cloud offers greater control but higher cost and limited scalability.

---

# 🌍 2) Public Cloud (Most common — Azure & AWS)

### ✔ What it is:

Cloud services offered to **anyone over the internet**

Run by:
Microsoft (Azure)
Amazon (AWS)

---

### 🔁 AWS Mapping:

Azure Public Cloud = AWS Public Cloud

Examples:
Azure VM ↔ EC2
Blob Storage ↔ S3

---

### ✅ Advantages (Exam loves these):

✔ No hardware to buy (no CapEx)
✔ Pay only for what you use
✔ Massive scalability
✔ Fast provisioning

❌ Less direct control over infrastructure

---

📌 Exam line:

> Public cloud is owned by cloud provider and offers pay-as-you-go scalability.

---

# 🔗 3) Hybrid Cloud (VERY IMPORTANT FOR AZ-900)

### ✔ What it is:

Combination of:

👉 Private cloud + Public cloud working together

---

### 🔁 AWS Mapping:

On-prem + AWS = Hybrid
On-prem + Azure = Hybrid

(Same idea)

---

### 🎯 Why companies use hybrid:

✅ Keep sensitive data private
✅ Use public cloud for extra load (bursting)
✅ Meet compliance needs

---

📌 Exam line:

> Hybrid cloud combines private and public clouds for flexibility and security.

---

# 📊 Quick Exam Comparison Table

| Feature     | Public Cloud        | Private Cloud       | Hybrid Cloud |
| ----------- | ------------------- | ------------------- | ------------ |
| Ownership   | Cloud provider      | Single organization | Both         |
| Cost        | Low (pay as you go) | High                | Medium       |
| Scalability | Very high           | Limited             | High         |
| Control     | Less                | Full                | Balanced     |
| Flexibility | High                | Low                 | Highest      |

---

# ☁ Multi-Cloud (Extra but asked sometimes)

### ✔ What it is:

Using **more than one public cloud**

Example:
AWS + Azure together

---

📌 Why:
✔ Avoid vendor lock-in
✔ Use best services from each cloud

---

# 🧩 Azure-Specific (Know conceptually for exam)

### 🔧 Azure Arc

👉 Tool to manage:

Azure + on-prem + AWS + other clouds

📌 Think:
**“One dashboard for all clouds”**

---

### 🖥 Azure VMware Solution

👉 Run VMware workloads directly in Azure

📌 For companies moving from private cloud → Azure

---

# 📒 Super Short Notebook Summary

> Cloud deployment models are Public, Private, and Hybrid. Public cloud is owned by providers like Azure/AWS and offers scalability with pay-as-you-go pricing. Private cloud is dedicated to one organization with higher control and cost. Hybrid cloud combines both for flexibility and security. Multi-cloud uses multiple public providers.

---

# 🎯 AWS Memory Shortcut

Private = Your datacenter
Public = AWS/Azure
Hybrid = Both connected
Multi-cloud = AWS + Azure

---
