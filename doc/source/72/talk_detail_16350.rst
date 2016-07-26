Resolving the SR-IOV conundrum for NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

If you deploy an openstack based NFV solution, you have to make a fundamental trade-off right off the bat -- you can either use a hypervisor/virtual switch based networking for VMs or you can use SR-IOV. A virtual switch based solution gives us all the “SDx goodness” that openstack promises (like self service, network virtualization, advanced traffic steering, distributed firewall/security, policy enforcement, etc) at the cost of additional processing on the hypervisor, OR you can use an SR-IOV based VM network that can achieve faster network function performance by doing a direct DMA to/from the NIC to the VM at the cost of sacrificing that “SDx goodness”. In this talk, we will show how this issue can be resolved cleanly by a modern SDN fabric. By moving the user intent to a policy framework that can be enforced directly in hardware, we can allow the hypervisors to give direct DMA access for network traffic without losing any flexibility provided by the SDx APIs/interfaces.  


* **Mandeep Dhami** *(Mandeep Dhami is a Principal Software Engineer @ Cisco where he currently works on open source projects like Openstack, Opendaylight and Openvswitch. He has dabbled in building networking and security solutions for service provider and datacenters for most of his career. An early pioneer in network virtualization, he led the team that developed the first network services virtualization platform while at Inkra networks. And most recently, before joining Cisco, he was leading the team that built BVS (Big Virtual Switch) at Big Switch Networks.)*

* **Mike Cohen** *(Mike Cohen is Director of Product Management at Cisco Systems.  Mike began his career as an early engineer on VMware's hypervisor team and subsequently worked in infrastructure product management on Google and Big Switch Networks.  Mike holds a BSE in Electrical Engineering from Princeton University and an MBA from Harvard Business School.)*

* **Amit Bose** *(Amit is a Techinical Leader at Cisco Systems and contributes primarily to the Group Based Policy project and Neutron.)*
