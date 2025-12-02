
# Advanced Networking Projects Portfolio by Ali Bagheri

## Overview
This repository showcases a collection of advanced networking projects developed by **Ali Bagheri** (Student ID: 97300111) during the **Advanced Computer Networks** course at Iran University of Science and Technology (IUST), as well as during my tenure as a **Network Monitoring and Security Analyst** at the United Nations Office in Tehran (UN-Iran). These projects are designed to simulate real-world enterprise-level network scenarios, focusing on routing protocols, traffic analysis, and network optimization. The work includes detailed documentation, configurations, and packet captures, reflecting high-level testing and analysis conducted in professional and academic settings.

## Project Sections

### 1. Cisco Multi-AS Network with OSPF and eBGP
**Description:** This project involves designing and simulating a multi-autonomous system (AS) network using Cisco Packet Tracer. It features two ASes (AS 65001 and AS 65002) interconnected via eBGP, with OSPF as the internal routing protocol. The network includes redundancy and failover testing by adding a backup link between routers R4 and R8.

- **Key Objectives:**
  - Structured IP addressing across AS1 and AS2.
  - Implementation of OSPF for intra-AS routing.
  - Configuration of eBGP peering between R6 and R8.
  - Redistribution of OSPF routes into BGP and vice versa.
  - Analysis of routing behavior before and after topology changes.
  - Validation of failover using traceroute commands.

- **Key Screenshots:**
  | # | Description                       | File Path                       |
  |---|-----------------------------------|---------------------------------|
  | 1 | AS1 Addressing Table & Topology  | `./cisco-project/images/as1-addressing-topology.png` |
  | 2 | AS2 Addressing & OSPF Neighbors  | `./cisco-project/images/as2-addressing-ospf.png`     |
  | 3 | eBGP Configuration on R6 & R8     | `./cisco-project/images/bgp-config-r6-r8.png`        |
  | 4 | Routing Tables Before/After Change| `./cisco-project/images/routing-before-after.png`    |
  | 5 | Traceroute Results for Failover   | `./cisco-project/images/traceroute-failover.png`     |

- **Significance:** Demonstrates robust network design, dynamic routing protocol interaction, and failover mechanisms critical for enterprise environments.

### 2. Wireshark Traffic Analysis (Project 1)
**Description:** This project analyzes a packet capture file (.pcapng) recorded during a real-world web browsing session and file upload to Gmail via a home Wi-Fi network using Wireshark.

- **Key Analyses:**
  - Protocol hierarchy and packet distribution (TCP, UDP, DNS, TLS, HTTP, etc.).
  - Identification of frequent IP endpoints and associated DNS queries.
  - Operating system detection using TTL values (e.g., Linux/Android-based devices).
  - Breakdown of HTTP versions (HTTP/1.1, HTTP/2, HTTP/3 over QUIC).
  - Total traffic volume, average packet size, and MTU estimation.
  - RTT (Round Trip Time) graph for TCP streams.
  - Detection of TCP retransmissions and packet loss during large file uploads.

- **Key Screenshots:**
  | # | Description                       | File Path                       |
  |---|-----------------------------------|---------------------------------|
  | 1 | Protocol Hierarchy Statistics    | `./wireshark-project1/images/protocol-hierarchy.png` |
  | 2 | I/O Graph of Traffic             | `./wireshark-project1/images/io-graph.png`           |
  | 3 | Endpoint Statistics (IPv4)        | `./wireshark-project1/images/endpoints-ipv4.png`     |
  | 4 | TTL-Based OS Detection            | `./wireshark-project1/images/ttl-os-detection.png`   |
  | 5 | RTT Graph for TCP Streams         | `./wireshark-project1/images/rtt-graph.png`          |

- **Significance:** Highlights advanced traffic analysis skills, essential for network troubleshooting and security monitoring in organizational settings.

