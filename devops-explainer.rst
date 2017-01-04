################
DevOps Explainer
################

This is a quick overview of technologies I don't understand. :)

Not included here: services themselves, like databases, web servers, load
balancers, etc.


Definitions
===========

AppArmor
  lorem ipsum quia dolor sit amet consectetur adipisci velit, sed quia non
  numquam eius modi tempora incidunt. 

cgroups
  Definition of cgroups

chroot
  lorem ipsum quia dolor sit amet consectetur adipisci velit, sed quia non
  numquam eius modi tempora incidunt. 

container
  Operating-system-level virtualization is a server virtualization method in which the kernel of an operating system allows the existence of multiple isolated user-space instances, instead of just one. Such instances, which are sometimes called containers, software containers, virtualization engines or jails, may look and feel like a real server from the point of view of its owners and users. [Wikipedia: `Operating-system-level virtualization <https://en.wikipedia.org/wiki/Operating-system-level_virtualization>`_]

LXC
  lorem ipsum quia dolor sit amet consectetur adipisci velit, sed quia non
  numquam eius modi tempora incidunt, ut labore et dolore magnam aliquam
  quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem
  ullam corporis suscipit laboriosam. 

virtualization
  Creating a number of virtual machines on one physical machine.


Technologies
============


Containers
----------


* `Docker`_


Virtual Machines
----------------

* Virtualbox
* VMware


Code-running-things
-------------------

* Ansible: an open-source automation engine that automates cloud provisioning, configuration management, and application deployment. [Wikipedia: `Ansible <https://en.wikipedia.org/wiki/Ansible_(software)>`_]

* Chef
* Puppet


Container formats
-----------------

* Docker Image
* `Open Container Initiative`_


Container runtimes
------------------

* `Docker Engine`_
* rkt


Container orchestration
-----------------------

* Kubernetes
* Mesos
* Fleet
* `Docker Swarm`_


Provisioning
------------

* `Docker Compose`_
* Ansible-container


Deployment environments
-----------------------

* Rancher
* ECS / GCS


Distributed configuration stores
--------------------------------

* `Consul`_
* etcd
* zookeeper


More things
===========


Other things to put someplace
-----------------------------

* fleet
* Jenkins
* `Nomad`_
* `Packer`_
* `Terraform`_
* Travis
* `Vagrant`_
* `Vault`_
* `Docker Registry`_
* `Docker Machine`_
* `Kitematic`_


Other sources of information
----------------------------

* https://coreos.com/docs/


.. End of the doc.  Links go down here:

.. _Consul: https://www.consul.io/
.. _Docker: https://docs.docker.com/
.. _Docker Compose: https://docs.docker.com/compose/
.. _Docker Engine: https://www.docker.com/products/docker-engine
.. _Docker Machine: https://docs.docker.com/machine/
.. _Docker Registry: https://github.com/docker/distribution
.. _Docker Swarm: https://docs.docker.com/swarm/
.. _Kitematic: https://kitematic.com/
.. _Nomad: https://www.nomadproject.io/
.. _Open Container Initiative: https://www.opencontainers.org/
.. _Packer: https://www.packer.io/
.. _Terraform: https://www.terraform.io/
.. _Vagrant: https://www.vagrantup.com/
.. _Vault: https://www.vaultproject.io/
