# -Setup-and-Use-a-Firewall-on-Windo# 📡 Telnet Server Setup & Testing (Kali Linux + Target Machine)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux%20%7C%20Ubuntu%20%7C%20Metasploitable-blue)  
![Security](https://img.shields.io/badge/Security-Lab%20Environment%20Only-red)

---

## 📌 Overview
This project demonstrates **how to set up and test a Telnet server** in a local lab environment using:
- **Target Machine** (Ubuntu/Debian/Metasploitable) as the Telnet server.
- **Kali Linux** as the Telnet client.  

It is useful for:
- Learning **legacy network services**.
- Practicing **Vulnerability Assessment & Penetration Testing (VAPT)**.
- Understanding **network connectivity troubleshooting**.

---

## ⚙️ Prerequisites
- Two systems on the **same network**:
  - **Server**: Ubuntu/Debian/Metasploitable  
  - **Client**: Kali Linux
- Root or `sudo` privileges.
- Basic networking knowledge (IP addresses, ports).

---

## 🛠 Server Setup (Target Machine)

1. **Update system packages**
   ```bash
   sudo apt update
ws-Linux
