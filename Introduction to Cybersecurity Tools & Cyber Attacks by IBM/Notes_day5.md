### Notes:

---

#### Day5

* `Introduction to key security tools`:
* `FIREWALLS`: It isolates organization's internet from larger internet, allowing some packets to pass and blocking others.
* filters traffics between networks.
* handle packets differently.
* Multi homed.
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

* `XML gateway` : It passes through a conventional firewall without inspection.
* It examines the payloads of the XML messages.
* Source IP is known, target IP makes sense.
* No executable code.
* Well formed payload.


* `Stateless and stateful firewalls` : 
* Stateless: No concept of "state"; Also called `Packet filter`; Less secure.
* Stateful: Have a state tables that allow the firewall to compare the current packets with the previous ones. slower than stateless firewalls but more secure.

* `Proxy firewalls` : act as an intermediate server. They terminate connections and start new ones.
