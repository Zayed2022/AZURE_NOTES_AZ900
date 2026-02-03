## 🔐 Azure Role-Based Access Control (RBAC) — AZ-900

**Azure RBAC** is an authorization system that controls who can access Azure resources and what actions they can perform based on assigned roles.<br>

---

## 📏 Principle of Least Privilege

• Users get only the access they need<br>
• No unnecessary permissions<br>
• Improves security and reduces risk<br>

---

📌 Exam Line:<br>
Grant minimum required permissions only.<br>

---

## 👥 How RBAC Works

• Azure provides built-in roles (Owner, Contributor, Reader, etc.)<br>
• You can create custom roles<br>
• Roles contain specific permissions<br>
• Users/groups are assigned roles<br>
• Access is automatically applied to resources<br>
<img width="488" height="267" alt="image" src="https://github.com/user-attachments/assets/7133f352-7bc6-4d62-8c80-ce3970423e48" />

---

## 📦 Common Built-in Roles (EXAM FAVORITE)

• Owner – full access + can assign roles<br>
• Contributor – full access but cannot assign roles<br>
• Reader – view-only access<br>

---

## 📍 RBAC Scope Levels (VERY IMPORTANT)

RBAC is applied at different scopes:<br>

• Management Group<br>
• Subscription<br>
• Resource Group<br>
• Individual Resource<br>

---

## 🌳 Hierarchical Inheritance

Permissions flow downward automatically:<br>

• Management group → subscriptions → resource groups → resources<br>

---

### 📌 Examples

Owner at management group → controls everything below<br>
Reader at subscription → can view all resources inside it<br>

---

## ⚙ How RBAC Is Enforced

• Enforced through Azure Resource Manager (ARM)<br>
• Works via:<br>
– Azure Portal<br>
– Azure CLI<br>
– PowerShell<br>
– Cloud Shell<br>

---

❗ RBAC controls resource actions only — not app-level data security.<br>

---

## ➕ RBAC Uses Allow Model

• Permissions are additive<br>
• Multiple roles combine permissions<br>
• No deny by default (deny is separate mechanism)<br>

---

📌 Example:<br>
One role allows read, another allows write → user gets both.<br>

---

## 🧠 AZ-900 Exam Keywords

• Authorization (not authentication)<br>
• Least privilege access<br>
• Role assignments<br>
• Scope hierarchy<br>
• Owner / Contributor / Reader<br>
• Enforced via Azure Resource Manager<br>

---

## 📒 Quick Notebook Summary

> Azure RBAC controls access to Azure resources using roles and scopes, ensuring users have only the permissions they need. Permissions inherit down the resource hierarchy and are enforced through Azure Resource Manager.

---

### 🎯 Super Easy Memory Trick

Login = Authentication (Entra ID)<br>
Permissions = Authorization (RBAC)<br>

---


