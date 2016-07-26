Scale-out virtual machine bandwidth using Neutron DVR and OSPF deployed using Docker containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Current neutron DVR implementation depends on L2 connected public networks which will cause scalability and performance issues when you want to support multiple racks. In this talk, we will dive into a L3 based DVR implementation. We will see how using pure L3 DVR implementation helps achieve higher scalability and programmability Neutron DVR. By using this scale-out L3 implementation, bandwidth is now on the order of the number of hypervisor nodes and only bound by the limitations of the physical network itself.


* **Hao Chen** *(Hao Chen, a Senior Software Engineer at EMC, currently works on VxRack Neutrino project. The project is a turnkey cloud-native IaaS solution based on OpenStack and Docker. Hao started his career in Cloudscaling as a developer for Open Cloud System, an OpenStack based cloud solution. During his stay in EMC, he focused on distributed system design and networking optimization. In particular, he implemented the L3 DVR solution and the glance scaleio backend solution for neutrino. Hao has deep knowledge in various OpenStack projects such as Keystone, Glance, Nova, Neutron, Ceilometer and Heat.)*
