Why do we like distributed storage backends more
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

More and more company starts to build IT system with virtualization and cloud computing technology, storage system has met more severe challenge. E.g. storage system need undertake more business. It should have higher performance, reliability and expansibility. Meanwhile cutting the cost, it should also keep the QoS level.Distributed storage backends have obvious advantage in performance comparing to ipsan storage backend, thus have attracted lots of attention from both vendors and users. Currently there are serveral distributed storage drivers available in cinder: EMC, VMware, netapp, ceph, hitachi, etc and the newly added FusionStorage. What's their pros and cons? What distinct feature do they have?In this topic, we will have a deepdive into the most common distributed storage backends in Cinder, disuss how downstream driver can help OpenStack become more secussful, moreover, we will share our experience of intergrate OpenStack with some of the distributed storage drivers.


* **Xiyuan Wang** *(Xiyuan Wang joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Zaqar, Glance and Cinder. He is one of the zaqar core members.)*

* **Zhenyu Zheng** *(Zhenyu Zheng joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Nova, Searchlight.)*

* **Duncan Thomas** *(Involved in Openstack since Cactus, and large HPC systems as adeveloper and admin before that. Worked on one of the first large Openstackpublic clouds, and one of the founding members of the Cinder team.)*
