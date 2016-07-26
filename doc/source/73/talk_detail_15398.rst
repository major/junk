Forget everything you knew about Swift Rings - here's everything you need to know about Swift Rings
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Swift is designed to make the most durable and available object storage system possible from your commodity hardware. From a few terabytes to dozens of petabytes and beyond Swift uses a consistent hashing ring to ensure data storage locations are dispersed to ensure failure-resistant operations of your clusters running at scale. Swift operators are ring masters. They interact with them constantly to maintain order in their clusters, adding new capacity to power their growing cloud, removing or replacing old and busted disks and nodes, or creating new powerful differentiated storage offerings based on their clusters unique characteristics, geography or features. In this talk we want to give you a deep dive into the rings: low level details how initial placement and rebalance works, best practices when designing cluster topology and ring management, and what you need to know about recent and upcoming changes like overloading, increasing partition power and composite rings.


* **Christian Schwede** *(Christian started working on Swift four years ago and works as a Principal Software Engineer at Red Hat. Most of his Swift related work is related to supporting customers running Swift and working on automation, testing and development tools.)*

* **Clay Gerrard** *(Clay Gerrard is a Sr. Software Engineer at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Clay was part of the original development team at Rackspace that created Rackspace Files, which became the Swift project within OpenStack when it was made open source. Clay has continued to be active in the OpenStack community as a contributor to the Swift project.)*
