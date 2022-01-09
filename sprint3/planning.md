RCOMP 2019-2020 Project - Sprint 3 planning
===========================================
### Sprint master: 1180782 ###

# 1. Sprint's backlog #

* Task T.3.1: Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building A.
* Task T.3.2: Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building B.
Final integration of each member’s Packet Tracer simulation into a single simulation.
* Task T.3.3: Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building C.
* Task T.3.4: Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building D.

# 2. Technical decisions and coordination #

#### OSPF Area Ids: ####
  - Backbone: 0
  - Building A: 1
  - Building B: 2
  - Building C: 3
  - Building D: 4

#### VoIP phone numbers and prefix digits schema ####
  - Fixed number of digits to be used: 6
  - Building A: 913100
  - Building B: 913200
  - Building C: 913300
  - Building D: 913400

#### DNS Domain Names ####
  - Building A: rcomp-19-20-de-g2 (root domain)
  - Building B: building-B.rcomp-19-20-de-g2
  - Building C: building-C.rcomp-19-20-de-g2
  - Building D: building-D.rcomp-19-20-de-g2

#### IPv4 node address of the DNS name server of each DNS domain ####
  - Building A: 10.166.112.254/25 (Mask: 255.255.255.128)
  - Building B: 10.166.117.129/28 (Mask: 255.255.255.240)
  - Building C: 10.166.120.3/24 (Mask: 255.255.255.0)
  - Building D: 10.166.124.2/24 (Mask: 255.255.255.0)

  - The name of the domain’s DNS name server has already been established to be ns within that domain.

# 3. Subtasks assignment #

  * 1170500 - Building A (T.3.1)
  * 1180730 - Building B (T.3.2)
  * 1180782 - Building C (T.3.3)
  * 1181628 - Building D (T.3.4)
