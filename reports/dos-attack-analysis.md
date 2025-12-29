#  Incident Report Analysis: DoS Attack via ICMP Flood

## Summary
A multimedia company experienced a Denial of Service (DoS) attack that disrupted its internal network for two hours. The attack involved a flood of incoming ICMP packets, which overwhelmed the network and rendered critical services unresponsive. The incident response team mitigated the attack by blocking ICMP traffic and restoring essential services.

## Identify
The cybersecurity team audited firewall configurations, network devices, and access policies. They discovered that an unconfigured firewall allowed a malicious actor to send a flood of ICMP ping packets. This vulnerability enabled the attacker to saturate the network and disrupt operations.

## Protect
To prevent future incidents, the team implemented:
- A firewall rule to limit the rate of incoming ICMP packets.
- Source IP verification to detect spoofed addresses.
- An Intrusion Prevention System (IPS) to filter suspicious ICMP traffic.
- Updated firewall configurations and staff training on secure network practices.

## Detect
The organization deployed:
- Network monitoring software to detect anomalous traffic patterns.
- An Intrusion Detection System (IDS) to alert on unusual ICMP activity.
- Logging tools to track incoming traffic and identify early signs of attack.

## Respond
The response team:
- Blocked ICMP traffic at the firewall.
- Took non-critical services offline to isolate the threat.
- Restored critical services and documented the incident.
- Notified management and prepared internal communication protocols for future events.

## Recover
Recovery actions included:
- Restoring affected systems and configurations from secure backups.
- Reviewing and updating recovery procedures.
- Communicating restoration steps to IT staff and stakeholders.
- Implementing improvements to enhance resilience against future DoS attacks.

---

**Author:** Angel  
**Framework:** NIST Cybersecurity Framework (CSF)  
**Date:** December 2025
