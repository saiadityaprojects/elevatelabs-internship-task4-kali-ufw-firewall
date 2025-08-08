# Elevate Labs Task 4: Kali Linux UFW Firewall Configuration

This repository documents **Task 4** of my cybersecurity internship at **Elevate Labs**, where I configured a basic firewall using UFW (Uncomplicated Firewall) on Kali Linux. The goal was to secure a local system by controlling inbound traffic — specifically allowing SSH (port 22) and blocking Telnet (port 23).

---

## 🔧 Task Objective

To manage network traffic filtering using UFW in Kali Linux by allowing secure services and blocking legacy/insecure ports. All configurations were performed in a controlled, educational environment.

---

## 🖥️ System Details

- **OS**: Kali Linux 2024.2  
- **Firewall Tool**: UFW  
- **Target IP**: `192.168.150.133`  
- **Terminal**: GNOME Terminal

---

## 🛠️ Commands Executed

```bash
sudo ufw status
sudo ufw enable
sudo ufw deny 23
sudo ufw allow 22
sudo ufw status numbered
sudo ufw delete deny 23
sudo ufw status verbose
