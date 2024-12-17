# Network Traffic Analysis and Incident Investigation

## Overview
This project investigates a simulated corporate network breach, conducted as part of the Security Blue Team’s Blue Team Junior Analyst Pathway. The primary objectives were to analyze network traffic, identify unauthorized activity, and diagnose the type of attack using industry-standard tools and techniques.

## Key Findings
- Identified a Man-in-the-Middle (MITM) attack and pinpointed the attacker’s MAC address.
- Analyzed FTP traffic to uncover and extract a critical file downloaded from the central server.
- Extracted sensitive details, including the Domain Administrator’s SSH password and user data.

## Tools Used
- **Wireshark**: For packet analysis and stream reconstruction.
- **Nmap**: For service discovery and network scanning.
- **Security Blue Team Labs**: For providing the simulated environment and traffic files.

## Steps
1. Accessed simulated network traffic files provided by the Security Blue Team’s Blue Team Junior Analyst Pathway.
2. Access the network traffic files provided by Security Blue Team's Blue Team Junior Analyst Pathway here [Activity:Network Analysis Challenge](https://elearning.securityblue.team/home/courses/free-courses/introduction-to-network-analysis#content#course-capstone#course-capstone#activity-network-analysis-challenge)
3. Opened the `.pcap` file in Wireshark and applied ARP filters to identify unusual traffic patterns.
4. Diagnosed MITM attack characteristics by analyzing ARP requests and replies.
5. Reviewed FTP traffic to locate a sensitive file and extracted embedded credentials using stream reconstruction.
6. Summarized findings and recommended mitigation strategies for MITM attacks.

## Learning Outcomes
- Enhanced proficiency in network packet inspection and stream analysis.
- Gained practical experience in diagnosing network attacks in real-world simulations.
- Strengthened understanding of network security protocols and their vulnerabilities.

