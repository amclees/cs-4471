# CS 4471 Final Exam

This exam is closed-book and should be taken in under 15 minutes.

## Multiple Choice

1. Ethernet frames are:

  a. Seen by all hosts on the same VLAN as the sender

  b. Seen by all hosts regardless of VLAN, since VLANs are a layer 3 protocol

  c. Seen only by the destination host

---

2. VLANs provide ___ separation of hosts

  a. Physical

  b. Wonderful

  c. Logical

  d. Layer 3

---

3. A port whose frames hold no VLAN information is a(n):

  a. Access port

  b. Trunk port

  c. Serial port

  d. Root port

  e. Gigabit Ethernet port

---

4. A port whose frames hold VLAN information can only be properly received and
forwarded on a(n):

  a. Access port

  b. Trunk port

  c. Serial port

  d. Root port

  e. Gigabit Ethernet port

---

5. An access port carries the traffic of:

  a. 1 VLAN

  b. 2 VLANs

  c. 1 or more VLANs from the same AS

  d. All VLANs

---

6. A switch port may be:

  a. Either an access or trunk port

  b. Both an access or trunk port

  c. Neither an access nor a trunk port

  d. a. and b.

  e. a. and c.

---

7. Devices are __ of their VLAN membership

  a. Solemnly aware

  b. Totally unaware

  c. Very wary

---  

8. A traditional Cisco trunk link may only be of speeds:

  a. 10 Mbps

  b. 100 Mbps

  c. 1000 Mbps

  d. 10000 Mbps

  e. a, b, and c

  f. b, c, and d

---

9. The maximum number of nonextended VLANs is:

  a. 1000

  b. 1001

  c. 1024

  d. 4094

  e. 4096

---

10. The maximum number of extended VLANs is:

  a. 1000

  b. 1001

  c. 1024

  d. 4094

  e. 4096

---

11. The VLAN frame tag is removed before the frame is send out an access link:

  a. True

  b. False

---

12. The VLAN frame tag contains a ___ to identify what VLAN the frame is from

  a. VLAN ID

  b. Network ID

  c. Source MAC address

---

13. ISL in the context of VLANs stands for:

  a. Inter-Server Link

  b. Internetwork Switch Link

  c. Inter-Switch Link

  d. Intranet Switch Link

---

14. The IEEE standard for frame tagging is:

  a. 801.1q

  b. 802.2xq

  c. 802.1q

  d. 801.12xqzzvy

---

15. The frame tagging method that puts a field into a frame (rather than onto):

  a. ISL

  b. The IEEE Standard from 14.

---

16. Putting a field into a frame implies:

  a. The destination MAC address must be recalculated

  b. The CRC must be recalculated

  c. The value of the frame delimiter must be recalculated

---

17. The user priority field, CFI, and VLAN ID respectively have what sizes in a
frame with a VLAN tag inserted:

  a. 3, 3, 10

  b. 8, 4, 2

  c. 3, 1, 12

  d. 32, 32, 4

---

18. The IEEE standard for frame tagging can support a maximum of what number of
VLANs given field size as its only constraint:

  a. 1022

  b. 1024

  c. 4094

  d. 4096

---

19. With trunking that inserts fields into or encapsulates frames, which of the
following VLAN methodologies becomes possible?

  a. One VLAN per router interface

  b. Logical subinterfaces corresponding to each VLAN

  c. IVR

  d. a. and b.

  e. b and c.

---

20. Your company has 980 VLANs, 50 layer 2 switches, and 2 routers (each with
10 Gigabit Ethernet ports). Which of the following VLAN methodologies do not
require further purchases?

  a. One VLAN per router interface

  b. Logical subinterfaces corresponding to each VLAN

  c. IVR

  d. a. and b.

  e. b and c.

---

21. IVR stands for:

  a. Iridium-valladium recycling

  b. Ion-volt routing

  c. Inter-VLAN routing

  d. Intra-VLAN routing

