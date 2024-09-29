
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
**Answer:** IPv4 uses 32-bit addresses allowing for 4.3 billion unique addresses, whereas IPv6 uses 128-bit addresses allowing for a vastly larger number of addresses. IPv6 also includes features like improved security and better address auto-configuration.


## What is a subnet mask?
**Answer:** A subnet mask is a 32-bit number that divides an IP address into two parts,One part identifies the host (computer), the other part identifies the network to which it belongs. 

What is a MAC address?

## What is a MAC address?
**Answer:** A MAC (Media Access Control) address is a 48-bit  address is a unique identifier assigned to a network interface card (NIC) MAC address is the physical address, which uniquely identifies each device on a given network. To make communication between two networked devices.

## What is DHCP?
**Answer:**  DHCP (Dynamic Host Configuration Protocol) is a network management protocol used to dynamically assign IP addresses and other network configuration parameters to devices on a network.

## What is DNS?
**Answer:** DNS (Domain Name System) is a hierarchical system that translates human-readable domain names (like www.example.com) into IP addresses.

## What is ARP?
**Answer:** ARP (Address Resolution Protocol) is a protocol used to map an IP address to a physical MAC address on a local area network.

## What is a router?
**Answer:**  A router is a network device that forwards data packets between computer networks, performing traffic directing functions.

## What is a switch?
**Answer:** A switch is a networking device that connects devices within a single network, using MAC addresses to forward data to the correct destination.

## What is a hub?
**Answer:** A hub is a network hardware device that connects multiple devices together and acts as a central connection point within a local area network (LAN). 

## What is the difference between a hub and a switch?
**Answer:** A hub broadcasts data to all devices in a network segment, while a switch intelligently sends data only to the device to which it is addressed, making switches more efficient.


## What is a firewall?
**Answer:** A firewall is a network security device that monitors and controls incoming and outgoing network traffic based on predetermined security rules.

## What is NAT?
**Answer:** NAT (Network Address Translation) is a method used to remap one IP address space into another by modifying network address information in the IP header while the packets are in transit.

## What is VPN?
**Answer:** VPN stands for Virtual Private Network. It allows you to connect your computer to a private network, creating an encrypted connection that masks your IP address to securely share data and surf the web, protecting your identity online.

## What is a VLAN?
**Answer:** A virtual local area network (VLAN) is a virtualized connection that allows multiple devices and network nodes from different LANs to be connected into a single logical network.

## What is the difference between TCP and UDP?
**Answer:** TCP (Transmission Control Protocol) is connection-oriented and ensures reliable data transmission, while UDP (User Datagram Protocol) is connectionless and faster but does not guarantee delivery.

## What is SSL/TLS?
**Answer:** SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are cryptographic protocols designed to provide secure communication over a computer network.

## What is an SSID?
**Answer:** An SSID (Service Set Identifier) is a unique identifier that names a wireless local area network (WLAN).

## What is the purpose of a gateway?
**Answer:** A gateway is a network device that acts as an entry and exit point of network, connecting different networks and enabling communication between them.

## What is a proxy server?
**Answer:** A proxy server is an intermediary server separating end users from the websites they browse, providing varying levels of functionality, security, and privacy.

## What is ICMP?
**Answer:** ICMP (Internet Control Message Protocol) is used by network devices, like routers, to send error messages and operational information, such as whether a service is available or a host can be reached.

## What is an ISP?
**Answer:** An ISP (Internet Service Provider) is a company that provides individuals and organizations access to the internet and other related services.

## What is the difference between a modem and a router?
**Answer:** A modem modulates and demodulates signals for internet access, while a router directs data packets between devices in a network.

## What is a NIC (Network Interface Card)?
**Answer:** A NIC is a hardware component that connects a computer to a network, enabling communication with other networked devices.

## What is network latency?
**Answer:** Network latency is the time it takes for data to travel from the source to the destination across network.

