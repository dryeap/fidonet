# fidonet

FidoNet is a **volunteer-run, store-and-forward computer network** that linked thousands of dial-up Bulletin Board Systems (BBSs) world-wide from 1984 until the late 1990s.  Created by the American programmer **Tom Jennings**, it allowed hobbyist Sysops to exchange private “NetMail”, public “EchoMail” conferences and files by batching messages into compressed packets that were relayed automatically during low-tariff night-time calls (Jennings, 1985, cited in Quarterman, 1990).

### 1  Technical foundations

| Aspect             | Details                                                                                                         | Key source                               |
| ------------------ | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| **Addressing**     | Hierarchical numbers → *Zone\:Net/Node.Point* (e.g., 1:321/12)                                                  | Quarterman & Wilhelm (1990, pp. 480-486) |
| **Protocols**      | Minimum compliance with **FTS-0001**: XMODEM file transfer, *.PKT* packet format, Zone Mail Hour calling window | Bush (1995)                              |
| **Software stack** | Mailer (*FrontDoor*, *BinkleyTerm*), Tosser/Scanner (*FastEcho*), BBS front ends (*PCBoard*, *Remote-Access*)   | Rheingold (1993)                         |
| **Scale**          | ≈ 35 000 active nodes by 1995 (Bates & Lansing, 1993)                                                           |                                          |

### 2  Operation and community governance

FidoNet was divided into six geographic **zones**; each zone contained regions, nets and individual nodes.  A weekly “nodelist” was distributed to keep routing tables synchronised.  Volunteer **Zone, Region and Net Co-ordinators** mediated technical disputes and maintained policy (Sterling, 1992).

### 3  Legacy

FidoNet anticipated many today’s Internet practices:

* peering based on least-cost routing;
* distributed moderation in EchoMail (a forerunner of Usenet newsgroups);
* early gateways to UUCP and SMTP e-mail (Quarterman & Wilhelm, 1990).
  Although dial-up FidoNet traffic collapsed after public Internet access became common, a niche “retro-computing” scene still exchanges packets over TCP/IP via the **Binkp** protocol (Dourish, 2015).

## FidoNet in Singapore

Milestone and Evidence from scholarly / book sources                  
1. **Arrival (1987-1988)**: *The Matrix* lists Net 600 as the first FidoNet **Net** covering Singapore and Malaysia, co-ordinated by sysop **Wing Lee** at node 6:600/0 (Quarterman & Wilhelm, 1990, p. 482).
2. **Growth (early 1990s)**: Zone 6 “registered over thirty nodes in Singapore alone”, reflecting the city-state’s inexpensive local-call regime and high PC penetration (Bates & Lansing, 1993)
3. **Typical services**: Local EchoMail areas such as **SG.GENERAL** and **ASIA.COMMS**, plus international echoes gated via Australian Zone-3 hubs (Quarterman & Wilhelm, 1990).
4. **Decline (late 1990s)**: Rapid roll-out of consumer Internet (SingNet 1994) led to a sharp fall in dial-up BBS activity; by 1999 only a handful of Singaporean FidoNet nodes remained active (Rheingold, 1999).

## References

Bates, B. J., & Lansing, K. P. (1993). *The new world of democratic telecommunications: FidoNet as an example of the new horizontal information networks.* Paper presented at the 43rd Annual Conference of the International Communication Association, Washington, DC.

Bush, R. (1995, 30 September). *FTS-0001: FidoNet technical standards.* FidoNet Technical Standards Committee.

Dourish, P. (2015). *How Othernets illuminate our feudal Internet.* Proceedings of the International Conference on the Internet and Society, 45-54.

Quarterman, J. S., & Wilhelm, P. A. (1990). *The matrix: Computer networks and conferencing systems worldwide.* Reading, MA: Addison-Wesley.

Rheingold, H. (1993). *The virtual community: Homesteading on the electronic frontier.* London: Secker & Warburg.

Sterling, B. (1992). *The hacker crackdown: Law and disorder on the electronic frontier.* New York, NY: Bantam Books.

PS: With assistance from gpt o3 model.
