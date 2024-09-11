# Elastic Stack SIEM Configuration and Management Lab

## Objective

The objective of building an Elastic SIEM lab is to set up a home lab environment using Elastic SIEM within a Kali Linux VM, where data is forwarded from the VM to the SIEM through the Elastic Defend agent. In this lab, security events are generated on the Kali Linux VM using Nmap, and these logs are then queried and analyzed within the Elastic web interface. To enhance visibility and monitoring, a dashboard is created to visualize the security events, accompanied by an alert system to notify when specific security events are detected.

### Skills Learned/Developed

- Advanced understanding of Elastic SIEM concepts and practical application.
- Ability to generate and recognize attack signatures and patterns.
- Expertise in dashboard creation in the Elastic SIEM to visualise security events and data patterns.
- Proficiency in querying, analysing, and interpreting security event logs.
- Ability to troubleshoot issues during the Elastic Agent installation, such as modifying commands based on archiitecture (x86_64 to arm64).
- Enhanced knolwedge to develop configurations to continuously generate and monitor security events to improve SIEM effectiveness.  

### Tools Used

- Parallels VM
- Kali Linux
- Elastic SIEM
- Elastic Defend Agent

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*

- Step 1: Set up an Elastic Account
- Step 2: Set up a Kali Linux VM
- Step 3: Install Elastic Defend as the Software Agent to Collect Logs and Forward the Data to the Elastic SIEM
- Step 4: Generate Security Events on the Kali Linux VM using Nmap
- Step 5: Query and analyse the Security Event logs generated in the Elastic SIEM using the Elastic web interface
- Step 6: Create dashboards to visualise the Security Events
- Step 7: Create an Alert
