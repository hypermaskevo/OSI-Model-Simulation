# Cisco Packet Tracer Lab - OSI Model Simulation

## Description
This lab is a network simulation created in **Cisco Packet Tracer**, focusing on analyzing network traffic using **OSI Model** layers. The topology includes:

### Devices Used:
- **Cisco 2911 Routers** (R1, R2)
- **Cisco 2960 Switches** (SW1, SW2)
- **PCs** (PC1)
- **Server** (SRV1)

### Network Structure:
- **192.168.1.0/24 subnet for local communication**
- **10.0.0.0/24 subnet for external communication**
- **Traffic analysis through simulation mode**

## Objectives
- Use **simulation mode** to analyze traffic.
- Identify which **OSI Model layers** are involved in different network operations.
- **Renew and release** IP addresses to observe **Layer 7 traffic**.

## Setup Instructions
1. Open the **.pkt** file in Cisco Packet Tracer.
2. Use **simulation mode** to capture and analyze packets.
3. Run `ipconfig /release` and `ipconfig /renew` on PC1 to generate DHCP requests.
4. Observe the packet flow and OSI Model layers involved.

## Screenshot
![Network Topology](/mnt/data/image.png)

## Notes
- **Focus on different protocols** and how they interact within the OSI Model.
- DHCP renewal will create **Layer 7 traffic** for analysis.

## Author
Created for educational purposes in **Cisco Networking Labs**.


