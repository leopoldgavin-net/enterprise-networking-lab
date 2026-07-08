# enterprise-networking-lab
Goal to design and set up a large hospital network that features all the benefits of a large enterprise level network while managing the complexity. 


# Hospital Network Simulation - Cisco Packet Tracer

## Overview

This project is a simulated hospital network created in Cisco Packet Tracer.

The goal of this project is to practice networking fundamentals including VLANs, routing, DHCP, DNS, and basic network design.

The network was built in phases, starting from a small LAN and expanding into a multi-department environment.


## Objectives

- Design a basic enterprise-style network
- Separate departments using VLANs
- Configure communication between networks
- Centralize network services
- Practice Cisco IOS configuration


## Technologies Used

- Cisco Packet Tracer
- Cisco IOS Commands
- VLANs
- Trunk Ports
- Inter-VLAN Routing
- DHCP
- DNS


## Network Layout

Current departments:

| Department | VLAN |
|-----------|------|
|Administration|10|
|Medical Staff|20|
|Servers|50|
|Guest Network|80|


## IP Addressing

| VLAN | Network |
|----|----|
|10|10.20.10.0/24|
|20|10.20.20.0/24|
|50|10.20.50.0/24|
|80|10.20.80.0/24|


## Project Phases

### Phase 1 - Basic Network Setup

Completed:
- Added router and switch
- Created VLANs
- Configured trunk links
- Enabled communication between VLANs


### Phase 2 - Network Services

Completed:
- Added server network
- Configured DHCP
- Configured DNS
- Hosted internal webpage


### Phase 3 - Network Expansion

In Progress:
- Add additional switches
- Add more departments
- Improve network layout


Future Improvements:

- Wireless networking
- Network security
- Redundancy
- Monitoring


## What I Learned

- How VLANs separate network traffic
- How trunk ports carry multiple VLANs
- How routers allow VLAN communication
- How DHCP simplifies IP management
- How DNS resolves names to IP addresses
