# Network Traffic Analysis and Incident Investigation

## Overview
This project investigates a simulated corporate network breach using Wireshark. The primary objectives were to identify unauthorized activity, extract sensitive details, and diagnose the type of attack.

## Key Findings
- Identified MITM attack and attacker’s MAC address.
- Extracted sensitive FTP data, including an administrator's SSH password.

## Tools Used
- **Wireshark**: Packet analysis and stream reconstruction.

## Steps
1. Captured network traffic using Wireshark.
2. Filtered for unusual ARP traffic to uncover MITM activity.
3. Analyzed FTP traffic and extracted sensitive data.
4. Diagnosed attack and proposed mitigation strategies.

## Learning Outcomes
- Developed strong proficiency in packet inspection and stream analysis.
- Enhanced understanding of network security protocols.

## How to Replicate
1. Download the sanitized `.pcap` file from the `Analysis_Files` folder.
2. Open in Wireshark and apply filters from `Tools_Scripts/filter_queries.txt`.
3. Follow the steps outlined in the walkthrough guide.
