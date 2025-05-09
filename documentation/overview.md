# Home SOC with Splunk - Overview

## Objective
This project sets up a lightweight, home-based Security Operations Center (SOC) using Splunk for log ingestion, monitoring, and basic threat detection.

## Key Components
- **Splunk Enterprise (Free Edition)** for log management and analysis
- **Universal Forwarders on Windows/Linux hosts** for log collection
- **Custom detection rules** for identifying specific attack patterns
- **Dashboards** for visual threat monitoring
- **Documentation** for deployment and usage

## Architecture
The architecture involves a central Splunk instance receiving logs from various endpoints via Universal Forwarders. Detection rules and dashboards are configured to analyze logs and present alerts in real-time.

### Key Use Cases
- Detect brute-force login attempts
- Monitor Windows Event Logs
- Track Sysmon events (e.g., process creation, network connections)

## Future Work
- Expand detection rules for additional attack patterns
- Automate alerting for high-severity incidents
