# Cybersecurity-Task-1
This project demonstrates how to scan a local network for open ports using Nmap to understand network exposure and basic security risks. The objective is to identify active services running on devices in a local network and analyze potential vulnerabilities.
📌 Overview

This project demonstrates how to scan a local network and identify open ports using Nmap, a popular network security tool. The goal is to understand basic network reconnaissance and security concepts.

🎯 Objectives

Learn how to perform port scanning

Identify open ports and running services

Understand basic network security risks

🛠️ Tools Used

Nmap

Windows Command Prompt / PowerShell

Local Wi-Fi Network

📚 Key Concepts

Port Scanning

TCP SYN Scan

IP Ranges (CIDR)

Network Reconnaissance

Open Ports

Network Security Basics

⚙️ Steps Performed

Checked IP address using:

ipconfig


Identified local network range:

192.168.1.0/24


Scanned the router/device using:

nmap -sS -T4 -F -Pn 192.168.1.1


Observed open ports and services.

📊 Scan Results
Port	State	Service
53	Open	DNS
80	Open	HTTP
443	Open	HTTPS
🔐 Security Notes

Open ports can expose services to attackers. Unnecessary services should be closed, and firewalls should be configured to improve security.
Screenshots
<img width="1030" height="313" alt="Screenshot 2026-02-12 193531" src="https://github.com/user-attachments/assets/b80e9f41-8391-41e5-904b-5e43a7186a48" />


✅ Conclusion

This project helped understand how network devices expose services through ports and how port scanning is used in cybersecurity for vulnerability assessment.
