# Web Recon: Multi-IP Discovery

## Description
Used Nikto to scan a legally permitted test web server, uncovering multiple IP addresses in the hosting setup. Investigated further to understand the infrastructure.

## Tools Used
- Nikto
- host 
- Nmap

## Steps
1. Ran a Nikto scan on a test web server.
2. Identified multiple IPs returned by the scan.
3. Used additional tools to explore the IPs’ roles.

## Findings
- Discovered multiple IPs (e.g., 141.193.213.21, 141.193.213.20), suggesting load balancing or redundancy.
- Confirmed IPs are part of a hosting provider’s network.
- Noted this could indicate a robust setup or a point to investigate further in a real pentest.

## Screenshots
- Nikto Output: [Insert screenshot of “Multiple IPs found…”]
- Nmap Scan : [Insert screenshot of ports/services, if you ran it]

## Reflection
Learned how reconnaissance reveals server setups. Next step: Dig into load balancer detection or vuln scanning.
