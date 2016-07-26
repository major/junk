Private Floating IPs for openstack Tenants
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Separate the notion of Floating from the actual network from which these IPs can be derived. This means that have a tenant specific FIP pool from which these Floating IPs can be derived. Via this mechanism we can restrict opening up access to backend systems directly to the data center/internet network and still achieve IP Failover using a pool of private Floating IPs


* **Shashank Jain** *(Shashank Jain has around 16 years of applications development experience based on different application servers and Cloud platforms.  Have worked in area of cloud computing on platforms like AWS, Openstack and Cloud Foundry. Has been working in area of containerization with Docker and Rocket. Has interests in area of distributed computing and Big Data platforms)*
