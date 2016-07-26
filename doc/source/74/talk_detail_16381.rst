Leveraging OpenStack-Ansible to deploy the Nova-LXD compute driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many ways of running containers in an OpenStack environment.  Many deployment scenarios run containers inside of instances.  However, containers can also be deployed outside of instances, and one method of doing that is by using the nova-lxd compute driver.  OpenStack-Ansible is a community-driven way to deploy an OpenStack cloud, including a mixed hypervisor cloud utilizing the new nova-lxd compute driver.  LXD allows the resource and performance benefits of application containers, without sacrificing core system services such as logging, or requiring application rewrites to utilize existing software.  In this talk, we will show users how to configure OpenStack-Ansible to deploy a mixed hypervisor environment using KVM and LXD.


* **Michael Gugino** *(Michael Gugino works for Walmart on their Cloud Operations team at in Reston, Virginia, USA. He has knowledge and experience with Python, Ansible, Puppet, C, MySQL, RabbitMQ, NoSQL, and of course, Linux. Michael contributes regularly to OpenStack-Ansible.)*

* **Jimmy McCrory** *(Jimmy McCrory is a Senior Cloud Engineer with Walmart's Global eCommerce division. He was a member of the team responsible for the deployments of Walmart's first production OpenStack clouds, and now has 3 years' experience deploying and operating large production OpenStack environments.)*
