Magnum and Ironic Integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running containers on bare metal hosts is of interest to some use cases and workloads.   We have integrated Magnum with Ironic for our internal project.   During this integration, we encountered Nova scheduling race condition that slowed down the provisioning.  We also found limitation on current Magnum bay model which restricts our choices for hardware.   In this talk, we will share how we integrated Magnum with Ironic, what Ironic features such as node inspection and secure boot that we used to automate configuration and provisioning of Magnum bay for Kubernetes cluster, what issues and what Magnum bay model limitation we have encountered, and the enhancement blueprints that we have submitted.  We will also talk about Ironic features which are still work in progress that will enhance Magnum and Ironic integration.  Lastly, we will give a demo of this work.


* **Wan-yen Hsu** *(I am a distinguished technolgist at HP Enterprise.  I am working on Ironic, Magnum and container orchestration engines.)*

* **Ligong Duan** *(I am a project manager at HP Enterprise. I work on Magnum and Ironic integration.)*
