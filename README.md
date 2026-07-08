# University Campus Network Design and Implementation

A comprehensive Cisco Packet Tracer project that simulates a scalable university campus network using a hierarchical network design. The project demonstrates enterprise networking concepts including VLAN segmentation, inter-VLAN routing, dynamic routing protocols, centralized network services, and simulated Internet connectivity.

---

## Project Overview

This project models a university campus consisting of multiple departments connected through a structured enterprise network.

### Departments

- Administration
- Academic
- Library
- Hostel
- Server Farm

The network is designed to provide secure communication, efficient routing, centralized services, and scalability for future expansion.

---

## Features

- VLAN Segmentation
- Router-on-a-Stick Inter-VLAN Routing
- Hierarchical Network Design
- Dynamic Routing
  - RIP Version 2
  - OSPF Area 0
  - EIGRP (AS 100)
- DHCP Server
- DNS Server
- HTTP & HTTPS Web Server
- FTP Server
- Email Server
- Simulated Internet Connectivity
- End-to-End Network Verification

---

## Network Architecture

The project follows a hierarchical campus network model consisting of:

- Internet Edge Router
- Core Layer
- Distribution Layer
- Access Layer
- Departmental Networks
- Server Farm

This architecture improves scalability, simplifies management, and provides efficient traffic flow across the campus.

---

## VLAN Design

The network is logically segmented into multiple VLANs to isolate departmental traffic and improve security.

Each VLAN has:

- Dedicated IP subnet
- Default Gateway
- DHCP Scope
- DNS Configuration

Inter-VLAN communication is achieved using Router-on-a-Stick with IEEE 802.1Q encapsulation.

---

## Dynamic Routing

To demonstrate multiple enterprise routing technologies, different routing protocols were implemented across departments.

| Protocol | Purpose |
|----------|---------|
| RIP Version 2 | Administration Network |
| OSPF Area 0 | Academic Network |
| EIGRP AS 100 | Library and Hostel Networks |

This project demonstrates interoperability between multiple routing protocols within the same enterprise environment.

---

## Network Services

### DHCP

- Centralized DHCP Server
- Automatic IP assignment
- Per-VLAN DHCP pools
- DHCP Relay (`ip helper-address`) configured on routers

### DNS

- Central DNS Server
- Name resolution for campus services

### Web Server

- HTTP/HTTPS services

### FTP Server

- File transfer services

### Email Server

- Email accounts configured for campus users

---

## Internet Simulation

An Internet Edge Router simulates external connectivity.

A loopback interface (`8.8.8.8`) represents an Internet destination, allowing all VLANs to verify outbound connectivity through the campus core.

---

## Testing & Verification

The following tests were successfully completed:

- VLAN-to-VLAN communication
- Inter-department connectivity
- Dynamic routing verification
- DHCP address assignment
- DNS name resolution
- Web server accessibility
- FTP connectivity
- Email communication
- Internet reachability

---

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- VLANs
- IEEE 802.1Q
- Router-on-a-Stick
- RIP Version 2
- OSPF
- EIGRP
- DHCP
- DNS
- HTTP/HTTPS
- FTP
- Email Services

---

## Repository Structure

```
University-Campus-Network/
│
├── CCN_Project.pkt
├── Campus_Network_Report.docx
├── Project_Screenshots.pdf
├── README.md
└── images/
    ├── topology.png
    ├── vlan-design.png
    ├── routing.png
    ├── services.png
    └── verification.png
```

---

## Learning Outcomes

This project strengthened my understanding of:

- Enterprise campus network design
- Layer 2 and Layer 3 switching concepts
- VLAN implementation
- Inter-VLAN routing
- Dynamic routing protocols
- Enterprise network services
- Network troubleshooting
- Cisco IOS configuration
- End-to-end network verification

---

## Author

**Sarib Shahid**

Computer Science Student

Interested in:
- Networking
- Cloud Computing
- Artificial Intelligence
- Infrastructure Automation

---

## License

This project is for educational purposes.
