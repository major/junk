How to troubleshoot a highly available OpenStack Cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It can easily become very complex to efficiently troubleshoot a highly available OpenStack cluster. OpenStack components, such as messaging services, load-balancers, and databases, need to be configured properly and tuned for optimum performance. Post-deployment, issues which arise need to be efficiently identified and resolved. Future deployments should benefit from lessons learned during troubleshooting. Throughout this session, we will discuss some of the more common issues which administrators encounter in their high availability deployments, how we learned to troubleshoot them, what the root cause was, and how we arrived at the right solution. Some of these problems are related with scaling load balancers that sit in front of API services, scaling rabbitmq message bus, issues related to MariaDB + Galera, and pacemaker fencing.


* **Andreas Karis** *(I am passionate about all things related to networking, to Linux and to the cloud. Currently, I am  specializing in all aspects of OpenStack and particularly Neutron.)*

* **Jack Waterworth** *(I work with Linux and I do what I love.  I have experience in High Availability cluster including OpenAIS, Corosync, and Pacemaker. Ive spent a lot of time supporting all aspects of Storage, including configuration and troubleshooting on host, fabric, and backend against arrays from NetApp, EMC and many others. I am currently specializing in all aspects of OpenStack and Ceph Cloud Storage. I specifically provide OpenStack support for all components of the stack, including Horizon, Neutron, Cinder, Glance, Nova as well as the supporting software such as MariaDB/MySQL with Galera, MongoDB, HAProxy, RabbitMQ and Pacemaker.  Due to the nature of the cloud, a lot of support includes collaborating closely with the OpenStack development engineers.)*
