RCOMP 2019-2020 Project - Sprint 2 - Member 1170500 folder
===========================================

## Notes
- Prefixo = 32 - log2(Nodes +2)
- Nodes = 2^(32-prefixo)-2
- To make the assignement of each network of the building, we used the rule bigger blocks first
-In this simulation, I didn't represent all CP's that were present on the structured cabling project, because the switches that would represent them would have the same configuration of the switches that I used in the simulation to represent CP's (1 per floor).
- Sometimes, upon booting, the floor 0 laptop re-sets its IP to an old one, instead of mantaining the one on the note. I have no ideia why it happens nor how to fix it.

## Informations
- End user outlets on the ground floor: **40** nodes.
- End user outlets on floor one: **40** nodes.
- Wi-Fi network: **24** nodes.
- Local servers, administration workstations, and machines (DMZ): **70** nodes.
- VoIP (IP-phones): **20** nodes.
- Backbone: **120** nodes.

## Distribuction
- My building IPv4 adress space starts at **10.166.112.0**.
- **Backbone (120)**
  - Subnet Address: 10.166.112.0/25.
  - Net Mask: 255.255.255.128.
  - First available address: 10.166.112.1.
  - Last available address: 10.166.112.126.
  - Broadcast: 10.166.112.127.
- **DMZ(70)**
  - Subnet Address: 10.166.112.128./25
  - Net Mask: 255.255.255.128.
  - First available address: 10.166.112.129.
  - Last available address: 10.166.112.254.
  - Broadcast: 10.166.112.255
- **End user outlets on the ground floor (40)**
  - Subnet Address: 10.166.113.0/26.
  - Net Mask: 255.255.255.192.
  - First available address: 10.166.113.1.
  - Last available address: 10.166.113.62.
  - Broadcast: 10.166.113.63.
- **End user outlets on floor one (40)**
  - Subnet Address: 10.166.113.64/26.
  - Net Mask: 255.255.255.192.
  - First available address: 10.166.113.65.
  - Last available address: 10.166.113.126.
  - Broadcast: 10.166.113.127.
- **Wi-Fi (24)** 27
  - Subnet Address: 10.166.113.128/27.
  - Net Mask: 255.255.255.224.
  - First available address: 10.166.113.129.
  - Last available address: 10.166.113.158.
  - Broadcast: 10.166.113.159.
- **VoIP (20)** 27
  - Subnet Address: 10.166.113.160/27.
  - Net Mask: 255.255.255.224.
  - First available address: 10.166.113.161.
  - Last available address: 10.166.113.190.
  - Broadcast: 10.166.113.191.
