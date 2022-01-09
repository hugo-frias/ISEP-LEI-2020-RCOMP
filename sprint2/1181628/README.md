
RCOMP 2019-2020 Project - Sprint 2 - Member 1181628 folder
===========================================

## Calculus
- Prefixo = 32 - log2(Nodes +2)
- Nodes = 2^(32-prefixo)-2

## Informations
- **End user outlets on the ground floor**: **40** nodes.
- **End user outlets on floor one**: **50** nodes.
- **Wi-Fi network**: **60** nodes.
- **Local servers, administration workstations, and machines (DMZ)**: **250** nodes.
- **VoIP (IP-phones)**: **25** nodes.

## Distribuction
- My building **IPv4 address space** starts at **10.166.124.0**.
- **DMZ (250)**
  - **Subnet Address**: 10.166.124.0/24.
  - **Netmask**: 255.255.255.0.
  - **First available address**: 10.166.124.1.
  - **Last available address**: 10.166.124.254.
  - **Broadcast**: 10.166.124.255.
  - **VLANID**: 293.
- **Wi-Fi (60)**
  - **Subnet Address**: 10.166.125.0/26.
  - **Netmask**: 255.255.255.192.
  - **First available address**: 10.166.125.1.
  - **Last available address**: 10.166.125.62.
  - **Broadcast**: 10.166.125.63.
  - **VLANID**: 292.
- **End user outlets on floor one (50)**
  - **Subnet Address**: 10.166.125.64/26.
  - **Netmask**: 255.255.255.192.
  - **First available address**: 10.166.125.65.
  - **Last available address**: 10.166.125.126.
  - **Broadcast**: 10.166.125.127.
  - **VLANID**: 291.
- **End user outlets on the ground floor (40)**
  - **Subnet Address**: 10.166.125.128/26.
  - **Netmask**: 255.255.255.192.
  - **First available address**: 10.166.125.129.
  - **Last available address**: 10.166.125.190.
  - **Broadcast**: 10.166.125.191.
  - **VLANID**: 290.
- **VoIP (IP-Phones) (25)**
  - **Subnet Address**: 10.166.125.192/27.
  - **Netmask**: 255.255.255.224.
  - **First available address**: 10.166.125.193.
  - **Last available address**: 10.166.125.222.
  - **Broadcast**: 10.166.125.223.
  - **VLANID**: 294.
- **Routing Table**  
   ![BD_RoutingTable](https://i.ibb.co/nBDKBPP/Routing-Table.png)
- **Notes**
  - To make the assignement of each network of the building, we used the rule bigger blocks first.
  - In this simulation, i didn't represent all CP's that were present on the structured cabling project, because the switches that would represent them would have the same configuration of the switches that i used in the simulation to represent CP's (1 per floor).
  - In this simulation, i didn't represent all HCC's that were present on the structured cabling project, because the switches that would represent them would have the same configuration of the switches that i used in the simulation to represent HCC's (1 per floor).