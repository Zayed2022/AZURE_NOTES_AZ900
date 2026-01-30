## 🌍 Azure Physical Infrastructure (AZ-900)

Azure physical infrastructure consists of global datacenters organized into regions, availability zones, and region pairs to provide reliability and resiliency.<br>

---

## 🏢 Azure Datacenters

• Physical facilities containing servers, networking, power, and cooling systems<br>
• Similar to traditional corporate datacenters but at global scale<br>
• Not directly accessed by customers<br>
• Grouped into regions and availability zones<br>

---

### 🔁 AWS Mapping

Azure Datacenters ↔ AWS Datacenters (inside regions)<br>

---

## 🌐 Azure Regions

**Definition:**
A region is a geographical area containing one or more datacenters connected by low-latency networks.<br>

---

### 📌 Key Points

• Resources are deployed into specific regions<br>
• Azure balances workloads within regions<br>
• Some services are region-specific<br>
• Some services are global (e.g., Entra ID, Azure DNS)<br>

---

### 🔁 AWS Mapping

Azure Region ↔ AWS Region (Mumbai, US-East-1, etc.)<br>

---

## ⚡ Availability Zones (VERY IMPORTANT FOR EXAM)

**Definition:**
Availability Zones are physically separate datacenters within a single region, each with independent power, cooling, and networking.<br>
<img width="404" height="404" alt="image" src="https://github.com/user-attachments/assets/01cbd584-bd89-4d0d-8deb-9adcdef4ef3d" />

---

### ✅ Benefits

• Protect against datacenter failures<br>
• Provide high availability<br>
• Connected with high-speed private networks<br>
• At least 3 zones in zone-enabled regions<br>

---

### 🔁 AWS Mapping

Azure Availability Zones ↔ AWS Availability Zones (same concept)<br>

---

### 📦 Types of Zone Services

**Zonal services:** pinned to a specific zone (VMs, managed disks)<br>
**Zone-redundant services:** auto-replicated across zones (storage, SQL DB)<br>
**Non-regional services:** resilient to zone and region failures (DNS, Entra ID)<br>

---

## 🌍 Region Pairs (Azure Special Concept)

**Definition:**
Each Azure region is paired with another region in the same geography, usually at least 300 miles apart for disaster recovery.<br>
<img width="1012" height="560" alt="image" src="https://github.com/user-attachments/assets/7cbac3ba-6a97-460c-90a5-ba438cde1e84" />

---

### 🎯 Purpose

• Automatic failover during regional disasters (for supported services)<br>
• Planned updates rolled out one region at a time<br>
• Data stays within same geography for compliance<br>

---

### 📌 Examples

• West US ↔ East US<br>
• Southeast Asia ↔ East Asia<br>

---

### ⚠ Exam Tip

Not all services auto-replicate — customers may need to configure replication.<br>

---

### 🔁 AWS Mapping

Azure Region Pairs ↔ AWS multi-region disaster recovery (conceptually similar)<br>

(AWS doesn’t have fixed pairs but same resilience idea)<br>

---

## 🛡 Sovereign Regions

**Definition:**
Isolated Azure regions designed for government and compliance needs.<br>

---

### 📍 Examples

• US Government regions (DoD, Gov Virginia, Gov Iowa)<br>
• China regions operated by 21Vianet<br>

---

### 📌 Purpose

• Legal compliance<br>
• Data sovereignty<br>
• Restricted access environments<br>

---

## 🧠 AZ-900 Exam Keywords

• Datacenters → Regions → Availability Zones<br>
• High availability through zones<br>
• Disaster recovery with region pairs<br>
• Global infrastructure<br>
• Sovereign regions for compliance<br>

---

## 📒 Quick Notebook Summary

> Azure physical infrastructure consists of global datacenters grouped into regions and availability zones for high availability and resiliency. Regions are paired to support disaster recovery, and sovereign regions provide isolated environments for compliance and legal requirements.

---

### 🎯 AWS Memory Shortcut

Region = AWS Region<br>
Availability Zone = AWS AZ<br>
Region pair = multi-region DR strategy<br>
Sovereign region = Gov/China special clouds<br>

---

