Service VM - speed up testing with containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Octavia (LBaaS project) use Service VM ideology. The project is using Nova to boot virtual machine responsible for serving our service - load balancer in that case. Testing projects like this require a lot of resources and time because on virtualized environment (gate) we're booting next virtual machines using Qemu as the hypervisor. Because of that, we're landing in nesting virtualization hell. Performance is horrible so testing the functionality of project is taking hours. In Octavia project after splitting tests into smaller chunks results with the testing time equal to around 1.5h. Because of that, there is the idea to use containers - LXD especially - to host and test that kind of projects and will be presented how to do this. What problems we had, identified bugs and how to use this technology in other projects.


* **Lubosz Kosnik** *(Lubosz Kosnik is a Cloud Software Engineer in OpenStack Innovation Center. He was responsible for a contribution to Neutron project and after a few months, he switched to Octavia (LBaaS) project where he is responsible for enabling containers to be used to serve Amphorae - image responsible for serving load balancers. Also, he was working on OpenStack Reference Architecture where he learned about how to operate and manage OpenStack cloud.)*
