How is Ceilometer/Gnocchi scale out?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The utilization data of the virtual or physical resources are very important in data center operations. Once stored persistently, these data could be retrieved for later analysis, such as metering and billing, and could be used to trigger actions when certain criteria are met, such as alarming, etc.  Ceilometer is the service designed to collect those data, and was complained for not scaling very well in its own data store. Gnocchi is the time-series database designed to solve the scale out issues, by working as the data store backend for Ceilometer. In this presentation, we’ll introduce the evaluation work we’ve done for Ceilometer/Gnocchi on how it scales out in typical configurations.  We’ll also give suggestions on how to configure Ceilometer/Gnocchi to make them perform well.


* **Lianhao Lu** *(Lianhao Lu works in Intel OpenSource Technology Center for Openstack. He's currently a core developer for Ceilometer.)*

* **Steve Lewis** *(OpenStack-ansible core developer)*

* **Sumant Murke** *(s/w engineer)*
