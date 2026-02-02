## 💾 Azure Storage Services — AZ-900

Azure Storage provides multiple cloud storage services for different data and workload needs.<br>

Main services include:<br>
• Azure Blob Storage<br>
• Azure Files<br>
• Azure Queue Storage<br>
• Azure Disk Storage<br>
• Azure Table Storage<br>

---

## ⭐ Benefits of Azure Storage

• Highly durable and available<br>
• Built-in redundancy options<br>
• Encrypted by default<br>
• Massively scalable<br>
• Fully managed by Azure<br>
• Globally accessible via HTTP/HTTPS<br>
• Supports multiple languages & tools<br>

---

## 📦 Azure Blob Storage (Object Storage)

**Definition:**
Blob Storage is a massively scalable object storage service for unstructured data such as text, images, videos, and backups.<br>

---

### ✅ Best For

• Serving images and documents<br>
• Video/audio streaming<br>
• Backups and disaster recovery<br>
• Log files and analytics data<br>
• Large-scale unstructured data storage<br>

---

### 🔁 AWS Mapping

Azure Blob Storage ↔ Amazon S3<br>

---

## 🗂 Blob Storage Access Tiers (EXAM FAVORITE)

---

### 🔥 Hot Tier

• Frequently accessed data<br>
• Highest storage cost, lowest access cost<br>

---

### ❄ Cool Tier

• Infrequently accessed data (≥30 days)<br>
• Lower storage cost than hot<br>

---

### 🧊 Cold Tier

• Rarely accessed data (≥90 days)<br>
• Even lower cost than cool<br>

---

### 📦 Archive Tier

• Long-term storage (≥180 days)<br>
• Lowest storage cost<br>
• Highest retrieval cost & latency<br>
• Data stored offline<br>

---

📌 Exam Shortcut:<br>
Hot = active data<br>
Cool/Cold = infrequent<br>
Archive = long-term backup<br>

---

## 📂 Azure Files (File Shares)

**Definition:**
Azure Files provides fully managed cloud file shares accessible via SMB and NFS protocols.<br>

---

### ✅ Key Benefits

• Replace on-prem file servers<br>
• Accessible by Windows, Linux, macOS<br>
• Fully managed (no OS/hardware)<br>
• High availability & resiliency<br>
• Can sync locally using Azure File Sync<br>

---

### 🔁 AWS Mapping

Azure Files ↔ Amazon EFS / FSx<br>

---

## 📩 Azure Queue Storage

**Definition:**
Queue Storage stores large numbers of messages for asynchronous processing between application components.<br>

---

### ✅ Use Cases

• Background processing<br>
• Decoupling app components<br>
• Triggering Azure Functions<br>
• Handling traffic spikes smoothly<br>

---

### 🔁 AWS Mapping

Azure Queue Storage ↔ Amazon SQS<br>

---

## 💽 Azure Disk Storage

**Definition:**
Azure Disks are block-level managed storage volumes used by Azure Virtual Machines.<br>

---

### ✅ Key Points

• Acts like virtual hard drives<br>
• Fully managed by Azure<br>
• High performance and resiliency<br>

---

### 🔁 AWS Mapping

Azure Disk ↔ Amazon EBS<br>

---

## 📊 Azure Table Storage

**Definition:**
Azure Table Storage is a NoSQL key-value datastore for structured but non-relational data.<br>

---

### ✅ Best For

• Large structured datasets<br>
• Fast access at scale<br>
• Schema-less storage<br>

---

### 🔁 AWS Mapping

Azure Table Storage ↔ Amazon DynamoDB (conceptually)<br>

---

## 🧠 AZ-900 Exam Keywords

• Blob = object storage<br>
• Files = file shares<br>
• Queues = messaging<br>
• Disks = VM storage<br>
• Tables = NoSQL storage<br>
• Access tiers for cost optimization<br>

---

## 📒 Quick Notebook Summary

> Azure Storage offers services for object storage (Blob), file sharing (Files), messaging (Queues), VM disks (Disks), and NoSQL data (Tables). It is secure, scalable, highly available, and includes multiple access tiers to optimize storage costs.

---

### 🎯 AWS Memory Shortcut

Blob = S3<br>
Files = EFS<br>
Queue = SQS<br>
Disk = EBS<br>
Table = DynamoDB<br>

---

