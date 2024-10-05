# Azure-Cyber-Attack-Monitor
This project demonstrates the setup and use of Microsoft Azure Sentinel as a SIEM (Security Information and Event Management) tool to monitor real-time cyber attacks. By deploying a honeypot virtual machine, it captures malicious 
activity such as RDP brute force attempts. The captured data is then analyzed using Azure Sentinel to track and visualize cyber threats globally.

Features:

 -Honeypot VM Deployment: Configured a virtual machine to attract malicious activity and capture attack attempts.
 
 -Geolocation Data Collection: Implemented a PowerShell script to retrieve geolocation data from attacker IP addresses.
 
 -Live Attack Visualization: Mapped cyber attack origins on a live world map using Azure Sentinel’s dashboard.
 
 -Threat Detection: Utilized Azure Sentinel's log analytics to identify and visualize failed login attempts and other suspicious activities.

Technologies:
  -Azure Sentinel 
   -PowerShell
    -Azure Virtual Machine (Windows 10)
     -Log Analytics Workspace
