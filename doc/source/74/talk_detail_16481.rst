Simple Scale Test for OpenStack Control Plane
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scale testing the OpenStack controller with physical or virtual hosts is not always feasible and is bounded by the resources available. In this talk we dive in to the various steps we followed to scale test the Platform9 Control plane with limited resources.With almost every OpenStack project it is possible to create a fake driver that creates the relevant objects either in memory or as simple files on the filesystem. Scale testing control plane using a fake driver allows creation of many hosts that connect and consume the control messages like a real host. This allows evaluating performance of various api processes, messaging queues and databases with thousands of hosts interacting with the OpenStack.Areas that we will discuss may include - enhancements made to fake driver in nova, implementation of similar fake drivers for cinder and possibly neutron. Other aspects of this talk would include performance metrics that we collected running OpenStack under various load conditions.


* **Pushkar Acharya** *(Pushkar Acharya is an early engineer with Platform9 Systems Inc., working on vSphere integration with Platform9 primarily in the nova, cinder and glance. Recently also started working on integrating VMware NSX plugin in neutron with Platform9 OpenStack.)*

* **Sachin Manpathak** *(I lead core openstack projects at Platform9 such as Nova, Cinder and Keystone. In the past, I was an engineer in  VMware Resource Management group responsible for Storage DRS and Storage IO Control. I am passonate about Cloud, Resource Management, Storage and Containers.)*
