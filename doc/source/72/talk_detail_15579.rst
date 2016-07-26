Network Dataplane Acceleration Techniques
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Increasing load on the network often comes at a high cost: having kernel process a lot of packets in a unit of time leads to significant increase in CPU utilization and performance degradation. Using  overlay networks (eg. VxLAN) where encapsulation/decapsulation takes place makes the situation even worse.   Modern hardware allows to take some load from CPU and distribute part of the network processing to the NIC. There are also software techniques that can be used in conjunction with hardware ones to improve throughput greatly.   In this talk we will demonstrate the effect various acceleration techniques  have on performance. We examine differences in throughput as well as the effect on CPU utilization when these techniques are used. In particular, we will touch the following technology areas: Usage of hardware offloads SR-IOV acceleration techniques Software-based acceleration with DPDK


* **Elena Ezhova** *(Elena has been working on OpenStack since Grizzly release and has contributed to such projects as Neutron and its advanced services, especially Octavia, LBaaS, as well as VPNaaS, Oslo, Tempest and Keystone. She was responsible for graduating the oslo.service library and currently is a member of its core team.)*

* **Sergey Matov** *(In Mirantis Sergey has been working on several Networking projects, such as Vyatta vRouter. Authored several features to vRouter, Sergey moved to OpenStack department. He took part in adapting NVF technologies for Mirantis OpenStack 9.0.)*

* **Dmitry Klenov** *(Dmitry has been involved into Mirantis services activities since OpenStack Folsom release adapting OpenStack technologies for customer needs. In Mitaka release Dmitry was driving the productization of NFV technologies for Mirantis OpenStack 9.0.)*
