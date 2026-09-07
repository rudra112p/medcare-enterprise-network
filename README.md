# medcare-enterprise-network
Multi-site enterprise healthcare network designed and implemented in Cisco Packet Tracer with VLANs, subnetting, DHCP, DNS, static routing, ACLs and network security.
# 🏥 MedCare Health Services — Enterprise Network Design & Implementation

A multi-site enterprise healthcare network designed and implemented using Cisco Packet Tracer. The project demonstrates secure network segmentation, inter-site connectivity, centralised network services, access control, and enterprise network administration across four healthcare locations.

## 📌 Project Overview

MedCare Health Services operates across four locations:

- Main Hospital (MHS)
- Central Clinic (CC)
- North-West Medical Branch (NWMB)
- South-East Medical Branch (SEMB)

The network was designed to provide secure and reliable communication between these sites while separating departmental traffic using VLANs and classless IPv4 subnetting.

The implementation includes VLAN segmentation, 802.1Q trunking, inter-VLAN routing, DHCP, DNS, Web and Email services, static WAN routing, extended Access Control Lists (ACLs), and device security.

The complete network implementation is available in the Cisco Packet Tracer `.pkt` file included in this repository.
## 🏗️ Network Architecture

The MedCare network follows a multi-site architecture connecting the Main Hospital (MHS), Central Clinic (CC), North-West Medical Branch (NWMB), and South-East Medical Branch (SEMB).

The Main Hospital provides departmental network segmentation for Clinical Services, IT, Administration, and Pharmacy. Central Clinic also contains centralised DNS, Web, and Email services used within the network.

Cisco 2911 routers provide WAN connectivity between the sites, while Cisco 2960 switches provide local network access and VLAN segmentation.

### Network Topology

![MedCare Enterprise Network Topology](screenshots/medcare-network-topology.png)
