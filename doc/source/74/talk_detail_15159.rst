Cinder Always On - Reliability And Scalability Guide
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder (OpenStack Block Storage project) can be found in >80% of OpenStack deployments. Configuring it to be robust, resilient and fast is important. However considering its high customizability, such as choice of deployment architecture, volume backend or backup backend, an always on Cinder is not a simple goal to achieve. In this talk we will explain how Cinder can be deployed in ways guaranteeing increased reliability and performance, as close as possible to "always on". We will walk you through latest innovations that are letting you keep your control plane and data plane up during upgrades, increased load or when experiencing breakdowns. These features include: cinder-volume service in A/A mode rolling upgrades support volume replication volume migration We will also share insight on the improvements in these matters that are planned for the future cycles.                  


* **Michał Dulko** *(Michał is software engineer working at Intel, engaged in OpenStack-related activities since Folsom release. Starting from Newton cycle he is serving the OpenStack community as a core reviewer in Cinder, where he is focused on control plane availability, scalability and upgradability. His professional interests are HA solutions, cluster management and building reliable distributed systems.)*

* **Gorka Eguileor** *(Cinder Core and Senior Software engineer at Red Hat contributing to OpenStack's Block Storage Service. Previous experience includes Artificial Intelligence, Embedded Systems and High Availability mobile payment platforms. Besides leading the effort to support Active-Active High Availability configurations in Cinder, he's also been working during the N cycle on removing DB access races on API nodes, optimizing DB queries on most common operations, and making improvements to the Rolling Upgrades and Microversions mechanisms in Cinder.)*
