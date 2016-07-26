Swift Deployment Automation in Cisco Intercloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Cisco Intercloud Storage team has worked with SwiftStack to build Swift deployment automation using SwiftStack and a variety of open source tools. The automation includes hardware provisioning, deployment of Swift, integration with various systems like Keystone, monitoring, etc, as well as unit-tests at the end. The automated workflow leverages Ansible to wrap Kickstart and Python (SwiftStack python modules) scripts for deployment and configuration, creating a repeatable, auditable and consistent process. The deployment takes into consideration different hardware profiles and cluster designs and will dynamically adjust parameters for various environments. It can be run repeatedly and the same process is leveraged for upgrades. At the end, after a Swift cluster build or upgrade, unit-tests are run against the cluster to verify that the system is working. The entire process of deploying/upgrading can be monitored/reviewed through the build pipeline GUI and/or through system logs.


* **Johnny Wang** *(Johnny is currently a Sr. Cloud Storage Engineer in Cisco Inter-Cloud and as the leader of Object Storage architects.  Prior to joining Cisco, he spent four years building a File Sync and Share system base on Object Storage in Hewlett Packard Enterprise after spending over nine years in a variety of design and development engineering and manager roles in Quanta Computer Inc. Johnny holds a BS and MS in Management Information System and is working as Ph.D candidate in Computer Engineering from Santa Clara University in California.)*
