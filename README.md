# Enterprise-Switching-Routing-Lab
# Cisco Packet Tracer Enterprise Switching & Routing Lab

## Overview
This project is a Cisco Packet Tracer enterprise networking lab that simulates expanding an existing enterprise network by adding and configuring a new access/distribution switch block. The project follows an access-distribution-core network model and focuses on VLAN segmentation, trunking, Layer 3 switching, routed links, link aggregation, dynamic routing, DHCP relay, and redundancy.

The lab was completed as part of an Advanced Computer Networks course and was designed to model a realistic enterprise environment where new network infrastructure must be integrated into an existing operational network.

## Project Goals
- Build and configure an enterprise-style switching topology in Cisco Packet Tracer
- Segment user groups using VLANs and access ports
- Configure 802.1Q trunk links between access and distribution switches
- Configure SVIs on multilayer switches for inter-VLAN routing
- Use routed ports and static routes to connect distribution switches
- Configure Layer 2 and Layer 3 EtherChannel using LACP
- Connect the distribution layer to the network core
- Replace static routing with OSPF dynamic routing
- Configure DHCPv4 pools and DHCP relay using ip helper-address
- Improve resiliency using RSTP, PortFast, BPDU Guard, and FHRP concepts
- Verify connectivity using ping, traceroute, routing tables, VLAN tables, trunk status, and EtherChannel commands

## Technologies and Concepts Used
- Cisco Packet Tracer
- VLANs and access ports
- 802.1Q trunking
- Native VLAN configuration
- Switch Virtual Interfaces (SVIs)
- Inter-VLAN routing
- Layer 3 switching
- Routed ports
- Static routing
- OSPF
- EtherChannel / LACP
- DHCPv4 server configuration
- DHCP relay / ip helper-address
- Rapid Spanning Tree Protocol (RSTP)
- PortFast and BPDU Guard
- First Hop Redundancy Protocols (FHRP)
- Enterprise access-distribution-core design

## What I Configured
- Added and connected access switches, multilayer distribution switches, PCs, laptops, access points, and an IP phone
- Assigned IPv4 addresses, subnet masks, default gateways, and DNS settings
- Created VLANs for Engineering, QA, Sales, Marketing, Voice, Guest, Management, Native, and Parking-Lot networks
- Configured access ports and trunk ports with native VLAN and allowed VLAN settings
- Configured SVIs on multilayer switches to act as default gateways for VLANs
- Enabled IP routing on Layer 3 switches for inter-VLAN communication
- Configured routed point-to-point links between distribution switches
- Added static routes and later transitioned routing toward OSPF
- Configured Layer 2 EtherChannel between access switches and Layer 3 EtherChannel between distribution switches using LACP
- Configured DHCP pools and DHCP relay so clients across VLANs could receive IP addresses from a centralized DHCP server
- Verified the network using IOS show commands, ping tests, and traceroute

## Verification
The completed topology was verified using:
- show vlan brief
- show interfaces trunk
- show ip interface brief
- show ip route
- show etherchannel summary
- show spanning-tree
- ping
- tracert
- DHCP client address assignment tests

## Key Takeaways
This project helped me understand how enterprise networks are built and expanded in layers. I practiced configuring VLAN segmentation, trunking, Layer 3 switching, redundancy, routing, and DHCP services while troubleshooting common issues such as native VLAN mismatches, blocked STP ports, DHCP failure across VLANs, and route reachability problems.

## Files
- enterprise-switching-routing-lab.pkt — Cisco Packet Tracer project file
- screenshots/ — topology and verification screenshots
