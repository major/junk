Monitoring Openstack with Elasticsearch Logstash and Kibana
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In our Openstack installation,  BulutM cloud monitoring system use  ELK stack (Elastic) to gather: Openstack logs Tenant based top n network statistics (bandwidth, pps, error, drop)  Compute host I/O, network, memory, cpu metrics Virtual machine I/O, network, memory, cpu metric The BulutM monitoring system is written in Python.  BulutM use Openstack API to get tenant information. Tenant information is stored in redis  and used by other scripts to automatize generation of Kibana dashboard, search and visualization objects.


* **Onur Bektaş** *(Onur Bektas is currently  a chief researcher in Network Technologies Department of the Turkish Academic Network and Information Center  (ULAKBIM). Onur has more than fifteen years of experience and on FreeBSD, Linux and Solaris operating systems administration and security.)*
