# Marlware Traffic Investigation - Security Onion

Author: Gabe Lowden

## Overview

This repository documents malware traffic investigations conducted using **Security Onion-2.4.201** in **EVAL Mode**, leveraging **Zeek** and **Suricata** for network analysis and alerting. 
The goal of these exercise was to explore, analyze, and document suspicious activity from a captured PCAP, demonstrating the process of network threat detection and rule creation in a SOC environment.


## Objective 

- Import and analyze a PCAP containing potential malware communication.
- Identify suspicious network behavior through Zeek logs
- Detect and correlate alerts using Suricata's signture-based IDS/
- Create custom rules and filters to highlight relevant traffic.
- Document the full investigation workflow in a reproducible manner

## Repository Structure

- '/docs' - Detailed analysis for Zeek logs, Suricata alerts, and PCAP metadata.
- '/screenshots' - Visual references.
- '/rules' - Custom Suricata rules created for this investigation.
- '/pcap' - Example PCAPS
    &#8627; pcap samples from: https://www.malware-traffic-analysis.net/index.html

## Lab Setup

### VMs Used

- Security Onion --> SOC Tools

---
