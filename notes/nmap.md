# 🔍 Nmap Notes

## What is Nmap?
Nmap (Network Mapper) is a free, open-source tool used for network discovery and security auditing. It is commonly used by cybersecurity professionals to identify hosts, services, and potential vulnerabilities in a network.

---

## Basic Commands
- `nmap <IP>` – Simple ping scan  
- `nmap -sV <IP>` – Scan and detect service versions  
- `nmap -A <IP>` – Aggressive scan (OS detection, version, script, traceroute)  
- `nmap -p 1-65535 <IP>` – Scan all ports  

---

## Example Output
```bash
PORT     STATE  SERVICE VERSION
22/tcp   open   ssh     OpenSSH 8.4
80/tcp   open   http    Apache httpd 2.4.49

---
