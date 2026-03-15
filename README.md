# Snort IDS / IPS Detection Lab

This project demonstrates the deployment and configuration of Snort as both an Intrusion Detection System (IDS) and an Inline Intrusion Prevention System (IPS).

The lab simulates real attack scenarios and validates Snort’s ability to detect and block malicious traffic in real time.

## Lab Overview

The lab environment includes a dual-interface architecture where Snort monitors and filters traffic between networks.

Snort was first configured in IDS mode for detection and monitoring, then transitioned to inline IPS mode to actively block malicious traffic.

## Key Implementations

- Installed and configured Snort on Ubuntu
- Created custom IDS detection rules
- Deployed Snort in Inline IPS mode using AFPacket
- Configured dual-interface architecture (NAT + Internal Network)
- Implemented drop rules to block malicious traffic

## Attack Simulation

Several attacks were simulated from an attacker VM:

- Telnet connection attempts (port 23)
- SYN flood attacks using hping3

Snort successfully detected and blocked malicious traffic in real time.

## Technologies

- Snort IDS / IPS
- Ubuntu Linux
- AFPacket
- Network Security Monitoring

## Documentation

Full implementation report available here:

Snort-IDS-IPS-Lab-Report.pdf
