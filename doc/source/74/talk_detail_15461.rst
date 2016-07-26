The Story of booting VM from Ceph RBD volume
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

eBay has a large scale OpenStack deployment. As a consequence, hypervisor failure is a common thing in daily life. This, in turn, becomes a real harassment for our internal cloud users in terms of VM availability. This talk will go through the overall story of how we address the issue by enabling VM boot from Ceph RBD volume in eBay. In this talk, we will go through different alternatives of booting VM from Ceph storage, the changes we did to make RBD VM as default option based on policy settings (image, flavor, production/dev etc), the challenges along the way and how we managed to fix. In the end, we were able to gradually rollout Ceph RBD based VM in a controlled manner. This talk will also share the latest effort of RBD VM auto-remediation to minimize VM downtime that end users can feel.


* **Yu Qiu (QY)** *(OpenStack Handyman)*

* **Vivek Jain** *(Leading Load Balancing and Storage Solutions at eBay Inc.)*

* **Emile Snyder** *(Emile has developed software on GNU/Linux systems for many years in C++, Python, Clojure and other languages.)*
