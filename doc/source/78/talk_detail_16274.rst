Glare - a unified binary repository for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Glare (from GLance Artifact REpository) is a new service in the Glance project that provides a secure and customizable unified binary repository for OpenStack. The idea behind Glare is to allow various OpenStack services to catalog different objects they use to operate. Images used by Nova to run the VMs are just the best known examples of such objects; other examples include Heat templates, Tacker blueprints, Murano packages, and so on. Obviously, this functionality is common for different kinds of objects, and is usually unrelated to the primary mission of respective projects using these objects. That's why we implemented a dedicated service that will take care of managing various data assets in OpenStack clouds. The talk will describe how Glare helps to manage different artifacts across the cloud, how you can build your own private and secure catalog with artifacts for your service, what deployers need to know about the installation process, and what is coming in the future.


* **Mike Fedosin** *(Mike Fedosin is a full-time upstream OpenStack developer with more than 10 years of experience in Software Development in enterprise, scientific and open-source projects. He has the title of Ph.D. in the development of cloud service architectures. Being one of the core developers of Glance, Mike is driving a number of cross-project initiatives there, like adoption of Glance v2 API across OpenStack, and owning several other large features. Also, Mike leads project Glare, which provides secure and customizable unified binary repository for OpenStack.)*

* **Kairat Kushaev** *(Software Engineer in Mirantis)*
