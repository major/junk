Full GPU virtualization support is coming
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently, most devices can be passed through to guest and works fine, one of the exceptions is the GPU, the GPU differs from the normal PCI device, it is usually integrated with a VGA compatibility mode and OS may use the legacy VGA mode to access the GPU, so we must to emulate all of the legacy VGA mode operations in VMM.Moreover it has some features that work poorly in virtual environment, like GPU reset. we often need to reset GPU to put GPU into a clean state between guest reboot, but some GPUs lack of FLR or reset incorrect. it may not be a serious problem on physical machine, because GPU reset often occurs while machine reset. but in virtualization, we must ensure host running robust and reset GPU separately while guest reset.all the issues make GPU virtualization more complex than normal PCI devices. but now, we have a new implementation of GPU virtualization (Xengt/Kvmgt), this topic is to briefly introduce the implementation and the usage in openstack in the future.


* **fan chen** *(nova in openstack, libvirt, qemu and kvm virtualizaiton contributor, used towork in fujitsu, huawei, have rich experience in virtualization techology, workedalong with intel OTC team in GPU virtualization area.  now working in easystackin china.)*
