
## Networking Fundamentals – Summary of Learned Concepts & Practicals

This section covers core networking concepts, protocols, and practical exercises focused on how data moves across networks and how security controls are applied.

---

### Port Forwarding
- Learned how port forwarding allows internal network services to be accessed from the Internet.
- Understood the difference between port forwarding and firewall behavior.
- Practiced identifying how public IP addresses forward traffic to private network services.
- Learned that port forwarding is configured on routers.

---

### Firewalls
- Learned the role of firewalls in controlling inbound and outbound network traffic.
- Understood packet inspection based on:
  - Source and destination
  - Ports
  - Protocols (TCP / UDP)
- Studied firewall categories:
  - Stateful firewalls (inspect entire connections)
  - Stateless firewalls (inspect individual packets)
- Learned that firewalls primarily operate at OSI Layers 3 and 4.
- Completed a practical firewall lab by blocking malicious traffic on port 80.
- Retrieved the flag: `THM{FIREWALLS_RULE}`

---

### VPN Basics
- Learned what a Virtual Private Network (VPN) is and how encrypted tunnels work.
- Understood VPN benefits:
  - Secure communication
  - Privacy and encryption
  - Anonymity
  - Connecting geographically separated networks
- Learned how TryHackMe uses VPNs to securely expose vulnerable machines.
- Studied common VPN technologies:
  - PPP – Authentication and encryption
  - PPTP – Easy setup but weak encryption
  - IPSec – Strong encryption using the IP framework

---

### LAN Networking Devices
- Learned the role of a Router:
  - Connects multiple networks
  - Performs routing
  - Operates at OSI Layer 3
- Learned the role of a Switch:
  - Connects multiple devices within a network
  - Operates at:
    - Layer 2 (MAC-based forwarding)
    - Layer 3 (MAC and IP routing)
- Understood VLAN (Virtual LAN) concepts:
  - Logical network segmentation
  - Improved security and traffic isolation
- Learned differences between routers, Layer 2 switches, and Layer 3 switches.

---

### Practical Network Simulator
- Used a network simulator to observe packet flow step-by-step.
- Sent TCP packets between devices and analyzed:
  - Handshake process
  - Routing behavior
  - Packet delivery
- Retrieved the flag: `THM{YOU'VE_GOT_DATA}`
- Observed 5 handshake entries in the network log.

---

**Status:** All tasks completed successfully with both theoretical knowledge and hands-on practice.
