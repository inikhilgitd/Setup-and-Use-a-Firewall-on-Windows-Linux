# Setup-and-Use-a-Firewall-on-Windows-Linux
Basic firewall management skills and understanding of network traffic filtering.
Firewall Setup and Configuration Guide
This repository provides comprehensive guides for setting up and configuring firewalls .
Objective
Configure and test basic firewall rules to allow or block network traffic using:
•	Windows: Windows Defender Firewall with Advanced Security
•	Linux: UFW (Uncomplicated Firewall)
Learning Outcomes
After completing this guide, you will:
•	Understand how to configure firewall rules on both Windows and Linux
•	Know how to test firewall effectiveness
•	Understand packet filtering principles
•	Be able to manage firewall rules programmatically and via GUI
For Windows Users
1.	Navigate to the windows/ directory
2.	Follow the step-by-step guide in windows/README.md
3.	Use provided PowerShell scripts for automation
For Linux Users
1.	Navigate to the linux/ directory
2.	Follow the setup guide in linux/README.md
3.	Run the setup script: ./ufw-setup.sh
 Testing Procedures
1.	Block Telnet (Port 23): Configure rules to deny inbound Telnet traffic
2.	Allow SSH (Port 22): Ensure SSH access remains available
3.	Connectivity Testing: Verify rules work as expected
4.	Rule Cleanup: Remove test rules and restore original configuration
