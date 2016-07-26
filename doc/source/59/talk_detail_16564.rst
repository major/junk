Towards to an Intelligent Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Intelligent cloud without human intervention is the ultimate goal of openstack. This presentation shares our story of how to achieve it. We are maintaining a cloud for developer usage for totally different purpose: * build server for CPU intensive workload, like andorid build. * openstack development like devstack environment setup, requires huge network bandwidth The trend of workload and users is not predictable, so need add new servers in peak time and remove them when idle. Furthermore, long time heavy work load usually makes server broken, so that we need identify then remove them in the 1st time. We try to use automation, but some steps still requires human intervention. Then we found Watcher, resource optimization in openstack, and defined our own strategies for workload balance & server consolication. Also developed some algorithm based on power/temperature metrics for intelligent management. Finally, our smart cloud runs well without any human intervention.


* **Gang Zhai** *(Gang joined Intel in 2003 as kernel engineer for driver development. From 2005, Gang switched to open source virtualization, like xen/kvm, with interests in VT enabling, live migration, GPU virtualization. In 2014, joined openstack community and mainly focused on telemetry work.  )*

* **Susanne Balle** *(Susanne is a senior Principal Engineer at Intel working on SDI and Cloud architecture and pathfinding. She has been involved in OpenStack since the Essex OpenStack summit. Her latest focus is on Watcher a service to optimize the Datacenter TCO via Data-analytics and ML models for OpenStack and non-OpenStack Clouds.)*
