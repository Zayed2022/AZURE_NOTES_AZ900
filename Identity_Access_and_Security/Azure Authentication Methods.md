## 🔐 Azure Authentication Methods — AZ-900

**Authentication** is the process of verifying the identity of a user, device, or service before granting access.<br>

(Like showing ID to prove who you are)<br>
<img width="898" height="440" alt="image" src="https://github.com/user-attachments/assets/34ea4ccc-0638-4a36-8a2b-4a0ca39036c1" />

---

## ☁ Common Azure Authentication Methods

• Password-based authentication<br>
• Single Sign-On (SSO)<br>
• Multifactor Authentication (MFA)<br>
• Passwordless authentication<br>

---

## 🔁 Security vs Convenience (Exam Concept)

• Password only = convenient but low security<br>
• MFA = high security but less convenient<br>
• Passwordless = high security + high convenience<br>

---

## 🔑 Single Sign-On (SSO)

**Definition:**
SSO allows users to sign in once and access multiple applications using the same credentials.<br>

---

### ✅ Benefits

• One username & password for many apps<br>
• Simplifies user experience<br>
• Reduces password fatigue<br>
• Easier access control management<br>
• Fewer helpdesk password resets<br>

---

📌 Important Exam Note:<br>
SSO is only as secure as the initial authentication method.<br>

---

## 🔐 Multifactor Authentication (MFA)

**Definition:**
MFA requires two or more verification factors to confirm identity during login.<br>

---

### 📦 Authentication Factors

• Something you know – password, PIN, security question<br>
• Something you have – phone, security code, token<br>
• Something you are – fingerprint, face scan, biometrics<br>

---

### ✅ Why MFA Is Important

• Protects against stolen passwords<br>
• Prevents unauthorized access<br>
• Strongly recommended for all accounts<br>

---

### ☁ Microsoft Entra MFA

• Phone call<br>
• SMS code<br>
• Authenticator app notification<br>

---

📌 Exam Line:<br>
MFA dramatically improves security.<br>

---

## 🔓 Passwordless Authentication (EXAM FAVORITE)

**Definition:**
Passwordless authentication removes the need for passwords and uses secure methods like biometrics or trusted devices.<br>

---

### ✅ Advantages

• Higher security than passwords<br>
• More convenient for users<br>
• No password theft risk<br>

---

## 🔐 Passwordless Options in Azure

---

### 💻 Windows Hello for Business

• Biometric (face/fingerprint) or PIN<br>
• Tied to specific Windows device<br>
• Built-in SSO support<br>
• Very secure for corporate PCs<br>

---

### 📱 Microsoft Authenticator App

• Phone becomes login method<br>
• Approve sign-in with notification<br>
• Uses biometric or PIN<br>
• Works across platforms<br>

---

### 🔑 FIDO2 Security Keys

• Physical hardware authentication devices<br>
• USB, NFC, or Bluetooth keys<br>
• Resistant to phishing attacks<br>
• Open authentication standard<br>

---

📌 Exam Line:<br>
FIDO2 = strongest passwordless method<br>

---

## 🧠 AZ-900 Exam Keywords

• Authentication vs authorization (don’t confuse)<br>
• SSO = one login many apps<br>
• MFA = multiple verification factors<br>
• Passwordless = no passwords + high security<br>
• Windows Hello, Authenticator, FIDO2 keys<br>

---

## 📒 Quick Notebook Summary

> Azure authentication includes passwords, Single Sign-On (SSO), Multifactor Authentication (MFA), and passwordless methods. MFA improves security using multiple verification factors, while passwordless options like Windows Hello, Authenticator App, and FIDO2 keys provide high security with better user experience.

---

### 🎯 Super Easy Memory Trick

SSO = one login everywhere<br>
MFA = extra verification step<br>
Passwordless = no passwords at all<br>

---

