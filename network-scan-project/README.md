# Home Network Scan Project

## Overview
This project demonstrates basic network discovery and service enumeration performed within a home lab environment using Nmap.

The objective was to identify active devices on the local network, detect open ports, and document basic networking/security findings.

---

## Tools Used
- Nmap
- Windows Command Prompt
- TCP/IP Networking

---

## Network Information

- Local IP Address: 192.168.0.50
- Subnet Mask: 255.255.255.0
- Network Range: 192.168.0.0/24

---

## Commands Used

### Host Discovery Scan
```bash
nmap -sn 192.168.0.0/24

### Service Detection Scan
```bash
nmap -sV 192.168.0.50

### IP Configuration
```bash
ipconfig

## Tasks Performed

-Identified active hosts on the network
-Performed basic port enumeration
-Detected running services
-Documented scan results and screenshots
-Saved and analyzed scan results

## Skills Demonstrated

-Network scanning
-Service enumeration
-Basic subnetting knowledge
-Command-line usage
-Technical documentation
-Command-line proficiency 
