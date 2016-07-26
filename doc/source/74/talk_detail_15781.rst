Rolling upgrade of bare metal Cloud (Ironic)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic is now widely used to manage bare metal provisioning in data centers, but large-scale data centers have multiple ironic services (conductor/api) running in a cloud. This causes a serious problem when operators try to upgrade the cloud to the latest version: how to upgrade the cloud with minimal downtime? Because at the moment, ironic only supports a cold upgrade, whereby operators upgrade all ironic services simultaneously, which breaks the service and is time consuming. We propose a rolling upgrade solution to ironic in order to support upgrading ironic services with minimal downtime. In this solution, there is no need to take down all the ironic services and upgrade them at the same time. Operators are able to upgrade ironic services one by one with the rest of the services still available. This provides a better experience for users and operators of the cloud.


* **Lin Tan** *(Software Engineer, Intel)*
