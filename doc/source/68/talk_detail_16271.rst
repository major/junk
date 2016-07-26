Tech refresh your production infrastructure. Rebuilding hypervisors while keeping the 9’s
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our oldest and largest OpenStack cluster has been running for a while and it’s been through a few OpenStack upgrades but there comes a time when the hardware and/or OS reaches EOL and needs to be refreshed. We have been given the task of re-imaging the entire fleet of hypervisors with minimal or no downtime to our users. This presentation will address some of the issues we have had with VM mass migrations and how we solved them. Preparation, cleaning to free capacity – No extra capacity was going to be available for the migration process Patching nova, backporting changes and CI for packages Testing – provisioning, integration, migration offline and online Communication to users Manual and automated migration, use of automation Impact of migrations on the infrastructure – from control plane to hypervisors and network Migrating XL flavors Bugs and Issues (timeout, missing image, libvirt bios, half migrated instances) Migrations and overprovisioning What have we learned


* **Gabriel Capisizu** *(Gabriel Capisizu is part of the Symantec’s Cloud Platform Engineering team. He has over 10 years years of experience with large scale distributed systems, Unix and networking.  Gabriel started with OpenStack in 2011 as part of PayPal’s cloud engineering. His focus is deployment automation, security and high availability within OpenStack.)*

* **Sergii Kashaba** *(Prinicpal Software engineer. Having more than 14 years of experience in different areas of software development. Now work closely with OpenStack, adopting it for large enterprise customers.)*
