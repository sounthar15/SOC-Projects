# Phishing-Led Compromise and Data Exfiltration Detection using Splunk

## Project Overview
This project demonstrates a phishing-led cyberattack investigation using Splunk SIEM.

The attack simulation includes:

- Phishing URL access
- Credential dumping
- PowerShell execution
- Lateral movement
- Data exfiltration
- Command-and-Control (C2) communication

This project was created as a SOC analyst practical demonstration to simulate a real-world attack lifecycle and perform threat detection using Splunk.

---

## Tools Used

- Splunk Enterprise
- Security Log Analysis
- MITRE ATT&CK Framework
- Incident Response Methodology

---

## Attack Scenario

A user account was compromised through phishing activity involving a malicious URL.

The attacker then:

1. Accessed phishing infrastructure
2. Performed credential dumping
3. Executed malicious PowerShell scripts
4. Moved laterally using remote execution
5. Exfiltrated sensitive data
6. Established C2 communication

The activity was investigated using Splunk logs, dashboards, alerts, and incident reporting.

---

## Dashboard Panels

This dashboard includes:

- Attack Event Trend
- Credential Theft Count
- Phishing URL Activity
- PowerShell Execution Events
- Lateral Movement Events
- Data Exfiltration Events
- C2 Communication Detection
- Attack Timeline

---

## Alerts Created

The following alerts were configured:

- Phishing URL Alert
- Credential Dumping Alert
- PowerShell Execution Alert
- Data Exfiltration Alert
- C2 Communication Alert

---

## MITRE ATT&CK Mapping

| Technique | Description |
|------------|-------------|
| T1566 | Phishing |
| T1003 | Credential Dumping |
| T1059.001 | PowerShell |
| T1021 | Remote Services |
| T1041 | Exfiltration |
| T1071 | C2 Communication |

---

## Project Files

This repository contains:

- phishing_exfiltration.log
- spl_queries.txt
- Phishing Incident Report PDF
- Dashboard XML code
- Splunk screenshots
- Alert screenshots
- Search screenshots

---

## Skills Demonstrated

- SIEM Monitoring
- Log Analysis
- Threat Detection
- Dashboard Creation
- Alert Engineering
- Incident Investigation
- Incident Reporting
- SOC Analyst Workflow

---

## Author

SOC Analyst Project Demonstration using Splunk SIEM
