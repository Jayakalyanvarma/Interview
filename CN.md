
# Computer Network Interview Questions and Answers

## What is a computer network?
**Answer:** A computer network is a group of interconnected computers that communicate with each other and share resources, such as files, printers, and internet connections.

## What are the types of computer networks?
**Answer:** The main types are Local Area Network (LAN), Wide Area Network (WAN), Metropolitan Area Network (MAN), and Personal Area Network (PAN).

- **LAN (Local Area Network):** Local Area Network is a group of computers connected to each other in a small area such as building, office.
- **PAN (Personal Area Network):** Personal Area Network is a network arranged within an individual person, typically within a range of 10 meters.
- **MAN (Metropolitan Area Network):** A metropolitan area network is a network that covers a larger geographic area by interconnecting different LANs to form a larger network.
- **WAN (Wide Area Network):** A Wide Area Network extends over a large geographical area such as states or countries. It is a larger network compared to LAN.

## What is network topology?
**Answer:** Network topology is the physical or logical arrangement of devices and connections in a network. It defines how devices are connected and how data flows.

- **Bus Topology:** All devices are connected to a single central cable (bus or backbone).
  - *Advantages:* Easy to install and extend. Requires less cable.
  - *Disadvantages:* Difficult to troubleshoot. A failure in the main cable stops all transmissions.

- **Star Topology:** All devices are connected to a central hub or switch.
  - *Advantages:* Easy to install, manage, and detect faults.
  - *Disadvantages:* If the hub fails, the entire network is inoperative.

- **Ring Topology:** Each device is connected to two others, forming a circular pathway for signals.
  - *Advantages:* Data is transferred sequentially, easy to manage.
  - *Disadvantages:* A failure can disrupt the entire network.

- **Mesh Topology:** Each device is connected to every other device.
  - *Advantages:* High redundancy and reliability.
  - *Disadvantages:* Expensive, complex installation.

- **Tree Topology:** Combines star and bus topologies.
  - *Advantages:* Supports future expandability, easy fault isolation.
  - *Disadvantages:* Difficult to configure, backbone failure affects the entire segment.

- **Hybrid Topology:** Combination of different topologies.
  - *Advantages:* Flexible, scalable, reliable.

## What is a protocol?
**Answer:** A protocol is a set of rules for communication between network devices, defining how data is transmitted and received.

## What is the OSI model?
**Answer:** OSI (Open System Interconnection) is a reference model describing how data moves from one computer to another, consisting of seven layers:
1. **Physical Layer:** Transmits bits from one node to another.
2. **Data Link Layer:** Ensures error-free transfer of data frames.
3. **Network Layer:** Routes data packets between networks.

## What is the TCP/IP model?
**Answer:** TCP/IP is a set of communication protocols used on the internet, with four layers: Data Link, Internet, Transport, and Application.

## What is an IP address?
**Answer:** An IP address is a unique identifier assigned to each device on a network for communication.

## What are the differences between IPv4 and IPv6?
**Answer:** IPv4 uses 32-bit addresses, whereas IPv6 uses 128-bit addresses for more unique addresses, improved security, and better auto-configuration.

## What is a subnet mask?
**Answer:** A subnet mask divides an IP address into a network and host portion.

## What is a MAC address?
**Answer:** A MAC address is a unique identifier assigned to a network interface card (NIC).

## What is DHCP?
**Answer:** DHCP (Dynamic Host Configuration Protocol) dynamically assigns IP addresses to devices on a network.

## What is DNS?
**Answer:** DNS (Domain Name System) translates domain names into IP addresses.

## What is ARP?
**Answer:** ARP (Address Resolution Protocol) maps an IP address to a physical MAC address.

## What is a router?
**Answer:** A router forwards data packets between networks.

## What is a switch?
**Answer:** A switch connects devices within a network and forwards data using MAC addresses.

## What is a hub?
**Answer:** A hub connects multiple devices and acts as a central connection point in a LAN.

## What is the difference between a hub and a switch?
**Answer:** A hub broadcasts data to all devices, while a switch sends data only to the intended device.

## What is a firewall?
**Answer:** A firewall monitors and controls network traffic based on security rules.

## What is NAT?
**Answer:** NAT (Network Address Translation) remaps one IP address space into another by modifying address information in packets.

## What is VPN?
**Answer:** VPN (Virtual Private Network) creates an encrypted connection to securely share data over the internet.

## What is a VLAN?
**Answer:** VLAN (Virtual Local Area Network) is a virtualized network segment within a LAN.

## What is the difference between TCP and UDP?
**Answer:** TCP is connection-oriented and reliable, while UDP is connectionless and faster but does not guarantee delivery.

## What is SSL/TLS?
**Answer:** SSL and TLS are cryptographic protocols for secure communication over a network.

## What is an SSID?
**Answer:** SSID (Service Set Identifier) names a wireless network.

## What is the purpose of a gateway?
**Answer:** A gateway connects different networks and enables communication between them.

## What is a proxy server?
**Answer:** A proxy server acts as an intermediary between users and websites for security and privacy.

## What is ICMP?
**Answer:** ICMP (Internet Control Message Protocol) sends error messages and operational information like service availability.

## What is the difference between a modem and a router?
**Answer:** A modem connects to the internet, while a router directs data between networked devices.

## What is a NIC (Network Interface Card)?
**Answer:** A NIC connects a computer to a network, enabling communication.

## What is network latency?
**Answer:** Network latency is the time it takes for data to travel from the source to the destination.

## What is a network packet?
**Answer:** A network packet is a formatted unit of data transmitted over a packet-switched network.

## What is a port number?
**Answer:** A port number is a numerical identifier for network services.

## What is subnetting?
**Answer:** Subnetting divides a larger network into smaller sub-networks using a subnet mask.

## What is a load balancer?
**Answer:** A load balancer distributes traffic across multiple servers to prevent any single server from being overwhelmed.

## What is a mesh network?
**Answer:** A mesh network connects all nodes directly, dynamically, and non-hierarchically.

## What is the three-way handshake in TCP?
**Answer:** The three-way handshake establishes a TCP connection using SYN, SYN-ACK, and ACK packets.

## What is a network protocol analyzer?
**Answer:** A tool used to capture, analyze, and decode network traffic (e.g., Wireshark).

## What is network security?
**Answer:** Network security involves practices and policies to protect network integrity, confidentiality, and availability.

## What is a default gateway?
**Answer:** A default gateway routes traffic from a local network to other networks.

## What is DNS caching?
**Answer:** DNS caching stores DNS query results locally to speed up domain name resolution.

## What is an IDS/IPS?
**Answer:** IDS (Intrusion Detection System) monitors traffic for suspicious activity; IPS (Intrusion Prevention System) actively blocks intrusions.

## What is a network socket?
**Answer:** A network socket is an endpoint for communication between devices on a network.

## What is port forwarding?
**Answer:** Port forwarding directs incoming traffic to a specific IP and port within a local network.

## Transport Layer Protocols:
**UDP (User Datagram Protocol):** Connectionless and faster, used where reliability is less important.
**TCP (Transmission Control Protocol):** Connection-oriented and ensures reliable data transmission.

## Application Layer Protocols:
- **HTTP (HyperText Transfer Protocol):** Used to transfer data on the web.
- **FTP (File Transfer Protocol):** Used to transfer files between hosts.
- **SMTP (Simple Mail Transfer Protocol):** Sends electronic mail over the internet.
- **SSH (Secure Shell):** Provides secure data transfer and remote login over an insecure network.

