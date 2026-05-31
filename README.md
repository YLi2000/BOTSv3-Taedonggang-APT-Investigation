# BOTSv3 Taedonggang APT Investigation

## 🎯 Project Overview

Deep-dive threat hunting and incident response analysis of an Advanced Persistent Threat (APT) campaign targeting Frothly brewery company. This investigation uses the Splunk Boss of the SOC v3 (BOTSv3) dataset to demonstrate comprehensive SOC analysis capabilities, detection engineering, and threat intelligence integration.

**Status**: 🔄 Investigation in Progress (Started: June 1, 2026)

---

## 📊 Dataset Information

- **Dataset**: Splunk BOTS v3 (Boss of the SOC v3)
- **Scenario**: Taedonggang APT campaign against Frothly organization
- **Time Range**: August 20, 2018 (24-hour window)
- **Environment**: Hybrid cloud (AWS + on-premises), Windows endpoints, Linux servers, Office 365
- **Data Volume**: ~12GB of security telemetry across 25+ data sources

---

## 🔍 Investigation Objectives

1. **Reconstruct the complete attack timeline** from initial access to data exfiltration
2. **Map adversary tactics and techniques** to MITRE ATT&CK framework
3. **Extract and document Indicators of Compromise (IOCs)**
4. **Develop detection rules** to identify similar attacks
5. **Provide actionable remediation recommendations**

---

## 🛠️ Tools & Technologies

- **SIEM Platform**: Splunk Enterprise
- **Query Language**: SPL (Splunk Processing Language)
- **Framework**: MITRE ATT&CK Navigator
- **Detection Rules**: Splunk correlation searches, Sigma rules
- **Documentation**: Markdown, screenshots, timeline analysis

---

## 📁 Repository Structure

├── evidence/
│ ├── screenshots/ # Investigation screenshots
│ ├── queries/ # SPL queries used during investigation
│ └── iocs/ # Extracted indicators of compromise
├── analysis/
│ ├── timeline.md # Attack timeline reconstruction
│ ├── attck-mapping.md # MITRE ATT&CK technique mapping
│ └── findings/ # Detailed findings by attack phase
├── detection-rules/
│ ├── splunk/ # Splunk correlation searches
│ └── sigma/ # Sigma rule format for multi-SIEM
└── artifacts/
├── attck-navigator.json # ATT&CK Navigator layer
└── ioc-list.csv # Comprehensive IOC list


---

## 📝 Investigation Log

| Date | Phase | Activity |
|------|-------|----------|
| 2026-06-01 | Setup | Repository initialized, folder structure created |
| TBD | Reconnaissance | Dataset exploration and sourcetype analysis |
| TBD | Initial Access | Identify phishing vector and entry point |
| TBD | Execution | Analyze malware execution and payload delivery |
| TBD | Persistence | Document persistence mechanisms |
| TBD | Privilege Escalation | Identify escalation techniques and CVEs |
| TBD | Lateral Movement | Map adversary movement across network |
| TBD | Collection & Exfiltration | Document data theft activities |
| TBD | Detection Engineering | Create detection rules and alerts |

---

## 🎓 Background & Context

As a SOC analyst with years of enterprise security operations experience, I'm conducting this investigation to:
- Demonstrate advanced threat hunting and incident response capabilities
- Build hands-on expertise with Splunk and Western security datasets
- Develop detection engineering content aligned with MITRE ATT&CK framework
- Showcase analytical methodology for the Canadian cybersecurity market

This project complements my professional experience in SIEM operations, incident response, and security automation.

---

## 📚 Resources & References

- [Splunk BOTS v3 Dataset](https://github.com/splunk/botsv3)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Sigma Rules Repository](https://github.com/SigmaHQ/sigma)

---

## 📫 Contact

**[Your Name]** | Calgary, AB, Canada  
📧 [Your Email]  
💼 [LinkedIn Profile URL]  

---

**License**: This analysis is for educational and portfolio purposes using publicly available security datasets.
