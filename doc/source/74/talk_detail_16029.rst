How to quickly build a multi-hypervisor dev/test environment on a single node using virtual computes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack today supports a variety of hypervisors such as KVM, ESXi, Hyperv, etc., as compute nodes. Devstack is the primary choice for developers to bring up a single node dev-test environment. A single node devstack supports only one kvm. Additional physical nodes are required to setup a multi-hypervisor environment. To address this issue, we are proposing a solution using nested hypervisors on ESXi which will instantiate multiple hypervisors on a virtual machine. We have developed an automation tool, which deploys devstack on a virtual machine, and multiple virtual hypervisors on separate virtual machines. A multi hypervisor dev-test environment can be instantiated on a single node by executing a single script. In this presentation, we will cover the following:• How to create a nested hypervisor using ESXi• How to use nested hypervisors for nova compute and neutron agents• Demo on how to run the tool and bring up a multi hypervisor environment


* **Siva Subramaniam M** *(I am working in Hewlett Packard Enterprise for the past 4 years.  Worked on products based on openstack, mainly involved in scale and performance testing using rally, functional testing.  Have worked on CI tools such as jenkins, and written various automation for the CI processes.)*

* **Balaji Ramamoorthi** *(6.5 Years of Experience with Virtaulization, Storage Currently working in Hewlett Packard Enterprise (HPE) as Helion Openstack QA  Scale & Performance Engg )*

* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*
