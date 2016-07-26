How to do Objects in Neutron the right way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Upgrades are the everyday life of OpenStack dev/ops. As neutron is a very complex project - its requirements for upgrades from technical point of view are high. Tools developed in oslo libraries based on nova and cinder experiences have to be enhanced for neutron use-cases. Things like multiple primary keys, extendable resources sent over RPC or API, high performance of SQL queries based on ORM relationships in database model are just examples of challenges that neutron community had to face when trying to adopt oslo.versionedobjects (OVO) library. This session would explain in details how objects are handled, how to add new or port existing resources in neutron to use OVO and how online data migrations can be performed. All of this would be presented as examples in neutron code. This would be an excellent source of knowledge for neutron community members as well as for other projects that are using oslo.versionedobjects library on how difficult use-cases can be handled.


* **Ihar Hrachyshka** *(Ihar is a software engineer at Red Hat. He spends most of his time hacking Neutron (also serving as a core reviewer for the project), nevertheless he is also interested in cross-project initiatives (Oslo, stable maintenance). Ihar is chairing the Neutron Upgrades team meetings and pushes the upgrades story for the project. Ihar is located in a European time zone, but lives as if he is not. "Because time zones are overrated".)*

* **Artur Korzeniewski** *(Artur Korzeniewski is a software engineer at Intel, currently working in Neutron community on subjects related to upgradability and HA of services. He is Neutron Upgrades team member, dedicated to improve the process of upgrade. Before joining the Neutron team, he was closely coupled with OpenStack since Diablo release, working on resource scheduling and compute assurance. Artur likes new challenges, path-finding and designing solutions from scratch. He is the Python language and networking fan. Artur has master degree in IT from Gdańsk University of Technology in Poland.      )*
