# SOC Home Lab – Wazuh SIEM

A hands-on Security Operations Center (SOC) home lab built for learning real-world threat detection, log analysis, and incident investigation using **Wazuh SIEM**.

## Lab Overview

This project demonstrates the deployment and operation of a complete SIEM environment for Blue Team / SOC practice.

### Architecture

| Role              | Operating System     | IP Address       | Purpose                          |
|-------------------|----------------------|------------------|----------------------------------|
| SIEM Server       | Ubuntu Server        | 192.168.56.107   | Wazuh Manager + Indexer + Dashboard |
| Endpoint          | Windows 10           | 192.168.56.106   | Monitored agent                  |
| Attacker          | Kali Linux           | 192.168.56.103   | Attack simulation                |

**Network:** VirtualBox Host-Only Network (`192.168.56.0/24`)

## Technologies Used

- **Wazuh** (SIEM) – Manager, Indexer, Dashboard
- **Windows Agent** – Log collection from Windows 10
- **Kali Linux** – Offensive testing and attack simulation
- **Nmap / Enumeration tools** – Generating security events
- VirtualBox – Lab virtualization

## Key Features Implemented

- Deployed Wazuh using the official all-in-one installation method
- Successfully enrolled and monitored a Windows 10 agent
- Simulated real attacks from Kali Linux (port scanning, SMB enumeration, etc.)
- Practiced L1 SOC workflows:
  - Alert triage
  - Threat hunting
  - Dashboard analysis
  - Incident investigation fundamentals
- Observed MITRE ATT&CK mapped alerts

## Lab Objectives

- Build a functional SIEM environment from scratch
- Understand agent enrollment and log collection
- Generate and analyze real security events
- Practice Blue Team / SOC Level 1 skills in a controlled environment

## Screenshots

*(Add your screenshots here)*

- Wazuh Dashboard overview
- Windows agent status
- Threat Hunting / Security Events
- Attack simulation from Kali
- Generated alerts

## Skills Demonstrated

- SIEM Deployment & Configuration
- Endpoint Monitoring (Windows)
- Log Analysis & Alert Triage
- Attack Simulation & Detection
- SOC Operations Fundamentals
- Linux & Windows System Administration

## Future Improvements

- Add Linux endpoint agent
- Install Sysmon on Windows for richer telemetry
- Create custom detection rules
- Build advanced dashboards
- Simulate more attack techniques (brute force, lateral movement, etc.)

## Author

**Lakshitha Madushan**  
Aspiring SOC Analyst | Cybersecurity Undergraduate – SLIIT  

- GitHub: [https://github.com/TCLMadushan](https://github.com/TCLMadushan)
- LinkedIn: https://www.linkedin.com/in/lakshitha-madushan-a47857271?utm_source=share_via&utm_content=profile&utm_medium=member_ios

---

> This lab was built for educational and skill development purposes only.
