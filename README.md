# marriott-cairo-enterprise-network
Secure dual-site enterprise network design for two Marriott hotels in Cairo, simulated in Cisco Packet Tracer
# Secure Dual-Site Enterprise Network Design for Marriott Hotels, Cairo

Graduation project for the Digilians Nano Degree (Network & Infrastructure track).
A Cisco Packet Tracer simulation of a two-site hotel network: JW Marriott (HQ)
and Cairo Marriott, Zamalek (Branch).

> Academic simulation only. Not affiliated with or endorsed by Marriott International.

## Features
- Dynamic routing with OSPF
- First-hop redundancy with HSRP
- Link aggregation with EtherChannel
- Site-to-site IPsec VPN between HQ and Branch
- VLAN segmentation
- Wireless with WLC and lightweight APs
- VoIP using Cisco CME
- CCTV integration
- IPv4/IPv6 dual-stack
- Router ACLs for traffic filtering

## Tools
Cisco Packet Tracer, Cisco IOS CLI

## Topology
![Network topology](topology/topology.png)

## Design Notes
Router ACLs were used in place of ASA firewall features because
Packet Tracer does not support the ASA fully.

## Repository Contents
| Folder | Description |
|---|---|
| `packet-tracer/` | Simulation file (.pkt) |
| `configs/` | Device configurations |
| `docs/` | Addressing table, VLAN plan, report |

## Author
Aya, CCNA | Network Engineer | Cairo, Egypt
