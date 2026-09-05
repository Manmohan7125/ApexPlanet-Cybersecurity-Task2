# ApexPlanet Cybersecurity Internship – Task 2

## Network Security & Scanning

This repository contains my work for **Task 2: Network Security & Scanning** of the ApexPlanet Software Pvt. Ltd. Cybersecurity & Ethical Hacking Internship.

## Objective

The objective of this task is to understand:

- Network reconnaissance
- Port and service scanning
- Vulnerability scanning
- Network traffic analysis
- Firewall basics

All security testing was performed in an **authorized isolated lab environment** using Kali Linux and the target test machine.

---

## Lab Environment

### Attacker Machine
- Operating System: Kali Linux
- Tools: Nmap, Wireshark, hping3, iptables

### Target Machine
- Metasploitable2 / authorized vulnerable test VM

### Network
- Private/Host-Only virtual network

---

## Task 2 Activities

### 1. Reconnaissance

The following reconnaissance techniques were studied:

- Whois
- Nslookup
- Google Dorking
- Shodan
- Ping Sweep
- Banner Grabbing

Detailed work:
`Reconnaissance.md`

---

### 2. Port & Service Scanning

Nmap was used to perform:

- TCP SYN Scan
- UDP Scan
- Service Version Detection
- Operating System Detection

The scan results were documented and analyzed.

Detailed report:
`Nmap-Scan-Report.md`

---

### 3. Vulnerability Scanning

A vulnerability scanner was studied/configured for scanning the authorized test machine.

The vulnerabilities were categorized according to their severity:

- Critical
- High
- Medium
- Low

Detailed report:
`Vulnerability-Report.md`

---

### 4. Packet Analysis with Wireshark

Wireshark was used to analyze network traffic including:

- HTTP
- FTP
- DNS
- TCP traffic
- SYN packet activity

Filters were used to identify and analyze relevant packets.

Detailed analysis:
`Wireshark-Analysis.md`

---

### 5. Firewall Basics

Basic firewall rules were studied using `iptables`.

The lab demonstrated how firewall rules can be used to:

- Allow specific traffic
- Deny specific traffic
- Control access to ports
- Reduce exposure to scanning attempts

Detailed report:
`Firewall-Analysis.md`

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Kali Linux | Security testing environment |
| Nmap | Network and port scanning |
| Wireshark | Packet/network traffic analysis |
| hping3 | Controlled network traffic testing |
| iptables | Firewall configuration |
| OpenVAS/GVM | Vulnerability assessment |
| Whois | Domain information gathering |
| Nslookup | DNS information gathering |

---

## Evidence

Screenshots and supporting evidence are organized in the following folders:

- `Screenshots/Recon/`
- `Screenshots/Nmap/`
- `Screenshots/Vulnerability/`
- `Screenshots/Wireshark/`
- `Screenshots/Firewall/`

Actual lab screenshots are included as evidence of the completed activities.

---

## Key Learning Outcomes

Through this task, I learned how to:

1. Perform basic network reconnaissance.
2. Identify hosts and open ports.
3. Detect running services and versions.
4. Analyze network packets using Wireshark.
5. Understand vulnerability severity.
6. Configure basic firewall rules.
7. Perform security testing safely inside an isolated lab environment.

---

## Disclaimer

All scanning and security testing documented in this repository was performed only on systems in an authorized and isolated lab environment for educational purposes.

No unauthorized systems or networks were targeted.

---

## Internship

**Organization:** ApexPlanet Software Pvt. Ltd.  
**Program:** Cybersecurity & Ethical Hacking Internship  
**Task:** Task 2 – Network Security & Scanning
