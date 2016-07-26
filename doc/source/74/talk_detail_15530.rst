A road to active-active mode of MySQL Galera in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Official OpenStack High availability guide configures MySQL Galera into active-backup mode, and so did all OpenStack Distribution we known. But in fact, MySQL Galera is a Multi-matser Cluster which is designed to work in active-active mode. So why OpenStack uses active-backup mode? Can we change it to active-active mode? This topic will give you a deep analysis on the performance and influence of both mode in stress tests. We will dig into each SQL and show you which part of the SQL is blocking us to use active-active mode.  Finally, we will share our solutions of how to optimize these SQLs.


* **Gangyi Luo** *(Engaged in OpenStack related work since 2014 and specialized in Nova, Ceilometer and OpenStack high availiability. )*

* **Bin Li** *(Specialized in MySQL Galera development.)*

* **Felix Ma** *(Specialized in Cinder.)*
