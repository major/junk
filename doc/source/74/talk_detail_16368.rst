How to calculate the transition between two states of your OpenStack cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The shortest path between two points is not always a straight line, and the transition between two states of your OpenStack cluster can be more complicated than just a set of sequential changes. That's when you need to move from configuration management to orchestration. We faced this same question when solving the Lifecycle Management problem in Fuel: how do we calculate the optimal way to make these transitions? Fuel Mitaka uses the context of current and expected states of a cluster and calculates the transition graph based on introduced changes. We use YAQL (Yet Another Query Language), developed by the Murano community, to make the process of calculation fully data driven. It means that each granular part of the transition graph watches its own context changes and makes a separate decision about whether to be skipped or to be executed.


* **Alexey Shtokolov** *(Since 2015 - Fuel Developer and Development Lead at Mirantis 2010 - 2015 - CIO/CTO at Sistema Mass-Media 2004 - 2010 - Physicist and Software Developer at Moscow State University and University of Washington State)*

* **Vladimir Kuklin** *(Vladimir has been working on Project Fuel since its inception in mid-2012,  responsible for the end-to-end deployment cycle, from basic provisioning of OpenStack cluster nodes, DB, AMQP and HA configuration to final configuration of all options selected by the end user as well as working on orchestration and business logic framework.)*
