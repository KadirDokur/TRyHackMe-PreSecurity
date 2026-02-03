# Network Fundamentals – LAN, Subnetting & Core Protocols

This section covers fundamental networking concepts including LAN topologies, subnetting, and essential network protocols. The module focuses on understanding how devices communicate within a network and how networks are designed, segmented, and managed.

---

## LAN Topologies

### Learned Concepts
- Definition of network topology as the design and structure of a network
- Common LAN topologies:
  - Star Topology
  - Bus Topology
  - Ring Topology
- Roles of switches and routers in local networks
- Importance of redundancy and fault tolerance

### Topology Overview
- **Star Topology**
  - Devices connect to a central switch or hub
  - Scalable and reliable
  - Expensive to set up and maintain
  - Central device failure impacts the network

- **Bus Topology**
  - Single backbone cable
  - Cost-efficient and simple
  - Prone to bottlenecks
  - Single point of failure

- **Ring Topology**
  - Devices connected in a loop
  - Minimal cabling
  - Easier fault isolation
  - Failure of one device or cable breaks the network

### Network Devices
- **Switch**
  - Connects multiple devices
  - Sends packets only to the intended destination
  - Reduces unnecessary network traffic

- **Router**
  - Connects different networks
  - Uses routing to forward data between networks

### Practical Work
- Interactive lab exploring LAN topologies
- Simulated topology failures
- Flag retrieval by breaking network designs

### Key Takeaways
- LAN stands for Local Area Network
- Routers perform routing
- Switches centrally connect devices
- Bus topology is cost-efficient
- Star topology is expensive to set up and maintain

---

## Subnetting

### Learned Concepts
- Purpose of subnetting in small and large networks
- Network segmentation using subnet masks
- Logical separation of devices within a network

### Subnetting Details
- Subnetting divides a network into smaller networks
- Subnet masks:
  - 32 bits in total
  - Each octet ranges from 0 to 255

### IP Address Roles
- **Network Address** – identifies the network
- **Host Address** – identifies devices
- **Default Gateway** – forwards traffic to other networks

### Benefits
- Improved efficiency
- Increased security
- Better network control

### Key Takeaways
- Subnetting divides networks into smaller parts
- Subnet masks are 32 bits
- Default gateway enables external communication

---

## ARP (Address Resolution Protocol)

### Learned Concepts
- Mapping IP addresses to MAC addresses
- Device identification within a local network

### How ARP Works
- Devices maintain an ARP cache
- ARP message types:
  - ARP Request
  - ARP Reply

### Key Takeaways
- ARP stands for Address Resolution Protocol
- MAC address is the physical identifier
- IP address is the logical identifier

---

## DHCP (Dynamic Host Configuration Protocol)

### Learned Concepts
- Automatic IP address assignment
- Dynamic network configuration

### DHCP Process
1. DHCP Discover
2. DHCP Offer
3. DHCP Request
4. DHCP ACK

### Key Takeaways
- DHCP automates IP address management
- Prevents IP conflicts
- Essential for scalable networks

---

## Skills Gained
- Understanding LAN designs and weaknesses
- Knowledge of subnetting fundamentals
- Familiarity with core network protocols
- Hands-on experience with interactive network labs

