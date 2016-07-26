Hiding in the Clouds: Secret Management with OpenStack Barbican
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We recently packaged OpenStack Barbican for RDO(RPM Distribution of OpenStack) and SOC(SUSE OpenStack Cloud), and created puppet manifests and chef recipes respectively to deploy it. We would like to share our experience doing this and the various problems we tackled in the process. Barbican is used by Cinder, Swift, LBaaS, Magnum and other services for various use cases which require the storage and retrieval of secrets. We will share our experiences in setting up these use cases and provide heat templates to allow others to easily replicate our results. Ultimately, attendees will get an idea of how to securely use barbican in a full-fledged OpenStack Cloud environment.


* **Sayali Lunkad** *(I started with OpenStack almost three years ago as an Outreachy intern and have been contributing to OpenStack since. I have worked on horizon previously. I have conducted various OpenStack workshops and frequently speak at events and meetups. Currently working as a developer at SUSE Linux.)*

* **Johannes Grassler** *(Johannes Grassler is an active OpenStack developer, specializing on Heat but also dabbling in other projects occasionally. He currently works as a Cloud Developer for SUSE Linux GmbH. Before that he used to work at SysEleven GmbH, where he built, operated and used an OpenStack cloud since 2014. He has been an an active member of OpenStack DACH e.V., a German OpenStack user group since its inception in 2014.)*

* **Ade Lee** *(Ade works for Red Hat, and has been involved in Dogtag development (and its integration into FreeIPA) for a number of years now. He has worked to integrate Dogtag and FreeIPA with Openstack, and is a core contributor to the Barbican project. Most recently, he has worked on puppet modules to deploy Barbican in Triple-O and RDO.)*
