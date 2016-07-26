Elevating Magnum to Production with Cinder and Manila Persistence
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Modern applications are using more and more data, which makes doing rapid development and testing with those data sets difficult and expensive.  For organizations which want to transition to using containers for dev, test, or even production, the prospect of migrating data from Cinder or Manila volumes into something perceived to be more container friendly is daunting.  However, the container orchestrators managed by Magnum, Swarm, Kubernetes, and Mesos, can all take advantage of those volumes directly using the Docker Volume Plugin paradigm. This session will explore how to clone Cinder and Manila volumes, introduce them to the orchestration platforms, and integrate them using the native persistent storage mechanisms for each orchestrator.  This drastically simplifies the process of dev and test for large data sets when the application is run in containers, and further removes barriers to transitioning to Docker for cloud native applications.


* **Andrew Sullivan** *(Andrew has worked in the information technology industry for over 10 years, with a rich history of database development, DevOps experience, and virtualization. He is currently focused on storage and virtualization automation, and driving simplicity into everyday workflows.)*
