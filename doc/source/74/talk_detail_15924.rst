Method for Monitoring Business Critical Baremetal servers using Monasca.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With Openstack Ironic-Baremetal neutron network provisioning in place, it became very easy to manage baremetal servers, including legacy servers like Web/Outlook/DNS/DHCP servers into cloud for tenants utilization. Though openstack successfully included baremetal servers into cloud, Cloud Admin should also be able to understand time-to-time baremetal server status, their metrics which is not currently available in openstack. This problem can be solved by monitoring various metrics of baremetal server like network utilization (Tx/Rx), CPU, Memory utilization using Monasca. Neutron ports of type baremetal contains physical switch/port information. From new Monasca plug-in we poll network metrics of physical switch using Netconf/SNMP and populate these metrics in Monasca API.This way User can understand time to time performance of the baremetal based on derived metrics.Monasca configuration will also allows users to specify which servers and metrics to be monitored by Monasca agent.


* **KRISHNA MOULI TANKALA** *(Currently working as Software Engineer at Hewlett Packard Enterprise, India. Major contributor to Neutron, Baremetal network provisioning, Lbaas, Octavia.)*

* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*
