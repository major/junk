Present and Future of OpenStack Ironic Drivers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Drivers are core components of Ironic. They define how Ironic interacts with hardware and ensure that different types of hardware can be represented by a consistent API. At the time of writing, Ironic has 24 production drivers in its source tree.It has become apparent that the way we compose and name drivers does not scale well. In the Newton release cycle we decided to completely rethink the notion of drivers in Ironic. This talk begins with the way drivers used to work in Ironic before the Newton cycle. It will then cover challenges we've faced with this schema. Finally, I will present the ideas and the results of the work known as Ironic driver composition reform. I will show how this change affects all of the interested parties: end users, operators and driver developers. I will also briefly cover the results of an effort to provide a 3rd party CI for all in-tree drivers.


* **Dmitry Tantsur** *(Ironic core developer, Ironic Inspector project founder. Bass player in leasure time.)*
