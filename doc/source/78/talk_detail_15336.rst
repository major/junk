BGP dynamic routing within OpenStack environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

BGP Dynamic routing was introduced as a Neutron service plugin in M release. It support advertising tenant prefix and FloatingIP host routes to external devices, such as Router, L3 Switch, Router reflactor and vRouter. In N release, it had been split out from Neutron as a subproject under Neutron Staduim.This topic will introduce how to use it within OpenStack.1. How to deploy it with devstack, and how to test in generally.2. How to deploy and meet your for different requirments in production deployment.3. Introduce the roadmap of BGP Dynamic routing project.- Split out the code and setup a new project in N release - Complete the more functions which used in project.- Need access another powerful driver for implementing more BGP functions.4. Divergent thinkingSupporting for mutil-AS in internal Openstack, the internal tenant could exchange their self routes with other tenants or external devices. What should we do next?  


* **hanzhang shi** *(Expertise in Networking domain and active contributor/follower of Openstack Neutron)*
