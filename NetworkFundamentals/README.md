# TryHackMe – Network Fundamentals

This repository documents my hands-on learning and foundational networking knowledge gained through the TryHackMe Network Fundamentals path.

The focus is on understanding how networks operate, how data is transmitted, and how core networking concepts relate to cybersecurity.

---

## Topics Covered

### What is Networking
- Networking is the practice of connecting devices to share data and resources.
- Enables communication between computers, servers, and services across local and global networks.
- Forms the foundation of all modern IT and cybersecurity operations.

### What is the Internet
- The internet is a global network of interconnected networks.
- Uses standardized protocols (TCP/IP) to enable communication worldwide.
- Relies on ISPs, routing, and DNS to function.

---

## Identifying Devices on a Network
- Devices on a network are identified using IP addresses and MAC addresses.
- Hostnames and DNS help map human-readable names to IPs.
- Network discovery is a key step in both administration and security testing.

### Ping (ICMP)
- ICMP is used to test connectivity between devices.
- `ping` helps determine if a host is reachable and measure latency.
- Commonly used in troubleshooting and network enumeration.

---

## Introducing LAN Topologies
- Common LAN topologies include star, bus, and mesh.
- Modern networks typically use star topology with switches.
- Topology impacts performance, fault tolerance, and security.

### A Primer on Subnetting
- Subnetting divides a network into smaller logical segments.
- Improves performance, organization, and security.
- Uses CIDR notation and subnet masks.

---

## ARP (Address Resolution Protocol)
- Maps IP addresses to MAC addresses within a local network.
- Essential for local network communication.
- ARP spoofing can be used as an attack vector if networks are misconfigured.

### DHCP (Dynamic Host Configuration Protocol)
- Automatically assigns IP addresses to devices.
- Simplifies network management.
- Misconfigured DHCP can lead to network disruptions or attacks.

---

## OSI Model
- Consists of 7 layers, from Physical to Application.
- Helps in understanding where protocols and attacks operate.
- Useful for troubleshooting and security analysis.

### OSI Layers Overview
1. Physical  
2. Data Link  
3. Network  
4. Transport  
5. Session  
6. Presentation  
7. Application  

---

## Packets and Frames
- Frames operate at the Data Link layer and use MAC addresses.
- Packets operate at the Network layer and use IP addresses.
- Encapsulation explains how data moves through network layers.

---

## TCP/IP
- Connection-oriented and reliable protocol.
- Uses acknowledgements and retransmissions.
- Commonly used for web, email, and file transfers.

### UDP/IP
- Connectionless and faster than TCP.
- No guarantee of delivery.
- Used for DNS, streaming, and real-time services.

---

## Ports 101
- Ports identify specific services on a host.
- Common ports include 80 (HTTP), 443 (HTTPS), 22 (SSH).
- Used by firewalls and security tools to control access.

---

## Port Forwarding
- Redirects traffic from one port to another.
- Commonly used to expose internal services to external networks.
- Can introduce security risks if improperly configured.

---

## Firewalls 101
- Firewalls filter network traffic based on rules.
- Can be hardware or software-based.
- Essential for protecting networks from unauthorized access.

---

## VPN Basics
- VPNs create encrypted tunnels over untrusted networks.
- Protect data confidentiality and integrity.
- Commonly used for remote access and privacy.

---

## LAN Networking Devices
- Switches forward traffic based on MAC addresses.
- Routers forward traffic based on IP addresses.
- Access Points connect wireless devices to wired networks.
- Firewalls enforce security policies.

---

## Security Perspective
- Proper network segmentation reduces attack surface.
- Understanding protocols helps detect misconfigurations.
- Foundational networking knowledge is critical for both red and blue teams.

---

## Outcome
Developed a strong foundation in networking concepts essential for cybersecurity, penetration testing, and network defense.

> This repository contains learning notes only. No flags, credentials, or confidential data are shared.
