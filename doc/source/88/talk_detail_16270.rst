An Interoperable Image Service Powered By OpenStack Glance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Glance supports uploading images for many formats (qcow2, docker, etc.) and purposes (VMs, volumes, containers, etc.). Being able to use an image, however, requires some specific knowledge, for example, what disk and container formats are supported in that cloud, the largest system disk available, etc.  Since Liberty, the Glance team has been working on a more refined API that will help users discover both the platform they can use to upload image data to and the particular formats, sizes, etc. supported in that cloud. This discovery mechanism helps build clients deterministically to build a seamless call for the image import process. This single workflow which lets operators define and users choose a way they want to upload image data makes uploads more performant and flexible.  And did we mentions that it's fully interoperable?  We want to tell you all about it.


* **Nikhil Komawar** *(Nikhil Komawar is the PTL for Glance in Newton release and a Glance subject matter expert at IBM. He's a Open Source and Open Community enthusiast.  He's a former Project Technical lead for the OpenStack Searchlight project and core there. He is also a mentor for the Outreachy program for technical development of the under-represented groups. He loves technical and process evolution.)*

* **Brian Rosmaita** *(Brian Rosmaita is a Senior Software Developer at Rackspace.  He's been an active technical contributor to OpenStack since the Folsom release and was a software developer on the Rackspace first generation cloud.  He's a core contributor to the Glance and Searchlight projects, and is the Glance technical lead for the OpenStack Innovation Center.  In his spare time, he's the host of Radio Ethiopia, a reggae and African music show that's broadcast on K-RACK, Rackspace's internal internet radio station.)*
