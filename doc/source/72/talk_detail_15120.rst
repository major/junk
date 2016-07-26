Distributing OpenStack Networking Across Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scaling OpenStack in many cases involves operating multiple OpenStack regions or using Nova cells. One of the significant network challenges faced by operators is how to connect workloads in this distributed environment. This is also a challenge encountered when attempting to operate a hybrid cloud with a mix of on-premise and offsite resources. Deploying multiple OpenStack instances and connecting them together presents unique networking challenges. Floating IP's are a common and workable solution for connecting workloads in these environments. However, floating IP's can also be an inefficient way to connect workloads.In this session we will introduce a solution for connecting multiple OpenStack deployments using BGP EVPN. We will discuss how it integrates with features already available in neutron such as address scopes, DVR, and BGP dynamic routing. We will also discuss the current state of development of this solution and what functionality to expect in future releases.


* **Steve Ruan** *(I am senior software engineer of IBM cloud networking service, focus on the OpenStack based hybrid cloud solution. I used to develop routing appliance in IBM SDN-VE since 2014, then developed in the OpenStack Neutron community especially on neutron-dynamic-routing project and developed in the OVN community. Before that I have more than 8 years in development of hardware switch and router.)*

* **Ryan Tidwell** *(Ryan Tidwell is a contributor to the OpenStack Neutron project and has been deploying and tinkering with OpenStack in various roles since the Diablo release of OpenStack.  Ryan has been working at HP (now Hewlett packard Enterprise) since 2008.  He is well-versed in developing manageability tools for systems administrators and OpenStack operators, building SDN controllers and applications, and currently contributes to OpenStack's Neutron project.  Raised in Northern Colorado, Ryan has a B.S. and M.S. in computer science from Colorado State University and the University of Colorado respectively.  He currently resides with his family in Roseville, CA.)*

* **Vikram Choudhary** *(Working with Huawei Technolgies India Pvt Ltd. Have around 7.5 years of experience in routing domain (protocols like RIP, OSPF and BGP). Have around 1.5 years of experience in openstack. Mainly contributing for neutron in openstack)*
