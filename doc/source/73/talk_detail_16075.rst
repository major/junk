Living on the Edge: Scalable Edge Caching and Disaster Recovery with OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As industry shifts towards building their own private and public storage clouds, OpenStack Swift has become an invaluable storage platform with numerous tools in the toolbox.  Once objects are distributed across multiple geographies though, the toolbox becomes lighter and lighter.  Currently OpenStack Swift assumes a mostly homogenous set of data centers over which to distribute data, which does not take into account that not every data center is created equally.  We are building an object storage solution, which builds upon unmodified OpenStack Swift, that supports on-disk caching of objects at edge data centers while always being stored at an organizations primary data centers that contain the DR, backup and archive facilities.  In our solution, applications can continue to failover and failback between data centers in the case of a disaster, but are no longer required to store a piece of the object store at every site. 


* **Dean Hildebrand** *(Dean Hildebrand is a senior researcher at the IBM Almaden Research Center and a recognized expert in the field of object storage as well as distributed and parallel file systems. Dr. Hildebrand pioneered pNFS, demonstrating the feasibility of providing standard and scalable access to any file system. He received a B.Sc. degree in computer science from the University of British Columbia in 1998 and M.S. and PhD. degrees in computer science from the University of Michigan in 2003 and 2007, respectively.)*

* **Gaurang Tapase** *(Gaurang Tapase is a software developer with IBM Spectrum Scale team. He mainly works on integration of Openstack storage components (Cinder/Manila/Swift) with Spectrum Scale. Previously, he has worked on development projects centered around object stores.)*
