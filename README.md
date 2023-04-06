# Introduction to Networking
This repo has been created to organize information related to networking foundations

### Open Systems Interconnection (OSI) Model

| Number | Layer        | Description                                    | Protocol Data Unit | Example                                                               |
| ------ | ------------ | ---------------------------------------------- | -----------------  | --------------------------------------------------------------------- |
| 7      | Application  | End User Layer                                 | Datagrams          | DNS, DHCP, FTP, HTTP, HTTPS, LDAP, NTP, POP3, SSH, SMTP, Telnet, TFTP |
| 6      | Presentation | Syntax, Data Representation and Encryption     | Datagrams          | SSL, TLS, JPEG, MIDI, MPEG, TIFF                                      | 
| 5      | Session      | Interhost Communication, Syn and Send to Ports | Datagrams          | NetBIOS, SQL, NFS, APIs                                               | 
| 4      | Transport    | End-to-End Connections                         | Segments           | TCP, UDP                                                              |
| 3      | Network      | Logical Addressing, Path Determination and IP  | Packets            | Routers, Layer 3 Switches, IPv4, IPv6, IPsec, ICMP, IGMP              |
| 2      | Data Link    | Physical Addressing, MAC and LLC               | Frames             | Switches, Bridges, Ethernet, VLAN, ARP (between 2 and 3)              |
| 1      | Physical     | Media, Signal, and Binary Transmission         | Bits               | Hubs, Repeaters, Cables (Copper, Fiber, Coax), Wireless               |

