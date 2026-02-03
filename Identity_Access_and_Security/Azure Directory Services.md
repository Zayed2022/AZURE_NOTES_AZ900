## 🧾 Azure Directory Services — AZ-900

**Microsoft Entra ID** is Azure’s cloud-based identity and access management (IAM) service used to manage users, sign-ins, and access to applications and resources.<br>

(It is the cloud version of traditional Active Directory)<br>

---

## ☁ On-Prem AD vs Microsoft Entra ID

**Active Directory (on-prem):**<br>
• Runs on Windows Server<br>
• Fully managed by organization<br>
• Local identity system<br>

**Microsoft Entra ID (cloud):**<br>
• Cloud-managed directory service<br>
• Global availability by Microsoft<br>
• Built-in security monitoring<br>
• Identity for Azure & Microsoft services<br>

---

📌 Exam Line:<br>
Entra ID = cloud identity service<br>
Active Directory = on-prem identity service<br>

---

## 🔐 Extra Security with Entra ID

• Detects suspicious sign-ins<br>
• Supports Multi-Factor Authentication (MFA)<br>
• Smart lockout protection<br>
• Self-service password reset<br>
• Banned password lists<br>

---

## 👥 Who Uses Entra ID?

• IT admins – manage access & policies<br>
• Developers – add authentication & SSO to apps<br>
• Users – manage passwords & identities<br>
• Microsoft service users – Azure, Microsoft 365, Dynamics<br>

---

## ⚙ Core Features of Microsoft Entra ID

---

### 🔑 Authentication

• User sign-in verification<br>
• MFA<br>
• Password protection<br>
• Smart lockout<br>

---

### 🔁 Single Sign-On (SSO)

• One login for many apps<br>
• Simplifies access control<br>
• Improves security & user experience<br>

---

### 📦 Application Management

• Manage cloud & on-prem apps<br>
• SaaS integrations<br>
• Application Proxy<br>
• My Apps portal<br>

---

### 💻 Device Management

• Register devices<br>
• Works with Microsoft Intune<br>
• Enforce Conditional Access rules<br>
• Allow only trusted devices<br>

---

## 🔗 Hybrid Identity (On-Prem + Cloud)

**Microsoft Entra Connect** synchronizes identities between:<br>

On-prem Active Directory ↔ Microsoft Entra ID<br>

---

### ✅ Benefits

• Same user identity in cloud & on-prem<br>
• SSO across environments<br>
• MFA works everywhere<br>
• Password sync<br>

---

📌 Exam Line:<br>
Entra Connect = identity synchronization tool<br>

---

## 🏢 Microsoft Entra Domain Services (Managed AD)

**Definition:**
Entra Domain Services provides managed domain services in Azure without managing domain controllers.<br>

---

### ✅ What It Provides

• Domain join<br>
• Group Policy<br>
• LDAP<br>
• Kerberos & NTLM authentication<br>
• Legacy app compatibility<br>

---

📌 Key Advantage:<br>
No need to install, patch, or manage domain controllers.<br>

Azure handles everything.<br>

---

## 🚀 Why Use Entra Domain Services?

• Lift & shift legacy apps to Azure<br>
• Apps needing classic AD authentication<br>
• No on-prem dependency<br>
• Fully managed AD in cloud<br>

---

## 🔄 How It Works

• Azure deploys two managed domain controllers<br>
• You define a domain namespace<br>
• Azure handles backups, updates, security<br>

---

## 🔁 Synchronization Flow (IMPORTANT)

On-prem AD → Entra ID → Entra Domain Services<br>

(one-way sync into Domain Services)<br>

❗ Changes in Domain Services do NOT sync back to Entra ID<br>
<img width="2560" height="757" alt="image" src="https://github.com/user-attachments/assets/bdbc50c7-fb55-463c-9326-de1906e8a1d1" />

---

## 🧠 AZ-900 Exam Keywords

• Microsoft Entra ID = cloud IAM<br>
• Authentication & SSO<br>
• MFA & security monitoring<br>
• Entra Connect = hybrid sync<br>
• Entra Domain Services = managed AD in Azure<br>
• No domain controller management<br>

---

## 📒 Quick Notebook Summary

> Microsoft Entra ID is Azure’s cloud identity and access management service providing authentication, SSO, MFA, and app access. It integrates with on-prem Active Directory using Entra Connect. Entra Domain Services offers fully managed domain services in Azure for legacy applications without maintaining domain controllers.

---

### 🎯 Super Easy Memory Trick

Entra ID = cloud login system<br>
Entra Connect = sync bridge<br>
Entra Domain Services = managed Active Directory in Azure<br>

---
