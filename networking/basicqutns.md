1. what is NAT,how does it work?
* Network Address Translation (NAT) is a service that enables private IP networks to use the internet and cloud. NAT translates private IP addresses in an internal network to a public IP address before packets are sent to an external network.
* [referhere](https://www.comptia.org/content/guides/what-is-network-address-translation)
* Why Use NAT?
NAT is a straightforward process. Most routing equipment you purchase at a store will implement it automatically, or with a simple click of a mouse. Let’s get a bit deeper into NAT’s role in IP conservation and explain its limited role in providing security services.

2. what is CIDR ?(Classless inter domain routing)
* Classless Inter-Domain Routing (CIDR) is an IP address allocation method that improves data routing efficiency on the internet. Every machine, server, and end-user device that connects to the internet has a unique number, called an IP address, associated with it. Devices find and communicate with one another by using these IP addresses. Organizations use CIDR to allocate IP addresses flexibly and efficiently in their networks. 

3. Network Principle
* A Device can communicate directly with other device in same network
* Router: router is a device which can transfer packets from one network to other.

4. Concepts
* IP Address: This is a unique number given to a device in a network. It has two schemes
     * IPv4
     * IPv6
* IPv4 is a 32 bit number organized into 4 octets (for each 1octet=8 bits) addressed as x.x.x.x
* IPv6 addresses have a size of 128 bits(16 octects).
* Execute ``ipconfig`` in command prompt(powershell)
* IP Address id combination of network id and host id

5. What Is a Network Interface?
A network interface is the point of interconnection between a computer and a private or public network. A network interface is generally a network interface card (NIC), but does not have to have a physical form. Instead, the network interface can be implemented in software. For example, the loopback interface (127.0.0.1 for IPv4 and ::1 for IPv6) is not a physical device but a piece of software simulating a network interface. The loopback interface is commonly used in test environments.
6. A computer network is a group of computers and various networking devices that connect to share information and resources. To uniquely identify each computer or networking device in the network, computer networks also use addresses. Addresses in computer networks are known as IP addresses. An IP address consists of two components: the network address and the host address. 
* The network address is used to find the subnet in which the computer or the device is located and 
* the host address is used to find the computer or the device in the subnet. If a large computer network is divided into smaller groups, each group is known as a subnet.
7. What is a Network Address?
* A Network Address is a logical or physical address that uniquely identifies a host or a machine in a telecommunication network. A network may also not be unique and can contain some structural and hierarchical information of the node in the network. Internet protocol (IP) address, media access control (MAC) address and telephone numbers are some basic examples of network addresses. It can be of numeric type or symbolic or both in some cases.
* [referhere](https://www.geeksforgeeks.org/what-is-a-network-address/)
# [referhere](https://www.guru99.com/networking-interview-questions.html)Interview questions(networking)

8. what is port in networking?
* A port is a number used to uniquely identify a transcation over a network by specifying both host and the service. 
* Port numbers are divided into three categories.
     * Well-known/System ports: Range 0–1,023
     * Registered ports: Range 1,024–49,151
     * Dynamic/Private ports: Range 49,152–65,535
* 1.Well-known/System Ports
Well-known ports also called as system ports, ranges from 0 to 1023 since many of the core services on Unix servers used these ports; also, it requires privilege permissions on the server for implementation.
* 2. Registered Ports
These ports range from 1024 to 49151 are not controlled or assigned. However, they can be registered to prevent redundancy.
* 3. Dynamic Ports
These ports range from 49152 to 65535, also known as private or non-reserved ports. These ports are not registered, assigned, or controlled. Dynamic ports are used for private or temporary ports.

Here is a list of some Registered and Dynamic ports. 
[referhere](https://www.educba.com/networking-ports/)for documentation of port numbers
* [referhere](https://www.geeksforgeeks.org/difference-between-ip-address-and-port-number/)for difference between port and IP address 

9. What is OSI, and what role does it play in computer networks?,What are the layers of the OSI reference model?
* OSI (Open Systems Interconnect) serves as a reference model for data communication. It is made up of 7 layers, with each layer defining a particular aspect of how network devices connect and communicate with one another. One layer may deal with the physical media used, while another layer dictates how data is transmitted across the network.
There are 7 OSI layers: 
1) Physical Layer-The physical layer does the conversion from data bits to the electrical signal, and vice versa. This is where network devices and cable types are considered and setup.
2) Data Link Layer-To organize the bits into frames 
3) Network Layer-to move packets from source to destination,The Network layer is responsible for data routing, packet switching, and control of network congestion. Routers operate under this layer.
4) Transport Layer-To provide reliable data process to process,.essege delivery and error delivery 
5) Session Layer-This layer provides the protocols and means for two devices on the network to communicate with each other by holding a session. This includes setting up the session, managing information exchange during the session, and tear-down process upon termination of the session.
6) Presentation Layer- to trnslate encrpt & compress the data 
7) Application Layer- To allow acees to network resources

 
10.  What is data encapsulation?
Data encapsulation is the process of breaking down information into smaller, manageable chunks before it is transmitted across the network. In this process that the source and destination addresses are attached to the headers, along with parity checks.

11.  What are gateways?
Gateways provide connectivity between two or more network segments. It is usually a computer that runs the gateway software and provides translation services. This translation is key in allowing different systems to communicate on the network.

12. What is the importance of implementing a Fault Tolerance System?
A fault tolerance system ensures continuous data availability. This is done by eliminating a single point of failure.


13.  How can you identify the IP class of a given IP address?
By looking at the first octet of any given IP address, you can identify whether it’s Class A, B, or C. If the first octet begins with a 0 bit, that address is Class A. If it begins with bits 10 then that address is a Class B address. If it begins with 110, then it’s a Class C network.

14.  What are firewalls?
Firewalls serve to protect an internal network from external attacks. These external threats can be hackers who want to steal data or computer viruses that can wipe out data in an instant. It also prevents other users from external networks from gaining access to the private network.
