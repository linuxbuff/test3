===============================
Procedures Documentation - Demo
===============================

Introduction
============

This section describes the a demo Procedure


Check Ansible Version
=====================

Log onto Ansible
----------------

Log onto the Ansible Server as an Admin user and issue command

.. code-block:: bash

  ansible --version
  

The above will show the current Ansible version


Update Ansible Inventory
========================

The Ansible inventory uses a YAML formatted file, therefore spacing is very important. 


Update Inventory
-----------------

Add the following block to the ``/etc/ansible/hosts`` files

.. code-block:: bash

  [webserver]
  servera.demo.net