---

22. Which command creates a VLAN on a switch?

  a. `vlan <vlan id> <interface id`

  b. `vlan <vlan id>`

  c. `vlan create <vlan id>`

  d. `no delete vlan <vlan id>`

---

23. Cisco switches have a default method of frame tagging. Which command
switches to another method?

  a. `switchport trunk encapsulation n-isl`

  b. `switchport trunk encapsulation dot1q`

  c. `switchport trunk tag n-isl`

  d. `switchport trunk tag dot1q`

---

24. From interface config mode, which command designates the current
interface(s) as trunk port(s)?

  a. `no access port`

  b. `switchport access vlan <vlan id>`

  c. `switchport trunk`

  d. `switchport mode trunk`

  e. `switchport access <vlan id>`

---

25. From interface config mode, which command designates the current
interface(s) as trunk port(s)?

  a. `no access port`

  b. `switchport access vlan <vlan id>`

  c. `switchport trunk`

  d. `switchport mode trunk`

  e. `switchport access <vlan id>`

---

26. From subinterface config mode, which command set the VLAN of the current
subinterface?

  a. `encapsulation dot1q <vlan id>`

  b. `encapsulation dot1q vlan <vlan id>`

  c. `switchport trunk <vlan id>`

  d. `switchport trunk vlan <vlan id>`

---

27. Which command will open an IVR interface?

  a. `switchport access <vlan id>`

  b. `int vlan 4097`

  c. `int vlan 2`

  d. `int vlan ivr 2`

  e. `no non-ivr interface`

---

28. The DMZ typically would not contain which of the following types of server?

  a. HTTP

  b. SMTP

  c. DNS

  d. CVS

---

29. Let S be the set of standard access control lists, E be the set of extended
access control lists, and N be the set of named access control lists. Which of
the following is true?

  a. S U E = N

  b. N ⊆ (S U E)

  c. (S ∩ E) ≠ ∅

---

30. The same access list can filter inbound and outbound packets.

  a. True

  b. False

---

31. The ID ranges for standard IP access lists are:

  a. 1-99, 1300-1999

  b. 1-100, 1300-2000

  c. 1-1000, 1400-1999

  d. 1-100, 1400-2000

---

32. 172.24.16.12 matches 172.24.0.0 with a wildcard mask of 0.0.128.255

  a. True

  b. False

---

33. Consider the following network topology:

```
Internet
  |
Router ----- Database User's Computer 192.168.0.10
  | int0
Fragile Unfirewalled Database Server 192.168.0.11
```

Which sequence of commands create an access list that prevents any non-internal
requests to the Fragile Unfirewalled Database Server if applied to int0 on
outbound traffic (assume no IP spoofing)?

  a. `access-list 1 permit 192.168.0.11 0.0.0.0`

  b. `access-list 101 permit 192.168.0.11 0.0.0.0`

  a. `access-list 1 permit 192.168.0.11 255.255.255.255`

  b. `access-list 101 permit 192.168.0.11 255.255.255.255`

---

34. Access lists must be applied on the nearest interface to:

  a. The source

  b. The destination

  c. **The** switch

  d. **The** router

  e. None of the above, access lists should be applied fairly throughout the
network so as not to exclude any routers from the thrill of dropping packets

---

35. Which of the following commands creates an extended access list to drop all
TCP segments?

  a. `access-list 1 deny udp any any`

  b. `access-list 101 deny udp any any`

  a. `access-list 1 deny tcp any any`

  b. `access-list 101 deny tcp any any`

---

36. RFC ___ describes IP addresses for internal use (with NAT)

  a. 1918

  b. 1919

  c. 2460

  d. 2461

---

37. The RFC from question 36 reserves the network 10.0.0.0 with a subnet mask
of:

  a. 255.0.0.0

  b. 255.255.0.0

  c. 255.255.255.0

  d. 255.128.0.0

