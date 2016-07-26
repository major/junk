Converging QEMU and TCMU for Container Storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers storage technologies are changing rapidly. Volume Plugins in Docker and Kubernetes open doors to 3rd party storage provisioning for containers. However, these technologies are all based on bind-mount, volume drivers have to implement storage functionalities on their own. On the other hand, QEMU has a different approach to provide storage for virtual machines. QEMU's block drivers abstracts different backend storage types and thus supports features like multi-tenancy, snapshot, and QoS, which are currently missing in Container storage drivers. This talk presents a new technology that converges QEMU and TCMU. This allows Containers to use rich storage features that are already available to Virtual Machines. This technology integrates QEMU's block layer with tcmu-runner, and enables Containers to access various storage backends and rich storage features.


* **Huamin Chen** *(A passionate system software developer, Huamin Chen contributes to open source projects spanning from A to Z: Apache BigTop, Ceph, fio, Gluster, Kubernetes, Tachyon, and ZFS. Huamin Chen is currently employed by Red Hat. Follow him at http://github.com/rootfs)*
