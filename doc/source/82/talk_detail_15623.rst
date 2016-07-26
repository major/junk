Network Trunking in OpenStack Neutron: How to Achieve Consensus?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enabling trunk ports (bp/vlan-aware-vms) in Neutron has been challenging for many reasons: it is a complex feature with several use cases we needed to take into consideration, poor performance was not acceptable, moreover a lot of attention led to long discussions. The first patch was sent for review in May of 2014. Today, October of 2016, when most of the work is done, we invite you to join us to look back and to learn from this experience. This talk will go through some anecdotes, analyze the pain points and will offer some solutions and advices on how to reach consensus. You will hear about: How we went through the various API proposals until one stuck; How we kept the Neutron API backwards compatible and technology agnostic while practically changing a fundamental premise of the Neutron network-port relationship; Why we analyzed many approaches via proof-of-concepts before picking the right one; and How we learned to better design accross OpenStack projects.


* **Rossella Sblendido** *(Rossella is a Software Engineer at SUSE. She's a core reviewer for Neutron and has been involved in SDN since 2010 . She's also a mentor for the OpenStack Outreach Program for Women.)*

* **Armando Migliaccio** *(Armando Migliaccio is the PTL for the Mitaka and Newton releases of the OpenStack Neutron Project. He has been involved in the OpenStack community since its early days, and has dealt with a number of OpenStack projects, and solutions in various capacities. Most recently he has been working in various open source projects, like OpenDaylight and Open vSwitch to help the industry usher in a new era of networking.  When he is away from his desk, Armando enjoys sunny California between one travel and another. )*

* **Bence Romsics** *(Bence Romsics has spent the last decade in the technology industry, first operating then engineering and developing software. He has a keen interest in distributed systems, software architecture and scaling. He has worked two years on tooling for a large-scale virtualization platform, another three working with OpenStack networking. Today he is working on finding ways to match the needs of the telecommunications sector with the ever developing offerings of cloud systems.)*
