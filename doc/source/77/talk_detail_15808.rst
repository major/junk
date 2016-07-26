Data Performance testing on NFV clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Normally vlan traffic is generated from a traffic generator to the VNF under test and looped back to the traffic generator to measure the throughput and latency of the VNF on N/S and E/W topologies. However, there are much more metrics like the VNF boot time, VNF processing performance and  vSwitch processing performance with variable CPU/Mem/Other resource allocations and bandwidth allocations, that can be done across multiple different topologies for both vlan and vxlan with different acceleration techniques like DPDK, SRIOV and PCIPT used in the VNF.In our presentation we cover the following,-Different L2/L3 topologies for both vlan and vxlan, with and without DVR-vlan/vxlan Traffic generation tool used-Comparing data performance results across different acceleration techniques to identify performance bottlenecks-Brief demo showcasing variable VNF/Vswitch resources allocations and its impact on data performance


* **Thalabathy Venkatesan** *(Working in HPE as a QA Specialist.)*

* **Maheshkumar Pandurangan** *(Cloud test architect working at HPE)*

* **Ashraf Vazeer** *(working at HPE as a QA specialist.)*
