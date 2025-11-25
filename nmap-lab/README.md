# 🔍 Nmap Lab — Network Scanning in an Isolated Environment

This lab demonstrates how to perform safe network enumeration using *Nmap* inside a fully isolated cybersecurity environment.

> 🧪 Part of my lab project:  
> https://github.com/Hanna-Solo/lab-setup

---

## 🎯 Purpose  
- Practice safe network scanning  
- Identify open ports, running services, and potential misconfigurations  
- Work inside an isolated Docker-based lab

---

## 🛰 Target Setup  
The target machine is part of the isolated lab created with Docker Compose.

---

## 📡 Nmap Scan Command

```bash
nmap -sC -sV -oN nmap.txt <TARGET-IP>

Replace <TARGET-IP> with the internal IP of the vulnerable container (e.g., Juice Shop or DVWA).


---

📝 Scan Output

See full scan results:
➡ nmap.txt


---

📸 Evidence (Optional)

Add a screenshot of the terminal running the scan.


---

🛡 Lessons Learned

Importance of safe, contained environments

Understanding exposed services

Identifying weak configurations

Forming a structured methodology for reconnaissance
