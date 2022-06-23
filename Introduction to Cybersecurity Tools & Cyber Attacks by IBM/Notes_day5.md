### Notes:

---

#### Day5

* `Introduction to key security tools`:
* `FIREWALLS`: It isolates organization's internet from larger internet, allowing some packets to pass and blocking others.
* `Need of firewalls` --> 
  * Prevention of service attacks: Avoid TCP connections.
  * Prevention of illegal modification or acces to internal data:
  * Allowing only authorized access to inside networks:
* Two types of firewalls: Application level and Packet-filtering.

---


* `Packet filtering` : Internal network connected to internet via router firewall. The router filters packet by packet based on:
  * source IP address, destination IP address.
  * TCP/UDP source and destination port numbers.
  * ICMP message type.
  * TCP SYN and ACK bits.

* `Application gateway` : These are also packet filters. They are applied on applications as well as on IP/TCP/UDP fields. Example: Allow selected internal users to telnet outside.
* `Limitations of firewalls and gateways` : IP spoofing: router doesn't know if data is really coming from the claimed source.
* Client softwares must know how to contact gateways.
* Filters often use all or nothing policy for UDP.

---

* `XML gateway` : 
