## 💾 Azure Storage Accounts — AZ-900

**Definition:**
An Azure Storage Account provides a unique namespace to store data in Azure and offers secure, scalable, durable, and highly available storage services over HTTP/HTTPS.<br>

---

## ☁ Key Characteristics

• Globally accessible<br>
• Highly available and durable<br>
• Massive scalability<br>
• Secure by default<br>
• Stores multiple storage services under one account<br>

---

### 🔁 AWS Mapping

Azure Storage Account ↔ AWS S3 bucket + related storage services (conceptually parent container)<br>

---

## 📦 Storage Services Inside an Account

• Blob Storage (object storage)<br>
• Data Lake Storage Gen2 (big data analytics)<br>
• Azure Files (file shares)<br>
• Queue Storage (messaging)<br>
• Table Storage (NoSQL key-value data)<br>

---

### 🔁 AWS Mapping

Blob Storage ↔ Amazon S3<br>
Azure Files ↔ Amazon EFS / FSx<br>
Queue Storage ↔ Amazon SQS<br>
Table Storage ↔ DynamoDB (conceptually)<br>

---

## 🔁 Redundancy Options (VERY IMPORTANT FOR EXAM)

• LRS – Locally Redundant Storage<br>
• ZRS – Zone-Redundant Storage<br>
• GRS – Geo-Redundant Storage<br>
• RA-GRS – Read-access Geo-Redundant Storage<br>
• GZRS – Geo-zone-redundant Storage<br>
• RA-GZRS – Read-access Geo-zone-redundant Storage<br>

---

📌 Exam Shortcut:<br>
LRS = one datacenter<br>
ZRS = multiple zones<br>
GRS = multiple regions<br>
RA = read access in secondary region<br>

---

## 🧾 Storage Account Types

---

### 📁 Standard General-purpose v2 (Most Common)

• Blob Storage<br>
• Azure Files<br>
• Queue Storage<br>
• Table Storage<br>
• Supports all redundancy types<br>
• Recommended for most workloads<br>

---

### ⚡ Premium Block Blobs

• High-performance blob workloads<br>
• Low latency<br>
• LRS or ZRS only<br>

---

### 📂 Premium File Shares

• High-performance Azure Files only<br>
• Supports SMB & NFS<br>
• LRS or ZRS<br>

---

### 📄 Premium Page Blobs

• Used mainly for VM disks<br>
• High performance<br>
• LRS only<br>

---

## 🌐 Storage Account Endpoints

Each storage account has a unique name across Azure.<br>

Naming rules:<br>
• 3–24 characters<br>
• Lowercase letters and numbers only<br>
• Must be globally unique<br>

---

### 📍 Endpoint Formats (Exam Favorite)

Blob Storage:<br>
`https://<account>.blob.core.windows.net`<br>

Data Lake Gen2:<br>
`https://<account>.dfs.core.windows.net`<br>

Azure Files:<br>
`https://<account>.file.core.windows.net`<br>

Queue Storage:<br>
`https://<account>.queue.core.windows.net`<br>

Table Storage:<br>
`https://<account>.table.core.windows.net`<br>

---

## 🧠 AZ-900 Exam Keywords

• Storage account = unique namespace<br>
• Highly available & scalable storage<br>
• Redundancy options (LRS, ZRS, GRS)<br>
• Multiple services in one account<br>
• Globally unique name<br>
• Service endpoints<br>

---

## 📒 Quick Notebook Summary

> Azure Storage Accounts provide a globally unique, secure, and scalable namespace for storing data using Blob, Files, Queue, and Table services. They support multiple redundancy models such as LRS, ZRS, and GRS for high availability and disaster recovery.

---

### 🎯 AWS Memory Shortcut

Storage account = container for all storage<br>
Blob = S3<br>
LRS = one location<br>
GRS = cross-region backup<br>
Endpoint = bucket URL style<br>

---


