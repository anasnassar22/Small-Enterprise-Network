# Small Enterprise Network - Inter-VLAN Routing

## Project Overview
This project demonstrates a functional network infrastructure for a small company using **Cisco Packet Tracer**. It features network segmentation, automated IP addressing, and inter-departmental communication.

## Network Topology
![Network Preview](https://github.com/anasnassar22/Small-Enterprise-Network/blob/main/Screenshot%202026-04-30%20012624.png?raw=true)

## Key Features
* **VLAN Segmentation:** * **VLAN 10 (Sales):** High-performance network for the Sales department.
    * **VLAN 20 (HR):** Secure network for HR and administrative tasks.
* **Inter-VLAN Routing:** Configured using the **Router-on-a-Stick** method to allow controlled communication between different VLANs.
* **Dynamic IP Allocation (DHCP):** A centralized DHCP server on the router automatically assigns IP addresses to all workstations, ensuring plug-and-play connectivity.
* **Trunking Protocol:** Optimized Trunk links between switches and the router to handle multi-VLAN traffic efficiently.

## Technologies Used
* **Cisco IOS CLI:** For advanced router and switch configuration.
* **Protocols:** 802.1Q (Trunking), DHCP, Inter-VLAN Routing.
* **Tools:** Cisco Packet Tracer.

## How to Run
1. Download the `.pkt` file from this repository.
2. Open it using **Cisco Packet Tracer**.
3. Use the **Simple PDU (Letter tool)** to ping between any two PCs to verify connectivity.
