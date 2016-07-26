Debugging of OpenStack services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Murphy's law states: "Anything that can go wrong, will go wrong.". When it does, one should be able to deal with it. Complex systems like OpenStack with many moving parts inside tend to break often when deployed on a large enough scale. And when something breaks, it's crucial that a developer analyzing the failure knows where to start and has some sort of methodology to perform root cause analysis. Often people come unprepared and start trying things at random or stick to primitive debugging techniques (like inserting print statements in the code), which is at best time-consuming and inefficient and at worst does not allow finding the root cause of the problem or leads to inability to reproduce the bug in question. The goal of this presentation is to share experience of troubleshooting issues in OpenStack services during development and in production, to make developers aware of existing tools and methods for debugging typical problems.


* **Roman Podoliaka** *(Roman got his master's degree in Computer Engineering from Kharkiv National University of Radio and Electronics in 2012. Roman's programming language of choice is Python, which he used on his last 3 jobs developing Web services and backends, as well as for contributing to open-source projects. Since 2013 Roman has been working for Mirantis on various OpenStack projects (Nova, oslo.db, TripleO) with the focus on improving overall stability, performance, code quality, as well as troubleshooting and fixing of complicated issues. Roman gave a few talks at the local Python community event - KharkivPy (http://kharkivpy.org.ua/) and PyCon UA (http://ua.pycon.org/).)*
