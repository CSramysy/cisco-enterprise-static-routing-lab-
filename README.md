# Enterprise Multi-Site Network Architecture & Routing Lab

## Overview
A hands-on Cisco Packet Tracer lab implementing a dual-site enterprise network architecture. This project demonstrates network topology design, IPv4 subnetting, device hardening, and cross-site static routing between Headquarter (HQ) and Branch networks.

## Network Topology
- **HQ Network:** `192.168.10.0/24` (Cisco ISR 4331 Router, Catalyst 2960 Switch, End Hosts)
- **Branch Network:** `192.168.20.0/24` (Cisco ISR 4331 Router, End Hosts)
- **Point-to-Point WAN Link:** `10.0.0.0/30`

## Key Implementation Steps
1. **Physical Cabling & IP Addressing:** Configured interfaces on Cisco ISR 4331 routers with appropriate IPv4 subnet masks.
2. **Static Routing:** Implemented bidirectional static routes (`ip route`) to enable end-to-end connectivity across WAN.
3. **Verification:** Tested full connectivity using ICMP Echo Requests (`ping`) with 0% packet loss.

## Files
- `enterprise-static-routing-lab.pkt`: Packet Tracer lab file.
