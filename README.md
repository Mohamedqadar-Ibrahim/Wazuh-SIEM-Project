# Wazuh SIEM Project 🚀

## Overview 📖
This project demonstrates the implementation of Wazuh, an open-source security information and event management (SIEM) tool, to monitor and analyze security events from a Windows virtual machine. The primary objective is to showcase the ability to detect and respond to potential security threats through log monitoring.

## Objective 🎯
The main objectives of this project are to:

| Objectives                                              |
|--------------------------------------------------------|
| Set up Wazuh to monitor a Windows VM for security events. |
| Configure a Wazuh agent on the Windows VM to send logs to Wazuh. |
| Trigger alerts in Wazuh by clearing Windows event logs and analyze them. |

## Tools Used 🛠️
- **Wazuh**: Security monitoring and event management platform.
- **Windows Virtual Machine**: The monitored environment.
- **Ubuntu Virtual Machine**: The Wazuh manager where logs are collected and analysed.
- **PowerShell**: For running installation commands on Windows.

## Steps Taken 🗂️

### 1. Wazuh Configuration and Account Info
Configured the Wazuh manager on Ubuntu. After installation, account details were retrieved for logging into the Wazuh dashboard.

![Wazuh Config](screenshots/wazuh%20configuration%20and%20account%20info%20screenshot%201.PNG)

### 2. Wazuh Login Page
Accessed the Wazuh dashboard using the provided URL and credentials.

![Wazuh login](screenshots/wazuh%20login%20page%20screenshot%202.PNG)

### 3. Wazuh Dashboard Overview
Upon logging in, the Wazuh dashboard was displayed, showing an overview of agents and security events.

![Wazuh dashboard](screenshots/screenshot%203%20wazuh%20dashboard.PNG)

### 4. Instructions to Connect to Windows VM
Generated commands in the Wazuh dashboard for installing the Wazuh agent on the Windows VM.

![Windows VM connection](screenshots/instructions%20to%20connect%20to%20windows%20VM%20screenshot%204.PNG)

### 5. Running Wazuh on Windows VM
Executed the commands in PowerShell to install and start the Wazuh agent on the Windows VM.

![Running on Windows](screenshots/running%20wazuh%20on%20windows%20VM%20screenshot%205.PNG)

### 6. Rules in Wazuh
Accessed the rules section in Wazuh to monitor for specific events, including the 'Microsoft Event Log Cleared' rule.

![Wazuh Rules](screenshots/Rules%20screenshot%206.PNG)

### 7. Event Logger Clearing Audit
Cleared the Windows event logs using the Event Viewer to trigger alerts in Wazuh.

![Event Logger](screenshots/Event%20Logger%20clearing%20audit%20screenshot%207.PNG)

### 8. Audit Log Cleared Results
Observed the alert in Wazuh indicating that the audit logs on the Windows VM had been cleared.

![Audit Log Cleared Evidence](screenshots/audit%20log%20cleared%20results%20screenshot%208.PNG)

## Conclusion 🏁
This project effectively demonstrates the capabilities of Wazuh in monitoring security events from a Windows environment. The ability to trigger alerts based on log changes emphasizes the importance of proactive security measures in cybersecurity.

## Future Improvements 🚀
- Explore advanced features of Wazuh for more comprehensive security monitoring.
- Implement additional agents across various operating systems for broader monitoring capabilities.
- Analyse other security events to enhance detection rules and responses.
