# Multi-Area OSPF Enterprise Network Deployment (GNS3)
Implementation of Multi-Area OSPF routing protocol with route summarization and authentication in a simulated enterprise network

# OSPF Multi-Area OSPFv2 Network Lab

## Project Overview
This project demonstrates a multi-area OSPF configuration designed and tested using GNS3 with Cisco 7200 series routers. The goal is to achieve full connectivity across different areas while optimizing routing tables.

## Network Topology & Features
- **Area 0 (Backbone), Area 1, and Area 2** configuration.
- Configured Inter-Area routing using ABRs (Area Border Routers).
- Implemented OSPF MD5 Authentication for security.
- Route summarization on ABR to reduce routing table size.
- Verified using Wireshark packet analysis for OSPF Hello and LSU packets.

## Technologies Used
- **Emulation Tool:** GNS3
- **Router Series:** Cisco 7200
- **Protocols:** OSPFv2, OSPFv3 (for IPv6 if used), DHCP, DNS

## Verification Commands Used
- `show ip route ospf`                                                                                                                                         
- `show ip ospf neighbor`
- `show ip ospf database`
