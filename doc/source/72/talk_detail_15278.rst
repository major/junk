How Scalable is OVN-powered OpenStack:  A Cloud Operator’s Perspective
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open Virtual Network (OVN) adds native support for virtual network abstractions. OVN is designed to be more scalable than the Neutron OVS implementation. As it reaches it's first release, work is underway to prove it's scalability in a large scale deployment. We present our methodology of building a CI/CD pipeline that helps OpenStack cloud operator to quickly identify performance and scalability bottlenecks in OVN, and to decide on the adoption of latest patches based on experimental results. Our solution deploys emulated compute nodes and real control plane setups, by containerization of OVN components, fake OVN chassis, and the rally-ovs extension. We will share the latest results from our experiments, as well as how these results help improve the overall scalability of OVN and OpenStack network functions powered by it. We also talk about how these results are enabling us to verify commits by integrating the work into the OVS/OVN continuous integration setup using travis-ci.


* **Hui Kang** *(Hui is a research staff member at IBM T.J. Watson Research Center. He is currentlywith the cloud infrastructure team, focusing on OpenStack, Docker, Linux kernel, etc. Hui has contributed to several open source projects, including openstack/kolla, Docker, CRIU, and ovn-scale-test. He also enjoys hacking OS kernel and learning hardware techniques.)*

* **Kyle Mestery** *(Kyle is a Distinguished Engineer and Director of Open Source Networking at IBM. He leads a team focused on Open Source networking at scale. Kyle is also a member of the OpenStack Technical Committee, and the former PTL of OpenStack Neutron for the Juno, Kilo, and Liberty cycles. Kyle lives with his wife and kids in Minnesota.)*

* **Lei Huang** *(Lei huang is currently an MTS 1 Software Engineer in ebay's Cloud IAAS Team, focusing on SDN for ebay private cloud. He created an ovs scalability test framework based on OpenStack/Rally. He is currently involved in a routed network solution at ebay.)*
