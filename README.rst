====================
ansible-role-gearman
====================

Ansible role to manage Gearman

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-gearman.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-gearman
* Bugs: https://bugs.launchpad.net/ansible-role-gearman

Description
-----------

A pure-Python asynchronous library to interface with Gearman.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install gearman
      hosts: gearman
      roles:
        - ansible-role-gearman
