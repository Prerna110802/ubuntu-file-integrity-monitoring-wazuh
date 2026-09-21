# Ubuntu File Integrity Monitoring with Wazuh

## Overview

This project demonstrates File Integrity Monitoring (FIM) on an Ubuntu endpoint using Wazuh.

File activity was performed on the Ubuntu system and monitored through Wazuh. The generated security events were reviewed in the Wazuh dashboard to understand the detected file activity.

## Objective

The objective of this project is to demonstrate how Wazuh can be used to monitor file-system activity on an Ubuntu endpoint and generate security events for investigation.

## Technologies Used

- Ubuntu Linux
- Wazuh
- Wazuh Agent
- Wazuh Manager
- File Integrity Monitoring (FIM)
- Wazuh Dashboard

## Project Workflow

Ubuntu File Activity
        ↓
Wazuh Agent
        ↓
Wazuh Manager
        ↓
File Integrity Monitoring (FIM)
        ↓
Security Alert
        ↓
Alert Investigation

## Implementation

1. Configured the Ubuntu system as a monitored endpoint.
2. Enabled file integrity monitoring through Wazuh.
3. Created file activity on the Ubuntu system.
4. Wazuh detected the file-system activity.
5. Reviewed the generated event in the Wazuh dashboard.
6. Opened the event details to investigate the detected activity.

## Wazuh Monitoring

### Wazuh Alert Logs

The Wazuh dashboard displays the security events generated from the monitored Ubuntu endpoint.

![Wazuh Alert Logs](screenshots/wazuh-alerts-details.png)

### Alert Details

The detailed event view provides additional information about the detected file activity.

![Wazuh Alert Details](screenshots/wazuh-alert.png)

## Key Learning

- Understanding File Integrity Monitoring (FIM)
- Monitoring Linux endpoints with Wazuh
- Understanding Wazuh security alerts
- Investigating file-system activity
- Using a SIEM dashboard for security monitoring
- Basic SOC alert investigation

## Conclusion

This project demonstrates a basic SOC monitoring workflow in which file activity on an Ubuntu endpoint is monitored using Wazuh and the resulting security event is investigated through the Wazuh dashboard.
