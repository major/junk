How to move toward Keystone v3: Neutron case-study
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Keystone is at the heart of an organism called OpenStack. Without it, it would be difficult to live. That's why it is important to know how to react to changes that arise from the minds of Keystone developers. Among many important changes in the v3 API for Keystone, like groups and domains, we can see the migration from the old term "tenant" to focus instead on "project". It can be painful to understand and further debug this, having become accustomed to the old usage and meaning of the term. Neutron decided to be compliant with this change and update all references to get rid of the deprecated term "tenant". Something that initially was thought to be a pretty straightforward update, turned out to be a very complex and time consuming venture. If you want to hear what kind of issues were encountered, what kind of obstacles can be expected, and if it's even worth it to pursue this goal, you'll hear all these things in this talk.  


* **Darek Smigiel** *(Dariusz started his journey with OpenStack in December 2014 and his first contribution upstream was in March 2015. Originally worked on TripleO with Ironic, where he improved the installation process. Dariusz started woking on the Neutron Project in October 2015. He is currently implementing Keystone v3 compatibility changes. Dariusz also has experience with other OpenSource projects and cutting-edge features in an advertising clearance system. In the spare time, he gives a talks about Python at conferences and with local communities.)*

* **Henry Gessau** *(Henry Gessau is a core reviewer for Neutron. He is the database 'lieutenant' for the project, and has also contributed to IPv6 features, project testing enhancements and the effort to move third-party (vendor) code from neutron into separate sub-projects in the Neutron stadium. Henry has worked in the networking industry for many years, but his passion lies in software design and development. After using C for decades, Henry is now a big fan of Python. He has lived in several countries and loves visiting new destinations.)*
