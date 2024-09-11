# OPNsense
🔥 OPNsense Firewall & IDS/IPS Project 🔥
Project Overview:
This project demonstrates the configuration and testing of Intrusion Detection and Prevention Systems (IDS/IPS) using OPNsense, an open-source firewall platform. The goal was to simulate various network attacks and tune OPNsense to detect and block malicious traffic in real-time.

->Features
Firewall Configuration: Created and managed firewall rules to control traffic flow between networks.
IDS/IPS Setup: Configured OPNsense to detect and prevent attacks with Intrusion Detection and Prevention Systems.
Real-Time Alerts: Monitored live traffic and generated alerts for malicious activities.
Traffic Blocking: Automatically blocked malicious traffic based on configured IDS/IPS rules.
Attack Simulations
I performed the following types of attacks from a virtual machine to test the IDS/IPS:

🔍 Port Scanning using Nmap
🚪 Brute-force Attacks on SSH using Hydra
💥 Denial-of-Service (DoS) attacks using Hping3
🛡️ Web Application Attacks such as SQL injection using SQLmap
Technologies Used
OPNsense – Firewall and IDS/IPS platform
Nmap – Network discovery and security auditing
Hydra – Brute-force login tool
Hping3 – Network tool for DoS and TCP/IP testing
SQLmap – Automated SQL injection tool
Linux VM – Attack environment
Key Learning Points
Intrusion Prevention: Tuned OPNsense to automatically block real-time attacks.
Network Monitoring: Analyzed traffic and implemented rule-based detection of malicious activities.
Firewall Management: Optimized firewall rules to maintain a balance between security and legitimate traffic.
Usage

->>To replicate this project:

Set up OPNsense on your firewall hardware or virtual machine.
Enable IDS/IPS in OPNsense and configure relevant rule sets (e.g., Emerging Threats).
Simulate attacks from another machine using tools like Nmap, Hydra, or Hping3.
Monitor the Intrusion Detection Alerts section to view blocked traffic and alerts.
Future Work
Implement further testing with more advanced attack techniques.
Explore integrating OPNsense with external logging and monitoring tools (e.g., ELK Stack, Grafana).
![opnsense2](https://github.com/user-attachments/assets/3bf9aa33-7184-42dd-a95b-8b53b3bfb79b)
![opnsense3](https://github.com/user-attachments/assets/afdc3bb2-a07c-4e8b-b6e1-a6ae78f0dd74)
![opnsense4](https://github.com/user-attachments/assets/cf6311a6-39cb-4f12-bfb4-4a5a7858eb4d)
<img width="1470" alt="opnsense7" src="https://github.com/user-attachments/assets/4fd6a4e0-b4dc-49a5-a68b-3ec939ff87b2">
<img width="1470" alt="opnsense7" src="https://github.com/user-attachments/assets/39993f5c-45fa-4d8b-933a-c63487cd4343">
<img width="1470" alt="opnsense9" src="https://github.com/user-attachments/assets/d7454ecd-e8b3-4c2d-a369-9b15bd9f804b">
<img width="1470" alt="opnsense10" src="https://github.com/user-attachments/assets/65071d05-2c0b-4ef2-8767-e871738d6046">



