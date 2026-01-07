# Jeremy’s IT Lab – CCNA Practice Labs

## Overview

This repository documents my hands-on journey through Jeremy’s IT Lab (CCNA-focused). It contains lab configurations, verification outputs, and notes created while practicing real-world networking concepts using Cisco Packet Tracer.

## Key Topics Covered

### 1. Networking Fundamentals

* OSI vs TCP/IP models
* Role of routers, switches, and end devices
* MAC vs IP addressing
* ARP, ICMP, and basic packet flow

These labs establish the foundation needed to understand how data moves across networks.

---

### 2. IP Addressing & Subnetting (Core Focus)

Subnetting is heavily emphasized throughout the labs, as it is a critical CCNA skill.

Key concepts practiced:

* Binary-to-decimal and decimal-to-binary conversion
* CIDR notation and subnet masks
* Calculating:

  * Network address
  * Broadcast address
  * Usable host range
* Subnetting for:

  * Different host requirements
  * Efficient IP utilization
* VLSM (Variable Length Subnet Masking)

Subnetting is applied practically when designing multi-router topologies and VLAN networks.

---

### 3. Switching & VLANs

Hands-on switching labs include:

* Access vs trunk ports
* VLAN creation and assignment
* 802.1Q trunking
* Native VLAN concepts
* Inter-VLAN communication (Router-on-a-Stick)

These labs demonstrate how switches segment networks at Layer 2 and how routing is required to enable communication between VLANs.

---

### 4. Routing & Routing Protocols

Routing is a major focus area in this repository.

#### Static Routing

* Manual route configuration
* Default routes
* Recursive vs fully specified static routes

#### Dynamic Routing Protocols

* **RIP (basic understanding)**
* **OSPF (primary focus)**:

  * Single-area OSPF (Area 0)
  * Router IDs
  * Network statements and wildcard masks
  * OSPF neighbor relationships
  * Route advertisement and convergence

Routing labs reinforce how routers exchange information and dynamically adapt to network changes.

---

### 5. EtherChannel

EtherChannel labs focus on improving redundancy and bandwidth between switches.

Concepts practiced:

* Purpose of EtherChannel
* Load balancing
* Protocols:

  * PAgP
  * LACP
* Configuration requirements:

  * Matching speed and duplex
  * Matching VLAN and trunk settings

EtherChannel is used to demonstrate enterprise-grade switching design.

---

### 6. Spanning Tree Protocol (STP)

To prevent Layer 2 loops, the following STP concepts are covered:

* Root bridge election
* Port roles and states
* STP cost and priority
* How STP interacts with redundant links and EtherChannel

These labs explain *why* loops occur and how STP maintains a loop-free topology.

---

### 7. WAN & NAT Concepts

* Basic WAN serial connections
* DCE vs DTE roles
* Clock rate configuration
* Static NAT and PAT concepts

These labs bridge the gap between LAN design and real-world internet connectivity.

---

### 8. Verification & Troubleshooting

Every lab emphasizes verification using Cisco IOS commands such as:

* `show ip route`
* `show ip interface brief`
* `show vlan brief`
* `show etherchannel summary`
* `show ip ospf neighbor`
* `ping` and `traceroute`

Troubleshooting is treated as a **core skill**, not an afterthought.

---

## Tools & Technologies Used

* Cisco Packet Tracer
* Cisco IOS CLI
* Git & GitHub for version control and documentation

---

## Learning Outcome

By completing these labs, I have developed:

* Strong subnetting and IP design skills
* Confidence configuring routers and switches
* Practical understanding of routing protocols (especially OSPF)
* Ability to design scalable and redundant Layer 2 and Layer 3 networks
* Hands-on troubleshooting experience

