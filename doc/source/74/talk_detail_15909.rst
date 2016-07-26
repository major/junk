Nginx in OpenStack:  a High Availability Solution for API services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Apache is the default web server to host Openstack API services, which is running well in small-scale clusters.  When a cluster reaches hundreds of nodes and api reach hundreds of concurrent requests,  shortcomings reveals. It cannot handle so many concurrent requests from external. In Qihoo’s production environments, we use Nginx rather than Apache to host API services, such as nova-api, glance-api, cinder-api and keystone etc. Besides, there are different release versions in a single cluster(for example, we are using the Kilo release of keystone, Liberty of nova, neutron etc.). And different versions depend on different package versions.  To overcome this disgusting problem, we use docker to isolate different versions of API services in a single node. With this solution, we get much better performance than ever on our production environment.


* **Xiaohua Yuan** *(Technologist at Qihoo 360. 3 year experience in Puppet-Openstack. Xiaohua Yuan has been working on a series of innovations related with automated operation for large-scale cloud based on OpenStack. Contribution to OpenStack: puppet-nova puppet-trove puppet-cinder)*
