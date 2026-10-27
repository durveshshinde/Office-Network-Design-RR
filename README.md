# Office Network Design Using Cisco Packet Tracer

## Project Overview
This project demonstrates the design and configuration of a small office network using Cisco Packet Tracer. The network separates three departments using VLANs and enables communication between them through inter-VLAN routing.

## Objectives
- Design a small office network.
- Configure VLANs for departmental segmentation.
- Configure trunking between the switch and router.
- Implement inter-VLAN routing using router subinterfaces.
- Test network connectivity and troubleshoot issues.

## Network Topology
- 1 Cisco router
- 1 Cisco switch
- 12 PCs
- Cisco Packet Tracer simulation environment

## VLAN Configuration

| VLAN ID | Department | Network | Default Gateway |
|---|---|---|---|
| 10 | HR | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Finance | 192.168.30.0/24 | 192.168.30.1 |

## Technologies Used
- Cisco Packet Tracer
- VLANs
- IEEE 802.1Q trunking
- Router-on-a-stick
- IPv4 addressing
- Inter-VLAN routing
- Ping and Cisco IOS verification commands

## Testing and Verification
The following commands were used to verify the configuration:

- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`
- `show ip route`
- `ping`

Connectivity tests confirmed successful communication between devices in different VLANs.

## Project Files
- `Office_Network_Design.pkt` — Packet Tracer simulation file.
- Network screenshots — topology, configuration, and connectivity test evidence.

## Learning Outcomes
- Understanding VLAN-based network segmentation.
- Configuring router subinterfaces and switch trunk ports.
- Understanding inter-VLAN communication.
- Practising basic network verification and troubleshooting.

## Author
Durvesh Shinde
