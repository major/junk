Arrebol: easy and efficient execution of Bag-of-Task applications on federated clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We present Arrebol, a service for the easy execution of Bag-of-tasks (BoT) applications in private, public and hybrid clouds. Arrebol provides an intuitive scripting language to define large BoT jobs in a succinct way. Using a command line interface, users can submit jobs to the Arrebol submission service. It parses the jobs and interacts with the underlying cloud to create the infrastructure required to run them. Then, it submits tasks to execute in parallel, and dismantles the infrastructure when it is no longer needed, making the management of the execution of jobs completely transparent to the users. BoT applications are ideally suited to be executed over elastic cloud infrastructures. We also discuss how Arrebol leverages Fogbow, a middleware for federating clouds, to increase the capacity of the infrastructure by exploiting different hybrid settings, including cloudbursting and cloud federation. Both Arrebol and Fogbow are available as open source under Apache 2.0 license.


* **Francisco Brasileiro** *(Francisco Brasileiro is a full professor at the Systems and Computing Department of the Federal University of Campina Grande (UFCG) in Brazil. His research is focused on the area of distributed computing, with focus on grid and cloud computing and support for escience applications. An updated list of publications can be found at http://dblp.uni-trier.de/pers/hd/b/Brasileiro:Francisco_Vilar. He currently coordinates the EUBrazil Cloud Connect project (http://eubrazilcloudconnect.org/) and leads the team developing Fogbow (http://fogbowcloud.org/), a middleware for the federation of private clouds. He is a member of UFCG's team that contributes with the Openstack community.)*

* **Andrey Brito** *(Andrey Brito is a Professor at UFCG (Universidade Federal de Campina Grande) in the Computer Science Department. Andrey’s main interests are robustness and scalability aspects of distributed systems. He coordinates R&D teams that have been contributing to OpenStack, specially regarding federation, hierarchical multitenancy and integration between Ironic and infrastructure managers.)*

* **Thiago Emmanuel Pereira** *(I received BSc (2008) and MSc (2010) degrees in Computing Science from the Federal University of Campina. I am a currentlty PhD student with the same university, associated with the distributed systems lab (www.lsd.ufcg.edu.br).)*
