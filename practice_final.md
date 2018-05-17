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

Todo:

* Chapters 13
* Chapters 14
* Chapters 15
* Chapters 16
* Chapters 17
* Chapters 18
* Chapters 19
* Chapters 20
* Chapters 21
* Chapters 22
