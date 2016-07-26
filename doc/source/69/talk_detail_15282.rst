Introduction to OpenStack's Components Architecture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is the leading Open Source Infrastructure as a Service (IaaS) platform formed by more than 50 interrelated components, and understanding the inside of a component can be a daunting experience for new contributors.In this talk we'll have a look at the internal architecture of the main OpenStack components, showing their similarities and disparities, and the common Oslo libraries used, providing solid group for new contributors that start looking at the code. As part of the OpenStack ecosystem, these components are not isolated entities, so we'll briefly go over the communications between components as well. By following from end to end a complex flow requiring communication between components, and explaining the weakest points where things could go wrong, the importance of having this full picture will be shown. In this talk we'll not go over the conceptual architecture of OpenStack itself, or cover all the different components.


* **Gorka Eguileor** *(Cinder Core and Senior Software engineer at Red Hat contributing to OpenStack's Block Storage Service. Previous experience includes Artificial Intelligence, Embedded Systems and High Availability mobile payment platforms. Besides leading the effort to support Active-Active High Availability configurations in Cinder, he's also been working during the N cycle on removing DB access races on API nodes, optimizing DB queries on most common operations, and making improvements to the Rolling Upgrades and Microversions mechanisms in Cinder.)*
