Give me Cinder volume for containerized apps on top of baremetal node!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Storage is an essential part of any computing systems. In OpenStack, Cinder provides persistent storage, but currently, Ironic only supports integrated storage and is not available Cinder volume as an external storage. By utilizing external storage at Ironic, user can run enterprise workloads on bare metal servers to ensure stable and predictable performance, and better data consistency etc. Also this can be applied to containerized apps on top of baremetal node. Enterprise workloads such as Database, fail over with state-full application on container need persistent and stable storage. There are two ongoing effort and one lacking feature to enable volume support for containerized apps on baremetal. - [Ironic] Cinder volume support- [Magnum] Ironic support- [Magnum] Volume support on baremetal node(not started) In this session, we explain recent updates of Ironic and Cinder integration effort and then discuss Ironic support for Magnum and volume support for container.


* **Mitsuhiro Tanino** *(Mitsuhiro Tanino is a software engineer who has been working for Hitachi since 2004 and a principal software engineer Hitachi Data systems since 2014. He has experience about development of virtual machine manager for heterogeneous cloud systems and RAS features for KVM virtual environments. His current working area is Cinder and Nova, he is enhancing reliability and stability features to achive Mission Critical systems requirements.)*

* **Satoru Moriya** *(Satoru is Researcher of Cloud management at Hitachi. Satoru has 10 years experience in software industory from hypervisor, linux kernel to OpenStack. Satoru currently focuses on improving bare metal server management in OpenStack, in particular, Ironic and Cinder integration to support boot from volume in Ironic.  )*
