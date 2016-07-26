Neutron generic mechanism driver for baremetal network provisioning for multi-vendor switches
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently openstack neutron requires separate mechanism driver for plumbing various underlay switches for different vendors and protocols for baremetal servers.This abstract is to eliminate the different vendor mechanism driver implementation and make it single generic mechanism driver. In this generic driver we can initialize the appropriate vendor driver i.e third party drivers based on the user input. We have developed this using stevedore library to load the vendor driver (third party) dynamically during network configuration.In this way we can manage multiple vendor hardware switches with different protocols.we will present how to plug a new vendor driver in the existing ML2 mechanism generic drivers for network provisioning for their hardware.    


* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*

* **KRISHNA MOULI TANKALA** *(Currently working as Software Engineer at Hewlett Packard Enterprise, India. Major contributor to Neutron, Baremetal network provisioning, Lbaas, Octavia.)*
