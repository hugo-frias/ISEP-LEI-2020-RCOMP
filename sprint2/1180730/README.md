RCOMP 2019-2020 Project - Sprint 2 - Member 1180730 folder
===========================================

- End user outlets on the ground floor: 60 nodes
- End user outlets on floor one: 70 nodes
- Wi-Fi network: 100 nodes
- Local servers and administration workstations (DMZ): 12 nodes
- VoIP (IP-phones): 35 nodes

Total of Nodes: 277


Therefore we will need 280 networks, where only 278 will be available. The hosts 60,70,100,12 and 35 are calculated using the correct rules of attribution of IPs.
So this is the network for the Building B:


Starts on this one B: 10.166.116.0


##### WiFi(100): 25 - 0.0.0.100

- Subnet Address: 10.166.116.0/25
- Subnet Mask: 255.255.255.128 (10000000)
- First available address: 10.166.116.1
- Last available address: 10.166.116.126
- Broadcast: 10.166.116.127
- Vlan ID: 272

##### Outlets (piso 1) (70):25 - 0.0.0.70

- Subnet Address: 10.166.116.128/25
- Subnet Mask: 255.255.255.128 (10000000)
- First available address: 10.166.116.129
- Last available address: 10.166.116.254
- Broadcast: 10.166.116.255
- Vlan ID: 271

##### Outlets (piso 0) (60): 26 - 0.0.0.60

- Subnet Address: 10.166.117.0/26
- Subnet Mask: 255.255.255.192
- First available address: 10.166.117.1
- Last available address: 10.166.117.62
- Broadcast: 10.166.117.63
- Vlan ID: 270


##### VoIP (35):26

- Subnet Address: 10.166.117.64
- Subnet Mask: 255.255.255.192
- First available address: 10.166.117.65
- Last available address: 10.166.117.126
- Broadcast: 10.166.117.127
- Vlan ID: 274

##### DMZ(12): 28

- Subnet Address: 10.166.117.128
- Subnet Mask: 255.255.255.240
- First available address: 10.166.117.129
- Last available address: 10.166.117.142
- Broadcast: 10.166.117.143
- Vlan ID: 273

#### Routing table

- 10.166.112.128/25 via 10.166.112.1
- 10.166.113.0/26 via 10.166.112.1
- 10.166.113.64/26 via 10.166.112.1
- 10.166.113.128/27 via 10.166.112.1
- 10.166.113.160/27 via 10.166.112.1
- 10.166.120.0/22 via 10.166.112.3
- 10.166.124.0/22 via 10.166.112.4



### Note1: In this simulation, I didn't represent all CP's that were present on the structured cabling project, because the switches that would represent them would have the same configuration of the switches that I used in the simulation to represent CP's (1 per floor).

### Note2: To make the assignement of each network of the building, we used the rule bigger blocks first