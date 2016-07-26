Building Multi-Cluster LBaaS in Yahoo! JAPAN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our private cloud came to be composed of a number of OpenStack cluster, It is also often one of the web service is distributed across multiple OpenStack. LBaaS is strongly associated with its own OpenStack, can not manage the instance of other OpenStack cluster in LBaaS. You can add a member in OpenStack in the IP address, but the data of LBaaS had become apart. Therefore, we built dedicated OpenStack for LBaaS and aggregated all the LBaaS data for the OpenStack clusters. And transparently requests to Neutron of LBaaS OpenStack from Compute OpenStack. By this configuration, each of the Compute OpenStack will request to the dedicated LBaaS as if it's own Neutron. As a result, it is possible to aggregate the data for LBaaS to one OpenStack, it became easier operation.In this session, we will talk about the design and configuration of the new LBaaS used in Yahoo! JAPAN.


* **Akira KAMIO** *(Akira Kamio is a OpenStack Engineer in Yahoo! JAPAN's Infrastructure team. Yahoo! JAPAN provides largest portal site in Japan. He mainly development of openstack-based private cloud in Yahoo! JAPAN.He likes server optimization, such as tuning the kernel and qemu/kvm. He has a particular interest in high performance hypervisor architectures.)*

* **YUUTA KINOSHITA** *(YUUTA KINOSHITA is Engineer in Yahoo! JAPAN's Infrastructure team.)*
