# Project overview
This repository contains an incident report created in response to analyze a network security incident. I was tasked to create a incident report using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. The company recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

## Summary
There was a flood of ICMP packets due to which the network services of the organization stopped responding. The IR team responded by blocking incoming ICMP packets, stopping all non critical network services offline, and restoring critical  network network services and it took  2 hours to restore normal business activity. Investigation found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall and it was a DDoS attack.

I used the following steps to navigate through the different steps of analyzing this cybersecurity event: 
- __Identify__ security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 
- __Protect__ internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 
- __Detect__ potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- __Respond__ to contain, neutralize, and analyze security incidents; implement improvements to the security process. 
- __Recover__ affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

---
[Download Complete Incident Report.DOCX]()
