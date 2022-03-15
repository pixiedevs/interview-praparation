# Computer Network: -

## TCP/IP
	It is a compressed version of the OSI model with only 4 layers. It was developed by the US Department of Defence (DoD) in the 1980s. The name of this model is based on 2 standard protocols used i.e. TCP (Transmission Control Protocol) and IP (Internet Protocol).

## HTTP
	HTTP is the HyperText Transfer Protocol which defines the set of rules and standards on how the information can be transmitted on the World Wide Web (WWW).  It helps the web browsers and web servers for communication. It is a ‘stateless protocol’ where each command is independent with respect to the previous command. HTTP is an application layer protocol built upon the TCP. It uses port 80 by default.

## HTTPS
	HTTPS is the HyperText Transfer Protocol Secure or Secure HTTP. It is an advanced and secured version of HTTP. On top of HTTP, SSL/TLS protocol is used to provide security. It enables secure transactions by encrypting the communication and also helps identify network servers securely. It uses port 443 by default.

## OSI
	OSI stands for Open Systems Interconnection. It has been developed by ISO – ‘International Organization for Standardization‘, in the year 1984. It is a 7 layer architecture with each layer having specific functionality to perform. All these 7 layers work collaboratively to transmit the data from one person to another across the globe. 


## UDP
	User Datagram Protocol (UDP) is a Transport Layer protocol. UDP is a part of the Internet Protocol suite, referred to as UDP/IP suite. It is an unreliable and connectionless protocol. So, there is no need to establish a connection prior to data transfer.

### POP protocol
	The POP protocol stands for Post Office Protocol. As we know that SMTP is used as a message transfer agent. When the message is sent, then SMPT is used to deliver the message from the client to the server and then to the recipient server. But the message is sent from the recipient server to the actual server with the help of the Message Access Agent. The Message Access Agent contains two types of protocols, i.e., POP3 and IMAP.

## Routing
	Routing is the process of establishing the routes that data packets must follow to reach the destination. In this process, a routing table is created which contains information regarding routes that data packets follow. Various routing algorithms are used for the purpose of deciding which route an incoming data packet needs to be transmitted on to reach the destination efficiently. 

### Adaptive Algorithms – 
	These are the algorithms that change their routing decisions whenever network topology or traffic load changes.

	example-

### Non-Adaptive Algorithms – 
	These are the algorithms that do not change their routing decisions once they have been selected. This is also known as static routing as a route to be taken is computed in advance and downloaded to routers when a router is booted.

example-
- Flooding
- Random walk

## Routing vs Flooding

| Routing 					| Flooding	|
| ------------- |:------------- |
| Routing table is required	| No routing table is required	|
| May give shortest path	| Always gives shortest path	|
| less reliable				| More reliable	|
| trafic is less			| Traffic is high	|
| No duplicate packets		| Duplicate packets are present	|



## Protocol:
	To make communication successful between devices, some rules and procedures should be agreed upon at the sending and receiving ends of the system. Such rules and procedures are called as Protocols.


## Types of network: -
#### PAN (Personal Area Network): -
	Let devices connect and communicate over the range of a person. E.g. connecting Bluetooth devices.

#### LAN (Local Area Network): -
	It is a privately owned network that operates within and nearby a single building like a home, office, or factory

#### MAN (Metropolitan Area Network): -
	It connects and covers the whole city. E.g. TV Cable connection over the city

#### WAN (Wide Area Network): -
	It spans a large geographical area, often a country or continent. The Internet is the largest WAN

#### GAN (Global Area Network): -
	It is also known as the Internet which connects the globe using satellites. The Internet is also called the Network of WANs.



## LAN (local area network) - enterprice network
	LANs are widely used to connect computers/laptops and consumer electronics which enables them to share resources (e.g., printers, fax machines) and exchange information.
	types - wireless lan, wired lan

## VPN (Virtual Private Network)
	VPN or the Virtual Private Network is a private WAN (Wide Area Network) built on the internet. It allows the creation of a secured tunnel (protected network) between different networks using the internet (public network). 

- types of vpn - 
	- Access VPN
	- Site-to-Site VPN
	- Intranet VPN
	- Extranet VPN

### Advantages of using a VPN
- VPN is used to connect offices in different geographical locations remotely and is cheaper when compared to WAN connections.
	
- VPN is used for secure transactions and confidential data transfer between multiple offices located in different geographical locations.
	
- VPN keeps an organization’s information secured against any potential threats or intrusions by using virtualization.
	
- VPN encrypts the internet traffic and disguises the online identity.


## Node:
	Any communicating device in a network is called a Node. Node is the point of intersection in a network. It can send/receive data and information within a network. Examples of the node can be computers, laptops, printers, servers, modems, etc.

## Link:
	 A link or edge refers to the connectivity between two nodes in the network. It includes the type of connectivity (wired or wireless) between the nodes and protocols used for one node to be able to communicate with the other.

## Network topology:
	is a physical layout of the network, connecting the different nodes using the links. It depicts the connectivity between the computers, devices, cables, etc.

	Types of network topology
	The different types of network topology are given below:

### Bus Topology:
	All the nodes are connected using the central link known as the bus.
	It is useful to connect a smaller number of devices.
	If the main cable gets damaged, it will damage the whole network.

### Star Topology:
	All the nodes are connected to one single node known as the central node.
	It is more robust.
	If the central node fails the complete network is damaged.
	Easy to troubleshoot.
	Mainly used in home and office networks.

### Ring Topology:
	Each node is connected to exactly two nodes forming a ring structure
	If one of the nodes are damaged, it will damage the whole network
	It is used very rarely as it is expensive and hard to install and manage

### Mesh Topology:
	Each node is connected to one or many nodes.
	It is robust as failure in one link only disconnects that node.
	It is rarely used and installation and management are difficult.

### Tree Topology:
	A combination of star and bus topology also know as an extended bus topology.
	All the smaller star networks are connected to a single bus.
	If the main bus fails, the whole network is damaged.

### Hybrid:
	It is a combination of different topologies to form a new topology.
	It helps to ignore the drawback of a particular topology and helps to pick the strengths from other.



## Special Thanks to: -
- [Praveen Yadav](https://www.linkedin.com/in/pixiedev)
- [Siddhartha Mishra](https://www.linkedin.com/in/sid0542)
