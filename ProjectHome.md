GridSim allows modeling and simulation of entities in parallel and distributed computing systems such as users, applications, resources, and resource brokers/schedulers for design and evaluation of scheduling algorithms.

Overview of GridSim functionalities:
  * incorporates failures of Grid resources during runtime.
  * new allocation policy can be made and integrated into the GridSim Toolkit, by extending from `AllocPolicy` class.
  * has the infrastructure or framework to support advance reservation of a grid system.
  * incorporates a functionality that reads workload traces taken from supercomputers for simulating a realistic grid environment.
  * incorporates an auction model into GridSim.
  * incorporates a datagrid extension into GridSim.
  * incorporates a network extension into GridSim. Now, resources and other entities can be linked in a network topology.
  * incorporates a background network traffic functionality based on a probabilistic distribution. This is useful for simulating over a public network where the network is congested.
  * incorporates multiple regional `GridInformationService` (GIS) entities connected in a network topology. Hence, you can simulate an experiment with multiple Virtual Organizations (VOs).
  * adds ant build file to compile GridSim source files.


For more information, please visit the [GridSim website](http://www.gridbus.org/gridsim).
In this website, you will find the source code, API, documentation and simple examples.

If you have any questions, please subscribe and email to the following mailing lists:
  * gridsim-users (at) lists.sourceforge.net         - for any queries and feedbacks
  * gridsim-developers (at) lists.sourceforge.net    - for contributing to GridSim