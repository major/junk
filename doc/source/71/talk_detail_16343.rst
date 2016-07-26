Boosting OpenStack Performance by using PyPy JIT as the default Python interpreter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk, we will demonstrate how to improve OpenStack performance by making PyPy JIT (Just-In-Time) as the default Python interpreter with no application code changes. We conducted a proof-of-concept study using PyPy JIT on five core components, Keystone, Nova, Neutron, Glance and Cinder.  Our result indicates performance gain by up to 35%, and often non-interpreter related bottlenecks are exposed after PyPy JIT is used, painting a bright picture for a wider adoption of PyPy JIT in all OpenStack components.  In addition, we will also explain how to experiment with PyPy JIT and share some of the issues and experience we have gained in the adoption process.  This talk is a continuation of a previous talk by Dave Stewart/John Dickson titled “Doubling Performance in Swift with No Code Changes” and presented in the OpenStack Summit Austin 2016, in which up to 111% gain was demonstrated on OpenStack Swift   .  .  


* **Peter Wang** *(Peter Wang is a software performance engineer in the Server Language Optimization Team in the Data Center Software Technology group at Intel. Peter has been working on various SW projects at Intel for over 20 years. In the last 12 years, he has been focusing on enterprise application benchmarking, performance analysis and tuning on x86 microarchiecture.  He is currently leading a team of engineers on improving the performance of the open sourced Python interpreters including CPython and PyPy)*
