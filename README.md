# Azure-NSG-Flow-Logs-Monitoring-Lab
This lab demonstrates a comprehensive solution for monitoring and analyzing Azure Network Security Group (NSG) flow logs. The lab provides a practical approach to network security analysis and threat detection in Azure environments by leveraging advanced cloud monitoring techniques.

# Key Features
 - Automated collection and processing of Azure NSG flow logs
- Centralized log storage and analysis
- Performance and security insights for cloud network infrastructure

# Technologies
- Azure Network Security Groups (NSG)
- Azure Log Analytics
- Azure Monitor

# Prerequisites
- Azure Subscription
- Basic understanding of cloud networking
- Familiarity with Azure services


#Setup Overview:
1.I configured Network Security Group (NSG) rules in Azure to restrict inbound connections.
2. My home IP address was added as an allowed source for RDP sessions.
![image](https://github.com/user-attachments/assets/f5061fc5-80cd-4745-8c20-972f4176918d)

Testing and Results:
1.Once connected via RDP, I ran a Flow Log Query using Azure Network Watcher to validate inbound connections. 
![image](https://github.com/user-attachments/assets/803f767d-1797-44a0-a63d-25e1e75a2897)

2.My "SourceIp" address was listed as successfully connected, while other unauthorized connections were denied
![image](https://github.com/user-attachments/assets/dfc6b6a7-fffe-48cb-94f7-9758a1bbb316)

 For instance, IP address 83.222.190.66, flagged as a malicious threat actor, was denied.
![image](https://github.com/user-attachments/assets/b650a0a7-ef02-4be3-8635-4e53985b9135)
![image](https://github.com/user-attachments/assets/41e19dbb-a7e5-46f6-a628-264ee28c0f73)

Used Claude ai to help generate a logical network diagram this helped me understanding of the Azure cloud environment.
![image](https://github.com/user-attachments/assets/13ddfd21-df19-4325-95d8-6ad95a245a76)
