# Cybersecurity Home Lab Portfolio
### Blue Team & Red Team Operations

## 📌 Project Overview
This repository documents my journey building a complete Security Operations Center (SOC) home lab. I simulated a corporate network environment to practice both offensive (Red Team) and defensive (Blue Team) operations.

## 🛠️ Tools & Technologies Used
* **Hypervisor:** VMware Workstation Pro
* **Attacker:** Kali Linux (Nmap, Nessus, Hydra, John the Ripper, Metasploit)
* **Victim:** Ubuntu Server 24.04 (Apache Web Server, OWASP Juice Shop)
* **SIEM:** Wazuh (Log Analysis, File Integrity Monitoring)
* **IDS:** Snort (Signature-based Intrusion Detection)
* **Networking:** SSH, UFW Firewall, Wireshark Traffic Analysis

## 📂 Lab Modules Completed

### 1. Network Configuration & Analysis
* Configured a secure NAT network connecting Attacker and Victim.
* Captured and analyzed TCP 3-Way Handshakes using **Wireshark**.
* Implemented SSH key-based authentication for secure remote access.

### 2. Blue Team Defense (SIEM & IDS)
* Deployed **Wazuh SIEM** to aggregate logs from the Ubuntu Server.
* Configured active monitoring agents to detect SSH brute-force attacks.
* Installed **Snort IDS** and wrote custom rules to detect ICMP scanning and Unauthorized Access.
* *Evidence:* See files `10_SIEM_Dashboard.png` and `12_Snort_Detection.png`.

### 3. Red Team Offense (Vulnerability Assessment)
* Performed network mapping using **Nmap** to identify open ports and service versions.
* Conducted vulnerability scanning using **Nessus Essentials** to audit system patch levels.
* Deployed **OWASP Juice Shop** (Docker) to practice web exploitation (SQLi/XSS).
* Cracked password hashes using **John the Ripper**.
* *Evidence:* See files `13_Nmap_Scan.png` and `16_Password_Cracked.png`.

## 🚀 Key Takeaways
This project gave me hands-on experience with the full lifecycle of a cyber attack, from initial reconnaissance to detection and log analysis. I am now proficient in setting up virtualized environments and interpreting security logs.
