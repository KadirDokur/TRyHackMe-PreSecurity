
# OSI Model Fundamentals

This section covers the **OSI (Open Systems Interconnection) Model**, explaining how data is transmitted across networks through layered architecture. Each layer has a specific responsibility, allowing devices with different designs and functions to communicate reliably.

---

## OSI Model Overview

### Learned Concepts
- Purpose and importance of the OSI Model in networking
- Layered approach to data communication
- Concept of **encapsulation**, where data is wrapped with additional information at each layer

### Key Takeaways
- OSI stands for **Open Systems Interconnection**
- The OSI model consists of **7 layers**
- Data encapsulation occurs as data moves through layers

---

## Layer 1: Physical Layer

### Responsibilities
- Handles the physical components of networking
- Transfers data using electrical signals
- Uses binary (0s and 1s) for communication

### Examples
- Ethernet cables
- Physical hardware connections

### Key Takeaways
- Lowest layer of the OSI model
- Uses **binary numbering system**
- Devices are connected via **Ethernet cables**

---

## Layer 2: Data Link Layer

### Responsibilities
- Handles **physical addressing**
- Adds **MAC addresses** to data frames
- Prepares data for transmission over the physical layer

### Key Concepts
- Network Interface Card (NIC)
- MAC address identification
- MAC addresses are hardware-based but can be spoofed

### Key Takeaways
- Focuses on MAC addressing
- Every networked device has a **Network Interface Card (NIC)**

---

## Layer 3: Network Layer

### Responsibilities
- Handles **routing and packet forwarding**
- Determines the most optimal path for data
- Uses logical addressing (IP addresses)

### Key Concepts
- Routing protocols:
  - OSPF (Open Shortest Path First)
  - RIP (Routing Information Protocol)
- Layer 3 devices: **Routers**

### Routing Decisions Based On
- Shortest path
- Reliability
- Connection speed

### Key Takeaways
- Uses **IP addresses**
- Packets take the most optimal route
- Routers operate at this layer

---

## Layer 4: Transport Layer

### Responsibilities
- Ensures data delivery between devices
- Chooses transmission protocol based on reliability needs

### Protocols

#### TCP (Transmission Control Protocol)
**Advantages**
- Guaranteed data accuracy
- Error checking and retransmission
- Synchronization between devices

**Disadvantages**
- Slower than UDP
- Requires stable connection
- Higher overhead

**Common Uses**
- Email
- Web browsing
- File downloads

#### UDP (User Datagram Protocol)
**Advantages**
- Faster than TCP
- No connection overhead
- Flexible for developers

**Disadvantages**
- No guarantee of delivery
- Packet loss affects user experience

**Common Uses**
- Video streaming
- ARP and DHCP
- Real-time applications

### Key Takeaways
- TCP guarantees accuracy
- UDP prioritizes speed
- Protocol choice depends on application needs

---

## Layer 5: Session Layer

### Responsibilities
- Establishes, manages, and terminates sessions
- Maintains active connections
- Uses checkpoints to resume data transfer if interrupted

### Key Takeaways
- A successful connection creates a **session**
- Sessions are unique per connection

---

## Layer 6: Presentation Layer

### Responsibilities
- Translates data between formats
- Ensures consistent data representation
- Handles encryption and decryption

### Examples
- HTTPS encryption
- Data formatting for compatibility

### Key Takeaways
- Acts as a **translator**
- Handles standardization and security

---

## Layer 7: Application Layer

### Responsibilities
- Interfaces directly with the user
- Defines how applications access network services

### Examples
- Web browsers
- Email clients
- File transfer applications
- DNS (Domain Name System)

### Key Takeaways
- Closest layer to the user
- Uses **Graphical User Interfaces (GUI)**

---

## Practical: OSI Dungeon

### Practical Work
- Interactive OSI dungeon challenge
- Correctly ordered OSI layers to escape
- Retrieved the flag by completing the challenge


---

## Skills Gained
- Deep understanding of the OSI Model
- Ability to map real-world protocols to OSI layers
- Knowledge of TCP vs UDP use cases
- Hands-on experience with OSI layer sequencing
