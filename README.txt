# Enterprise Hospital Network Design (Cisco Packet Tracer)

## Overview

This project simulates the design and implementation of an enterprise hospital network supporting multiple departments, centralized services, and scalable infrastructure.

The goal was to design the network using enterprise principles including segmentation, scalability, redundancy, security, and operational management.


## Business Requirements

The hospital requires:

- Separate networks for different departments
- Centralized infrastructure services
- Scalable design for future expansion
- Reliable connectivity between departments
- Secure access controls between sensitive systems


## Network Architecture

Architecture Model:

Collapsed Core Enterprise Design

Layers:

- Core Layer
- Access Layer


## Technologies Implemented

- VLAN Segmentation
- 802.1Q Trunking
- Inter-VLAN Routing
- DHCP Services
- DHCP Relay
- DNS Services
- Internal Web Hosting
- Enterprise IP Addressing

Future:

- OSPF Dynamic Routing
- EtherChannel
- HSRP Redundancy
- Wireless LAN
- ACL Security Policies
- Network Monitoring


## VLAN Design

| VLAN | Name | Purpose |
|----|----|----|
|10|ADMIN|Administrative users|
|20|MEDICAL|Doctors and nurses|
|30|MEDICAL_DEVICES|Healthcare equipment|
|40|LAB|Laboratory systems|
|50|SERVERS|Infrastructure services|
|70|SECURITY|Security cameras/access systems|
|80|GUEST|Visitor network|


## IP Addressing

| Network | Subnet | Gateway |
|-|-|-|
|Admin|10.20.10.0/24|10.20.10.1|
|Medical|10.20.20.0/24|10.20.20.1|
|Servers|10.20.50.0/24|10.20.50.1|
|Guest|10.20.80.0/24|10.20.80.1|


## Current Topology

(Insert topology image)


## Project Phases

### Phase 1 - Network Foundation
Completed:

- VLAN creation
- Router-on-a-stick
- Inter-VLAN communication


### Phase 2 - Enterprise Services
Completed:

- DHCP Server
- DHCP Relay
- DNS
- Internal web services


### Phase 3 - Campus Expansion
In Progress:

- Core switch implementation
- Floor access switches
- Additional departments


### Phase 4 - Routing Expansion

Planned:

- Dynamic routing


### Phase 5 - High Availability

Planned:

- HSRP
- EtherChannel


### Phase 6 - Security

Planned:

- ACLs
- SSH hardening
- Port security


## Testing

|Test|Expected Result|Status|
|-|-|-|
|VLAN routing|Departments communicate|Passed|
|DHCP assignment|Clients receive IP addresses|Passed|
|DNS lookup|Names resolve correctly|Passed|


## Lessons Learned

(Document problems encountered and troubleshooting steps)