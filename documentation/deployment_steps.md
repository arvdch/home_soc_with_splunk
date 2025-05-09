# SOC Lab Deployment Steps

Follow these steps to deploy and configure the home SOC lab with Splunk:

## Prerequisites
- **Splunk Enterprise (Free Edition)** installed on a central server (e.g., a VM or physical machine).
- **Universal Forwarder** installed on client machines (Windows/Linux).
- **Proper network configuration** for forwarding logs from client systems to the Splunk server.

## Step 1: Install Splunk on the Central Server
1. Download and install Splunk from [Splunk's website](https://www.splunk.com/).
2. Launch Splunk and sign in using the default credentials (`admin:changeme`).
3. Set up a free license for **Splunk Enterprise**.

## Step 2: Install Universal Forwarders on Client Machines
1. Download the Splunk Universal Forwarder from the Splunk website.
2. Install the forwarder on Windows or Linux systems that you want to monitor.
3. Configure the forwarder to forward logs to the Splunk instance.
    - Modify `inputs.conf` to specify which logs to monitor.
    - Modify `outputs.conf` to point to the Splunk server.

## Step 3: Verify Data Collection
1. Check the Splunk dashboard to ensure logs are being ingested from client systems.
2. Review the log sources to ensure key logs (Windows Event Logs, Sysmon, etc.) are present.

## Step 4: Configure Dashboards and Detection Rules
1. Use Splunk’s predefined detection rules for basic threats.
2. Create custom dashboards for monitoring the health of your SOC and alerting on critical incidents.

## Step 5: Test and Validate the Setup
1. Trigger simulated attacks (e.g., brute force login attempts, unauthorized access).
2. Verify if the dashboards and alerts are functioning as expected.

---

## Troubleshooting
- If logs are not appearing, check the Universal Forwarder's status.
- Verify the network connection between the forwarder and the Splunk server.
