Fast and Faster: OpenStack Security Groups using SmartNIC-Accelerated Connection Tracking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack's security groups facilitate micro-segmentation of cloud infrastructure. Historically they have been implemented using the Linux bridging and firewalling facilities. The latest Open vSwitch release (2.5) can interface to the Linux kernel connection tracking (conntrack) module to improve the performance and granularity of security group implementations.  This presentation describes the OVS conntrack architecture and the expressiveness it offers. It covers the integration of OVS conntrack with OpenStack via an OVN driver or a ML2 plugin. It furthermore describes how OVS conntrack can be accelerated by employing SmartNICs, yielding improved throughput and reduced CPU utilization.


* **John Hurley** *(John has been working with Netronome for 4 years looking at the acceleration of SDN and virtual switching using multiple generations of Netronome’s Flow Processors and Intelligent Server Adapters. Prior to this he has been involved in academic research into network analytic and security systems at the Centre for Secure Information Technology (CSIT), Belfast, and product development through startup company TitanIC. He completed a MEng in Computer Science in 2006 and a PhD in 2009, both at the Queen’s University of Belfast.)*
