Zuul + Ironic: Automate you Lab as Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Zuul manges Openstack infrastructure workflows and OpenStack Ironic is baremetal service. In our team (100*X), we are deploying Zuul and using FusionSphere (Huawei OpenStack with baremetal service) as CI cloud in each lab or a group of racks.  In our labs, our business is testing FusionSphere (Huawei OpenStack) itself with different scenarios. It looks like community running its infrastructure on OpenStack public clouds, which means we are testing Cloud on Cloud. The difference or the challenge is that vm service is far from enough. We need strong baremetal service to run complex real deployment and mange devices other from physical servers, switches. And we have face more design points on baremetel cloud, such as affinity/anti-affinity, group provision ability etc. Currently, we don't have a 100% good sulotion yet, but we could share what we have thought about and current difficulties. Futher, those experiences are also helpful for the datacentor automation.


* **Zhenguo Niu** *(Software Engineer, working on the OpenStack Bare Metal and Dashboard services, contributing to openstack as Horizon core member, involving in Ironic, Nova, etc. As an OpenStack contributor for Huawei, Zhenguo is responsible for developing projects and features from inception to conclusion in OpenStack, driving contributions on behalf of the internal development team, acting as an interface toward OpenStack, promoting needed architectual changes required for our projects.)*

* **Kun Huang** *(Kun has been working on cloud computing 5 years. He has great experience on open source contributing, performance analysis and continuious integretion. And also he is core reviewer in rally team. Kun was in UnitedStack and he majored in OpenStack Swift, designed and developed early version of boot system of UOS 1.0. After joining Huawei, Kun firstly was invoived in designing cloud image service and help initialize OPNFV team. Currenetly Kun is leading CI&CD team of Cloud OS and trying to build high automated infrastructure.)*

* **wang hua** *(As an OpenStack contributor from Huawei, Hua Wang is responsible for upstream development. Now he is focused on Magnum and the integration of Container and OpenStack. Previously he participated in Huawei FusionSphere OpenStack and has experience in Nova and Glance.)*
