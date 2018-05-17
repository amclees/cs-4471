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

Todo:

* Chapters 15
* Chapters 16
* Chapters 17
* Chapters 18
* Chapters 19
* Chapters 20
* Chapters 21
* Chapters 22
