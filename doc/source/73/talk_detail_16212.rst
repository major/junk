Unleashing the power of Oracle Database with shared filesystems and OpenStack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Oracle Database can give superior performance when used with ZFS storage Appliance over dNFS. ZFS Storage appliance(ZFSSA) has hooks to listen to cues from the database over dNFS. This reduces the tuning effort required when provisioning shares from Manila when integrating with a database. The compression ratios are also improved drastically when integrating Oracle database with Manila on ZFSSA. dNFS enables fibre-channel like performance but with reduced operational and capital cost of file based storage. With DTrace based analytics in the ZFSSA, it is easy to identify individual database's performance which can help with storage optimization and identification of performance issues. There will be a demo in which the database will be hosted on a VM on Nova and the shares on ZFSSA will be provisioned by Manila.


* **Kedar Vidvans** *(Kedar is a senior software developer working for Oracle. Kedar works with the Oracle ZFS Storage appliance(ZFSSA) team and is responsible for developing and maintaining ZFSSA storage drivers in OpenStack. Kedar has been associated with OpenStack since the kilo release.)*

* **Juan Zuluaga** *(Juan is a principal software engineer with Oracle and has 15+ years of experience in the industry. Juan is responsible for developing and maintaining on the ZFS Storage appliance drivers in OpenStack. Juan has been associated with OpenStack since the juno release.)*

* **Alka Deshpande** *(Alka is a senior software manager with Oracle having 20+ years of experience in the storage industry. Alka manages the team that is responsible for developing and maintaining Oracle ZFS Storage Appliance OpenStack drivers.)*
