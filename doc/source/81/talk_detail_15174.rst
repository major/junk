Networking considered the Achilles heel of container clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the popularity of containers increases, several alternatives for supporting these in OpenStack clouds are emerging. However, given the much higher instance (per hypervisor) density found in real-world production clouds for containers, the usual virtual networking implementations - successfully applied to VMs in the past - have become an Achilles heel. In this talk we present several relevant alternatives, focusing on the networking aspects of each solution. In particular, we present the networking models used with multiple instance management options, such as Nova (nova-docker), Magnum, and Kuryr  (and possibly Zun) projects. We consider all existing container networking solutions from the Docker Container Network Model to the AppC Container Network Interface, and their interaction with OpenStack Neutron. We evaluate and quantify the performance and scalability of the networking alternatives. 


* **Mohammad Banikazemi** *(Mohammad is a research staff member at the IBM T.J. Watson Research Center. His research interests include cloud computing and software-defined networking. He is a senior member of the ACM and the IEEE and an active contributior to Neutron. Mohammad lives with his family in NYC.)*

* **Marcio Silva** *(Software Engineer at IBM Research)*

* **George Almasi** *(Dr. Almasi is a Research Staff Member in the Software DefinedInfrastructure Department at the IBM TJ Watson Research Center. Heholds a PhD in Computer Science from the University of Illinois andhas been employed by IBM since his graduation. He has worked onseveral supercomputer projects like Blue Gene and PERCS, and hasauthored and co-authored several papers on the design of messagingsystems and programming models in High Performance Computing. He isnow an expert on various aspects of OpenStack installation.)*
