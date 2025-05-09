# Threat Detection Strategy

The SOC lab is designed to detect a variety of attack patterns and suspicious activity based on event logs and Sysmon data.

## Key Detection Rules
- **Brute Force Login Detection**:
  - Detect failed login attempts from the same IP address or user account.
- **Suspicious Process Creation**:
  - Identify processes that exhibit abnormal behavior or are commonly used in attacks (e.g., PowerShell, WMI).
- **Unusual Network Connections**:
  - Detect connections to uncommon ports or external IPs known for malicious activity.

## Future Detection Enhancements
- Detection of lateral movement using network traffic analysis.
- Identifying malware based on unusual file behavior or signatures.
