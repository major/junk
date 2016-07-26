Manila share data does not simply move and protect itself, oh wait, it does!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Typical datacenters comprise of products from multiple storage vendors, and usually no two products behave the same. Thus, operators often rely on complex scripts and tools to move data, provide high availability and protect it from disasters. As a multi-storage abstraction, OpenStack Manila is invested in addressing such requirements through a consistent API to avoid vendor lock-in. We have made tremendous progress with features such as Migration and Replication, and a new service that can handle data plane operations and assist in moving data between shared file systems. We enhanced the design of storage availability zones as failure domains and allowed for them to be consistent with Nova and Neutron availability zones. We will discuss use cases and demonstrate the use of these features while indicating best practices and troubleshooting tips that might come in handy when using both these features in your data center. We’ll also discuss the roadmap for these features.


* **Rodrigo Barbieri** *(Rodrigo is a core reviewer in Manila since Mitaka release, driver developer for Hitachi since Juno release, and a researcher in the field of Fault Tolerance. He is focused on Manila upstream development and has contributed with several new major features, notably Share Migration and Data Service. He started working with OpenStack in Juno release by deploying OpenStack distributions and developing Hitachi storage device drivers for Cinder and Manila projects.    )*

* **Goutham Pacha Ravi** *(Goutham is an active contributor to OpenStack Block Storage and Shared File Systems projects. Prior to OpenStack, he has worked on several projects involving data protection across storage systems. Aside from his code contributions, Goutham spends a lot of his time building cross project synchronization and advocating for user experience and API stability. He is the API working group liaison for the Shared File Systems project.)*
