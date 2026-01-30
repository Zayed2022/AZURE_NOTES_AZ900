## 🌐 Azure Virtual Networking (VNet) — AZ-900

Azure Virtual Network (VNet) enables secure communication between Azure resources, the internet, and on-premises networks.<br>

---

## 🧱 What Azure VNet Does

• Connect Azure resources (VMs, apps, databases)<br>
• Connect Azure to on-premises networks<br>
• Enable internet access<br>
• Provide isolation and segmentation<br>
• Control routing and traffic flow<br>
• Filter and secure network traffic<br>
• Connect multiple VNets together<br>

---

### 🔁 AWS Mapping

Azure Virtual Network (VNet) ↔ AWS VPC<br>
Subnets ↔ AWS Subnets<br>

---

## 🌍 Public vs Private Endpoints

**Public Endpoint:**<br>
• Has public IP address<br>
• Accessible from internet<br>

**Private Endpoint:**<br>
• Has private IP within VNet<br>
• Accessible only inside Azure network<br>

---

## 🔐 Isolation & Segmentation

• Each VNet has its own private IP address space<br>
• IP space is not internet routable<br>
• VNets are divided into subnets<br>
• Subnets organize and isolate resources<br>
• Supports built-in or custom DNS<br>

---

## 🌐 Internet Communication

• Assign public IP to resources<br>
• Use public load balancers for inbound access<br>

---

## 🔁 Communication Between Azure Resources

• VMs, AKS, App Service Environments can connect inside VNet<br>
• Service Endpoints securely connect to Azure services (SQL, Storage)<br>

---

## 🏢 Connect Azure to On-Premises (Hybrid Networking)

---

### 🔐 Point-to-Site VPN

• Individual device connects to Azure VNet<br>
• Encrypted connection over internet<br>

---

### 🏗 Site-to-Site VPN

• On-prem gateway connects to Azure gateway<br>
• Entire network appears connected<br>
• Encrypted tunnel over internet<br>

---

### 🚀 ExpressRoute (Exam Favorite)

• Private dedicated connection to Azure<br>
• Does NOT use public internet<br>
• High security & bandwidth<br>

---

### 🔁 AWS Mapping

Azure VPN ↔ AWS VPN<br>
Azure ExpressRoute ↔ AWS Direct Connect<br>

---

## 🛣 Routing Network Traffic

• Default system routes provided by Azure<br>
• Custom routes using route tables (UDR)<br>
• BGP propagates routes from on-prem to Azure<br>

---

## 🚦 Filtering Network Traffic

---

### 🔒 Network Security Groups (NSG)

• Inbound and outbound security rules<br>
• Allow or block traffic<br>
• Based on IP, port, protocol<br>

---

### 🧰 Network Virtual Appliances (NVA)

• Special firewall or networking VMs<br>
• Advanced traffic control and security<br>

---

### 🔁 AWS Mapping

NSG ↔ AWS Security Groups / NACLs<br>

---

## 🔗 Connect Virtual Networks

---

### 🔄 VNet Peering

• Direct private connection between VNets<br>
• Traffic stays on Microsoft backbone<br>
• Can connect across regions<br>

---

### 🛣 User Defined Routes (UDR)

• Custom routing between subnets or VNets<br>
• Full control of traffic paths<br>

---

## 🧠 AZ-900 Exam Keywords

• VNet = private Azure network<br>
• Subnets for segmentation<br>
• Public vs private endpoints<br>
• VPN & ExpressRoute hybrid connectivity<br>
• NSG for traffic filtering<br>
• VNet peering for network linking<br>

---

## 📒 Quick Notebook Summary

> Azure Virtual Network provides private networking for Azure resources with isolation, secure communication, routing control, traffic filtering, and hybrid connectivity using VPN and ExpressRoute. VNets can be segmented into subnets and connected through peering.

---

### 🎯 AWS Memory Shortcut

VNet = VPC<br>
Subnet = Subnet<br>
NSG = Security Group<br>
VPN = VPN Gateway<br>
ExpressRoute = Direct Connect<br>
Peering = VPC Peering<br>

---
