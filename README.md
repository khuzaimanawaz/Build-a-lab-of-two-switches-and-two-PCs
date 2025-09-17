# Cisco Packet Tracer Lab – Switches, PCs & Basic Configurations
📌 Overview

This lab demonstrates a basic networking setup using Cisco Packet Tracer.
It covers switch configuration, VLAN interfaces, IP addressing, connectivity tests, and remote access setup.

🖥️ Topology

2 × Cisco Layer 2 Switches

2 × PCs

Connections: Straight-through and crossover cables

⚙️ Configurations Performed

Assigned hostnames to switches

Configured VLAN 1 SVI with IP addresses

Verified interfaces with show ip int brief

Checked connectivity with ping & ARP

Observed MAC address learning with show mac address-table

Configured Telnet (vty lines) & enable password for remote access

Saved running configuration to startup

✅ Verifications

PC ↔ Switch ↔ PC communication successful

Switch ↔ Switch connectivity verified

Telnet access working with password authentication

MAC tables dynamically updated after traffic

🔑 Key Learnings

Importance of configuring SVIs for switch management

Difference between user mode, privilege mode, and config mode

How switches learn MAC addresses dynamically

Hands-on practice of remote access (Telnet) vs. secure SSH

Real-world habit: always save your config

🚀 Next Steps

Extend lab with VLAN segmentation

Add routing between VLANs (Inter-VLAN Routing)

Configure SSH instead of Telnet for secure remote management
