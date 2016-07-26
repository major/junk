Perform schema rolling  upgrades in just one release cycle
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Reliable Openstack deployment should be as close to 100% availability as possible and always up to date with the latest release. To achieve this, during an upgrade services should be stopped and replaced with new one with noAPI downtime. In projects like keystone, glance or neutron this means keeping compatibility of DB schema between releases. The complexity of maintaining this compatibility, while keeping performance and security on a high level, is a hot topic in the community. Current approach in projects like nova or cinder requires keeping the data compatibility for 2 or 3 releases. In this presentation we want to show solutions, how to reduce the data migration time period to one release cycle. This would reduce the code complexity and performance overhead in database layer.


* **Artur Korzeniewski** *(Artur Korzeniewski is a software engineer at Intel, currently working in Neutron community on subjects related to upgradability and HA of services. He is Neutron Upgrades team member, dedicated to improve the process of upgrade. Before joining the Neutron team, he was closely coupled with OpenStack since Diablo release, working on resource scheduling and compute assurance. Artur likes new challenges, path-finding and designing solutions from scratch. He is the Python language and networking fan. Artur has master degree in IT from Gdańsk University of Technology in Poland.      )*

* **Grzegorz Grasza** *(Working at Intel on OpenStack from 2014, contributing in High Availability and Upgrades areas accross many projects. Previously developed and run network level monitoring and filtering security applications in WheelSystems.com and SurfSafe.com. Experienced Python and Erlang programmer, started at Grono.net, which was the largest deployment of Django and Python in 2005, later worked as a Solutions Architect at SensiSoft.com, making classified ads vertical portals for large UK, US and South Africa publishers.  )*

* **Hemanth Makkapati** *(Hemanth Makkapati is Senior Software Engineer at Rackspace. He primarily works on Rackspace's Cloud Images product that is based on Openstack Glance. Hemanth is a Glance core and has been involved with Openstack since Havana. He is also a part of the Openstack Innovation Center where his current focus areas include rolling upgrades and improving configuration for Glance. In his spare time, Hemanth plays badminton and follows soccer. YNWA!)*
