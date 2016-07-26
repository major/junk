Automating ITIL Configuration Management for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the traditional, non-virtual datacenter, enterprises have evolved ITIL systems such as CMDB and DNS to manage their infrastructure.  However, with OpenStack, there is no automatic method to integrate the VM creation with these features.  This presentation will provide a detailed, in depth engineering analysis of the design we have developed to automatically update DNS and CMDB when a VM is created.  Conversely, we automatically remove the CMDB record and DNS record when the VM is destroyed.  These methods are automatic and do not impact the creation or deletion of the VM; nor do they change the API calls to create/destroy VMs in OpenStack.  Further, ths is the best part, our software does not modify the OpenStack code so upgrading is very easy.


* **William Bloom** *(William has 25 years of experience as a UNIX system administrator, manager, storage engineer, and most recently as a Cloud design engineer.  William has worked in Intel Manufacturing, LSI Logic Manufacturing, Legato IT, EMC.  Most recently, William just completed 10 years at Cisco in a variety of  IT roles from data protection design, storage design, and most recently OpenStack design.  William is currently working as a software developer and Scrum Master for CITEIS (Cisco IT Elastic Infrastructure Services).)*
