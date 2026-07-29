# Enterprise Multi-VLAN Office Network

## Technologies

- Cisco Packet Tracer
- VLAN
- Subnetting
- OSPF Routing
- DHCP
- DNS
- HTTP (Web Server)
- Port Security
- SSH
- Inter-VLAN Routing

---

## Topology

- 3 Cisco 2911 Routers
- 4 Cisco 2960 Switches
- 1 DHCP/DNS Server
- 1 Web Server
- 5 End Devices (PCs & Printer)

---

## Network Segments

| Department | VLAN | Network |
|------------|------|----------------|
| Finance | VLAN 10 | 192.168.10.0/24 |
| Sales | VLAN 20 | 192.168.20.0/24 |
| HR | VLAN 30 | 192.168.30.0/24 |
| Server Room | VLAN 40 | 192.168.40.0/24 |

---

## Routing

- OSPF Dynamic Routing
- Multi-Router Connectivity
- Inter-VLAN Routing
- End-to-End Network Communication

---

## Services

- DHCP Server
- DNS Server
- Web Server (HTTP)
- Automatic IP Address Assignment
- Automatic Default Gateway Assignment
- DNS Name Resolution

---

## Security

- SSH Remote Management
- Switch Port Security
- Shutdown Violation Mode
- Restrict Violation Mode
- Secure MAC Address Learning

---

## Features

- VLAN Segmentation
- Dynamic Routing with OSPF
- DHCP Relay (IP Helper Address)
- DNS Resolution
- Web Server Access
- Secure Remote Management
- Port Security Configuration
- Enterprise Network Design

---

## IP Addressing

| Link | Network |
|------|----------|
| Router1 ↔ Router2 | 10.0.0.0/30 |
| Router2 ↔ Router3 | 10.0.0.4/30 |

---

## Project Objectives

- Design a small enterprise office network.
- Separate departments using VLANs.
- Configure OSPF for dynamic routing.
- Deploy DHCP, DNS, and Web services.
- Secure switch ports using Port Security.
- Enable secure device management via SSH.
- Verify end-to-end connectivity between all VLANs.

---

## Verification

✔ DHCP Lease Successful

✔ DNS Resolution Working

✔ Web Server Accessible

✔ OSPF Neighbor Adjacency Established

✔ Inter-VLAN Communication Successful

✔ SSH Remote Access Functional

✔ Port Security Tested

---

## Skills Demonstrated

- Enterprise Network Design
- IPv4 Addressing & Subnetting
- VLAN Configuration
- Inter-VLAN Routing
- OSPF
- DHCP
- DNS
- HTTP
- SSH
- Port Security
- Cisco IOS Configuration
- Network Troubleshooting
