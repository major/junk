Running virtual machines and system containers on a single compute host effectively
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Since Kilo there is a new hypervisor type “parallels” in Nova brought up via libvirt. It was renamed to Virtuozzo in Liberty while its nova.conf parameter remains the same. Since Liberty there is a new Cinder volume driver called vzstorage. How do these two OpenStack components connect to each other and what benefits do they bring in addition to the most mature and widely used QEMU/KVM hypervisor? If you are interested in running via KVM not only Linux guests effectively but also Windows ones, if you are interested in creating elastic cloud where Virtual Machines can live side by side with System containers, if you are interested in live migration production quatily not only for virtual machines but also for containers, it will be worth visiting the presentaion. I will try to concentrate not on Virtuozzo product itself, but on improvements we are making regarding virtualization in opensource ecosystem in general and OpenStack in particular.  


* **Maxim Nestratov** *(Maxim has been working for more than 10 years in virtualization sphere taking part in building both server and consumer software products. Maxim helped as lead developer to impement key parts of Parallels Desktop for Mac such as memory management, suspend/resume/snapshot features. He played the key role in developing networking engine in Parallels Containers for Windows product. Currently Maxim is a maintainer of Virtuozzo driver in libvirt and he is a lead developer in the team that integrates Virtuozzo stack of products with OpenStack.)*

* **Andre Moruga** *(Andre Moruga is a Director of Program Management at Virtuozzo. He worked at Parallels on Parallels Automation, which is a service delivery platform that helps telcos and service providers to aggregate the cloud services they are offering. Andre has succeeded in driving integration efforts with the products and services that fit into “Infrastructure as a Service” and “Platform as a Service” category.)*
