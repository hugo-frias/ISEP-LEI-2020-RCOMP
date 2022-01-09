
  
RCOMP 2019-2020 Project - Sprint 2 planning  
===========================================  
### Sprint master: 1181628 ###  
  
(This file is to be created/edited by the sprint master only)  
  
# 1. Sprint's backlog #  
  
![SprintBacklog](https://i.ibb.co/h2nPwtS/Sprint-Backlog.png)  
  
# 2. Technical decisions and coordination #  
  
(In this section, all technical decisions taken in the planning meeting should be mentioned.      Most importantly, all technical decisions impacting on the subtasks implementation must be settled on this        meeting and specified here)  
  
- **Backbone cable types to be used**  
  - Optical fibre cables: 10baseFL and 10baseFB.  
- **VLANIDs range to be used**  
  - **Our Group**: 260 - 300.  
     - **Basic Math**: 300-260=40/4=10.  
  - **Building A**: Starts at 260.  
     - **Really Used**: 260-264.  
     - **Backbone**: 265.  
  - **Building B**: Starts at 270.  
     - **Really Used**: 270-274.  
  - **Building C**: Starts at 280.  
     - **Really Used**: 280-284.  
  - **Building D**: Starts at 290.  
     - **Really Used**: 290-294.  
- **VLAN names to be used**  
  - BX-FX-OUTLETS.  
  - BX-WiFi.  
  - BX-DMZ.  
  - BX-VoIP.  
     - Where X represents the building and the floor.  
- **VTP domain names to be used**  
  - vtdeg2.  
  
- **IPv4 address space to be used (addresses block)**  
  - **Our Group**: 10.166.112.0/20.  
  - **Next Group**: 10.166.128.0/20.  
     - **Basic Math**: 128-112=16/4=4.  
  - **Building A**: Starts at 10.166.112.128/23.  
  - **Building B**: Starts at 10.166.116.0/22.  
  - **Building C**: Starts at 10.166.120.0/22.  
  - **Building D**: Starts at 10.166.124.0/22.  
  - **Backbone**: Starts at 10.166.112.0/25.  
     - **Router A**: 10.166.112.1.  
     - **Router B**: 10.166.112.2.  
     - **Router C**: 10.166.112.3.  
     - **Router D**: 10.166.112.4.  
  
- **ISP router IPv4 node address**  
  * **Our Group**: 17.10.10.149/30.  
  
- **VoIP phones**  
  - We’ll use the **7960** model.  
- **WiFi Router**  
  - We’ll use the **2811** model.  
- **Switch**  
  - We’ll use the **PT-Empty** model.  
- **DMZ Server**  
  - We’ll use the **Server-PT** model.  
- **PC**  
  - We’ll use the **PC-PT** model.  
- **Laptop**  
  - We’ll use the **Laptop-PT** model.  
  
- **Some notes about the nomenclature**  
  - BX-ROUTER.  
  - BX-ICC.  
  - BX-FX-HCC.  
  - BX-FX-CP.  
  - BX-FX-PC.  
  - BX-FX-VIP.  
  - BX-FX-DMZ.  
  - BX-FX-AP.  
  - BX-FX-LPT.  
      - Where X represents the building and the floor.

- **Some notes about Packet Tracer simulation**
  - We will only represent redudant cable links in the campus simulation. We will connect, in each building, the switches representing HCC's and, at the campus level, we will connect the switches representing ICC's.

- **~~Application protocols outlining (further coordination may be required between members)~~**
  - --**x**--  
# 3. Subtasks assignment #  
  
(For each team member (sprint master included), the description of the assigned subtask in sprint 2)  
  
  * **1170500** - Building **A**.  
  * **1180730** - Building **B**.  
  * **1180782** - Building **C**.  
  * **1181628** - Building **D**.
