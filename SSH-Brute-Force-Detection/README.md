# SSH Brute Force Detection using Splunk

## Project Overview

This project demonstrates detection and investigation of an SSH brute force attack using Splunk SIEM. The project includes log analysis, dashboard creation, alert engineering, and incident reporting.

---

# Tools Used

- Splunk Enterprise
- SSH Authentication Logs
- MITRE ATT&CK Framework

---

# Attack Scenario

Multiple failed SSH login attempts were detected from suspicious external IP addresses targeting user accounts such as:

- root
- admin
- test

The activity indicated a brute force attack targeting the SSH service.

---

# Dashboard Features

- Failed Login Trend
- Top Attacker IPs
- Targeted Usernames
- Authentication Failure Events
- Total Failed Attempts

---

# Alert Created

## SSH Brute Force Detection Alert

Trigger Condition:
- More than 3 failed login attempts from same IP address

---

# MITRE ATT&CK Mapping

- T1110 – Brute Force
- T1078 – Valid Accounts

---

# Skills Demonstrated

- SIEM Monitoring
- Log Analysis
- Threat Detection
- Alert Engineering
- Dashboard Creation
- Incident Response
- MITRE ATT&CK Mapping

---

# Project Screenshots

## Dashboard
Stored in screenshots folder.

## Alert Configuration
Stored in screenshots folder.

## Splunk Log Analysis
Stored in screenshots folder.

---

# Reports

- Incident Report PDF available in reports folder.
- Dashboard Export PDF available in reports folder.

---

# Conclusion

This project demonstrates a complete SOC workflow including attack detection, investigation, dashboard monitoring, alert creation, and incident reporting using Splunk SIEM.
