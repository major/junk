How Did Our Private Cloud Realize Better Application SLA Using Open vSwitch with DPDK
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In recent years, our OpenStack private cloud resources (65k+ VM, 25k vCPU, 350TB memory) that support Yahoo! JAPAN web services require 6x network performance per server compared with traditional server farm as a result of VM aggregation and higher density.Additionally, huge and/or burst network traffic (5~10x than ordinary) we have often received from internet. More internal backend traffic (DNS, RDB, MQ, etc.) happend accordingly.In such situations, we faced a network performance issue in our cloud.To overcome this, we have adopted Open vSwitch with DPDK as a software L2 switch on HyperVisor instead of LinuxBridge, built new mitaka cluster (serving 8000+ VM scale) on OCP (Open Compute Project) servers, and started operation phase now.As we found many problems through our activities from OvS/DPDK PoC phase to operation phase, we will present about combination limitation related OvS/DPDK/NIC driver, network architecture/performance, L7 SLA, operation perspective, and future works.


* **Yusuke Tatsumi** *(Yusuke Tatsumi is a network infrastructure engineer at Yahoo! JAPAN. He belongs Site Operation Division, Infrastructure Engineering Department, support our own production web services by providing several resources(Servers, networking, Storages, Datacenter facilities).For 6 years, He had buit/maintein/managed "physical" production network. From last year, He started work about "virtual" networking such as DPDK, Open vSwitch, HyperVisor IP fabric especially in OpenStack environment.  )*

* **Hiroaki Morikawa** *(Hiroaki Morikawa has been working on OpenStack development project in Yahoo! JAPAN since 2012.Currently, he's been involved in projects related to network virtualization and most recently focused on Neutron DPDK plugin.)*

* **Naoyuki Mori** *(Naoyuki Mori is Application Engineer at Developer Relations Division, Software & Services Group at Intel. He has been working closely with software eco system partner to help optimizing for Intel Architecture. Recent years, he has focus on networking optimization such as DPDK, Open vSwitch, as well as storage ceph and OpenStack.)*
