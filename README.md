# Advanced Networking Projects Portfolio  
**Ali Bagheri** · UN ICT Specialist

[![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?logo=cisco&logoColor=white)](#)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white)](#)
[![GNS3](https://img.shields.io/badge/GNS3-00A1E0?logo=gns3&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Linux-WSL2-FCC624?logo=linux&logoColor=black)](#)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](#)
[![Last Updated](https://img.shields.io/badge/Updated-December%202025-0066CC)](#)

---

## Overview
This repository presents a collection of **enterprise-grade networking projects** developed by **Ali Bagheri** (Student ID: 97300111) during the **Advanced Computer Networks** course at **Iran University of Science and Technology (IUST)**, and in parallel with real-world responsibilities as a **Network Monitoring & Security Analyst** at the **United Nations Office in Tehran (UN-Iran)**.

These projects go far beyond typical academic labs — they reflect **real operational scenarios**, deep protocol understanding, troubleshooting under pressure, and pre-production validation techniques used daily in mission-critical environments.

---

## Project Sections

### 1. Cisco Multi-AS Network with OSPF + eBGP + Automatic Failover
**Enterprise-scale dual-AS topology** with full redundancy  
- Two autonomous systems (AS 65001 & AS 65002)  
- OSPF multi-area inside each AS  
- eBGP peering over loopback interfaces  
- Full route redistribution (OSPF ↔ BGP)  
- Physical backup link (R4–R8) to trigger automatic failover  
- Detailed before/after routing table & traceroute validation  

**Real-world relevance:** Same design principles applied in UN Tehran for inter-site connectivity and disaster recovery.

### 2. Wireshark Real-Traffic Forensics & Performance Analysis
Live packet capture during web browsing + large file upload (Gmail over home Wi-Fi)  
- Protocol hierarchy breakdown (TLS, QUIC, HTTP/3, DNS)  
- OS fingerprinting via TTL  
- HTTP/1.1 vs HTTP/2 vs HTTP/3 (QUIC) usage  
- TCP retransmission & packet loss identification  
- RTT graphing and traffic volume metrics  
- MTU & fragmentation analysis  

**Used in production:** Same methodology applied to detect anomalies and performance bottlenecks in UN internal network.

### 3. Deep Dive: DHCP, ARP, Routing Tables & NAT Mechanics
Full dissection of lower-layer and host configuration protocols  
- Complete DHCP DORA + Release process with packet-level explanation  
- ARP request/reply behavior in LAN  
- Windows & WSL routing table management  
- NAT translation process for private-to-public internet access  

**Daily operational toolset** at UN Tehran for client onboarding and connectivity troubleshooting.

---

## Tools & Technologies
- **Cisco Packet Tracer 8.x** · **GNS3**  
- **Wireshark 4.x** (Statistics, TCP Stream Graphs, IO Graphs)  
- **Windows 11 + WSL2 (Ubuntu)**  
- **Linux networking tools** (`ip`, `ss`, `tcpdump`)  
- **Cisco IOS configuration** (OSPF, eBGP, redistribution, route-maps)

---

## Why This Portfolio Matters
These projects are not simulations — they are **battle-tested patterns** from:
- Designing resilient multi-site routing for UN agencies  
- Performing live traffic forensics during security incidents  
- Validating network changes before deployment in production  
- Training junior analysts on protocol behavior and troubleshooting  

Every configuration, capture, and analysis here has been used (or directly inspired) from real enterprise environments.

---

## Project Highlights (Visual Overview)

<div align="center">

<img src="https://github.com/user-attachments/assets/9d90cd10-9872-4cef-88c9-6552a89c7d7d" alt="Cisco Multi-AS Topology & Addressing" width="48%"/>
<img src="https://github.com/user-attachments/assets/e9abb016-49f0-4979-ae7e-c7dd998758ed" alt="eBGP Configuration & OSPF Neighbors" width="48%"/>

<img src="https://github.com/user-attachments/assets/7012b4e3-4541-469e-99e2-40b51900e8b3" alt="Wireshark Protocol Hierarchy & Traffic Analysis" width="48%"/>
<img src="https://github.com/user-attachments/assets/908a13ff-f028-4fa6-a7ca-fc0ba1d135f4" alt="DHCP DORA Process Deep Dive" width="48%"/>
<img src="https://github.com/user-attachments/assets/d5d21715-a5a3-4b78-af38-c1f091f93ae7" alt="ARP, Routing Table & NAT Analysis" width="48%"/>

</div>

---

## Contact
**Ali Bagheri**  
ICT Specialist 
- LinkedIn: [linkedin.com/in/aibgr](https://www.linkedin.com/in/aibgr)  
- Email: ali.bagheri@un.org  

> Open to collaboration on enterprise network design, security auditing, traffic forensics, and performance optimization projects.

---
*Last updated: December 02, 2025*
