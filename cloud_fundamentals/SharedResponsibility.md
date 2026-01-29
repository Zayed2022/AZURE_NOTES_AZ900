# 🔐 Shared Responsibility Model — AZ-900 Smart Notes (Mapped with AWS)

## 📌 Core Idea (Exam Definition)

> In cloud computing, security and management responsibilities are shared between the cloud provider (Microsoft Azure) and the customer.

---

## 🏢 Traditional Datacenter vs Cloud

### On-Prem (Before Cloud):

👉 You manage EVERYTHING

Servers
Security
Power
Cooling
Networking
OS
Applications
Data

---

### ☁ In Cloud (Azure/AWS):

Responsibilities are **split**

---

# 🔁 AWS vs Azure (Same Concept!)

AWS calls it: **Shared Responsibility Model**
Azure calls it: **Shared Responsibility Model**

👉 100% SAME in both clouds

---

## 🏗 What Azure (Cloud Provider) is ALWAYS Responsible For

(= AWS responsibility too)

✅ Physical datacenter
✅ Physical servers (hosts)
✅ Network hardware
✅ Power & cooling
✅ Physical security

📌 Think: “Anything you can touch = cloud provider”

---

## 👤 What YOU (Customer) are ALWAYS Responsible For

(Exam loves this!)

✅ Your data
✅ Who can access it (IAM / Azure AD)
✅ User accounts & identities
✅ Devices accessing cloud

📌 Think: “What you store and who can use it = you”

---

# ⚖ Responsibilities Change Based on Service Type

Same as AWS CP 👇

| Service Model | AWS Example | Azure Example | Who Manages More?     |
| ------------- | ----------- | ------------- | --------------------- |
| IaaS          | EC2         | Azure VM      | YOU manage most       |
| PaaS          | RDS         | Azure SQL     | Shared                |
| SaaS          | Gmail       | Microsoft 365 | Provider manages most |

---

### 🧱 IaaS (Most work for you)

Azure VM / AWS EC2

You manage:

* OS updates
* Patches
* Applications
* Data

Azure/AWS manage:

* Hardware
* Network
* Physical security

---

### ⚙ PaaS (Middle ground)

Azure SQL / AWS RDS

Provider manages:

* OS
* Database engine
* Infrastructure

You manage:

* Data
* Users
* Queries

---

### 📦 SaaS (Least work for you)

Microsoft 365 / Gmail

Provider manages almost everything
You just manage:

* Users
* Data

---

# 🧠 AZ-900 Exam Keywords (MEMORIZE)

Microsoft repeats these a lot:

✅ “Customer is always responsible for data”
✅ “Cloud provider handles physical infrastructure”
✅ “Responsibility depends on IaaS, PaaS, SaaS”
✅ “More control = more responsibility”

---

# 📒 One-Page Notebook Summary

> In the shared responsibility model, Azure manages physical datacenters, servers, networking, power, and cooling. Customers always manage data, identities, and access. Responsibility varies by service model: IaaS = customer manages most, PaaS = shared, SaaS = provider manages most.

---

### 🎯 AWS Shortcut Memory Trick:

👉 Physical stuff = AWS/Azure
👉 Data + users = You
👉 More control = more responsibility

---

