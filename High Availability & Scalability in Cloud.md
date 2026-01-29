## 📈 High Availability & Scalability in Cloud (AZ-900)

When deploying cloud applications, two key goals are:<br>
• High Availability (uptime)<br>
• Scalability (handling demand)<br>

---

## ✅ High Availability

**Definition:**
High availability ensures cloud resources remain accessible and operational even during failures or disruptions.<br>

---

### ☁ In Azure (and AWS)

• Applications are deployed across multiple datacenters/regions<br>
• Built-in redundancy reduces downtime<br>
• Services come with uptime guarantees called SLAs (Service Level Agreements)<br>

---

### 🔁 AWS Mapping

Azure High Availability ↔ AWS High Availability<br>

Examples:<br>
• Azure Availability Zones ↔ AWS Availability Zones<br>
• Azure Load Balancer ↔ AWS ELB<br>

---

### 📌 Exam Points

• High availability focuses on uptime<br>
• Achieved through redundancy and SLAs<br>
• Protects against failures and outages<br>

---

## 📊 Scalability

**Definition:**
Scalability is the ability to increase or decrease cloud resources to meet workload demand.<br>

---

### ☁ Why Scalability Matters

• Handle traffic spikes smoothly<br>
• Avoid performance issues<br>
• Reduce cost when demand drops<br>
• Supports consumption-based pricing model<br>

---

## 🔄 Types of Scaling (VERY IMPORTANT FOR EXAM)

---

### ⬆ Vertical Scaling (Scale Up / Down)

• Increase or decrease resource power<br>
• Add more CPU, RAM, or storage to a VM<br>
• Suitable for short-term or limited growth<br>

**AWS Mapping:**<br>
Resize EC2 instance ↔ Resize Azure VM<br>

**Exam Line:**<br>
Vertical scaling changes resource size<br>

---

### ➕ Horizontal Scaling (Scale Out / In)

• Add or remove multiple resources<br>
• Add more VMs or containers during high demand<br>
• Remove them when demand drops<br>
• Often automated (auto-scaling)<br>

**AWS Mapping:**<br>
Auto Scaling Group ↔ Azure VM Scale Sets<br>

**Exam Line:**<br>
Horizontal scaling adds or removes resources<br>

---

## 🧠 AZ-900 Exam Keywords

• High availability = uptime & reliability<br>
• Scalability = adjust resources to meet demand<br>
• Vertical scaling = increase power<br>
• Horizontal scaling = increase number of resources<br>
• SLA = uptime guarantee<br>

---

## 📒 Quick Notebook Summary

> High availability ensures cloud services remain operational through redundancy and SLAs. Scalability allows resources to grow or shrink based on demand. Vertical scaling increases resource capacity, while horizontal scaling adds or removes resource instances.

---

### 🎯 AWS Memory Shortcut

High availability = multiple AZs working together<br>
Vertical scale = bigger machine<br>
Horizontal scale = more machines<br>

---

