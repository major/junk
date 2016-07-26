KVM and QEMU Internals: Understanding the IO Subsystem
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will break down the plethora of options available for delivering storage to a virtual machine in KVM/QEMU. It will detail the mechanics and performance trade offs inherent in the different AIO modes, caching options, paravirtualization drivers, and thread settings. We will outline which OpenStack configuration options lead to the most desireable KVM/QEMU configuration settings, and what could be done to further enhance OpenStack's ability to take advantage of everything KVM/QEMU has to offer. Highlights of performance data will be shared that characterize how these settings affect real world MySQL workloads.  


* **Kyle Bader** *(Kyle Bader is a Senior Solution Architect working in the Storage Solutions Team at Red Hat, lending his design and operational skills with Ceph to help develop tested solutions that ensure repeatable success when deploying distributed, fault-tolerent, multi-petabyte storage systems. Prior to Red Hat, Kyle had architectural roles at both Inktank and DreamHost. Kyle was part of the team that brought the first production Ceph clusters to the world, supporting DreamHost's DreamObjects and DreamCompute services.)*
