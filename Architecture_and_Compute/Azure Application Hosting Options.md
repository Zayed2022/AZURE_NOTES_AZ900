## 🌐 Azure Application Hosting Options (AZ-900)

Azure provides multiple ways to host applications depending on control, scalability, and management needs.<br>

Main options include:<br>
• Virtual Machines (IaaS)<br>
• Containers (PaaS/Orchestration)<br>
• Azure App Service (PaaS)<br>

---

## 🖥 Virtual Machines for Hosting

• Full control over OS and environment<br>
• Custom software and configurations<br>
• Requires OS patching and maintenance<br>
• Best for legacy or specialized workloads<br>

**AWS Mapping:**<br>
Azure VM ↔ AWS EC2<br>

---

## 📦 Containers for Hosting

• Lightweight application hosting<br>
• No full OS management<br>
• Fast scaling and deployment<br>
• Ideal for microservices<br>

**AWS Mapping:**<br>
AKS/ACI ↔ EKS/Fargate<br>

---

## ⚙ Azure App Service (IMPORTANT PaaS HOSTING)

**Definition:**
Azure App Service is a fully managed platform for hosting web applications, APIs, background jobs, and mobile backends without managing infrastructure.<br>

---

### ✅ Key Benefits

• No server or OS management<br>
• Automatic scaling<br>
• High availability built-in<br>
• Supports Windows and Linux<br>
• Continuous deployment from GitHub/Azure DevOps/Git repos<br>
• Built-in security and load balancing<br>

---

### 🔁 AWS Mapping

Azure App Service ↔ AWS Elastic Beanstalk (conceptually similar PaaS)<br>

---

## 📦 Types of App Services

---

### 🌍 Web Apps

• Host websites and web applications<br>
• Supports .NET, Java, Python, PHP, Node.js, Ruby<br>
• Windows or Linux hosting<br>

---

### 🔌 API Apps

• Host RESTful APIs<br>
• Supports multiple languages and frameworks<br>
• Swagger integration<br>
• Can be consumed by any HTTP/HTTPS client<br>

---

### ⚙ WebJobs

• Run background tasks or scripts<br>
• Triggered or scheduled execution<br>
• Used for app backend processing<br>

---

### 📱 Mobile Apps

• Backend services for mobile apps<br>
• Cloud database integration<br>
• User authentication via social providers<br>
• Push notifications<br>
• Backend logic execution<br>

---

## 🧠 AZ-900 Exam Keywords

• PaaS hosting service<br>
• No infrastructure management<br>
• Automatic scaling & high availability<br>
• Web apps, APIs, background jobs, mobile backends<br>
• Continuous deployment<br>

---

## 📒 Quick Notebook Summary

> Azure provides application hosting through VMs, containers, and Azure App Service. App Service is a fully managed PaaS platform for hosting web apps, APIs, background tasks, and mobile backends with built-in scaling, security, and high availability.

---

### 🎯 AWS Memory Shortcut

VM hosting = EC2<br>
Container hosting = EKS/Fargate<br>
App Service = Elastic Beanstalk style PaaS<br>

---

