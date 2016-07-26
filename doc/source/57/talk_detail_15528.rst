OpenStack & VMware heterogeneous virtualization practice in China Mobile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We can benefit from heterogeneous virtualization, firstly we had large batch of existing VMware resources in our company, we want utilize them with KVM together, secondly vm in VMware can take advantage of HA, DRS and other advance features which had been proved stable and reliably. The presentation will introduce our works and experiences in heterogeneous virtualization, consists of three parts:Firstly we will explain how to manage ESXi network without VMware NSX. We developed two Neutron ML2 mechanism drivers for ESXi standard vSwitch and DVS, and these drivers supports VLAN network mode which is sufficient in our private cloud. Secondly we will introduce enhanced features for our customers. For example, VMware instance live-migration, vm clone, vm snapshot. We will introduce our design method. At last, we provide a method about importing VM from vSphere. We will also cover the following topics in detail, getting VM info from vCenter, and synchronize these infos to OpenStack.


* **Gangyi Luo** *(Engaged in OpenStack related work since 2014 and specialized in Nova, Ceilometer and OpenStack high availiability. )*

* **Dongcan Ye** *(Dongcan Ye is a software developer in AWcloud, now is responsible for OpenStack integrated VMware and Neutron.)*

* **Jialong Zhang** *(Jialong Zhang is a software developer in AWcloud, now is responsiblefor OpenStack Nova development.)*
