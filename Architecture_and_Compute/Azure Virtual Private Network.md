## 🔐 Azure Virtual Private Network (VPN) — AZ-900

A Virtual Private Network (VPN) creates an encrypted tunnel over the public internet to securely connect private networks together.<br>

---

## 📡 Why Use VPN in Azure

• Secure data transfer over internet<br>
• Encrypted communication<br>
• Connect cloud and on-prem networks<br>
• Protect sensitive information<br>

---

### 🔁 AWS Mapping

Azure VPN Gateway ↔ AWS VPN Gateway<br>

---

## 🚪 Azure VPN Gateway

**Definition:**
Azure VPN Gateway is a virtual network gateway that enables secure encrypted connectivity between Azure VNets, on-premises networks, and devices.<br>

---

### 🔗 Supported Connections

• Site-to-Site VPN (on-prem network ↔ Azure VNet)<br>
• Point-to-Site VPN (individual device ↔ Azure VNet)<br>
• VNet-to-VNet VPN (Azure network ↔ Azure network)<br>

---

📌 Only one VPN gateway per VNet (but can connect to multiple locations).<br>

---

## 🔐 VPN Types (Exam Concept)

---

### 📋 Policy-Based VPN

• Uses static IP address rules<br>
• Encrypts specific traffic defined by policies<br>
• Older approach<br>

---

### 🛣 Route-Based VPN (Preferred)

• Uses dynamic routing<br>
• More flexible and resilient<br>
• Supports:<br>
– VNet-to-VNet connections<br>
– Point-to-Site<br>
– Multisite connections<br>
– ExpressRoute coexistence<br>
– High availability scenarios<br>

---

📌 Exam Line:<br>
Route-based VPN is preferred and more flexible than policy-based VPN.<br>

---

## ⚙ High Availability Options for VPN Gateway

---

### 🔄 Active/Standby (Default)

• Two gateway instances deployed automatically<br>
• One active, one backup<br>
• Automatic failover<br>
• Short connection interruption<br>

---

### 🔁 Active/Active

• Both gateways active simultaneously<br>
• Each has its own public IP<br>
• Uses BGP routing<br>
• Higher availability<br>

---

### 🚀 ExpressRoute Failover

• VPN acts as backup if ExpressRoute fails<br>
• Ensures continuous connectivity<br>

---

### 🛡 Zone-Redundant Gateways

• Deployed across availability zones<br>
• Protect against zone failures<br>
• Higher resiliency and uptime<br>

---

## 🧠 AZ-900 Exam Keywords

• Encrypted tunnel over internet<br>
• VPN Gateway<br>
• Site-to-site, point-to-site, VNet-to-VNet<br>
• Route-based vs policy-based VPN<br>
• High availability configurations<br>
• Hybrid connectivity<br>

---

## 📒 Quick Notebook Summary

> Azure VPN uses encrypted tunnels to securely connect Azure VNets with on-premises networks, devices, or other VNets. Azure VPN Gateway supports site-to-site, point-to-site, and network-to-network connections, with route-based VPN being the preferred method and built-in high availability options.

---

### 🎯 AWS Memory Shortcut

Azure VPN Gateway = AWS VPN Gateway<br>
Route-based VPN = modern flexible VPN<br>
Site-to-site = office ↔ cloud<br>
Point-to-site = laptop ↔ cloud<br>

---

