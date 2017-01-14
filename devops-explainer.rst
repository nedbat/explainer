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
  Operating-system-level virtualization is a server virtualization method in which the kernel of an operating system allows the existence of multiple isolated user-space instances, instead of just one. Such instances, which are sometimes called containers, software containers, virtualization engines or jails, may look and feel like a real server from the point of view of its owners and users. [`W <https://en.wikipedia.org/wiki/Operating-system-level_virtualization>`__]

  `What even is a container? <http://jvns.ca/blog/2016/10/10/what-even-is-a-container/>`_

virtualization
  Creating a number of virtual computers on one physical computer.


Technologies
============


Containers
----------

Containers provide virtual computers by virtualizing at the process, file system and permissions level: each machine has a separate set of these user-level constructs, but share the lower-level operating system.  This means less overhead per machine.

* Docker_
* LXD_


Virtual Machines
----------------

Virtual Machines provide virtual computers by virtualizing at the hardware level: each machine believes it has control of the hardware.  Each virtual machine needs a complete operating system.  This is more overhead for each machine, but also means that you can mix operating systems: a Windows host can run a Linux guest.

* Virtualbox
* VMware


Orchestration / Deployment Management
-------------------------------------

* Ansible_: an open-source automation engine that automates cloud provisioning, configuration management, and application deployment. [`W <https://en.wikipedia.org/wiki/Ansible_(software)>`__]
* Chef
* Puppet
* SaltStack_
* Fabric


Container formats
-----------------

* Docker Image
* `Open Container Initiative`_


Container runtimes
------------------

* `Docker Engine`_
* rkt_


Container orchestration
-----------------------

* Kubernetes_: a platform for automating deployment, scaling, and operations of application containers across clusters of hosts, providing container-centric infrastructure.
* Mesos_
* Fleet_
* `Docker Swarm`_


Provisioning
------------

* `Docker Compose`_
* `Ansible Container`_


Deployment environments
-----------------------

* Rancher
* ECS / GCS


Distributed configuration stores
--------------------------------

* Consul_
* etcd_
* zookeeper_


More things
===========


Other things to put someplace
-----------------------------

* AMI
* Atlas
* AWS
* Flannel_
* Jenkins
* Nomad_
* Packer_
* Terraform_
* Travis
* Vagrant_
* Vault_
* `Docker Registry`_
* `Docker Machine`_
* Kitematic_


Other sources of information
----------------------------

* https://coreos.com/docs/
* https://linuxcontainers.org/


.. End of the doc.  Links go down here:

.. _Ansible: http://docs.ansible.com/ansible/index.html
.. _Ansible Container: https://www.ansible.com/ansible-container
.. _Consul: https://www.consul.io/
.. _Docker: https://docs.docker.com/
.. _Docker Compose: https://docs.docker.com/compose/
.. _Docker Engine: https://www.docker.com/products/docker-engine
.. _Docker Machine: https://docs.docker.com/machine/
.. _Docker Registry: https://github.com/docker/distribution
.. _Docker Swarm: https://docs.docker.com/swarm/
.. _etcd: https://coreos.com/etcd/docs/latest/
.. _Flannel: https://coreos.com/flannel/docs/latest/
.. _Fleet: https://coreos.com/fleet/docs/latest/
.. _Kitematic: https://kitematic.com/
.. _Kubernetes: http://kubernetes.io/
.. _LXD: https://linuxcontainers.org/lxd/introduction/
.. _Mesos: http://mesos.apache.org/
.. _Nomad: https://www.nomadproject.io/
.. _Open Container Initiative: https://www.opencontainers.org/
.. _Packer: https://www.packer.io/
.. _rkt: https://coreos.com/rkt/
.. _SaltStack: https://saltstack.com/
.. _Terraform: https://www.terraform.io/
.. _Vagrant: https://www.vagrantup.com/
.. _Vault: https://www.vaultproject.io/
.. _zookeeper: https://zookeeper.apache.org/
