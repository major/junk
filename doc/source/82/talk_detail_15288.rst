Understanding Rolling Upgrades
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We all have heard about rolling upgrades, but except for the people involved in the implementation most will not know how it really works. Unfortunately we cannot properly review patches or efficiently change the code base without really understanding it, since any new patch can potentially break rolling upgrades.Sure, most errors will be caught at the gate, but not only is that inefficient, but also doesn't solve everything, as now you'll have to figure out the patch's issue and a solution. And let's not forget that no CI is perfect, and some issues that fall between the cracks could be caught during reviews.This talk is meant for all developers regardless of the level of adoption of rolling upgrades within their projects, as it will not only cover the different aspects of the rolling upgrades but also go a little bit deeper into the versioned objects library explaining things like backporting, relationships, manifests, the remotable decorator, version bumping, etc.


* **Gorka Eguileor** *(Cinder Core and Senior Software engineer at Red Hat contributing to OpenStack's Block Storage Service. Previous experience includes Artificial Intelligence, Embedded Systems and High Availability mobile payment platforms. Besides leading the effort to support Active-Active High Availability configurations in Cinder, he's also been working during the N cycle on removing DB access races on API nodes, optimizing DB queries on most common operations, and making improvements to the Rolling Upgrades and Microversions mechanisms in Cinder.)*
