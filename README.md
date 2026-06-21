# Enterprise-VLAN-Segmentation-VoIP-Network-Design-Lab-Cisco-Packet-Tracer-
Enterprise network simulation featuring VLAN segmentation, inter-VLAN routing, DHCP services, and VoIP integration. Designed to replicate a real-world hospital-style infrastructure with isolated data, voice, and server networks.

# 🏢 Enterprise VLAN Segmentation & VoIP Network Design Lab

## 📌 Project Overview

This project is an enterprise-style network simulation built using Cisco Packet Tracer. It models a real-world hospital-inspired infrastructure with logically separated networks for data, voice, and servers.

The design focuses on scalability, segmentation, and service reliability using VLANs, inter-VLAN routing, DHCP, and VoIP integration.

All IP addressing schemes, VLAN IDs, and physical layout have been modified for lab and documentation purposes.

---

## 🧠 Network Architecture

The network is segmented into three primary VLANs:

### 🔹 VLAN 10 – Data Network
- Used for end-user devices (PCs, workstations)
- Subnet: `192.168.10.0/24`
- Gateway: `192.168.10.1`
- DHCP assigned to clients

### 🔹 VLAN 20 – Voice Network
- Used for IP telephony (VoIP devices)
- Subnet: `192.168.20.0/24`
- Gateway: `192.168.20.1`
- IP phones registered and functional via Call Manager configuration

### 🔹 VLAN 30 – Server Network
- Hosts internal services such as DHCP and network infrastructure services
- Subnet: `192.168.30.0/24`
- Gateway: `192.168.30.1`

---

## 🔧 Core Features Implemented

- VLAN segmentation for traffic isolation and security
- IEEE 802.1Q trunk links between switches and router
- Router-on-a-Stick inter-VLAN routing
- DHCP services for automatic IP allocation (VLAN 10 clients)
- VoIP configuration with working IP phone registration
- Call Manager Express (CM) integration for voice services
- Centralized server network for service management
- Separation of data and voice traffic for performance optimization

---

## 📡 Network Behavior & Traffic Flow

- End devices in VLAN 10 automatically receive IP addresses via DHCP
- IP phones in VLAN 20 obtain network configuration and register to Call Manager services
- VLAN 30 hosts centralized infrastructure services
- Inter-VLAN routing enables controlled communication between segments
- Voice traffic is logically isolated to ensure call stability and reduced congestion

---

## 🛠 Technologies & Protocols Used

- Cisco Packet Tracer
- VLANs (IEEE 802.1Q)
- Router-on-a-Stick Inter-VLAN Routing
- DHCP (Dynamic Host Configuration Protocol)
- VoIP / IP Telephony
- Cisco Call Manager Express (CM)
- Layer 2 & Layer 3 switching concepts

---

## 🎯 Key Skills Demonstrated

This project demonstrates practical understanding of:

- Enterprise network design principles
- VLAN segmentation and traffic isolation
- Inter-VLAN routing architecture
- DHCP scope configuration and management
- VoIP deployment in enterprise environments
- Network troubleshooting and service validation
- Scalable infrastructure design

---

## 📁 Repository Contents

- Toplogy (`.pkt`)
- Network documentation (this README)
- Screenshots in folder
- video representaion of data travel

---

## 🚀 Future Enhancements

- Implement Access Control Lists (ACLs) for tighter security policies
- Add redundancy using HSRP or VRRP
- Introduce wireless VLAN integration
- Expand VoIP system with multiple departments or sites

Author:
Jamill Naipao
