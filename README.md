# Splunk SOC Lab – Home-Based Threat Detection Environment

## 📌 Overview
This project documents the creation of a lightweight, home-based Security Operations Center (SOC) using Splunk. It simulates real-world log collection, detection engineering, and alerting workflows using Windows/Linux virtual machines.

## 🎯 Objectives
- Set up Splunk and Universal Forwarder.
- Collect logs from multiple endpoints.
- Build dashboards and custom detection rules.
- Monitor host and system behavior with SPL queries.

## 🛠️ Tools & Technologies
- Splunk Enterprise
- Splunk Universal Forwarder
- Windows 11, Ubuntu
- Sysmon, Winlogbeat, PowerShell
- Python for log parsing

## 📂 Folder Structure
- `documentation/`: Lab architecture, diagrams, and notes.
- `configs/`: Splunk and UF configuration files.
- `detection_rules/`: SPL correlation rules.
- `dashboards/`: JSON or XML dashboards.
- `scripts/`: Automation scripts.
- `logs/`: Sanitized sample log files.

## 🚀 Getting Started
1. Clone this repo.
2. Deploy Splunk on your primary VM.
3. Install Universal Forwarder on target endpoints.
4. Configure inputs/outputs.
5. Import dashboards and correlation rules.

## 📈 Roadmap
- [ ] Integrate network-based detection (Suricata)
- [ ] Add MITRE ATT&CK mapping
- [ ] Enable email/SMS alerting

## 👤 Author
[@arvdch](https://github.com/arvdch)

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.
