A Nova Scheduler for Public Cloud Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the advent of Nova Cells v2, the need for high throughput VM scheduling is becoming increasingly critical to the operation of OpenStack at public cloud scale.  For Cells v2, in particular, the requirement to use a global scheduler means that the scheduler must be able to manage more hypervisors and, potentially, many more VMs.  As with all things cloud, horizontal scaling seems like a natural solution.  However, in the case of the Caching Scheduler, for instance, more schedulers means more resource contention which often results in the infamous "No Valid Host" error.We present performance results for multiple scheduler implementations in an attempt to identify the best one to resolve the resource contention problems, and subsequent throughput deficiencies, encountered in distributed scheduling. One such implementation makes novel use of Redis as a remote, in-memory DB in place of the usual Nova DB.


* **Ryan Rossiter** *(Ryan Rossiter has been with IBM for 2 years, joining after graduating from South Dakota State University. He started working on automation and testing for IBM Cloud Manager with OpenStack. From there, he went on to work upstream in Nova and Magnum. Ryan is now working on IBM's public cloud, specifically on the development and deployment of Nova and the VM service within IBM BlueMix.)*

* **Chris Kirkland** *(I'm an Engineer on the Cloud Foundation Services Performance Team at IBM.  I spend most of my time working on Nova/Heat but have worked on IBM BlueMix web services as well.  In addition to performance, I'm very interested in Development and Automation.  I am primarily a Python developer but working on becoming more proficient in Golang. Before joining IBM, I received an MS in Applied Mathematics (conc. Computation Mathematics) from North Carolina State University.  In my spare time, I assistant direct a Barbershop chorus in Austin, TX.)*
