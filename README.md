# RDP Brute Force & Suspicious Powershell Activity Incident Response & Case Management Lab

# Simulate a real-world SOC Tier 1 investigation workflow involving:
- RDP brute force attack
- Encoded PowerShell execution
- PowerShell download cradle activity
- Incident investigation
- Jira case management

# Technologies Used: 
- Splunk Enterprise
- Jira 
- Kali Linux
- Windows 10
- Hydra
- PowerShell

# Attack Simulation:
- Hydra brute force
- Encoded PowerShell
- Download cradle

# Detection Logic:
- Event ID 4624
- Event ID 4625
- Event ID 4104
- Event ID 4634
- Logon ID:3

# Investigation:
- Source IP identification
- Username analysis
- Parent-child process analysis
- Network connections

# Deliverables:
- Splunk alerts
- Jira incident ticket
- Incident response report
