## 🛡 Defense-in-Depth — Azure Security Concept

**Defense-in-Depth** is a layered security strategy designed to protect data by using multiple levels of security controls.<br>

The goal is to **slow down attacks**, limit damage, and prevent unauthorized access — even if one layer is breached.<br>

---

## 🎯 Core Objective

👉 Protect sensitive information<br>
👉 Prevent unauthorized access<br>
👉 Avoid relying on a single security control<br>

---

📌 Exam Line:<br>
Defense-in-depth uses multiple security layers to protect data from attacks.<br>

---

## 🧱 Defense-in-Depth Layers (From Outside to Center)

Each layer protects the next one inside it — with **data at the core**.
<img width="271" height="305" alt="image" src="https://github.com/user-attachments/assets/da2fee5d-65d0-4788-9b1a-d4f5975ea47a" />

---

### 🏢 Physical Security

• Protect datacenters and hardware<br>
• Control building access<br>
• Surveillance and restricted zones<br>

---

### 👤 Identity & Access

• Control who can access resources<br>
• Use SSO (Single Sign-On)<br>
• Enable MFA (Multi-Factor Authentication)<br>
• Audit sign-ins and changes<br>

---

### 🌐 Perimeter

• Protect against large-scale attacks<br>
• Use DDoS protection<br>
• Use perimeter firewalls<br>

---

### 🔗 Network

• Segment networks (subnets, NSGs)<br>
• Deny by default<br>
• Allow only required traffic<br>
• Secure on-premises connectivity<br>

---

### 🖥 Compute

• Secure virtual machines<br>
• Patch systems regularly<br>
• Use endpoint protection<br>
• Reduce malware risks<br>

---

### 📦 Application

• Build secure apps by design<br>
• Fix vulnerabilities early<br>
• Secure secrets (keys, passwords)<br>
• Follow secure development practices<br>

---

### 🗄 Data (MOST IMPORTANT TARGET)

• Protect business & customer data<br>
• Control access permissions<br>
• Encrypt stored data<br>
• Follow compliance rules<br>

---

## 🔄 Why Multiple Layers Matter

If one layer fails → another layer blocks the attacker.<br>

This:

• Slows attackers<br>
• Reduces blast radius<br>
• Gives time to detect & respond<br>

---

## 🧠 AZ-900 Exam Keywords

• Layered security model<br>
• Multiple protection mechanisms<br>
• Data at the center<br>
• No single point of failure<br>
• Physical → Identity → Network → Compute → App → Data<br>

---

## 📒 Quick Notebook Summary

> Defense-in-depth is a layered security approach that protects data by using multiple security controls across physical, identity, network, compute, application, and data layers to reduce risk and prevent breaches.

---

### 🎯 Easy Memory Trick

**P I P N C A D**

Physical
Identity
Perimeter
Network
Compute
Application
Data

(Data is always the final target 🎯)

---

