Network traffic telemetry with OVS DPDK in Monasca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Handling the ever increasing network traffic requires NFV to design and build networks that have scalability, flexibility and elasticity to it. One of the widely used tool for this purpose is the Data Path Development Kit (DPDK) libraries. Heavy traffic seeds the need to perform efficient network analytics over DPDK which involves monitoring network metrics such as Tx/Rx throughputs. Currently in Monasca, when ports are DPDK enabled, the libvirt plugin does not store and query metrics measurement/stats for the ports and hence is unable to collect the network metrics.We address this problem by collecting the metric for DPDK port using ovs plugin integration with the monasca-agent. Ovs plugin fetches the port stats from ovsdb using ovs-vsctl commands and store the queried metrics in a cache and from there we calculate the rate for the tx/rx packets for the dpdk enabled ports.


* **Ashish Gupta** *(I'm working with Openstack more than 4 years. Now I'm Senior Software developer at Hewlett Packard. My main interest is in Cloud computing especially OpenStack .Contributed my work in neutron related project such as vpnaas,lbaas,fwaas , networking-l2gw ,automation (tempest), ironic baremetal networking provisioning mech driver implementaion,monasca-agent ovs/libvirt plugin  implementation and testing.Currently involve in automating monasca-agent ovs/libvirt plugin.)*

* **Alok Maurya** *(Working as  Sr. Software engineer at  HPE . I and  responsible  for  performing scalability  testing of  HPE Helion  products . I have  been actively involved  in  contributing in upstream  in  different  projects networking-l2gw , monsaca , tempest .)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*
