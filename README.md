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

![Wazuh Configuration and Account Info](https://path-to-your-screenshot/CpEvhiA1IEJTN5VNuk5UtdQx)

### 2. Wazuh Login Page
Accessed the Wazuh dashboard using the provided URL and credentials.

![Wazuh Login Page](https://path-to-your-screenshot/WVP0vpJzUaQerc8yA6TjvWkI)

### 3. Wazuh Dashboard Overview
Upon logging in, the Wazuh dashboard was displayed, showing an overview of agents and security events.

![Wazuh Dashboard Overview](https://path-to-your-screenshot/41cet8PylbO50SosWQj4gS6I)

### 4. Instructions to Connect to Windows VM
Generated commands in the Wazuh dashboard for installing the Wazuh agent on the Windows VM.

![Instructions to Connect to Windows VM](https://path-to-your-screenshot/wazuh configuration and account info screenshot 1.PNG)

### 5. Running Wazuh on Windows VM
Executed the commands in PowerShell to install and start the Wazuh agent on the Windows VM.

![Running Wazuh on Windows VM](https://path-to-your-screenshot/Jh48QTP0qOgZ8Khaja99o595)

### 6. Rules in Wazuh
Accessed the rules section in Wazuh to monitor for specific events, including the 'Microsoft Event Log Cleared' rule.

![Rules in Wazuh](https://path-to-your-screenshot/7cg39RK6zvjqh5lsivrnCuX9)

### 7. Event Logger Clearing Audit
Cleared the Windows event logs using the Event Viewer to trigger alerts in Wazuh.

![Event Logger Clearing Audit](https://path-to-your-screenshot/ww5VCoa6NNBcJfpfAD1I5U72)

### 8. Audit Log Cleared Results
Observed the alert in Wazuh indicating that the audit logs on the Windows VM had been cleared.

![Audit Log Cleared Results](https://path-to-your-screenshot/audit log cleared results screenshot 8.PNG)

## Conclusion 🏁
This project effectively demonstrates the capabilities of Wazuh in monitoring security events from a Windows environment. The ability to trigger alerts based on log changes emphasizes the importance of proactive security measures in cybersecurity.

## Future Improvements 🚀
- Explore advanced features of Wazuh for more comprehensive security monitoring.
- Implement additional agents across various operating systems for broader monitoring capabilities.
- Analyse other security events to enhance detection rules and responses.
