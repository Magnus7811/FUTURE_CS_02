# FUTURE_CS_02 - SOC Alert Monitoring & Incident Response Simulation

## 🛡️ About the Project

This repository contains the complete analysis and deliverables for **Task 2** of my Cybersecurity Internship with **Future Interns**.

The objective was to simulate the daily responsibilities of a **SOC Analyst** by monitoring security alerts, analyzing malicious behavior, and performing incident response using a **SIEM setup** based on the Elastic Stack (ELK) in Kali Purple.

---

## 🧰 Tools & Environment

- **Kali Purple Linux** (Manual Setup)
- **Elastic Stack (ELK)** – Elasticsearch, Logstash, Kibana
- **Sample Logs** – System logs, Authentication logs, Malware alerts, Network traffic
- **KQL** – Kibana Query Language for filtering and log analysis

---

## 🔍 Key Activities Performed

| Phase                             | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| SIEM Setup                       | Manual deployment and access to Kibana dashboard in Kali Purple            |
| Alert Identification             | Time-based filtering, field exploration, and suspicious activity detection |
| Investigation of Attacker Behavior | Identified PowerShell usage, registry tampering, and backdoor creation     |
| Privilege Escalation Detection   | Detected MSI abuse & SYSTEM-level execution from attacker artifacts        |
| Persistence Mechanisms           | Found backdoor account creation, task scheduling, registry modification    |

---

## 🧪 MITRE ATT&CK Tactics Identified

- **Discovery** – System enumeration, network probing
- **Privilege Escalation** – MSI exploitation, AlwaysInstallElevated abuse
- **Persistence** – Admin account creation, scheduled task, registry autorun
- **Execution** – PowerShell and Batch file execution
- **Defense Evasion** – Use of system binaries (LOLBins)

---

## 📁 Repository Structure

```bash
FUTURE_CS_02/
├── README.md
└── SOC_Incident_Report.pdf
