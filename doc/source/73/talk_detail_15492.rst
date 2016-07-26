Openstack swift object storage simulator for scale test using Containers/VMs.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack Swift has ability to scale to a huge object store but to test this with large no of physical nodes can leads to a higher cost constraints. In order to overcome the dependency on the physical nodes and HDD to configure Swift we deployed Swift proxy and object nodes on VMs/containers running on any hypervisor/docker-host. Thus we can have a large number of proxy and object nodes having required no. of virtual disk drives (by adding external storage from any storage array to the hypervisor/host ) to meet a scale of required object storage. We will cover the following:• How to deploy and configure proxy and object node as a VM/container• How to clone that VM to create required number of proxy and object nodes.• How many proxy and object nodes on a single baremetal hardware can be deployed and cost savings• Automation to deploy swift services on cloned VMs – Deploy hundreds of swift nodes within minutes• Test results and comparisons with physical nodes.


* **Ankit Goel** *(I am working as test engineer in Helion openstack on swift scale (Object storage)  )*

* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*

* **Raja Sekhar Reddy Juturu** *(I am a QA in HPE working on Helion openstack career grade and telecomm.solutions.)*
