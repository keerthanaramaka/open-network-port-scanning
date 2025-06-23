#  Scan Local Network for Open Ports

This project helps you scan your **local network** to identify open ports on connected devices,understand network exposure andevaluate potential security risks.

## Objectives

- Discover devices in your local network
- Identify open ports and running services
- Analyze potential security vulnerabilities
- Save and review scan results for auditing


# Target Host
192.168.29.198 i.e., IPV4 Address

# Use Cases

- Security auditing.
- Vulnerability assessment
- Network troubleshooting
- Penetration testing documentation

## Quick Start
Run the scan with :
```bash
nmap -sS 192.168.29.0/24 -oN scan_results.txt


