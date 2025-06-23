---
title: "Snort IDS Analysis"
date: 2025-05-23T23:51:22-05:00
draft: false

toc: false
images:
tags:
  - cybersecurity
  - detection
  - snort
---

## Creating Secure Intrusion Detection System

One of my recent projects is a **Instrusion Detection System**, designed using pcap files. This project is used to demonstrate the various different details of attacks would look like on intrusion detection systems. 

### What It Does
The system is used to analyze various TCP ports, detect malformed packets, payloads, and uses custom snort rules to authenicate events/flag. 

### Key Features
- **Port Scan Detection**: Analyzed TCP port scans, characterized traffic patterns, and created custom snort rules.
- **Malformed Packet Analysis**: Identified IP flooding and packet anomalies.
- **Malicious Payload Identification**: Used Wireshark to detect and analyze malicious payloads.
- **Custom Snort Rules**: Developed rules for TFTP write requests and RADIUS authentication events.

### How It Works
You are given capture files, which can be used to create your own custom snort rules in order to detect intrusions, as well as analyze in wireshark. Group 1 capture is used for port scanning to find packet anomalies. Group 2 is used as a capture to help demonstrate the appearance of malformed packets. Group 3 is used to detect malicious payloads through snort. Finally, Group 4 is used to create your own custom snort rules to detection instrusions into the system which can send alerts and detect anomalies/attacks.

### Try It Yourself
You can find the full code and instructions on my [GitHub repository](https://github.com/kneeble/IDS-Snort-Analysis). Feel free to clone the project, analyze locally, or even tweak it to add your own detections/features!

---

This project was a great way to explore security threats while creating something fun and nostalgic. If you have any questions or suggestions, feel free to reach out!