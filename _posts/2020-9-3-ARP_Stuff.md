---
layout: post
title: Some Stuff About ARP 
---
ARP Stands address resolution protocol.It is a simple protocol which helps us identify MAC addresses.
Hosts or routers are recogonised on the network level by IP addresses.Similarly, at the physical level they are recogonised by their mac address.
* note: ARP is a network layer protocol 

# Network Address mapping
These physical and network addresses need to be mapped.We need to know which ip address has which mac address.

## 1.Static Address Mapping:
Here we make a table about which IP address belongs to which MAC.But this has a few drwabacks which include:

=> MAC address can change whith change in the NIC

=> In some LAN Networks ,MAC address changes every time the computer is turned on.

=>Acomputer can moce from one physical network to another which can change Mac .(note: MAC is unique in a network not universally)

## 2.Dynamic Address Mapping
If we know one of the two addresses ,then we can use some protocol to find the other
We used to use ARP and RARP.RARP is deprecated and DHCP is more used these days.

# ARP packet format
![image_tpm](https://raw.githubusercontent.com/techathena/techathena.github.io/master/images/arp.jpg)

The fields are:
#### Hardware Type(16 bit)
#### Protocol Type(16 bit)
#### Hardware Length(8 bit)
#### Protocol Length(8 bit)
#### Operations(16 bit)
#### Sender hardware address(variable)
#### Sender protocol address(variable)
#### Target hardware address(variable)
#### Target Protocol address(variable)

# There are four cases of ARP 
 * Host has packet to send to same network
* Host has packet to send to another network
* router has packet to send to another network
* Router get packet to send to a host in same network


Sources: Data Communications and Networking by Behrouz A. Forouzan
