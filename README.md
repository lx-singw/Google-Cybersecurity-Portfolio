# Google Cybersecurity Professional Certificate Portfolio
This repository contains practical, hands-on portfolio projects completed during the Google Cybersecurity Professional Certificate program. It demonstrates my technical competency in automating security tasks, querying databases for threats, managing Linux access controls, and investigating network traffic anomalies

[![Google Certificate](https://shields.io)](https://coursera.org)
[![Language - Python](https://shields.io)](https://python.org)
[![Language - SQL](https://shields.io)](https://wikipedia.org)
[![OS - Linux](https://shields.io)](https://ubuntu.com)

## 🚀 Executive Summary
This repository serves as a centralized portfolio documenting the hands-on technical labs and case studies completed during the **Google Cybersecurity Professional Certificate** program. 

Leveraging my foundational academic background in computer science, these projects demonstrate practical competency in defensive security, network monitoring, automation, and incident response within enterprise environments.

---

## 🛠️ Technical Skills & Tools Core


| Domain | Core Tools & Frameworks Mastered |
| :--- | :--- |
| **Languages** | Python 3, Bash Scripting, SQL (PostgreSQL / MySQL) |
| **Infrastructure & OS**| Linux (Ubuntu CLI), Windows Event Viewer, TCP/IP Suite |
| **Security Operations** | Wireshark, Tcpdump, Splunk (SIEM), Chronicle (SIEM/SOAR) |
| **Frameworks & Compliance** | NIST Cybersecurity Framework (CSF), OWASP Top 10, IAM (Least Privilege) |

---

## 📂 Highlighted Project Case Studies

### 🐍 1. Python Automation: Managing Access Control Allow-Lists
* **Directory Link:** [`/python-automation`](./python-automation)
* **The Challenge:** An enterprise server required dynamic updates to its IP firewall allow-list file to remove employees who left the organization or changed departments. Manual updates were prone to human error and created security vulnerabilities.
* **The Solution:** Developed a production-ready Python script that opens and parses a target text file containing approved IP addresses. The script utilizes file handling operations (`.read()`, `.split()`) and conditional logic to cross-reference an internal deletion list, remove unauthorized lines, and update the server configuration file securely using `.write()`.
* **Key Skills:** Python File I/O, String Manipulation, List Operations, Defensive Coding.

### 🛢️ 2. SQL Threat Hunting: Incident Investigation & Log Queries
* **Directory Link:** [`/sql-databases`](./sql-databases)
* **The Challenge:** A Security Operations Centre (SOC) flag indicated an anomalous, unauthorized login attempt originating from a remote IP address outside standard South African operational hours.
* **The Solution:** Executed precise relational database queries to extract security telemetry across thousands of employee login records. Used strict structural filters (`WHERE`, `AND`, `OR`) and operators (`LIKE '%xyz%'`) to map compromised user sessions, isolate exact login timestamp profiles, and discover unauthorized system changes.
* **Key Skills:** Relational Database Queries, Data Filtering, Schema Mapping, Log Analysis.

### 🐧 3. Linux Systems Security: Access Control & Permissions Audit
* **Directory Link:** [`/linux-administration`](./linux-administration)
* **The Challenge:** An internal compliance audit revealed that general-level server directories contained sensitive human resource and system configuration files accessible to non-privileged system users.
* **The Solution:** Used the Linux Command Line Interface (CLI) to conduct a comprehensive permissions audit. Executed system commands (`chmod`, `chown`, `chgrp`) to reassign file ownership, lock down file modification rights, and establish strict user-group policies enforcing the Principle of Least Privilege.
* **Key Skills:** Linux CLI navigation, File Permissions (rwxrwxrwx), Security Compliance, User Access Management.

### 🔍 4. Traffic Triage: Packet Analysis via Wireshark & Tcpdump
* **Directory Link:** [`/siem-wireshark-labs`](./siem-wireshark-labs)
* **The Challenge:** A network segment experienced a sudden spike in traffic, raising alarms for a potential distributed denial-of-service (DDoS) attack or active data exfiltration.
* **The Solution:** Monitored live network interfaces using `tcpdump` to capture packets into standard `.pcap` files. Exported data into **Wireshark** to filter for abnormal protocol distributions (DNS/HTTP), reconstruct raw TCP streams, and locate malformed headers indicative of malicious network scanning tools.
* **Key Skills:** Packet Analysis, Protocol Triage, Network Fundamentals, Telemetry Diagnostics.

---

## 📊 Academic Foundation & Certifications
* **Google Cybersecurity Professional Certificate** — Coursera (Verified Credential)
* **BSc in Computing (In Progress)** — University of South Africa (UNISA)
* **Computer Science Coursework (Historical)** — University of the Witwatersrand (Wits)

---

## 📬 Let's Connect

I am actively seeking junior positions within South African tech teams, specifically targeting **Junior Security Analyst**, **SOC Analyst (L1)**, or **System Support** roles.

* **LinkedIn:** [://linkedin.com](https://://linkedin.com)
* **Email:** [your.email@domain.co.za](mailto:your.email@domain.co.za)
* **Location:** Johannesburg, South Africa 🇿🇦
