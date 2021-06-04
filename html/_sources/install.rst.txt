=================================
Installation Documentation - Demo
=================================


Introduction
============

This section describes the Linux Installation


Check Ansible Server
====================

Log onto Ansible
----------------

Log onto the Ansible Server as an Admin (user with sudo yum) user and issue command

.. code-block:: bash

  uname -a
  cat /etc/redhat-release


The above will show the current linux version



Check yum repos
---------------

.. code-block:: bash

  yum repolist

Ensure that there are no repos with 0 items



Configure Variables
-------------------

Define additional variables

There should be an additional variables that need to be defined

.. code-block:: bash

  export DUMMYVAR=foo





Installation via Command Line
=============================

Run Job
-------

Issue the command, press ``y`` and then ``[ENTER]`` when prompted 

.. code-block:: bash

  sudo yum update

.. warning::

    This command may take some time



Reboot
------

If kernel packages were updated, issue the following command:


.. code-block:: bash

  sudo reboot



``Note:`` Confirm server reboots
