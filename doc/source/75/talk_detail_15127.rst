OpenStack Compliance the DevOps Way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Chances are if you run an OpenStack cloud, you have some form of compliance you have to adhere to. It may be some internal CIO driven compliance written in 1993, or external compliance requirements like HIPPA or PCI. We'll show you how Blue Box Cloud manages its compliance by utilizing the power of DevOps and open source software to not only enforce (Ansible) our adherence to compliance but to actively monitor and alert (Serverspec, Sensu, ELK) the moment a server falls out of compliance. Of course this is not a magic wand that will make your systems PCI compliant, the underlying operating system and software need to have the appropriate features to support the compliance requirements. For example, we are not injecting any magic to perform automated password rotation in keystone (that would need to be solved in keystone itself, or custom middleware) but rather enabling or configuring the keystone options to do so.


* **Paul Czarkowski** *(Paul Czarkowski is a Cloud Engineer at IBM Blue Box where he implements OpenStack for Enterprise clients and does Docker R&D.  When he isn't coding you can find him baking bread and winning cookoffs around Austin TX.)*

* **Zachary Sais** *(Zachary Sais is a Software Engineer at IBM Cloud where he automates and deploys monitoring frameworks for enterprise OpenStack clients. Prior to IBM, he graduated from the University of Texas at Austin with a degree in Computer Science. In his downtime, you can find Zach brewing delicious beer and playing golf in Austin, Tx.)*

* **Rachel Wong** *(Rachel Wong is a software engineer at IBM Cloud where she works with the Security and QA Testing team in order to test Openstack UI, APIs, and infrastructure. Before working at IBM, she graduated from the University of Texas at Austin with a BS in Computer Science. Currently residing in Austin, TX, she spends most her time playing Ultimate Frisbee and attending happy hours.)*
