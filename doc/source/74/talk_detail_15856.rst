Building a Fortress: The easiest way to get full Role-based Access Control in Openstack Keystone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Keystone doesn’t support full Role-based access control (RBAC) by itself, but there is a very easy way to fix that by using a third-party application—Apache Fortress. Apache Fortress is an access management system based on the ANSI RBAC (INCITS 359) standard. It stores rules in OpenLDAP or Active Directory and has a nice web interface for viewing and modifying permission. Apache Fortress has everything you need for RBAC: ANSI RBAC implementation. Everything is already created, described, and documented. Apache Fortress stores entities (users, roles, permissions) in OpenLDAP or Active Directory, making it perfect for enterprises who already use LDAP or Active Directory for identity management. Because of Fortress' use of standardized LDAP backends, it is easily integrated with many other enterprise applications. Apache Fortress has RESTful APIs and a web interface. Apache Fortress integration with Keystone requires only a few lines of code changes to oslo.policy.


* **Kseniya Tychkova** *(Software developer with five years experience working in IT as a software developer, web developer, deployment engineer, integration engineer, and database administrator. Joined the OpenStack community in 2015. Currently works at Mirantis in the Enterprise Readiness Engineering team. The main goal of the team is to make OpenStack suitable for the Enterprise world. Areas of interests : Keystone, SSO (SAML), Kerberos, Apache Fortress RBAC System.)*
