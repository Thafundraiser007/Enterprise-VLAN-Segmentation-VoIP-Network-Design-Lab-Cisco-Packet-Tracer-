# 🏢 Enterprise VLAN Segmentation & VoIP Network Design Lab

![Network Topology](https://github.com/user-attachments/assets/88bab0e4-eb1b-41b6-b833-898d59cd8811)

## 📌 Project Overview

This project is an enterprise-style network simulation built using Cisco Packet Tracer. It models a hospital-inspired infrastructure with logically segmented networks for data, voice, and server services.

The design focuses on scalability, security, and service reliability using VLAN segmentation, inter-VLAN routing, DHCP, and VoIP integration.

All IP addressing schemes, VLAN IDs, and physical layout have been modified for lab and documentation purposes.

---

## 🧠 Network Architecture

The network is segmented into three VLANs:

### 🔹 VLAN 10 – Data Network
- End-user devices (PCs, workstations)
- Subnet: `192.168.10.0/24`
- Gateway: `192.168.10.1`
- DHCP assigned

### 🔹 VLAN 20 – Voice Network
- IP telephony devices (VoIP)
- Subnet: `192.168.20.0/24`
- Gateway: `192.168.20.1`
- Call Manager Express (CME) enabled

### 🔹 VLAN 30 – Server Network
- Internal services (DHCP and network services)
- Subnet: `192.168.30.0/24`
- Gateway: `192.168.30.1`

---

## 🔧 Core Features Implemented

- VLAN segmentation for traffic isolation and security
- IEEE 802.1Q trunking between switches and router
- Router-on-a-Stick inter-VLAN routing
- DHCP services for automatic IP assignment (VLAN 10)
- VoIP configuration with IP phone registration
- Call Manager Express (CME) integration
- Centralized server-based network services

---

## 📡 Network Behavior

- VLAN 10 devices receive IP addresses via DHCP
- VLAN 20 IP phones register with Call Manager services
- VLAN 30 provides internal network services
- Inter-VLAN routing enables controlled communication between segments
- Voice traffic is isolated for performance and reliability

---

## 🛠 Technologies Used

- Cisco Packet Tracer
- VLANs (802.1Q)
- Router-on-a-Stick Inter-VLAN Routing
- DHCP (Dynamic Host Configuration Protocol)
- VoIP / IP Telephony
- Cisco Call Manager Express (CME)

---

## 📁 Repository Contents

- Packet Tracer topology file (`.pkt`)
- Screenshots folder (network validation & testing)
- Video demonstration of packet/data flow
- README documentation

---

## 🎯 Key Skills Demonstrated

- Enterprise network design
- VLAN segmentation and traffic isolation
- Inter-VLAN routing architecture
- DHCP configuration and management
- VoIP deployment and troubleshooting
- Network validation and testing

---

## 🚀 Future Improvements

- Implement ACL-based security policies
- Add redundancy (HSRP/VRRP)
- Expand wireless VLAN integration
- Multi-site VoIP expansion
- Network monitoring (SNMP/syslog simulation)

---

## 👤 Author
Jamill Naipao
