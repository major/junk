Keystone and Barbican working together to improve Fernet security
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Fernet, Fernet, Fernet. Since the last Openstack release Fernet tokenshave been get a lot of attention. Key management is integral tosecurity with Fernet. Unfortunately this is left as an implementationdetail to be handled by the local devops team. Surely there is abetter way.This presentation will guide you through:      1. What is Fernet? Why should you consider switching to it?      2. How can Barbican improve the management of Fernet tokens.      3. What are the pros and cons of using Barbican. Is it more secure?      4. Proof of concept demo which will show Keystone using Barbican         for Fernet key storage and a tool to rotate the keys while         stored in Barbican.We will show that it is possible to leverage the Operator's investmentin HSM and Barbican to improve the security and management of Fernetwith minimal interaction with the Configuration Management system.


* **Sean Perry** *(Sean Perry has been a Linux and open source developer for the last 18years. Starting at a local ISP back in the modem days and then VALinux, he has since worked on iSCSI management, Xen, workstation DiskEncryption and Honeypot networks for Symantec, and now OpenStack atHPE. For the last year and a half Sean has been part of the HPE HelionOpenStack team working on Keystone.)*

* **Fernando Diaz** *(Fernando Diaz is an active OpenStack Core Contributor, focusing on Barbican Development. Born and raised in Miami, Florida, Fernando recieved his B.ASc. in Computer Science at Florida International University. Fernando is currently a Cloud Developer for IBM and works on Key Protect, IBM's Key Management Solution. Currently resides in Austin, Texas. He helps keep Austin weird.)*
