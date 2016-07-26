Scaling Neutron Networks to Ten Thousand Ports
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the increasing adoption of Neutron networking in production environments, cloud operators have greater expectations for the number of ports supported by a Neutron network. This problem is further compounded by projects such as Magnum and Kuryr that bring container orchestration and networking to Neutron users. Supporting this scale is challenging and puts significant pressure on the SDN controllers and their southbound database. The difficulty lies not only the actual number of ports but also the expected churn from short-lived containers. While a distributed controller mitigates some this pressure, the southbound DB is still a bottleneck in most cases. With the goal of making a ten thousand port network a reality, in this session we address the scalability problem from two dimensions. First is scalability in the virtual plane, by designing southbound models that allow loading the ports based on demand. Second, we tackle the physical plane by scaling across many physical hosts.


* **Alex Bikfalvi** *(I am a developer at the networking virtualization software company Midokura. There, I contribute to the MidoNet project, with a focus on the control plane. Previously, I worked both in the industry as a software engineer as well as in academia as a networking researcher on networking and distributed systems, having earned a PhD from the Carlos III University in Madrid.)*

* **Adrian Serrano** *(Software Engineer by the Autonomous University of Barcelona, has expertise in network traffic analysis products for desktop and cloud platforms. Currently part of Midokura's core team, developing MidoNet, the open-source network virtualization software for IaaS clouds.)*
