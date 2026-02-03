## 🔁 Azure Storage Redundancy — AZ-900

Azure Storage automatically creates multiple copies of data to protect against hardware failures, outages, and disasters.<br>

Redundancy ensures:<br>
• High availability<br>
• Data durability<br>
• Disaster recovery protection<br>

---

## 🎯 Choosing Redundancy Depends On

• Replication within primary region<br>
• Replication to secondary region (disaster recovery)<br>
• Read access to secondary region if primary fails<br>
• Cost vs availability tradeoff<br>

---

## 🏢 Redundancy in Primary Region

---

### 📍 Locally Redundant Storage (LRS)

• Data copied 3 times in one datacenter<br>
• Lowest cost option<br>
• Protects against disk/server failure<br>
• Does NOT protect against datacenter disaster<br>

📌 Durability: 11 nines (99.999999999%)<br>
<img width="273" height="285" alt="image" src="https://github.com/user-attachments/assets/9a8f1b90-e3bc-4a1d-98e1-cad683c9050e" />

---

### ⚡ Zone-Redundant Storage (ZRS)

• Data copied across 3 availability zones in same region<br>
• Protects against datacenter failures<br>
• High availability within region<br>
• Recommended for mission-critical apps<br>

📌 Durability: 12 nines (99.9999999999%)<br>
<img width="503" height="501" alt="image" src="https://github.com/user-attachments/assets/e8f3f4ee-86a4-4062-ab19-7d1c167c8162" />

---

### 🔁 AWS Mapping

LRS ↔ single AZ storage<br>
ZRS ↔ multi-AZ storage (like S3 standard across AZs)<br>

---

## 🌍 Redundancy Across Regions (Disaster Recovery)

---

### 🌎 Geo-Redundant Storage (GRS)

• LRS in primary region (3 copies)<br>
• Asynchronously replicated to secondary region (LRS)<br>
• Protects against regional disasters<br>

📌 Data not readable unless failover happens (default)<br>

📌 Durability: 16 nines<br>
<img width="731" height="371" alt="image" src="https://github.com/user-attachments/assets/92115863-90ff-4ed9-a2f1-1497dc9613ae" />

---

### 🌐 Geo-Zone-Redundant Storage (GZRS)

• ZRS in primary region (across zones)<br>
• LRS in secondary region<br>
• Highest availability + disaster protection<br>

📌 Best for critical systems<br>

📌 Durability: 16 nines<br>
<img width="960" height="615" alt="image" src="https://github.com/user-attachments/assets/5f5c21ce-da2a-4a46-9b3b-c51d6999b477" />

---

### 🔁 AWS Mapping

GRS/GZRS ↔ cross-region replication in AWS (S3 CRR conceptually)<br>

---

## 📖 Read Access Options (VERY IMPORTANT)

---

### 📘 RA-GRS

• Same as GRS<br>
• Allows read access to secondary region anytime<br>

---

### 📗 RA-GZRS

• Same as GZRS<br>
• Allows read access to secondary region anytime<br>

---

📌 Exam Line:<br>
RA = Read access without failover<br>

---

## ⏳ Replication Behavior (Exam Tip)

• Replication to secondary region is asynchronous<br>
• Small chance of data loss during disaster<br>
• Controlled by RPO (Recovery Point Objective)<br>
• Typical RPO < 15 minutes<br>

---

## 🧠 AZ-900 Redundancy Quick Table

| Option  | Same DC | Multi Zone | Multi Region | Read Secondary |
| ------- | ------- | ---------- | ------------ | -------------- |
| LRS     | ✅       | ❌          | ❌            | ❌              |
| ZRS     | ❌       | ✅          | ❌            | ❌              |
| GRS     | ✅       | ❌          | ✅            | ❌              |
| RA-GRS  | ✅       | ❌          | ✅            | ✅              |
| GZRS    | ❌       | ✅          | ✅            | ❌              |
| RA-GZRS | ❌       | ✅          | ✅            | ✅              |

---

## 📒 Quick Notebook Summary

> Azure Storage redundancy protects data using multiple copies across datacenters, availability zones, and regions. LRS replicates within one datacenter, ZRS across zones, GRS across regions, and GZRS combines zone and regional protection. RA options allow read access in secondary regions.

---

### 🎯 Super Easy Memory Trick

L = Local (one datacenter)<br>
Z = Zone (multiple AZs)<br>
G = Geo (another region)<br>
RA = Read Access secondary<br>

---
