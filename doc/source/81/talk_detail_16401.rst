Building Immutable LXD Container Images from Scratch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Linux container images traditionally include system services and utilities that are not always needed or desired by application developers.  Ideally, containers should only have the files and executables actually needed by the application.  This apporach reduces the size of the container images significantly, as well as reducing the need to patch unused software for bug and security fixes.  LXD is a system level container that provides features not typically found in other application-oriented containers.  The nova-lxd compute driver enables organizations to run LXD system containers on bare metal in an OpenStack cloud, instead of using nested virtualization inside of instances.In this presentation, I plan to present how to build a minimal LXD container image from scratch that can execute an application in an OpenStack cloud.  This minimal application image will be built from distribution-provided packages and automated with Ansible, allowing for ease of use and repeatability.


* **Michael Gugino** *(Michael Gugino works for Walmart on their Cloud Operations team at in Reston, Virginia, USA. He has knowledge and experience with Python, Ansible, Puppet, C, MySQL, RabbitMQ, NoSQL, and of course, Linux. Michael contributes regularly to OpenStack-Ansible.)*
