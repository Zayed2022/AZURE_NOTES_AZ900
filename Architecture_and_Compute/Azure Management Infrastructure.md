## 🗂 Azure Management Infrastructure (AZ-900)

Azure management infrastructure organizes resources using a hierarchical structure to manage access, billing, and governance efficiently.<br>

Hierarchy (top to bottom):<br>
**Management Groups → Subscriptions → Resource Groups → Resources**<br>

---

## 📦 Azure Resources

**Definition:**
A resource is the basic building block in Azure — anything you create such as VMs, databases, networks, or AI services.<br>

---

### 📌 Examples

• Virtual Machines<br>
• Virtual Networks<br>
• Databases<br>
• Storage accounts<br>
• Cognitive services<br>

---

### 🔁 AWS Mapping

Azure Resource ↔ AWS Resource (EC2, S3, RDS, etc.)<br>

---

## 📁 Resource Groups

**Definition:**
Resource groups are logical containers that hold related Azure resources together.<br>

---

### ✅ Key Characteristics

• Every resource must belong to one resource group<br>
• A resource can belong to only one resource group at a time<br>
• Resource groups cannot be nested<br>
• Deleting a resource group deletes all its resources<br>
• Permissions apply to all resources inside the group<br>

---

### 🎯 Why Use Resource Groups

• Organize resources by project or environment<br>
• Apply access control easily<br>
• Delete environments quickly (dev/test)<br>
• Manage resources together<br>

---

### 🔁 AWS Mapping

Azure Resource Group ↔ AWS Resource grouping via tags (conceptually similar)<br>

---

## 🧾 Azure Subscriptions

**Definition:**
A subscription is a boundary for billing, access control, and resource management in Azure.<br>
<img width="654" height="269" alt="image" src="https://github.com/user-attachments/assets/abc09ece-ba78-4949-b553-c22f29479c8b" />

---

### 📌 Key Functions

• Required to use Azure services<br>
• Links to an Azure account (Entra ID identity)<br>
• Can contain multiple resource groups<br>
• One account can have multiple subscriptions<br>

---

### 🧱 Subscription Boundaries

**Billing boundary:** separate cost tracking & invoices<br>
**Access boundary:** apply different permissions & policies<br>

---

### 🎯 Common Uses for Multiple Subscriptions

• Separate dev/test/production environments<br>
• Isolate departments or teams<br>
• Track costs separately<br>
• Meet compliance needs<br>

---

### 🔁 AWS Mapping

Azure Subscription ↔ AWS Account<br>

---

## 🏗 Azure Management Groups

**Definition:**
Management groups organize multiple subscriptions to apply policies and access controls at scale.<br>

---

### ✅ Benefits

• Apply governance policies across many subscriptions<br>
• Centralized access control (RBAC)<br>
• Support large enterprise environments<br>
• Policies inherit down the hierarchy<br>

---

### 📌 Examples

• Restrict VM regions across all subscriptions<br>
• Apply security policies centrally<br>
• Grant user access across multiple subscriptions at once<br>

---

### 📊 Management Group Facts (Exam Focus)

• Up to 10,000 management groups per directory<br>
• Hierarchy depth up to 6 levels (excluding root & subscription)<br>
• Each group/subscription has only one parent<br>
• Management groups can be nested<br>
<img width="608" height="376" alt="image" src="https://github.com/user-attachments/assets/5c8e7cb8-d845-457c-a18b-9512b7d73850" />

---

### 🔁 AWS Mapping

Azure Management Groups ↔ AWS Organizations (organizational units concept)<br>

---

## 🧠 AZ-900 Exam Keywords

• Resource = basic unit<br>
• Resource Group = logical container<br>
• Subscription = billing & access boundary<br>
• Management Group = governance across subscriptions<br>
• Hierarchical inheritance<br>

---

## 📒 Quick Notebook Summary

> Azure organizes resources in a hierarchy: management groups contain subscriptions, subscriptions contain resource groups, and resource groups contain resources. This structure enables efficient governance, access control, and cost management across environments.

---

### 🎯 AWS Memory Shortcut

Resource = EC2/S3/etc<br>
Resource Group = tagged grouping concept<br>
Subscription = AWS account<br>
Management Group = AWS Organizations<br>

---

