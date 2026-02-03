
# Networking Fundamentals – TCP/IP, UDP, Ports & Data Transmission

This document summarizes the key concepts, tasks, and practical exercises completed as part of the **Pre Security – Networking Fundamentals** module on TryHackMe. The content reflects the topics studied and hands-on activities performed during the room.

---

## Task 1: Packets and Frames

### What Was Learned

* **Packets** and **frames** are fundamental units of data transmission in networks.
* A **packet** operates at **Layer 3 (Network Layer)** of the OSI model and contains IP-related information such as source and destination IP addresses.
* A **frame** operates at **Layer 2 (Data Link Layer)** and encapsulates the packet, adding information such as **MAC addresses**.
* The process of wrapping packets inside frames is known as **encapsulation**, while removing this information is called **decapsulation**.
* Packets enable efficient data transmission by breaking large data into smaller pieces, reducing network congestion.

### Key Concepts

* IP addressing is associated with **packets**.
* Data without IP addressing information is referred to as a **frame**.
* Standardization in networking is essential to ensure reliable communication between billions of devices.

---

## Task 2: TCP/IP

### What Was Learned

* **TCP/IP** is a core networking model consisting of four layers:

  * Application
  * Transport
  * Internet
  * Network Interface
* TCP/IP functions similarly to the OSI model but in a simplified form.
* **TCP (Transmission Control Protocol)** is a **connection-oriented** protocol that ensures reliable data delivery.
* TCP guarantees data integrity and correct order through acknowledgements and sequence numbers.

### TCP Characteristics

**Advantages:**

* Ensures data integrity
* Synchronizes data transmission
* Reliable communication

**Disadvantages:**

* Slower than UDP
* Requires a stable connection
* Reserves system resources during communication

### Important TCP Headers

* Source Port
* Destination Port
* Source IP
* Destination IP
* Sequence Number
* Acknowledgement Number
* Checksum
* Flags

### Three-Way Handshake

The TCP connection setup process consists of:

1. **SYN** – Client initiates the connection
2. **SYN/ACK** – Server acknowledges and synchronizes
3. **ACK** – Client confirms and data transfer begins

### Connection Termination

* TCP connections are closed using **FIN** packets.
* Both sides must acknowledge the closure to properly release resources.

---

## Task 3: Practical – TCP Handshake

### Practical Exercise

* A static lab was used to correctly reassemble the TCP three-way handshake.
* The handshake flow between two devices (Alice and Bob) was analyzed and reconstructed.

### Result

* Successfully completed the handshake simulation.
* Retrieved the final flag:

```
THM{TCP_CHATTER}
```

---

## Task 4: UDP/IP

### What Was Learned

* **UDP (User Datagram Protocol)** is a **stateless** protocol.
* Unlike TCP, UDP does not establish a connection before sending data.
* No acknowledgements or guarantees of delivery are provided.

### Use Cases

* Suitable for applications that can tolerate data loss:

  * Video streaming
  * Voice calls
  * Online gaming

### UDP Characteristics

**Advantages:**

* Faster than TCP
* No connection overhead
* Flexible for developers

**Disadvantages:**

* No data integrity checks
* No delivery confirmation
* Poor performance on unstable connections

### Common UDP Headers

* Time To Live (TTL)
* Source Address
* Destination Address
* Source Port
* Destination Port
* Data

---

## Task 5: Ports and Services

### What Was Learned

* **Ports** are numerical identifiers (0–65535) used to direct network traffic to specific services.
* Ports allow multiple services to operate on a single device.
* Ports between **0–1024** are known as **well-known ports**.

### Common Ports and Protocols

| Protocol | Port | Description              |
| -------- | ---- | ------------------------ |
| FTP      | 21   | File transfer service    |
| SSH      | 22   | Secure remote login      |
| HTTP     | 80   | Web traffic              |
| HTTPS    | 443  | Secure web traffic       |
| SMB      | 445  | File and printer sharing |
| RDP      | 3389 | Remote desktop access    |

* Services can run on non-standard ports (e.g., HTTP on port 8080).
* When using non-standard ports, the port number must be specified explicitly.

### Practical Challenge

* Connected to a remote IP address on a specific port to verify understanding of port-based communication.

**Flag obtained:**

```
THM{YOU_CONNECTED_TO_A_PORT}
```

---

## Key Takeaways

* Gained a solid understanding of how data is transmitted across networks.
* Learned the differences between TCP and UDP and their real-world use cases.
* Practiced analyzing packet structure, handshakes, and port-based communication.
* Built foundational networking knowledge essential for cybersecurity and penetration testing.
