# Detection Rules

These Splunk rules are designed to detect common attack patterns and suspicious activities in your home SOC setup.

## Brute Force Login Detection
- **File:** `brute_force_login.spl`
- **Description:** Detects multiple failed login attempts from the same IP address, typically indicative of a brute-force attack.
- **Event Source:** Windows Event Logs (EventCode 4625)

## Suspicious Process Creation Detection
- **File:** `suspicious_process_creation.spl`
- **Description:** Flags suspicious process creations such as PowerShell, cmd.exe, or wscript.exe, which are often leveraged in attacks.
- **Event Source:** Sysmon Process Create Logs

## Unusual Network Connections Detection
- **File:** `unusual_network_connections.spl`
- **Description:** Flags network connections to uncommon ports, which may indicate malicious activity or data exfiltration.
- **Event Source:** Firewall Logs
