-  Network is two or more entities sharing resource and information.
- network become a powerful tool when share resource with same network or distinct network.
- computer on network can act client(send request for resource) or a server(control and provide access to resources but have higher RAM, CPU, STORAGE).
### Need of Network
- enhance communication ,share resources, centralized management, Internet.
#### Classification of Networks
- Classification by Geography. Based on geographical boundaries span by network itself. (LAN, WAN, MAN) 
- Classification by Component roles. Based on networked computer play in the network operation. (peer-to-peer, server-based, client-based).
#### IP(Internet Protocol) address
- Network Layer Protocol (identify machine on a network, allow transfer of file).
- a device connect to network uses internet protocol.
- IP4(32-bit)192.1.2..3 --dot decimal format---generate by DHCP or Manually, (0-255)
- IP6(128-bit)  .
- when machine connect to network generate ip and given.
- every ip address has Network(identify network), HOST(identify the user) parts.
- **public ip** (used in WAN network) ,**private ip** (used in LAN network).
- NAT(Network Address Translation).

#### Five class of private ip4
- class A(host 24bit) --(0-127 bit)
- B(host 16bit) ---- (128-191bit)
- C(host 8bit) ------(192-223bit)
- D E
#### Reserved IPV4 Address--- 
- cannot be assigned to device on a network.
1. address for beginning 127 reserved for loop back and internal testing.
2. 0's for all hosting bit reserved for network address.
3. 1 or 255 for all hosting bit position is reserved for broadcast address
#### IPv6
- it is alpha-number. identify an end point device.
- automatically generated.
#### MAC Address
- it given to manufacturer of that network adapter.it is wifi adapter or internet port it help us to connection.48 bit(6 octet in hex) (00-15-C5-49-04-A9)
- has two part --- Organizational Unique Id.
-                       - Universally Administered Address.
#### OSI Reference model
- An idea that way network work. it show how data transfer between 2 hosts/servers.
- there are 7 layer.(1-3  communication technology,  5-7  to user application).
- All people seem to need data processing.
- please do not through sausage pizza away  .
###### Layer-7 (Application Layer)
- represent service and provide data to the presentation layer.
- use protocols : HTTP, FTP, MTP.
###### Layer-6 (presentation Layer)
- representation of transmitted data.
- translate different data representation from Application layer into uniform standard format.
- provide service for the secure efficient data transmission.(data encryption and data compression).
- your data is data.
- use protocols : SSL
##### Layer-5 (Session Layer)
- allow two application on different computer to establish session, use session and end session.(eg file transfer, Remote login)
- establish which side transmit, when and how long it transmits.
- perform token management and sync.
- your data is data.
- use protocol : RPC, NETBIOS.
##### Layer-4 (Transport Layer)
- manage transmission packet.
- sender : Repackage long message when necessary into small packet for transmission.
- Receiver  : Reassemble packet in correct order to get  the original message.
- Handle error  recognition and recover.
-                        :-transport layer at receiving acknowledges packet delivery.
-                        :-resend missing packet.
-  YOUR DATA : SEGMENTS
- use PROTOCOLS  : TCP, UDP.
##### Layer-3 (Network Layer)
- manage address of data with in ip address.
- addresses message and translates logical address and name to physical address.
- determine the route from the source to the destination computer.
- manage traffic problem such as switching , routing, controlling the congestion of data packets.
- your data is PACKET.
- use PROTOCOLS : ICMP, ARP, NAT, IP.
##### Layer-2 (Data Link Layer)
- receiver : Package raw from physical layer into frames.(structured packet for data.)
- reliable transmission of frame.
-                             :-  it waits for an acknowledgment from receiving computer.
-                             :- retransmission frame not received acknowledgement. 
- your data is FRAMES.
- PROTOCOLS : PPP, NDP, CDP.
##### Layer-1 (Physical Layer)
- Transmit bits from one computer to another.
- Regulate the transmission of a stream of bits over a physical medium.
- Define how the cable is attached to the network adapter and
- What transmission technique is used to send data over cable.
-                    :- definition of 0's and 1's. how many volt represents a 1 and how long a bit lasts.
-                     :- how many pin a connector has, and what function of each pin is ?
- Your DATA is Bits
- PROTOCOLS : RS-449.
###### TCP 
- CONNECTION - Oriented protocol.
- establishes connection between receiver and sender. it uses three way Hand Shake .(eg email, online video , simple browsing).
##### UDP
- connectionless.
- less reliable, but faster and more straightforward.
- used in higher speed like Streaming or Gaming.
#### TCP/IP
- a reference model like the OSI model.
- new model ,most used model have four layer
#### Firewall
- network security device that monitor incoming and outgoing network decide whether to allow or block specific traffics.
- it is a collection of rule to allow and deny network traffics.
- you cannot access some host from other network .
- every OS have firewall Built-in.
**Switch, Router, Hub, Gateway, Repeater, NIC, Modem, Bridge.**
- Repeater  : - help to boost / amplify the speed of internet, in long route.
- Bridge : - used to connect different LAN.

