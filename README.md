I'm not a developer.
====================
##### I'm just an infra guy doing some random stuff.

Started more than 10 years ago at the lowest level of the IT ladder, helpdesk & support, and climbed my way up to the architect level.

Done and practiced several technologies during my operations experiences: network, virtualization, security... but when I started working with voip and video, my heart was stolen.

VoIP, video and IMs (aka Unified Communication & Collaboration) had it all:
* you need to know **networks** (_because how traffic is routed and how the phones interacted with switches with lldp&cdp and how trasport affects quality of real time traffic, so QoS as well, are topics of prime importance_).
* you needed to know **security** and firewalls (_because you need to secure negotiation & real time traffic, understand very well NAT and its implications in protocols like SIP, not to mention the importance of PKIs_).
* you need to know how **protocols** work (_~~h.323~~ SIP is an entire world per se with STUN/TURN and STIR/SHAKEN_).
* you need to know **DNS** and **load balancing** (_'cause a service is useless if you don't know how to find/discover it_)
* you need to understand **virtualization** (_'cause -you know- you don't waste a physical machine for just making audio/video calls, right...? Even though things like transcoding have dedicated HW technology, known as DSP, which suddenly has to be emulated in software... easy stuff, right?_)
* you needed to understand **databases** (_when you deal with **a lot** of phone devices/phone numbers aka dial plan, being able to directly read or manipulate your data in SQL makes a difference_).
* you needed to be **able to script** (_doing stuff in bulk really saves a lot of efforts and spares you from the misery of human fallacy, God bless the inventor of APIs_).

Cisco Call Manager in particular was the epitome of this: the most powerful communication solution existing to date, able to do it all, with all sort of technology crammed in. If you think you cannot do something with the Call Manager (_well, UC related obviously_) it means you don't know it enough.

So, while becoming a UCC specialist, I was in fact becoming a jack of all trades of IT.

More recently, having developed almost every useful skill in UCC, I'm tinkering with DevOps stuff: some scripting, some containers, some git, some Jenkins... that's a whole lot of new interesting stuff to learn. You'll find here some of my experiments in this new journey!