---

38. NAT is most of configured on:

  a. Hosts

  b. Internal routers

  c. Border routers

  d. Layer 3 switches

---

39. Static NAT allows for:

  a. Mapping internal IP addresses to a pool of global IP addresses that are
distributed on the fly by a router

  b. Mapping one-to-one between internal and global IP addresses

  c. PAT

---

40. Dynamic NAT allows for:

  a. Mapping internal IP addresses to a pool of global IP addresses that are
distributed on the fly by a router

  b. Mapping one-to-one between internal and global IP addresses

  c. PAT

---

41. Overloading allows for:

  a. Mapping internal IP addresses to a pool of global IP addresses that are
distributed on the fly by a router

  b. Mapping one-to-one between internal and global IP addresses

  c. PAT

---

42. Which of the following commands is part of configuring static NAT on a
router between 199.2.2.2 and 10.1.1.1?

  a. `ip nat inside source static 10.1.1.1 199.2.2.2`

  b. `nat inside source static 10.1.1.1 199.2.2.2`

  c. `ip nat outside source static 199.2.2.2 10.1.1.1`

---

43. Which of the following is part of configuring a pool of IP addresses for NAT
to use?

  a. `ip nat pool swimming 199.2.2.1 199.2.2.220 netmask 255.255.255.0`

  b. `ip nat pool john 199.2.2.1 199.2.2.220 netmask 255.205.255.0`

  c. `nat pool kyle 199.2.2.1 199.2.2.220 netmask 255.255.255.0`

---

44. Which of the following could be a part of configuring PAT?

  a. `ip nat inside source list 1 pool net pat`

  b. `ip nat outside source list -5 pool net pat`

  c. `ip nat outside source list 1 pool swimming pat`

  d. `ip nat inside source list 1 pool kyle overload`

---

45. An IPv6 address consists of ___ 16-bit blocks.

  a. 6

  b. 7

  c. 8

  d. 12

---

46. The first 48 bits of an IPv6 address are the:

  a. MAC address

  b. Global prefix

  c. Interface ID

  d. Subnet

---

47. The next 16 bits of an IPv6 address are the:

  a. MAC address

  b. Global prefix

  c. Interface ID

  d. Subnet

---

47. The next 64 bits of an IPv6 address are the:

  a. MAC address

  b. Global prefix

  c. Interface ID

  d. Subnet

---

48. Which of the following is not a valid IPv6 address?

  a. `2001::12::1234:56ab`

  b. `2001::12:0:0:1234:56ab`

  c. `2001:db8:3c4d:12::1234:56ab`

---

49. Any IPv6 address starting with ___ is a multicast address.

  a. `no multicast`

  b. `ff`

  c. `fe`

  d. `f0`

---

50. Anycast addresses are typically only configured on:

  a. Hosts

  b. Switches

  c. Bridges

  d. Hubs

  e. Routers

---

51. The difference between anycast and multicast addresses is:

  a. Anycast delivers the datagram to only one devices, the closest

  b. Multicast delivers the datagram to all devices on the address

  c. a. and b.

  d. a. and b. reversed (they are the opposite of the correct answer)

---

52. IPv6 addresses that are globally routable are called \_\_\_ and start with
\_\_\_.

  a. Global unicast addresses, `2000`

  b. Link-local addresses, `2000`

  c. Global unicast addresses, `db8`

  d. Link-local addresses, `fc00`

---

53. Unique local addresses are routable

  a. True

  b. False

---

54. Link-local addresses are routable

  a. True

  b. False

---

55. The original IETF recommendations for IETF allocation for the registry, ISP,
company, and subnet portions of a global unicast address were (in bit offset
from the address type specifier):

  a. 23, 32, 48, 64

  b. 24, 31, 48, 64

  c. 22, 32, 48, 64

  d. 32, 36, 42, 48

---

