# networking-basics-for-cyber-security
Task-based practical guide covering Firewall concepts, rule configuration, port management, connectivity testing, log analysis, and security impact for Cyber Security beginners.
# 🔐 Networking Basics for Cyber Security

## 📌 Task 3 – Elevate Labs

### 👤 Name: Ch Rohit Kumar  
### 🎓 University: Aditya University  
### 📧 Email: rohitkumarrrr20@gmail.com  

---

## 📖 Project Overview

This repository contains practical and theoretical knowledge about **Firewall Configuration and Network Security Basics**.

The task covers:

- Firewall concepts
- Configuring firewall rules
- Allowing/Denying ports
- Testing connectivity
- Observing logs
- Blocking malicious IPs
- Documenting firewall rules
- Explaining security impact

---

# 🔥 1. Firewall Concepts

A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined security rules.

### 🎯 Purpose
- Prevent unauthorized access
- Protect against malware
- Enforce network security policies

### 🧱 Types of Firewalls
- Packet Filtering Firewall
- Stateful Inspection Firewall
- Proxy Firewall
- Next-Generation Firewall (NGFW)

### 🖥 Deployment Types
- Network-Based Firewall
- Host-Based Firewall

---

# ⚙ 2. Configure Firewall Rules

Firewall rules define which traffic is:
- Allowed
- Blocked

### Rule Components:
- Source IP
- Destination IP
- Port Number
- Protocol (TCP/UDP/ICMP)
- Direction (Inbound/Outbound)
- Action (Allow/Deny)

### Windows Configuration Steps:
1. Run `wf.msc`
2. Select Inbound or Outbound Rules
3. Click New Rule
4. Select Port
5. Choose TCP/UDP
6. Enter Port Number
7. Select Allow or Block
8. Apply Profile
9. Finish

---

# 🚪 3. Allow / Deny Ports

Common Ports:
- 80 → HTTP
- 443 → HTTPS
- 22 → SSH
- 21 → FTP

Allow only required ports.
Block unused or insecure ports.

---

# 🌐 4. Test Connectivity

### Tools Used:

- `ping`
- `telnet`
- `Test-NetConnection` (PowerShell)
- Web Browser Testing

Example:
