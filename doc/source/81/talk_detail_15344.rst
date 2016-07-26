Deploy container clusters on baremetal with tenants isolated
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker and Containers are taking the application development world by storm, but with all of their benefits there are some limitations and challenges. One key challenge is security between containers, especially when those containers are in different security zones. In areas like Financial Services and Medical Records, companies have widely different security requirements. Today there are no solutions within the Docker ecosystem to fulfill those security requirements while maintaining performance and scale. We will demonstrate a solution to this problem using OpenStack Magnum, Ironic integration, and Neutron Networking with networking-generic-switch plugin. This solution uses: – A Neutron extension to provision ports on generic switch – An Ironic extension to coordinate the port provisioning – Magnum to deploy the container clusters This allows deployment of secure, flexible, scalable bare-metal clusters.


* **wang hua** *(As an OpenStack contributor from Huawei, Hua Wang is responsible for upstream development. Now he is focused on Magnum and the integration of Container and OpenStack. Previously he participated in Huawei FusionSphere OpenStack and has experience in Nova and Glance.)*

* **Hongbin Lu** *(Hongbin is currently a Senior Software Engineer in Huawei Technologies. He is serving as the Project Team Lead (PTL) for OpenStack Magnum project in Newton release cycle. He is also the founder/core reviewer of the Zun project (a new container service for OpenStack). His expertise including container related technologies, application deployment and management, and cloud computing.)*

* **Zhenguo Niu** *(Software Engineer, working on the OpenStack Bare Metal and Dashboard services, contributing to openstack as Horizon core member, involving in Ironic, Nova, etc. As an OpenStack contributor for Huawei, Zhenguo is responsible for developing projects and features from inception to conclusion in OpenStack, driving contributions on behalf of the internal development team, acting as an interface toward OpenStack, promoting needed architectual changes required for our projects.)*
