You don't need a policy file
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Any project which wished to have policy enforcement in OpenStack has been using on the always reliable oslo.policy library. However, until recently it required that a project manually maintain and ship with a default policy file. This has placed a burden on packagers to ensure it's installed correctly, and on deployers who must manually check for additional policy rules that they should configure.   Recent changes to oslo.policy now allow for a project to register their default policies in code, eliminating the need for a policy file to be maintained. It is also possible to generate a sample policy file which is guaranteed to contain all used policies and which can be used to automate a check for new policies that have been added.   This talk will walk through how a project can take advantage of these new capabilities, and what benefits are offered to deployers when a project uses them.


* **Andrew Laski** *(I spent many years working on Nova for the Rackspace public cloud involved in development and operations.  Much of my focus has been on the reliability and scalability of Nova.  I now work for Mirantis and dedicate much of my bandwidth to the development of Nova, and other projects as opportunities arise, continuing to push forward on reliability and scalability.)*
