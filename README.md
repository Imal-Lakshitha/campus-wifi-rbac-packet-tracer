# campus-wifi-rbac-packet-tracer
Campus Wi-Fi RBAC network using VLANs, ACLs, and NAT in Cisco Packet Tracer
# 📡 Campus Wi-Fi Network with Role-Based Access Control (RBAC)

## 📌 Project Overview
This project demonstrates the design and implementation of a **secure campus Wi-Fi network** using **Cisco Packet Tracer**.  
The network uses **Role-Based Access Control (RBAC)** to control user access based on roles such as **Student, Staff, and Admin**.

The goal of this project is to simulate a **real-world campus network** with proper **segmentation, security, and Internet access**.

---

## 🎯 Objectives
- Design a campus Wi-Fi network using VLANs
- Implement Role-Based Access Control using ACLs
- Allow controlled inter-VLAN communication
- Provide Internet access using NAT
- Apply basic network security best practices
.
---

## 🧩 Network Design
The network is divided into multiple VLANs:

| VLAN ID | Role    | Access Policy |
|-------|---------|---------------|
| 10 | Student | Internet only |
| 20 | Staff | Server + Internet |
| 30 | Admin | Full access |
| 40 | Server | Internal services |

The network uses **Router-on-a-Stick** for inter-VLAN routing.

---

## 🔐 Access Control Policy (RBAC)

### 🧑‍🎓 Student
- ❌ Cannot access Staff, Admin, or Server
- ✅ Can access the Internet

### 👨‍💼 Staff
- ❌ Cannot access Student or Admin
- ✅ Can access Server and Internet

### 👨‍💻 Admin
- ✅ Full access to all VLANs
- ✅ Internet access

Extended **Access Control Lists (ACLs)** are used to enforce these policies.

---

## 🌐 Internet Access
- Network Address Translation (**NAT**) is configured on the Campus Router
- All VLANs can access the Internet
- Internet is simulated using an ISP router

---

## 🛠️ Technologies Used
- Cisco Packet Tracer  
- VLANs & 802.1Q Trunking  
- Router-on-a-Stick  
- Extended Access Control Lists (ACLs)  
- Network Address Translation (NAT)  
- Wireless Access Points  
- IP Addressing & Subnetting  

---

## 📁 Repository Contents
- `Campus_WiFi_RBAC_Final.pkt` – Cisco Packet Tracer project file
- `screenshots/` – Network topology and testing screenshots
- `README.md` – Project documentation

---

## 🧠 What I Learned
- VLAN-based network segmentation
- Implementing RBAC using ACLs
- Troubleshooting Layer 2 and Layer 3 issues
- Wireless network configuration in campus environments
- Real-world networking concepts used in enterprises

---

## 🚀 Future Improvements
- DHCP server implementation
- Firewall integration
- Attack–Defense network simulation
- Network monitoring and logging
- Automation and scripting

---

## 👤 Author
**Imal**  
Aspiring Network Engineer  
Learning CCNA & Network Security

---

## 🏷️ Tags
`#Networking` `#Cisco` `#CCNA` `#PacketTracer` `#NetworkSecurity` `#VLAN` `#ACL` `#RBAC`
