Pitfalls on the way of migrating legacy applications to latest OpenStack (Xenial+Mitaka)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NTT West, Japanese major telecommunication provider company, migrated existing virtualized environment consist from legacy servers and SAN storages to OpenStack Mitaka on Ubuntu16.04 LTS.   This project caused various changes of infrastructure, operation and culture. We focused issues derived by those changes which are conflicts with migration and operation of existing application. To mitigate these issues, we adopt multi vendor Cinder storage and use them as boot volume with multiple AZ. This enables virtual servers to be configured HA cluster with shared volume.We also designed cinder-volume and cinder-backup use cases based on existing backup process.   In this presentation, we introduce issues and resolution not only for migration of legacy application but also caused by using latest version of Mitaka and Ubuntu16.04(Xenial). We also share existing issues and future improvements.


* **Shigeaki Kimura** *(Shigeaki Kimura is an assistant manager at R&D Center, NTT-West.He is engaged in the development of a server platform for providing telecommunication services.He is challenging the OpenStack to evolve NTT-West's server infrastructure every day.)*

* **Hiroshi Koiwai** *(Hiroshi Koiwai has been active mainly on infrastructure technology several years and leads an organization of OSS/Cloud technical development & promotion recently.)*

* **Takahiro Higashi** *(Takahiro is a Senior Architect at Solinea KK which is Japanese liaison of Solinea, Inc. Takahiro brings over 20 years of technology and management experience to the Solinea KK. Prior to joining Solinea, Takahiro worked for cloud company and managed cloud platform support force. His background is in software development product management.)*
