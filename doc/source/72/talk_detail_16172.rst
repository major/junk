Accelerating Data Delivery to Containers via OpenStack and SmartNICs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker provides management of Linux containers with a high level API providing a lightweight solution that runs processes in isolation. It provides a way to automate software deployment in a secure and repeatable environment. When used with OpenStack it becomes much more powerful since it’s then possible to manage several hosts, which in turn manage hundreds or thousands of containers. NAT is often used in conjunction with Linux bridging and firewalling to securely connect containers to public networks. Offloading Linux bridging, iptables, and NAT to SmartNICs can increase the throughput and reduce the CPU utilization associated with network connectivity for containers. In order to support a large number of containers, demultiplexing to a commensurate number of host endpoints is required. This presentation explores these requirements in detail while describing options for high performance and accelerated implementations and the implications on OpenStack, specifically Nova and Neutron.


* **Daniel Proch** *(Daniel Proch is responsible for Solutions Architecture at Netronome.  His role includes technology strategy, network architecture, and hardware and software planning.  Previously he was Vice President of Product Management responsible for their line of Intelligent Server Adapters and software.  He has engineering and telecommunications degrees from Carnegie Mellon University and the University of Pittsburgh.)*
