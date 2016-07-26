You Got Your Cloud in My Mainframe!  Confessions of a 3rd-Party CI Operator & Enterprise Consultant
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We've seen patterns emerge in mainframe cloud deployments, and from running our Third-Party CI system.   OpenStack on z/VM runs the hundreds of Ubuntu, Red Hat, and SUSE VMs in the LinuxONE Community Cloud ... and its OpenStack controller... on a single system.   Our CI system runs 20 tempest runs in parallel, with 4 x86 blades all pounding away at a single system.   Our enterprise users include major banks, insurance companies, payroll processors, healthcare providers, and IT service providers.   We'll share things we've learned along the way about playing nice with what-is in the enterprise, scaling compute nodes, and images that go Bump! in the night.


* **John Arwe** *(I've grunged around in the mainframe kernels (z/OS SRM/WLM mostly, recently a bit of z/VM and zKVM) for many years, and took a wide detour doing standards and open source work (W3C SML and LDP, OSLC, OASIS, DMTF, Eclipse, REST APIs, Linked Data) in the middle. Lately I've been schizophrenically focused on both the z/VM nova CI system and architecting/debugging client deployments of the OpenStack and hypervisor back-end components.)*

* **Ji  Chen** *(Ji Chen is a software engineer in IBM who focuses mainly on z/VM system management (s390x arch).  His daily work includes mainframe z/VM virtualization enablement on OpenStack, including the total stack of z/VM system management software such as SMAPI, xCAT, OpenStack enablement components, etc.  He is an active nova upstream community contributor.  Before working in IBM, he worked in Samsung and UTStarcom majoring in embedded system development such as embedded DBMS, operating system , file system etc.)*
