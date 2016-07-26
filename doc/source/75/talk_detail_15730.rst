Trust-based delivery of sensitive material to a Virtual Machine or Docker Container
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you ever wondered how to validate that that a VM or the container being launched is trusted and secure before you push secrets and sensitive content to it?   Not only that, what if we can bind secrets so that they are only accessible on the specific server on which the container is running?   This turns out to be one of the key pain points and requirements for container developers.  This can be done today using Intel TXT, Intel Cloud Integrity Technology and TPMs on hardware. In this session Intel and IBM Security Architects will walk through the solution architecture with OpenStack and CloudFoundry and demonstrate how it is possible to:  Verify the integrity of the Docker platform on which the container image is being launched Verify the integrity of the container images being launched Release the secrets and keys based on the verification of this integrity Wrap the keys/secrets with the host platform TPM binding key so only that platform can release the keys/secrets


* **Raghu Yeluri** *(Raghu Yeluri is a Principal Engineer and lead Security Solutions Architect in the Data Center & Cloud Products Group at Intel Corporation with focus on virtualization and cloud security usages, solution architectures and technology initiatives. In this role, he drives security solution Pathfinding and development to deliver hardware-assisted security solutions that enable deep visibility , orchestration and control in multi-tenant Clouds.  Raghu is a regular technical speaker at conferences like OpenStack Summit, Intel Developer FOrum, VMWorld, on trust and security in Cloud computing, boundary control and Geo-fencing for sensitive workloads with OpenStack, and trusted docker Containers.  )*

* **Travis McPeak** *(Travis enjoys securing and breaking security of software equally.  He is a firm believer in the necessity of intelligent security automation.  When not working on security and software he enjoys snowboarding, travelling, and consuming quality food and beer.)*