## What is a network packet?
**Answer:** A network packet is a formatted unit of data carried by a packet-switched network, containing both control information and user data.

## What is a port number?
**Answer:** A port number is a numerical identifier in networking used to distinguish different services or processes on a single device, such as HTTP (port 80) or FTP (port 21).

## What is the purpose of a subnet?
**Answer:** A subnet, or subnetwork, is a logical division of an IP network into multiple smaller network segments. The process of dividing a network into subnets is called subnetting. 

## What is subnetting?
**Answer:** Subnetting is the process of dividing a larger network into smaller, more manageable subnetworks, using a subnet mask to designate portions of the IP address space for network and host addresses.

## what is load Balancer?
**Answer:** A load balancer distributes network or application traffic across multiple servers to ensure no single server becomes overwhelmed, enhancing the availability and reliability of applications.


## What is the three-way handshake in TCP?
**Answer:** The three-way handshake is a method used in TCP/IP networks to establish a connection between a client and server, involving SYN, SYN-ACK, and ACK packets.

## What is a network protocol analyzer?
**Answer:** A network protocol analyzer is a tool used to capture, analyze, and decode network traffic for troubleshooting and monitoring purposes. Wireshark is a popular example.

## What is network security?
**Answer:** Network security involves policies and practices designed to protect the integrity, confidentiality, and availability of networked systems and data from unauthorized access, misuse, or attacks.

## What is a default gateway?
**Answer:** A default gateway is a node that routes traffic from a local network to devices on other networks, typically through a router.

## What is DNS caching?
**Answer:** DNS caching stores DNS query results locally to speed up the resolution of domain names and reduce the load on DNS servers.

## What is an IDS/IPS?
**Answer:** IDS (Intrusion Detection System) monitors network traffic for suspicious activity, while IPS (Intrusion Prevention System) actively prevents and blocks intrusions.


## What is a network socket?
**Answer:** A network socket is an endpoint for sending or receiving data across a computer network, defined by an IP address and port number.

## What is port forwarding?
**Answer:** Port forwarding is a network configuration that directs incoming traffic from a specific port on an external IP address to a specific port and IP address within a local network, commonly used for remote access to services.

## Transport Layer Protocols:
- **TCP:** stands for Transmission Control Protocol.
- **1**It provides full transport layer services to applications.
- **2**It is a connection-oriented protocol means the connection established between both the ends of the transmission. For creating theconnection, TCP generates a virtual circuit between sender and receiver for the duration of a transmission.

- **1**UDP stands for User Datagram Protocol.
- **2**UDP is a simple protocol and it provides nonsequenced transport functionality.
- **3**UDP is a connectionless protocol.
- **4**This type of protocol is used when reliability and security are less important than speed and size.


## Application Layer Protocols:

## Http:
- **1**HTTP stands for HyperText Transfer Protocol.
- **2**It is a protocol used to access the data on the World Wide Web (www).
- **3**The HTTP protocol can be used to transfer the data in the form of plain text, hypertext, audio, video, and so on.
- **4**HTTP is similar to the FTP as it also transfers the files from one host to another host.

## Ftp:
- **1**FTP stands for File transfer protocol.
- **2**FTP is a standard internet protocol provided by TCP/IP used for transmitting the files from one host to another.
- **3** is also used for downloading the files to computer from other servers.

## Smtp:
- **1**SMTP stands for Simple Mail Transfer Protocol.
- **2**SMTP is a set of communication guidelines that allow software to transmit an electronic mail over the internet is called Simple Mail 

## Transfer Protocol.
- **1**It is a program used for sending messages to other computer users based on e-mail addresses.
- **2**It can send a single message to one or more recipients.
- **3**Sending message can include text, voice, video or graphics.

## Ssh:
- **1**SSH stands for Secure Shell or Secure Socket Shell. It is a cryptographic network protocol that allows two computers to communicate and share the data over an insecure network such as the internet. It is used to login to a remote server to execute commands and data transfer from one machine to another machine.
