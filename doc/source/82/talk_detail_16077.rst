Reconciling Datera Intent Defined Storage with Cinder's Volume-centric Model in a Cinder Driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder is designed to provide a well-defined and standard interface formanaging block storage devices. In doing so it has also standardized the wayin which we define and manipulate storage devices. This often comes in directconflict with some of the features provided on a vendor's backend storagedevice. This presentation will cover our solution for finding a happy mediumbetween the traditional Cinder "Volume-centric" storage definition and Datera's"Application/Intent-based" storage solutions and steps other storage startupslooking to join the OpenStack Cinder community can take to come to a similarcompromise. * Cinder's volume-centric view of storage* Datera's intent-defined storage* Round-peg Square-hole problem* Overview of a Cinder driver's role in defining backend storage* Datera's current solution * Possible generic-volume-group addition here (pending implementation in Newton)* Detail possible problems other storage solutions might run up against


* **Matt Smith** *(I like Python, hacking on Vim, messing with my toolchain and generally being a bit rambunctious.)*
