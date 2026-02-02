## 📁 Azure File Movement Options — AZ-900

Azure provides tools to move, copy, and synchronize individual files or small datasets into and within Azure Storage.<br>

Main tools include:<br>
• AzCopy (CLI-based transfer)<br>
• Azure Storage Explorer (GUI-based management)<br>
• Azure File Sync (hybrid file synchronization)<br>

---

## ⚡ AzCopy (Command-Line Tool)

**Definition:**
AzCopy is a command-line utility for copying and synchronizing blobs and files between local systems and Azure Storage accounts.<br>

---

### ✅ Key Features

• Upload files to Azure<br>
• Download files from Azure<br>
• Copy between storage accounts<br>
• Synchronize files/blobs (one-direction only)<br>
• High-performance transfers<br>
• Can interact with other cloud providers<br>

---

📌 Exam Tip:<br>
AzCopy sync is one-way only (not bi-directional).<br>

---

### 🔁 AWS Mapping

AzCopy ↔ AWS CLI + S3 sync (conceptually)<br>

---

## 🖥 Azure Storage Explorer (GUI Tool)

**Definition:**
Azure Storage Explorer is a desktop application that provides a graphical interface to manage Azure Storage resources.<br>

---

### ✅ Key Features

• Visual file & blob management<br>
• Upload/download data easily<br>
• Move data between storage accounts<br>
• Works on Windows, macOS, Linux<br>
• Uses AzCopy behind the scenes<br>

---

### 🔁 AWS Mapping

Azure Storage Explorer ↔ AWS S3 Console / Cloud tools GUI (conceptually)<br>

---

## 🔄 Azure File Sync (Hybrid Sync Tool)

**Definition:**
Azure File Sync keeps on-premises Windows file servers synchronized bi-directionally with Azure Files in the cloud.<br>

---

### ✅ Key Capabilities

• Centralize file shares in Azure Files<br>
• Bi-directional synchronization<br>
• Multiple on-prem caches globally<br>
• Fast local access + cloud backup<br>
• Easy server replacement after failure<br>
• Supports cloud tiering (hot local, cold cloud data)<br>

---

📌 Exam Line:<br>
Azure File Sync = hybrid + bi-directional sync<br>

---

### 🔁 AWS Mapping

Azure File Sync ↔ AWS DataSync + caching solutions (conceptually)<br>

---

## 🧠 AZ-900 Exam Keywords

• AzCopy = CLI file transfer<br>
• Storage Explorer = GUI management tool<br>
• File Sync = hybrid bi-directional sync<br>
• One-way vs two-way sync differences<br>
• Cloud tiering for cost optimization<br>

---

## 📒 Quick Notebook Summary

> Azure offers AzCopy for fast command-line file transfers, Azure Storage Explorer for graphical storage management, and Azure File Sync for bi-directional synchronization between on-prem file servers and Azure Files with cloud tiering.

---

### 🎯 Easy Memory Trick

AzCopy = fast copy CLI<br>
Storage Explorer = visual tool<br>
File Sync = hybrid two-way sync<br>

---
