Telemetry: Practice In Large-scale Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We have a more than 300 nodes OpenStack enviroment. With scale came the challenges of operations and telemetry of this cloud. We enhanced our monitor system with ceilometer, aodh, zabbix and other monitoring software. We use independent message queue system to improve stability and isolation, and redesigned the way we record the metric and samples to deal with high concurrent queries and manage data life cycle. And change cluster form to improve the writing ability of database. Then we try to collect physical machine monitoring information with other software and send them to ceilometer for unified storage and preparing for alarm.


* **Chen chaozhe** *(Tech Lead and Founding Engineer from Easystack. He contributes primarily on OpenStack telemetry and trove Project, also works on Easystack billing system. Now his main responsibility is focusing on building monitoring and billing system for Easystack products. )*
