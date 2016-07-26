50PB Multi-site Cloud Object Storage in China Mobile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

    The cloud storage is becoming the most important part of IaaS platform, because internet and mobile internet produced a mass of video, image and some other unstructured data. Therefore, ChinaMobile built 50PB cloud storage service for enterprise and individual customer this year.      There are some challenges in this program: one is the scale of storage service, it contains more than 1000 servers totally, we haven't found too much successfull cases; the other one is the unified namespace that crossed multi-site. We did sufficient investigation and research, including Ceph, Swift and some other options.      Finally, We decided to build and operate 50PB Object Storage service based on Ceph. The object storage service has also been integrated with our OpenStack-powered cloud platform to store the backups of virtual machines and glance images. We use the new multi-site architecture of ceph to meet the needs of scale and erasure code to reduce the total cost.  


* **Zhandong Guo** *( I worked for EMC after got master degrade from Beijing University of Posts and telecommuniations in 2011, and focus on object storage, Hybrid cloud platform and some other fields. In 2014, I become the employee of China mobile. As a team leader, Be responsible for the development of cloud object storage system which is the important part of CMCC cloud platform. From 2015, we focus on the practice of ceph.)*

* **Rongze Zhu** *(Cloud Architect, OpenStack/Ceph contributor. Responsible for financial and large enterprise OpenStack private cloud architecture design. Many years experience in the block storage system. Builded public cloud based OpenStack in 2012. Developed a distributed block storage system for large-scale production environment in 2013.     )*

* **Jiaying Ren** *(UMCloud software engineer,Ceph contributor,Being put in charge of Ceph object storage at UMCloud now .Having being focused on OpenStack/Ceph since 2015,operating dozens of OpenStack/Ceph private cloud,having been responsible for the design & implementation of Ceph admin platform,OpenStack functionality CI platform.)*
