Virtual Machine HA on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many workloads in today’s datacenters are like pets. Their lifespan is in years; they run mission critical service that must be up 24x7. Modern, cloud native applications are designed to tolerate failures. The cloud methodology encourages Cattle approach which treats VMs as commodity. In the near future Pet workloads will coexist with Cattle due to many reasons - (1) During the transition from a datacenter environment to the cloud, a mix of workloads prevail. (2) Legacy applications cannot be easily converted to cloud paradigm. Given the state of enterprise workloads, Virtual Machine High Availability (VM HA) is a must have capability.In the OpenStack community, HA solutions typically deploy Pacemaker with Corosync. At Platform9, we chose Consul to implement a VM HA solution. We found it is easy to adopt and scalable. In this talk we present this feature, experience of running Pet VMs with HA in production and the metrics used to measure effectiveness of VM HA.


* **Sachin Manpathak** *(I lead core openstack projects at Platform9 such as Nova, Cinder and Keystone. In the past, I was an engineer in  VMware Resource Management group responsible for Storage DRS and Storage IO Control. I am passonate about Cloud, Resource Management, Storage and Containers.)*
