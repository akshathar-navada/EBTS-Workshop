
## Virtual LAN

   
   Virtual LAN (VLAN) is a concept in which we can divide the devices logically on layer 2 (data link layer). Generally, layer 3 devices divide broadcast domain but 
broadcast domain can be divided by switches using the concept of VLAN. 
 
   VLAN is a custom network which is created from one or more local area networks. It enables a group of devices available in multiple networks to be combined into 
one logical network. The result becomes a virtual LAN that is administered like a physical LAN. The full form of VLAN is defined as Virtual Local Area Network.


## Wireless Network and types

   A wireless network allows devices to stay connected to the network but roam untethered to any wires. Access points amplify Wi-Fi signals, so a device can be far from
a router but still be connected to the network. 
There are four types of wireless networks :

1. Wireless local area networks

2. Wireless metropolitan area networks

3. Wireless personal area networks 

4. Wireless wide area networks 


## IT Infrastructure

The components of IT infrastructure are made up of interdependent elements, and the two core groups of components are hardware and software.
Hardware components can include Desktop computers, Servers, Data centers, Hubs, Routers, Switches, Facilities. 
Software components can include Content management systems (CMS), Customer relationship management (CRM), Enterprise resource planning (ERP), Operating systems, Web servers.


## Web Application Firewall

A WAF or web application firewall helps protect web applications by filtering and monitoring HTTP traffic between a web application and the Internet. It typically 
protects web applications from attacks such as cross-site forgery, cross-site-scripting (XSS), file inclusion, and SQL injection, among others. A WAF is a protocol 
layer 7 defense (in the OSI model), and is not designed to defend against all types of attacks. This method of attack mitigation is usually part of a suite of tools 
which together create a holistic defense against a range of attack vectors.


## IDS and IPS

Intrusion Detection System: An IDS is designed to detect a potential incident, generate an alert, and do nothing to prevent the incident from occurring. While this may
seem inferior to an IPS, it may be a good solution for systems with high availability requirements, such as industrial control systems (ICS) and other critical 
infrastructure. For these systems, the most important thing is that the systems continue running, and blocking suspicious (and potentially malicious) traffic may 
impact their operations. Notifying a human operator of the issue enables them to evaluate the situation and make an informed decision on how to respond.

Intrusion Prevention System: An IPS, on the other hand, is designed to take action to block anything that it believes to be a threat to the protected system. As
malware attacks become faster and more sophisticated, this is a useful capability because it limits the potential damage than an attack can cause. An IPS is ideal for
environments where any intrusion could cause significant damage, such as databases containing sensitive data.


## Servers

A Server is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients". This architecture 
is called the client–server model. Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or 
performing computation for a client. A single server can serve multiple clients, and a single client can use multiple servers. A client process may run on the same 
device or may connect over a network to a server on a different device.[1] Typical servers are database servers, file servers, mail servers, print servers, web servers,
game servers, and application servers.


## Clustering

Clustering refers to the interconnection of servers in a way that makes them appear to the operating environment as a single system. As such, the cluster draws on the
power of all the servers to handle the demanding processing requirements of a broad range of technical applications. It also takes advantage of parallel processing in
program execution. Shared resources in a cluster may include physical hardware devices such as disk drives and network cards, TCP/IP addresses, entire applications, 
and databases. The cluster service is a collection of software on each node that manages all cluster-specific activity, including traffic flow and load balancing. The
nodes are linked together by standard Ethernet, FDDI, ATM, or Fibre Channel connections.


## Virtual Machine

A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines 
run on a physical “host” machine. It is a virtual environment that functions as a virtual computer system with its own CPU, memory, network interface, and storage,
created on a physical hardware system (located off- or on-premises). Software called a hypervisor separates the machine’s resources from the hardware and provisions 
them appropriately so they can be used by the VM. 


## Level 2 and Level 3 Switches

Layer 2 switching works on the Data Link Layer and uses network-device, Media Access Control (MAC) Addresses to determine where to forward frames. Both switches and
bridges are used in Layer 2 switching to break up a large collision domain into multiple smaller ones.

The main difference between a Layer 2 and Layer 3 switch is the routing function. A Layer 3 switch (also called a multilayer switch) performs all the functions a 
Layer 2 switch does; however, it has both static and dynamic routing functions. In other words, Layer 3 switching combines the functionality of both a switch and a 
router by inspecting incoming packets and making routing decisions that are based on source and destination addresses.


## TCP and UDP ports 

port 21 - File Transfer Protocol (FTP) control (command)

port 22 - Secure Shell (SSH), secure logins, file transfers (scp, sftp) and port forwarding

port 25 - Simple Mail Transfer Protocol (SMTP) used for email routing between mail servers


## Common Threats

1. Computer virus : Computer viruses are pieces of software that are designed to be spread from one computer to another. They’re often sent as email attachments or 
   downloaded from specific websites with the intent to infect your computer — and other computers on your contact list — by using systems on your network. Viruses
   are known to send spam, disable your security settings, corrupt and steal data from your computer including personal information such as passwords, even going as
   far as to delete everything on your hard drive.
   
