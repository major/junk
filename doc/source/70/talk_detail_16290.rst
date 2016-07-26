Reclaim those unused instances, images: Mors - Lease Management for OpenStack objects.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A large section of OpenStack is used is for running Dev, Test or Sales lab. Lab means creating a large number of objects (Instances, Images, Volumes, etc). OpenStack makes creating these objects really easy, but deletion of unused items is always forgotten. Introducing Mors - a simple service that will help reclaim precious computing and storage resources. Using Mors you can set up expiration lease policies on Instances and Images per tenant, upon expiration of the lease Mors will warn owners of images or instances. Users will be able to extend their expiration leases in a constrained manner, failure to do so will mean Mors will either power-off or delete the instances. It is simple to understand and very effective. In this talk author would present how to configure and user Mors for your own OpenStack environment. Furthermore, you will also learn how to add support for more OpenStack objects to the Mors framework and extend it further.


* **Roopak Parikh** *(Roopak Parikh is one of the Co-founder and CTO at Platform9 Systems Inc. Platform9 Systems is one of the OpenStack distribution and service providers. Prior to Platform9 Systems Roopak help technical leadership roles at VMware helping them build various management products including vCloud Director (VCD).)*

* **Susmitha  Kanakamedala** *(Susmitha likes to work on system software, solve hard problems. She works on Nova, Glance & Keystone projects at Platform9. She contributed heavily to Mors (a new lease system for OpenStack objects). In past she spent time working on Resource management problems at VMware and working on networking aspects at Cisco.)*
