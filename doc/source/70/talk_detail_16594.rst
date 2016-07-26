Will it run on *my* OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Cloud Foundry ecosystem uses a tool called BOSH for packaging, installation, and updating workloads. Validating that BOSH can be used on an installation of OpenStack is currently a tedious and error-prone manual task. It's made harder by the fact that usually not a single team has expertise in both areas. Our team is building an open-source validation testsuite that encapsulates expert knowledge about the interaction of BOSH and OpenStack in a tool, which is easy to use for non-experts as well. It helps to find out if an OpenStack installation is ready to run BOSH, or which changes need to be done. The testsuite provides a DSL to express the requirements of a workload on OpenStack, which can be run as a set of validation tests, and gives feedback about required changes to the OpenStack setup. In this talk, we take a look how to express workload specific requirements in a simple series of tests, and report about the experience we gained with that in the Cloud Foundry project.


* **Marco Voelz** *(Marco is working for SAP SE and is the Product Owner of the Bosh OpenStack CPI. Developed in open-source, it is the abstraction layer used in Bosh, the tool to install Cloud Foundry and its services, on everybody's favorite IaaS.)*

* **Cornelius Schumacher** *(Cornelius works as engineering manager in the cloud and systems management department at SUSE Linux, which is working on projects such as OpenStack, Docker, and a variety of systems management tools. Cornelius is driving SUSE's technical involvement with Cloud Foundry, in particular the work on the BOSH OpenStack Cloud Provider Interface. He is a long time contributor to many open source projects for more than a decade, such as KDE, openSUSE, the Open Build Service, or recently Cloud Foundry. Cornelius is a regular speaker at Linux and open source events, mostly in Europe, but also in the US or in Brazil.)*
