Security group performance improvement with ipset for multi-region environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation explains security group in multi-region environment: why it is needed, what is a problem, and how resolve it.'Region' is one of methods to separate OpenStack environment for redundancy. Each region is independent OpenStack environment except keystone. To use multi-region environment for backup or disaster recovery, VM instances in each region need to communicate each other to share their data. Therefore security group to allow the communication between regions have to be set up.However there is a critical performance problem when setting up security group across region, because to allow connection between regions, we have to add rules using remote_ip_prefix and specify IP address of each instances one by one. The number of iptable rules are increased and it causes performance degradation of network.To resolve this problem, I propose to optimize iptable rules using ipset in L2 agent so that a bunch of iptable rules can coalesce into one group.


* **Takao Indoh** *(Takao Indoh has been working for support service of Linux system in Fujitsu since 2001, especially working for crash dump for mission critical server, and has also committed several open source communities relevant to crash dump framework, LKCD(Linux Kernel Crash Dump), diskdump, kdump, and so on. Also working for improving network feature like Open vSwitch, DPDK, etc.  )*
