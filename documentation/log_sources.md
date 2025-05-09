# Log Sources

## Key Log Sources
- **Windows Event Logs**:
  - Security (for login attempts, user creation)
  - Application and System logs
- **Sysmon Logs** (for process creation, network connections, etc.)
- **Linux Logs**:
  - `/var/log/auth.log` (for authentication and sudo usage)
  - `/var/log/syslog` (general system logs)
- **Custom logs** from security tools like antivirus or firewall logs

---

## Log Forwarding Configuration
Logs from the above sources are forwarded by Splunk Universal Forwarders to the Splunk instance for analysis and correlation.
