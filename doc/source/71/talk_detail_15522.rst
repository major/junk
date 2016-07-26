Why should I consider a converged architecture for my OpenStack cloud?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The typical approach to architecting an OpenStack cloud deployment separates the deployment of the control plane of the cloud onto dedicated server infrastructure, providing physical separation from storage and compute services providing resources to tenants of the cloud. This approach has some limitations in terms of flexibility, fault tolerance and scalability. The Ubuntu OpenStack converged cloud architecture treats the control plane of the cloud as a discrete set of services. By spreading those services as far and wide as possible (including on storage and compute servers), we can achieve an high level of resilience, improve fault tolerance and increase the scalability of the individual components of the control plane an OpenStack cloud with no ‘special place’ for control plane services.


* **James Page** *(James as been involved in Open Source software since 2000, evangelising and delivering the use of Free and Open Source technologies in a major UK bank. In 2010, James discovered Ubuntu and became involved in both the development of Ubuntu and shortly afterwards OpenStack. James is part of the team responsible for delivering and supporting OpenStack as part of every Ubuntu release and for the Juju Charms for OpenStack, the best way for deploying and managing OpenStack deployments on Ubuntu at any scale.)*
