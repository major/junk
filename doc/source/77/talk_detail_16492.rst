Can we use OPNFV Doctor framework in OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In telecom operation, fault management is essential to achieve high service availability. This is typically realized by a monitoring system which is specific to hardware and application as they are tightly coupled before introduction of NFV. To realize the same network service availability in NFV, we have to make sure to have the same level of monitoring functionality in a cloud type platform. The OPNFV Doctor project focuses on this requirement and has proposed missing features to the OpenStack community. We present our implementation of a fault management framework for NFV realized by different OpenStack services and comprising various exemplary use cases of compute/network/storage resource faults. This talk also provides insights on how to adopt this framework to various types of deployment models and operational policies utilizing Congress and Vitrage. The results of multiple PoCs will be shared to show the performance of this framework in particular w.r.t immediate notification.


* **Ryota Mibu** *(Ryota Mibu has been working on integrating cloud technologies to telecommunication platform form 2012 in NEC. He has been contributing OpenStack projects, including Neutron, Ironic and Ceilometer. He is the Project Lead of "Doctor" which is one of the OPNFV projects and focusing on building a framework for fault management for high availability of Network Services on top of virtualized infrastructure.)*

* **masahito muroi** *(Masahito Muroi is a software enginer in NTT. He is now working as a cloud architect for NTT's public/private cloud, and also working as a core developer of OpenStack Congress Project and Masakari. He's started to join OpenStack Community and develop NTT's cloud with OpenStack since Diablo release.)*

* **Ohad Shamir** *(Ohad is a product manager in CloudBand, Nokia. In his role, Ohad is leading Analytics and monitoring for the CloudBand NFV product line and he is also responsible for open source activity in CloudBand. Ohad is driving Vitrage, an official OpenStack project, initiated by CloudBand, for root cause analysis, deduced alarms and states.)*
