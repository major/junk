DPDK accelerated OVS in OpenStack: How We Got Here
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Recent versions of Open vSwitch (OVS) provide an accelerated datapath based on the Data Plane Development Kit (DPDK) libraries. The acceleration that DPDK provided is vital for meeting the high performance, high determinism requirements of NFV workloads. As the most widely deployed virtual switching in OpenStack, Open vSwitch (OVS) is a key vector in the race to enable real-time applications within OpenStack. Intel has been working with its partners since 2013 to bring the benefits of OVS with DPDK to OpenStack, and this work is finally bearing fruit. In this talk, we explore the work that has been done and the work that is still ongoing to bring the benefits of OVS-DPDK to OpenStack. We detail how users can benefit from these changes, and the impact they can expect to see. Finally, we detail how users can get started exploring these changes themselves, and how they can configure these solutions to deliver the maximum possible performance for their workloads.


* **Stephen Finucane** *(I'm a software developer working in the OpenStack team in Intel Shannon. I predominantly work with Nova, though I've also been known to tinker with Neutron. I previously worked in the Open vSwitch team, also in Shannon, where I led internal testing and validation efforts.)*

* **Seán Mooney** *(Seán Mooney is a network software engineer in Intel's Network Platforms Group. He's passionate about high performance networking and open source software with a particular interest in virtual switching and orchestration technologies. His latest contribution to the OpenStack project is the ML2 Mechanism Driver for OVS+DPDK-netdev.)*
