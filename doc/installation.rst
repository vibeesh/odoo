========================================
Installation
========================================

.. toctree::
   :maxdepth: 1

Overview
========
Installation of Odoo is really easy. We built a comprehensive library of best
practices coded into a human readable installation protocol language called Ansible.
Those protocols are well commented so you might find all the information you need right at the source.

What you need for a kickstart is:

.. code-block:: python
    :linenos:

    ubuntu 14.04 LTS # A local Virtual Machine is recommended, you can find some preconfigured boxes at vagrant.com/odoo
    if Windows == True: Oracle VirtualBox
    sudo apt-get install ansible # you cann browse available protocols ("playbooks") here: www.github.com/odoo/playbooks
    # Probably you should adapt them to your needs, they are all very well commented
    ansible go # that's it

Dev-Tools
=========
If you want start coding, we collected here some tools we love:

   - Pycharm
   - Vim
   - Vagrant/Docker Environment
   - A collection of useful and approved code snippets for your IDE: link here to a github
   - Xpath browser

(with links to further information)

Security and Performance
========================
Advanced section, which is written in a way that lets the customer know, that this is all very secure and very performant, cutting edge technology

Scalability
===========
Here some vps, opennebula, amazon, private serverfarm, etc... stuff to guide (professionals) AND impress (customers)