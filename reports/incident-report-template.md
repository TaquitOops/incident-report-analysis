#  Incident Report Analysis (NIST CSF)

## Summary
On December 15, 2025, a multimedia company experienced a Denial of Service (DoS) attack that disrupted its internal network for approximately two hours. The attack was executed through a flood of incoming ICMP packets, which overwhelmed the firewall and caused critical services to stop responding. Normal traffic could not access network resources, and business operations were interrupted. The incident response team mitigated the attack by blocking ICMP traffic, isolating non-critical services, and restoring essential network operations. This incident highlighted the importance of proper firewall configuration and continuous monitoring.

## Identify
The cybersecurity team audited firewall configurations, network devices, and access policies. They discovered that the firewall had not been properly configured, allowing a malicious actor to send a flood of ICMP ping packets. This vulnerability enabled the attacker to saturate the company’s network and disrupt services. All critical network resources needed to be secured and restored to a functioning state.

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
- Source IP verification on the firewall to detect spoofed packets.  

## Respond
The response team contained the incident by:
- Blocking ICMP traffic at the firewall.  
- Taking non-critical services offline to isolate the threat.  
- Restoring critical services and documenting the incident.  
- Analyzing network logs to identify suspicious activity.  
- Notifying upper management and preparing communication protocols for future events.  
- Reporting the incident to legal authorities if required.  

## Recover
Recovery actions included:
- Restoring affected systems and configurations from secure backups.  
- Reviewing and updating recovery procedures.  
- Communicating restoration steps to IT staff and stakeholders.  
- Implementing improvements to enhance resilience against future DoS attacks.  
- Gradually bringing non-critical services back online after the ICMP flood subsided.  

---

**Notes/Reflections:**  
This incident demonstrated the critical need for proactive firewall configuration, layered defenses, and continuous monitoring. By combining preventive hardening techniques with responsive measures, the organization improved its resilience against denial-of-service attacks and strengthened its overall cybersecurity posture.
