# [Quentel Davis] | Cybersecurity Portfolio

Welcome to my cybersecurity portfolio. This repository serves as a central hub documenting my hands-on technical experience, home lab deployments, and security research. My work focuses on threat detection, network security, and security automation.

📬 **Connect with me:**
* **LinkedIn:** [linkedin.com/in/quenteldavis](https://linkedin.com)
* **Email:** quentdavis8@gmail.com


---

## 🛠️ Technical Skills & Toolbelt

### 🔵 Blue Team & Defensive Security
* **SIEM / Log Analysis:** Splunk Enterprise, Elastic Security (ELK), Wireshark, Zeek
* **Endpoint Detection & Response (EDR):** Microsoft Defender for Endpoint, LimaCharlie
* **Operating Systems:** Linux (Ubuntu/Debian), Windows Server (Active Directory), macOS

### 🔴 Red Team & Threat Simulation
* **Network Scanning & Enumeration:** Nmap, Masscan, Dirbuster
* **Exploitation Frameworks:** Metasploit, Burp Suite Professional
* **Threat Emulation:** Atomic Red Team (Mitre ATT&CK mapping)

### ⚙️ Cloud & DevSecOps
* **Cloud Environments:** AWS (IAM, VPC, CloudTrail), Microsoft Azure
* **Automation & Scripting:** Python (Log Parsing, API Integration), Bash, PowerShell

---

## 📂 Portfolio Projects & Labs

### 🏠 [SOC Home Lab Deployment & Threat Detection](./SOC-Labs/)
* **Overview:** Built a virtualized enterprise network to simulate attacks and analyze defensive telemetry.
* **Architecture:** Configured a Windows Server 2022 Active Directory Domain Controller and a Windows 10 target endpoint. Forwarded Sysmon and Windows Event logs via Universal Forwarder to a centralized Splunk instance hosted on Ubuntu Linux.
* **Key Outcome:** Executed credential dumping via Mimikatz and mapped the telemetry in Splunk to create custom alerting dashboards for unauthorized LSASS access.

### 🛡️ [Phishing & Malware Analysis Case Study](./SOC-Labs/Phishing-Analysis.md)
* **Overview:** Analyzed a real-world phishing email targeting a corporate environment in a safe, isolated sandbox.
* **Key Outcome:** Extracted malicious indicators of compromise (IoCs) including domain names, IP addresses, and file hashes from a hidden `.eml` attachment. Defanged the malicious URL and performed open-source intelligence (OSINT) via VirusTotal to document the attacker's infrastructure.

### 🐍 [Automated Threat Intelligence Log Parser](./Scripts/)
* **Overview:** Developed a custom Python script designed to expedite incident response triage for web servers.
* **Key Outcome:** The script automatically parses Apache/Nginx access logs, extracts unique IP addresses exhibiting suspicious behavior (e.g., hundreds of `404` errors indicating directory busting), cross-references them against the AbuseIPDB API, and generates a formatted markdown threat report.

---

## 📜 Certifications & Education

* **CompTIA Security+** | Issued 2025
* **AWS Certified Cloud Practitioner** | Issued 2026
* **B.S. in Computer Science / Cybersecurity** | University Name, Expected Graduation 2027

---

## 📈 Current Focus & Continuous Learning

I am currently expanding my skill set by:
1. Preparing for the **Blue Team Level 1 (BTL1)** certification to deepen my incident response capabilities.
2. Building an automated cloud security monitoring pipeline in **AWS** using Lambda and GuardDuty.
3. Actively solving challenges on **HackTheBox** and **TryHackMe** to stay sharp on modern adversarial tactics.
