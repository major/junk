Network of the Future: Accelerated OpenStack Networking with Contrail vRouter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenContrail system enables OpenStack to support virtual networks that span across datacenters, using a vRouter software dataplane component. However, running the dataplane purely within the hypervisor can have a significant CPU and memory bandwidth cost. We describe how a programmable NIC (SmartNIC) can accelerate the dataplane by offloading the routing function and directly delivering traffic into and out of VMs. With the concept of “representative interfaces” and a vendor-neutral offload API, the presence of hardware acceleration can be almost transparent to the orchestration and management layers.This new approach requires OpenStack to treat VM and hardware interfaces differently from those of traditional NICs. We examine the tradeoffs of various acceleration architectures, and the implications of SmartNICs to OpenStack architecture. The resulting system offers the flexibility of software while improving on the resource usage and performance of traditional hardware.


* **Ted Drapas** *(Ted Drapas is a director of software engineering at Netronome leading the vRouter acceleration effort.  Ted has 10 years of experience at Netronome working on security appliance and SDN software.)*

* **Chris Telfer** *(Chris Telfer is a distinguished software engineer at Netronome System where he has worked for the past 8 years. Among other endeavors, he works on the vRouter acceleration project at Netronome.)*

* **Raja Sivaramakrishnan** *(Raja Sivaramakrishnan is a distinguished software engineer at Juniper Networks. He is currently working on the vRouter forwarding component in the Contrail network virtualization solution. Previously, he worked on forwarding infrastructure in Junos for multiple router/switch platforms at Juniper.)*
