Adaptive Monitoring and Auto-recovery of Openstack services in kolla
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kolla is helping to make each service running independently.when some container killed, currently there is a difficulty in getting the status of the service and container and manual intervention required to start the container which creates a downtime in the whole clusterThere is 3 ways we can monitor the kolla services1. Reactive:This kind of monitoring can be achived by the orchestration engine updates the monitoring system2. Proactive:This kind of monitoring can be achived by adding precautionary measures for the known issues, where, if the issue occurs it immidiately starts the precaution to eradicate the fault.3. Adaptive:This is better suited for monitoring a frequently changing system like docker containers, as it can adapt itself to the micro services that get intorduced into the containers. Now the question is “Is the adaptive montoring a full solution to the abovementioned challenges?"- We need solutions at different levels of openstack services and containers and hypervisor


* **Satya Routray** *(Open-source enthusiast who loves new technologies and lookout for areas to innovate. Been working in virtualization and cloud based technologies for the past several years. Previously worked on various components of Openstack such as Compute, Neutron, Cinder, Swift, Docker. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Presented on Monitoring Docker and Dockerised applications in 2015 OpenStack Tokyo summit. Presented on Optimising NFV service chains on openstack using docker in 2016 Openstack Austin summit Presented on Multenancy for docker container with keystone in 2016 Openstack Austin summit)*

* **Don Nalezyty** *(None)*