56. Which command enables all IPv6 routing on a Cisco router?

  a. `no shutdown ipv6`

  b. `no disable ipv6`

  c. `ipv6 unicast-routing`

  d. `no shutdown ipv6 all-routing`

  e. `ipv6 enable`

---

57. Using the `ipv6 address <address>/<prefix length>` command, how can the
device's padded MAC address be used to automatically fill the interface ID
portion of the address?

  a. `ipv6 address <address>/<prefix length>` will automatically handle it

  b. `ipv6 address <address>/<prefix length> eiu-48`

  c. `ipv6 address <address>/<prefix length> eui-64`

  d. `ipv6 address <address>/<prefix length> eui-48`

  c. `ipv6 address <address>/<prefix length> mac`

---

58. In the most common MAC padding schema (from 57.), the MAC is padding by:

  a. Prepending `FFFF`

  b. Appending `FFFF`

  c. Prepending `FFFE`

  d. Appending `FFFE`

  e. Generating 16 random bits, then XORing them with each of the 4 16-bit
portions of the max address. This result is then placed into a 2x2 matrix which is
multiplied with a random matrix in a Galois field.

---

59. Which command enables IPv6 stateless autoconfig using MAC padding?

  a. `ipv6 address autoconfig on`

  b. `no manual ipv6 address default`

  c. `no manualconfig ipv6`

  d. `ipv4 address autoconfig default`

  e. `ipv6 address autoconfig default`

---

60. In the stateless autoconfig process, RS and RA respectively stand for:

  a. Router solicitation and router advertisement

  b. Router solicitation and route advertisement

  c. Route solicitation and router advertisement

  d. Route slip and router aversion

---

61. DAD is \_\_\_.

  a. Dicyclic A-class error Detection

  b. Duplicate Address Detection

  c. Duplicate Advertisement Distrust

---

62. DAD is implemented with two types of messages:

  a. NS/NA

  b. NA/NR

  c. AR/VR

  d. NA/AR

---

63. Which of the following commands set up an IPv6 default route?

  a. `ipv6 route ::/0 gi0/0`

  b. `ipv6 route 2001:DB8:43:91::2/64 gi0/0`

  c. `ip route ::/0 gi0/0`

---

64. What is the size of the IPv4 header?

  a. 32 bytes

  b. 20 bytes

  c. 128 bytes

  d. 32768 bits

---

65. The type field in an ICMPv6 packet is how many bits?

  a. 7

  b. 8

  c. 9

  d. 16

  e. 4

---

66. A ping request uses the ICMPv6 message type of:

  a. 128

  b. 129

  c. 254

  d. 255

  e. 256

---

67. STP stands for:

  a. Special Tree Protocol

  b. Spanning Tree Primer

  c. Specific Time Protocol

---

68. The root bridge is the bridge with the:

  a. Lowest bridge ID

  b. Highest bridge ID

  c. Median bridge ID

---

69. The bridge ID is formed by:

  a. Appending the bridge priority to the MAC address

  b. Prepending the bridge priority to the MAC address

  c. Adding the bridge priority to the MAC address

---

70. A root port is:

  a. A port which does not forward any frames

  b. A port with the lowest cost to reach a particular network segment

  c. The port with the lowest path cost to the root bridge

---

71. A blocking port is:

  a. A port which does not forward any frames

  b. A port with the lowest cost to reach a particular network segment

  c. The port with the lowest path cost to the root bridge

---

72. A designated port is:

  a. A port which does not forward any frames

  b. A port with the lowest cost to reach a particular network segment

  c. The port with the lowest path cost to the root bridge

---

73. Which of the following statements is true?

  a. All forwarding ports are either designated or blocking

  b. All blocking ports are either root or forwarding

  c. All designated ports are either forwarding or root

---

74. All host data must stop passing through switches as STP converges:

  a. True

  b. False

---

