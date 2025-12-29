#  Incident Report Analysis (NIST CSF)

## Summary
A multimedia company experienced a Denial of Service (DoS) attack that disrupted its internal network for two hours. The attack was carried out through a flood of incoming ICMP packets, which overwhelmed the firewall and caused critical services to stop responding. The incident response team mitigated the attack by blocking ICMP traffic, isolating non-critical services, and restoring essential network operations.

## Identify
The incident management team audited firewall configurations, network devices, and access policies. They discovered that the firewall had not been properly configured, allowing a malicious actor to send a flood of ICMP ping packets. This vulnerability enabled the attacker to saturate the company’s network and disrupt services.

## Protect
To strengthen defenses, the team implemented:
- A firewall rule to limit the rate of incoming ICMP packets.  
- Source IP verification to detect spoofed addresses.  
- An Intrusion Prevention System (IPS) to filter suspicious ICMP traffic.  
- Updated firewall configurations and staff training on secure network practices.  

## Detect
To detect similar incidents in the future, the organization deployed:
- Network monitoring software to identify anomalous traffic patterns.  
- An Intrusion Detection System (IDS) to alert on unusual ICMP activity.  
- Logging tools to track incoming traffic and provide early warnings.  

## Respond
The response team contained the incident by:
- Blocking ICMP traffic at the firewall.  
- Taking non-critical services offline to isolate the threat.  
- Restoring critical services and documenting the incident.  
- Notifying management and preparing communication protocols for future events.  

## Recover
Recovery actions included:
- Restoring affected systems and configurations from secure backups.  
- Reviewing and updating recovery procedures.  
- Communicating restoration steps to IT staff and stakeholders.  
- Implementing improvements to enhance resilience against future DoS attacks.  

---

**Notes/Reflections:**  
This incident highlighted the importance of proper firewall configuration, continuous monitoring, and layered defenses. By combining proactive hardening techniques with responsive measures, the organization strengthened its resilience against future denial-of-service attacks.
