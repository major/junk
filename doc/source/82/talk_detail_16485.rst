Neutron L3 Flavors
~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron has had a modular system to load multiple drivers to provide layer 2 connectivity since Havana. This enables a single Neutron deployment to service multiple use cases (e.g. bare metal, SR-IOV, and DPDK). However, there was no mechanism to load multiple L3 drivers so operators were forced to choose a single plugin to provide routers and floating IPs for an entire deployment. To provide this capability, the concept of 'router flavors' was introduced during the Newton development timeline.  During this talk we will cover how operators and users will interact with router flavors to create routers that provide features optimized for specific use cases (e.g. deep packet inspection, high performance hardware routing, packet logging, etc) while using regular Neutron routers for everything else. We will then give a crash course on how to develop a new driver for the flavor framework to cover all of the high-level requirements for a developer to make his/her own driver.


* **Kevin Benton** *(Kevin Benton is currently a Software Engineer at Mirantis. He has been contributing to Neutron since Havana while he was working at Big Switch Networks and has been a core reviewer since 2014. He is the Lieutenant of the reference implementation and also serves on the Neutron drivers team, helping the PTL define the direction of the project by selecting features to work on. He prefers to spend time improving the stability and performance of Neutron and its reference implementation to give deployers reliable OpenStack networking without immediately turning to a vendor.)*

* **Armando Migliaccio** *(Armando Migliaccio is the PTL for the Mitaka and Newton releases of the OpenStack Neutron Project. He has been involved in the OpenStack community since its early days, and has dealt with a number of OpenStack projects, and solutions in various capacities. Most recently he has been working in various open source projects, like OpenDaylight and Open vSwitch to help the industry usher in a new era of networking.  When he is away from his desk, Armando enjoys sunny California between one travel and another. )*