75. The IEEE specifies STP link costs for links of speeds 10, 100, 10000, and 10000
Mb/s. What are their respective values?

  a. 64, 32, 8, 2

  b. 100, 19, 4, 2

  c. 100, 20, 4, 1

  d. 100, 50, 25, 12

---

76. If two bridges share a link and both would benefit from it being a
designated port, how is the dispute resolved?

  a. Bridge priority

  b. Bridge ID

  c. Link cost

  d. Chance

---

77. The bridge priority is a number in the range ([Ruby syntax](https://ruby-doc.org/core-2.5.1/Range.html)):

  a. (0..65536)

  b. (0...65536)

  c. (0..32768)

  d. (0...32768)

---

78. Which of the following is not an STP variant?

  a. IEEE 802.1d

  b. PVST+

  c. IEEE 802.1e

  d. PVST++

  e. Rapid PVST+

---

79. The BPDU is:

  a. A controller tasked with managing STP

  b. A unit of information sent between switches during STP convergence

  c. A data storage unit that backs up STP data in a database

---

80. One advantage of PVST+ is:

  a. It doesn't take absurd amounts of time to converge

  b. It is a Cisco standard

  c. It is not an STP variant, so this question is invalid

---

81. PVST++ uses a longer bridge ID than IEEE 802.1d

  a. True

  b. False

  c. PVST++ is not an STP variant, but PVST+ uses a longer bridge ID

  d. PVST++ is not an STP variant; event PVST+ does not use a longer bridge ID

  e. PVST+ and PVST++ are both not STP variants, so the comparison is
meaningless

---

82. RSTP converges faster than non-RSTP because:

  a. It doesn't, RSTP isn't a real STP variant

  b. It allows all bridges to forward BDPUs

  c. It uses different timers to detect failures more quickly

  d. It uses two extra port states to deal with failures more effectively

---

83. PortFast is a:

  a. Proprietary Cisco protocol that speeds up STP convergence

  b. Proprietary Cisco protocol that speeds up the transition to forwarding
state of specific interfaces when a bridge is connected

  c. Open standard that speeds up STP convergence

  d. Open standard that speeds up the transition to forwarding
  state of specific interfaces when a bridge is connected

---

84. Which command starts RSTP on a Cisco switch?

  a. `no shutdown rstp`

  b. `no shutdown spanning-tree rapid-pvst`

  c. `spanning-tree mode rapid-pvst`

  d. RSTP is not an STP variant so it cannot be enabled, but if it were a
variant it would probably look like `no shutdown rstp`

  e. `spanning-tree mode rapid pvst`

---

85. The original standard for STP can recover automatically in under 15 seconds
upon a failure

  a. True

  b. False

---

86. With DAI enabled, DHCP offers are:

  a. Guaranteed to reach their destination regardless of connection

  b. Only accepted from trusted interfaces

  c. Met with a retaliatory DDOS attack if they come from untrusted interfaces

  d. Accelerated to allow faster network expansion

---

87. IEEE 802.1x is a standard for \_\_\_-based networking

  a. Authentication

  b. Identity

  c. Blockchain

  d. STOP

  e. None of the above

---

88. The authentication server in IEEE 802.1x is called what?

  a. DIAMETER

  b. PERIMETER

  c. RADIUS

  d. SURFACE AREA

  e. ARC LENGTH

---

89. With proxy ARP enabled, routers respond to ARP requests:

  a. In the same subnet as the host

  b. On a different subnet from the host

  c. On the other side of a firewall from the host

  d. That are invalid

---

90. FHRPs allow:

  a. Mapping multiple physical routers to one logical one

  b. Mapping one logical router to other logical ones

  c. Mapping multiple logical routers to one physical one

---

91. HSRP is a FHRP distinguished by being:

  a. Cisco proprietary

  b. An open standard

  c. Having 4 classes of routers involved in its operation

  d. a. and c.

  e. b. and c.

---

92. HSRP uses:

  a. A single virtual MAC address for each logical router

  b. Each router's physical MAC address except when routers are lost

  c. Multicast Hello messages to verify devices are up

  d. a. and c.

  e. b. and c.

  f. a., b., and c.

---

93. The HSRP MAC address has three parts: an OUI, the HSRP ID, and the HSRP
group number. The respective lengths of these parts in bytes are what?

  a. 24, 16, 8

  b. 22, 14, 12

  c. 3, 2, 1

  d. 4, 1, 1

---

94. HSRP uses timers. Which list includes all HSRP timers?

  a. Hello, Standby, Active, Hold

  b. Hold, Active, Wait, Hello

  c. Standby, Hello, Reactive, Wait

  d. Standy, Hello, Active, Release

---

95. HSRP utilizes standby routers to relieve congestion as necessary.

  a. True

  b. False

---

96. EIGRP is a:

  a. Classful distance-vector protocol

  b. Classful link-state protocol

  c. Classless distance-vector protocol

  d. Classless link-state protocol

---

97. EIGRP is intercompatible with other protocols, that is, some routers being
routed through may be running another protocol.

  a. True

  b. False

---

98. A new router running EIGRP sends a ___ request to its interfaces

  a. Hello

  b. ACK

  c. Metric

  d. No request is sent when a new router joins

---

99. If two routers running EIGRP have different AS numbers:

  a. They will not consider each other neighbors

  b. They will broadcast to route to the new AS through all their interfaces

  c. They will enter an endless flood of Hello and ACK packets

---

100. Each EIGRP session maintains a table T of neighbors' IP addresses, hold
time intervals, SRTTs, and queue information. This table is called:

  a. Neighbor table

  b. Routing table

  c. Session table

  d. This table does not actually exist and thus has no name

  e. Topology table

---

101. View the following figure:

```
    5      1
NY --- LA --- SF
```

The AD and FD from NY to SF are:

  a. 5, 4

  b. 4, 5

  c. 1, 6

  d. 6, 1

  e. 5, 1

---

102. The EIGRP topology table differs how from a routing table:

  a. It contains additional locational metadata

  b. It contains backup routes called feasible successors

  c. It is stored as a JSON file in the cloud

  d. EIGRP does not have such a table

---

103. EIGRP has 5 types of packets. What are they?

  a. Hello, ACK, Response, Search, Query

  b. ACK, Search, Reply, Query, `no Query`

  c. Hello, Query, Reply, ACK, Update

  d. GET, PUT, POST, PATCH, DELETE

---

104. The algorithm in EIGRP that selects the best path for inclusion in the
routing table is called:

  a. TOURNAMENT

  b. DUAL

  c. DAUL

  d. This algorithm is called EIGRP. There is not another separate algorithm

---

105. Routing information updates received from a neighbor are forwarded to all
other EIGRP neighbors. This process is called:

  a. PortSmart

  b. SmartPort

  c. Split Horizon

  d. Smart Horizon

  e. This is not what happens! Updates are forwarded back to **ALL** EIGRP
neighbors including the sender.

---

106. When the best path is selected in EIGRP, four factors are considered. They
are:

  a. Load, Bandwidth, Latency, Accuracy

  b. Speed, Reliability, Security, Cost

  c. Bandwidth, Delay, Load, Reliability

  d. Only one factor is considered: bandwidth. Other factors are too minor to
earn a spot in a proprietary Cisco protocol.

---

107. EIGRPv6 exists and is EIGRP for IPv6

  a. True

  b. False

---

108. OSPF is often used in small personal networks due to its simplicity

  a. True

  b. False

---

109. OSPF Area 0 is also known as:

  a. The spine area

  b. The backbone area

  c. The external routing domain

  d. The backyard domain

---

110. The ASBR is in what area?

  a. 0

  b. Any area other than 0

  c. Any area

---

110. An OSPF link is:

  a. Any network

  b. Any network or interface

  c. Any interface added to the OSPF instance

  d. a. and c.

  e. OSPF does not define what a link is

---

111. An OSPF RID is

  a. The IP address of a link

  b. The IP address of an interface

  c. An IP address that identifies a router

  d. A UUID for a route

  e. The uppercase version of a UNIX utility for mapping UUIDs to other IDs

---

112. OSPF neighborship has conditions. What are they?

  a. Equivalent Area ID

  b. Equivalent Stub Area Flag

  c. Equivalent Password

  d. Equivalent Hello/Dead Intervals

  e. All of the above

  f. a., b., and c

  g. None of the above

---

113. Adjacencies are formed with all OSPF neighbors

  a. True

  b. False

---

114. In OSPF, all routers on a shared network establish adjacency with two
routers. What are they?

  a. DR/BDR

  b. AR/ABR

  c. ASBR/BASBR

  d. The above answers are not sufficient to represent all possible OSPF
configurations

---

115. The ___ protocol discovers neighbors and maintains their relationships in
OSPF.

  a. Hello

  b. Link state

  c. Distance-vector

  d. Such a protocol does not exist, the protocol is just OSPF

---

116. The neighborship database is typically stored in the cloud. Choose the best
answer from below.

  a. True

  b. False

  c. OSPF has no neighborship database

  d. The database uses Redis so it needs to be running in-memory on the router

---

117. \_\_\_s are OSPF messages containing routing information sent between
routers

  a. LSA

  b. BSA

  c. RSA

  d. AES

  e. DSA

  f. OSPF does not exchange routing information between routers

---

118. An area ID is associated with:

  a. A router

  b. An interface

---

119. All routers and networks in an OSPF area must be contiguous

  a. True

  b. False

---

120. How many standard modes of operation of OSPF are there?

  a. 13

  b. 2

  c. 3

  d. 4

  e. OSPF always uses broadcast multi-access mode and no other modes exist

---

121. OSPF has three stages. What are they (order matters)?

  a. Neighbor and adjacency initialization, SPF tree calculation, LSA flooding

  b. Neighbor initialization, SPF tree calculation, LSA P2P advanced transfer

  c. Neighbor and adjacency initialization, LSA flooding, SPF tree calculation

  d. OSPF has four stages

---

122. Point-to-point and broadcast OSPF instance respectively use what multicast
addresses for transferring LSAs to all adjacent links?

  a. 224.0.0.5, 224.0.0.6

  b. 224.0.0.6, 224.0.0.5

  c. 224.0.1.5, 224.0.0.5

  d. 224.0.0.5, 224.0.1.5

  e. OSPF does not transfer LSAs

---

123. SPF calculation happens for each:

  a. OSPF instance

  b. Backbone area

  c. Area

  d. Network

  e. Link

  f. SPF calculation does not happen because of a special OSPF feature known as
RAID-0

---

124. Which command enables OSPF on a Cisco router?

  a. `no shutdown ospf <process id>`

  b. `no stop ospf <process id>`

  c. `router ospf <process id>`

  d. `ospf <process id>`

  e. Cisco routers do not support OSPF

---

125. OSPF area numbers are \_\_\_-bit \_\_\_ integers

  a. 32, unsigned

  b. 32, signed

  c. 16, unsigned

  d. 16, signed

  e. They are arbitrary precision floating point numbers

---

126. The `network` Cisco IOS command takes an IP address and a subnet mask as
two of its arguements

  a. True

  b. False

  c. There is no such command

---

127. Which command disables OSPF for a particular interface on a Cisco router?

  a. `passive-interface <interface id>`

  b. `no ospf <interface id>`

  c. `ospf-interface off <interface id>`

  d. `no no disable ospf <interface id>`

  e. None of the above

---

Todo:

* Chapters 19
* Chapters 20
* Chapters 21
* Chapters 22
