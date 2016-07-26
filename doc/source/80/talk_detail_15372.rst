Unified Command client and SDK for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStackClient (OSC) is an unified command client for OpenStack. It has implemented 5 core projects‘ basic commands, and provides a plugin mechanism for other clients to work with it. OpenStack SDK is a library providing APIs for those apps who want to communicate with OpenStack core services. Using OSC and SDK will avoid unnecessary dependency, and obtain well organized commands and APIs. We have made great progress in these two projects (600+ commits) in 2016. Keystone has deprecated its command client. Nuetron is migrating from Neutron client to OSC. Nova has clarified that Nova client will be deprecated, and suggested to enhance OSC. 17 other projects have implemented their clients as OSC plugin. We also integrated SDK into OSC to implement commands. OSC PTL Dean shared why we need unified client during the keynotes in Austin, but didn't give much detail. Now, many developers started to use OSC, and joined OSC and SDK community. So, it's time to know the inside of OSC and SDK.


* **Chen Tang** *(Tang Chen has been a Linux kernel developer since 2012, and mainly worked in memory management, KVM, qemu and libvirt communities. He started to work in OpenStack community since the beginning of 2015, and became a core reviewer of OpenStackClient (python-openstackclient). He is now working on Nova and OpenStackClient development.)*

* **Rui Chen** *(RuiChen is a OpenStack upstream developer team leader at Huawei, he has joined into OpenStack community since the Icehouse release. RuiChen is active contributor in OpenStack development mainly in OpenStackClient, Nova and Congress. Follow RuiChen on his blog, http://kiwik.github.io)*
