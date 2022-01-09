RCOMP 2019-2020 Project - Sprint 2 - Member 1180782 folder
===========================================

## Informations

- End user outlets on the ground floor: **40** nodes.
- End user outlets on floor one: **44** nodes.
- Wi-Fi network: **60** nodes.
- Local servers, administration workstations, and machines (DMZ): **250** nodes.
- VoIP (IP-phones): **40** nodes.

## Distribuction

- My building IPv4 adress space starts at **10.166.120.0/22**.
- To make the assignement of each network of the building, we used the rule bigger blocks first.

- **DMZ (250)**
  - Subnet Address: 10.166.120.0/24.
  - Subnet Mask: 255.255.255.0.
  - First available address: 10.166.120.1.
  - Last available address: 10.166.120.254.
  - Broadcast: 10.166.120.255.
  - VLANID used: 284

- **Wi-Fi (60)**
  - Subnet Address: 10.166.121.0/26.
  - Subnet Mask: 255.255.255.192.
  - First available address: 10.166.121.1.
  - Last available address: 10.166.121.62.
  - Broadcast: 10.166.121.63.
  - VLANID used: 282

- **End user outlets on floor one (44)**
  - Subnet Address: 10.166.121.64/26.
  - Subnet Mask: 255.255.255.192.
  - First available address: 10.166.121.65.
  - Last available address: 10.166.121.126.
  - Broadcast: 10.166.121.127.
  - VLANID used: 281

- ** VoIP (IP-phones) (40)**
  - Subnet Address: 10.166.121.128/26.
  - Subnet Mask: 255.255.255.192.
  - First available address: 10.166.121.129.
  - Last available address: 10.166.121.190.
  - Broadcast: 10.166.121.191.
  - VLANID used: 283

- **End user outlets on the ground floor (40)**
  - Subnet Address: 10.166.121.192/26.
  - Subnet Mask: 255.255.255.192.
  - First available address: 10.166.121.193.
  - Last available address: 10.166.121.254.
  - Broadcast: 10.166.121.255.
  - VLANID used: 280

- **Routing Table**

- This is the routing table of the router of this building:

  - Destination: 10.166.112.128/25   Next Hop: 10.166.112.1
  - Destination: 10.166.113.0/26     Next Hop: 10.166.112.1
  - Destination: 10.166.113.64/26    Next Hop: 10.166.112.1
  - Destination: 10.166.113.128/27   Next Hop: 10.166.112.1
  - Destination: 10.166.113.160/27   Next Hop: 10.166.112.1
  - Destination: 10.166.116.0/22     Next Hop: 10.166.112.2
  - Destination: 10.166.124.0/22     Next Hop: 10.166.112.4

- **Notes**
- In my simulation, i represented every cross connect of the scructured cabling project. Because of
the switch model required, on the campus simulation, i had to cut one switch (CP) of one switch representing
one HCC because, like the information present in the planning.md, we only represented redundant cable links on
the campus simulation.