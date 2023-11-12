# Multimedia Company DDoS Attack - Incident Report

## Overview

In response to a significant security incident, this report details the analysis, response, and preventive measures taken by the cybersecurity team at a multimedia company that provides web design, graphic design, and social media marketing solutions. The incident involved a distributed denial of services (DDoS) attack through an ICMP flood, which led to a temporary disruption of all network services.

## Project Scope

### Background

The multimedia company, specializing in digital services for small businesses, experienced a DDoS attack compromising its internal network for two hours. The attack involved a flood of ICMP packets, rendering normal internal network traffic inaccessible. The incident management team responded promptly by blocking incoming ICMP packets, suspending non-critical network services, and restoring critical functions once the threat was mitigated.

### Objectives

The primary objectives of this incident report are as follows:

1. **Analysis:** Provide a detailed analysis of the DDoS incident, examining its nature, impact, and the tactics employed by the malicious actor(s).

2. **Response:** Outline the cybersecurity team's response strategy, including the implemented measures to mitigate the attack and restore normal operations.

3. **Prevention:** Propose preventive measures based on the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to enhance the company's network security.

## NIST CSF Analysis

### Identify

- **Incident Nature:** A malicious actor executed an ICMP flood attack, affecting the entire internal network.
- **Response Priority:** Secure and restore critical network resources.

### Protect

- **Mitigation Measures Implemented:**
  - New firewall rule to limit incoming ICMP packets.
  - IDS/IPS system to filter suspicious ICMP traffic.

### Detect

- **Security Measures Implemented:**
  - Source IP address verification on the firewall to identify spoofed IP addresses.
  - Network monitoring software for abnormal traffic pattern detection.

### Respond

- **Future Response Plan:**
  - Isolate affected systems to prevent further disruption.
  - Attempt to restore disrupted critical systems and services.
  - Analyze network logs for suspicious activity.
  - Report incidents to upper management and legal authorities, if applicable.

### Recover

- **Recovery Steps:**
  - Restore access to network services to a normal state.
  - Block external ICMP flood attacks at the firewall.
  - Temporarily halt non-critical network services to reduce internal traffic.
  - Prioritize the restoration of critical network services.
  - Bring back online non-critical systems and services after ICMP flood subsides.

## Next Steps

1. **Reflection:**
   - Evaluate the effectiveness of the response plan and its alignment with NIST CSF principles.
   - Identify areas for improvement in incident handling and response.

2. **Stakeholder Communication:**
   - Use this report to communicate the incident, response, and preventive measures to stakeholders.

## Feedback

Your feedback on this incident report is invaluable. Please review the detailed incident analysis and recommendations in the provided [GitHub repository](https://github.com/JustinAntunes-Cardoso/Multimedia-Incident-Report) and share your insights.

---

**Note:** I've completed this incident report independently.

