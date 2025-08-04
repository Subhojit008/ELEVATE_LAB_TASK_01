# 🔍 Task 1: Scan Your Local Network for Open Ports

## 🎯 Objective:
To perform a basic port scan on a local network device using Nmap to identify open ports and understand network exposure. This task helps build foundational skills in network reconnaissance and cybersecurity awareness.

---

## 🛠 Tools Used:
- **Nmap (Zenmap GUI)** – for scanning and identifying open TCP ports.
- **Operating System** – Windows 10
- **Target IP** – 192.168.29.238

---

## 📡 Step-by-Step Execution:

### 1. Find Local IP Range:
Used the `ipconfig` command to identify local IP.
Local network range: `192.168.29.0/24`

---

### 2. Scan Target IP using Zenmap (Nmap GUI):

**Command Used:*nmap -sS 192.168.29.238*

This performs a **TCP SYN scan**, a fast and common way to identify open ports.

---

## 📊 Actual Nmap Output:
Nmap scan report for 192.168.29.238
Host is up (0.00018s latency).
Not shown: 593 closed tcp ports (reset)
PORT STATE SERVICE
135/tcp open msrpc
139/tcp open netbios-ssn
445/tcp open microsoft-ds
4343/tcp open unicall
4449/tcp open privatewire
8000/tcp open http-alt
8089/tcp open unknown

Nmap done: 1 IP address (1 host up) scanned in 0.39 seconds
