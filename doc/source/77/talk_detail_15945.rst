Successful rapid NFVi deployment - take 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During 2015 and 2016, many of the leading providers, such as Orange, AT&T or Telefonica have experienced some NFV lab trials, proof of concepts and some early NFV deployments. Based on these early deployments, NFV is perceived as a complex solution to be deployed with OpenStack. From 6WIND’s experiences, we have seen some lab trials which require many weeks before having an environment that is high performance ready. Most of the engineering efforts are spent in setting up the nodes because of the constraints related to the DPDK powering the NFVi virtual switching: setting up the proper DPDK PCI NICs, configuring the vswitch VLAN or VXLAN, trying to debug with tools like tcpdump, getting a SDN controller into the game, provisionning the security groups. Beyond 2016, getting rapidly a running NFVi will become critical for the maturity of deploying NFV. Fuel can be used to solve such rapid deployments of DPDK based NFVi.


* **Vincent JARDIN** *(Vincent Jardin is 6WIND's CTO. He is responsible to lead the architectures and developments for high performance packet processing. He co-founded the Quagga project, the open source project for routing, and remains one of its main contributors. He also helped found DPDK.org, an open source community that enables high performance network applications such as Network Functions Virtualization (NFV). Vincent has a strong knowledge on the packet processing technologies.)*

* **Irina Povolotskaya** *(Maintainer of Fuel Plugins SDK. Currently, drive different integration types like Fuel Plugins and OpenStack Drivers/Plugins validations. Constantly support dialog with Community to make the workflow clear, transparent and easy-to-go for contributors.)*