### 3. Wireshark Deep Dive into DHCP, ARP, Routing, and NAT (Project 2)
**Description:** This project provides an in-depth analysis of the DHCP process (DORA cycle), ARP resolution, routing table management, and NAT functionality using Wireshark captures and WSL (Windows Subsystem for Linux) tools.

- **Key Analyses:**
  - Detailed breakdown of DHCP Discover, Offer, Request, ACK, and Release packets.
  - ARP request/response analysis for IP-to-MAC resolution.
  - Examination of routing tables and default gateway configuration on Windows.
  - Explanation of NAT's role in enabling internet access with private IPs.

- **Key Screenshots:**
  | # | Description                       | File Path                       |
  |---|-----------------------------------|---------------------------------|
  | 1 | DHCP DORA Packet Sequence        | `./wireshark-project2/images/dhcp-dora-sequence.png` |
  | 2 | ARP Request/Reply Capture        | `./wireshark-project2/images/arp-request-reply.png`  |
  | 3 | Routing Table (route PRINT)       | `./wireshark-project2/images/routing-table.png`      |
  | 4 | NAT Process Diagram              | `./wireshark-project2/images/nat-diagram.png`        |
  | 5 | Interface Details in WSL          | `./wireshark-project2/images/wsl-interface.png`      |

- **Significance:** Offers a comprehensive understanding of low-level network protocols and configurations, crucial for network administration and security.

## Repository Structure
```
├── cisco-project/
│   ├── Cisco Project-Bagheri.pdf          (Detailed report, 10 pages)
│   ├── images/
│   │   ├── as1-addressing-topology.png
│   │   ├── as2-addressing-ospf.png
│   │   ├── bgp-config-r6-r8.png
│   │   ├── routing-before-after.png
│   │   └── traceroute-failover.png
│   └── packet-tracer-files/               (Optional .pkt files)
├── wireshark-project1/
│   ├── Wireshark Project 1-AliBagheri.pdf (Detailed report, 8 pages)
│   ├── capture.pcapng
│   └── images/
│       ├── protocol-hierarchy.png
│       ├── io-graph.png
│       ├── endpoints-ipv4.png
│       ├── ttl-os-detection.png
│       └── rtt-graph.png
├── wireshark-project2/
│   ├── Wireshark 2.pdf                    (Detailed report, 11 pages)
│   ├── dhcp-capture.pcapng
│   └── images/
│       ├── dhcp-dora-sequence.png
│       ├── arp-request-reply.png
│       ├── routing-table.png
│       ├── nat-diagram.png
│       └── wsl-interface.png
└── README.md                              (This file)
```

## Tools and Technologies
- **Cisco Packet Tracer** (v8.x) and GNS3 for network simulation.
- **Wireshark** (v4.x) for packet analysis and traffic visualization.
- **Windows 10/11 + WSL2 (Ubuntu)** for network configuration and testing.
- **Linux Networking Tools** (ip, ifconfig, tcpdump).
- **Cisco IOS Commands** for routing protocol configuration.

## Importance of These Projects
These projects replicate the complexities encountered in real-world enterprise networks, such as those at the United Nations Office in Tehran. They emphasize:
- Ensuring network stability and redundancy through dynamic routing.
- Rapid troubleshooting and forensic analysis using packet captures.
- Deep protocol understanding for optimizing network performance.
- Pre-deployment testing to validate changes in production environments.

## Contact
**Ali Bagheri**  
Network Engineer | Security Specialist  
- LinkedIn: [linkedin.com/in/alibagheri-net](https://linkedin.com/in/alibagheri-net)  
- Email: ali.bagheri.net@gmail.com  

> Available for collaboration on enterprise network design, security, monitoring, and optimization projects.

---
*Last Updated: December 02, 2025, 01:15 PM EST*
```

This README is fully detailed, professionally structured, and ready to be copied and pasted into your GitHub repository. It includes sections for each project, highlights their significance, and provides specific paths for the five requested images per project, ensuring a comprehensive overview of your work.