2. Rogue security software : Rogue security software is malicious software that mislead users to believe that they have network security issues, most commonly a 
   computer virus installed on their computer or that their security measures are not up to date. Then they offer to install or update users’ security settings. 
   They’ll either ask you to download their program to remove the alleged viruses, or to pay for a tool. Both cases lead to actual malware being installed on your
   computer.
   
3. Trojan horse : Trojan is a malicious bit of attacking code or software that tricks users into running it willingly, by hiding behind a legitimate program.
   They spread often by email; it may appear as an email from someone you know, and when you click on the email and its included attachment, you’ve immediately 
   downloaded malware to your computer. Trojans also spread when you click on a false advertisement. Once inside your computer, a Trojan horse can record your 
   passwords by logging keystrokes, hijacking your webcam, and stealing any sensitive data you may have on your computer.
 
4. Adware and spyware : 

      Adware is any software that is designed to track data of your browsing habits and based on that, show you advertisements and pop-ups. Adware collects data with your
   consent — and is even a legitimate source of income for companies that allow users to try their software for free, but with advertisements showing while using the 
   software. The adware clause is often hidden in related User Agreement docs, but it can be checked by carefully reading anything you accept while installing software. 
   The presence of adware on your computer is noticeable only in those pop-ups, and sometimes it can slow down your computer’s processor and internet connection speed.
   When adware is downloaded without consent, it is considered malicious.
   
      Spyware works similarly to adware, but is installed on your computer without your knowledge. It can contain keyloggers that record personal information including 
   email addresses, passwords, even credit card numbers, making it dangerous because of the high risk of identity theft.
  
5. Computer worm : Computer worms are pieces of malware programs that replicate quickly and spread from one computer to another. A worm spreads from an infected 
   computer by sending itself to all of the computer’s contacts, then immediately to the contacts of the other computers.
   
6. DOS and DDOS attack : 

   DoS attack or denial-of-service, a malicious traffic overload that occurs when attackers overflood a website with traffic. When a website has too much traffic, it’s
   unable to serve its content to visitors. It is performed by one machine and its internet connection, by flooding a website with packets and making it impossible for
   legitimate users to access the content of flooded website. Fortunately, you can’t really overload a server with a single other server or a PC anymore. 

   A DDoS attack or distributed denial-of-service attack, is similar to DoS, but is more forceful. It’s harder to overcome a DDoS attack. It’s launched from several
   computers, and the number of computers involved can range from just a couple of them to thousands or even more.
   
   
## NAT Network

Network Address Translation (NAT) is a process in which one or more local IP address is translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts. Also, it does the translation of port numbers i.e. masks the port number of the host with another port number, in the packet that will be routed to the destination. It then makes the corresponding entries of IP address and port number in the NAT table. NAT generally operates on a router or firewall. 

## MAC address

A media access control address (MAC address) is a unique identifier assigned to a network interface controller (NIC) for use as a network address in communications
within a network segment. This use is common in most IEEE 802 networking technologies, including Ethernet, Wi-Fi, and Bluetooth. Within the Open Systems 
Interconnection (OSI) network model, MAC addresses are used in the medium access control protocol sublayer of the data link layer. As typically represented, MAC 
addresses are recognizable as six groups of two hexadecimal digits, separated by hyphens, colons, or without a separator.

## IPV4 and IPV6

IPv4 and IPv6 are internet protocol version 4 and internet protocol version 6, IP version 6 is the new version of Internet Protocol, which is way better than IP 
version 4 in terms of complexity and efficiency. 

Difference Between IPv4 and IPv6: 

|  IPv4	                                                                   |  IPv6                                                                               |
| ------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | 
| IPv4 has a 32-bit address length	                                        | IPv6 has a 128-bit address length                                                   |
| It Supports Manual and DHCP address configuration	                      | It supports Auto and renumbering address configuration                              |
| In IPv4 end to end, connection integrity is Unachievable	                | In IPv6 end to end, connection integrity is Achievable                              |
| It can generate 4.29×109 address space	                                  | Address space of IPv6 is quite large it can produce 3.4×1038 address space          |
| The Security feature is dependent on application	                         | IPSEC is an inbuilt security feature in the IPv6 protocol                           |
| Address representation of IPv4 is in decimal	                            | Address Representation of IPv6 is in hexadecimal                                    |
| Fragmentation performed by Sender and forwarding routers	                | In IPv6 fragmentation performed only by the sender                                  |
| In IPv4 checksum field is available	                                     | In IPv6 checksum field is not available                                             |
| It has broadcast Message Transmission Scheme	                            | In IPv6 multicast and anycast message transmission scheme is available              |
| In IPv4 Encryption and Authentication facility not provided	             | In IPv6 Encryption and Authentication are provided                                  |
| IPv4 has a header of 20-60 bytes.	                                        | IPv6 has header of 40 bytes fixed                                                   |
| IPv4 can be converted to IPv6	                                           | Not all IPv6 can be converted to IPv4                                               |
| IPv4 consist of 4 fields which are separated by dot (.)	                | IPv6 consist of 8 fields, which are separated by colon (:)                          |
| IPv4 supports VLSM(Variable Length subnet mask).	                         | IPv6 does not support VLSM.                                                         |




