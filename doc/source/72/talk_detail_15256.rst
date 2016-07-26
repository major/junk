Stateful Service Meets Stateless Gateway: Resolve Bottlenecks to Horizontally Scale L3 Gateways
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Stateless layer 3 gateways appear to be a simple way to increase scalability and on-ramp traffic to your virtual network. Growing throughput requirements can easily be met with additional gateway nodes. However, the apparent simplicity of L3 gateways scaling breaks down with the addition of stateful L4 functionality, such as NAT or load balancing, when the gateways quickly become a bottleneck. In this session, we present how we identified, debugged and ultimately solved this problem. To this end, we borrowed from the design of Google Maglev and built on top of the high performance foundation offered by Cisco's Vector Packet Processing (VPP) for DPDK. During the session, we demonstrate this functionality built on top of open-source MidoNet, although the same solution can be transposed to alternative SDNs.


* **Ivan Kelly** *(I've been active in virtual networking with Midokura since early 2015, previous having worked on the networking stack of SymbianOS for Nokia. I also spent a large part of my career at Yahoo, building distributed systems and databases, most notably Apache BookKeeper and Apache Omid.)*

* **Alex Bikfalvi** *(I am a developer at the networking virtualization software company Midokura. There, I contribute to the MidoNet project, with a focus on the control plane. Previously, I worked both in the industry as a software engineer as well as in academia as a networking researcher on networking and distributed systems, having earned a PhD from the Carlos III University in Madrid.)*
