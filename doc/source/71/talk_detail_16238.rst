Stateful Applications in OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Paypal moved stateless workloads to Openstack cloud a few years ago. At PayPal, 100% of front and mid-ier applications run on Openstack. The next logical step is to start moving stateful applications into cloud.   This presents a new set of challenges. In a multi-tenant environment, how do you guarantee that data access is restricted. Recovery is not as simple as spinning up a new compute instance. Data needs to be presented to this new instance ASAP. Load balancers do not solve the problem. Network block storage means you might choke other applications transacting over the network. Solutions range from onboarding these applications on bare metal computes in the cloud (buying some advantage by way of agility) to containerized solutions with a managed storage layer, engineered for fast recovery from failure.  We will present an introductory version of this talk at OpenStack East. This follow-up presentation tracks progress and provides more color to conclusions reached so far.


* **Anant Kumar** *(Anant is currently responsible for managing the Paypal Cloud, the world's largest Openstack deployment. Spent over a decade working in Cisco Engineering, another 2 running a technology driven Fashion eCommerce business and then Indoor Location at Aruba Networks. Currently responsible for managing the Paypal Cloud. PayPal runs the world's largest OpenStack cloud with ~10000 servers. All of paypal.com and applications run on this cloud. An OpenStack newbie 2 years ago, am still learning the intricacies of deploying and managing a cloud using Openstack.  The complexity of running the cloud is in managing the underlying infrastructure and automation around that. )*

* **Jasdeep Sahni** *(Services architect at PayPal)*
