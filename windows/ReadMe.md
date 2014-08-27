Windows Vagrant Box
=======================


This vagrant box launches a windows 7 ulitimate edition environment.

----------


Prerequisites
-------------
> **You will need:**

> - Vagrant - for vagrant installation instructions click [here](https://docs.vagrantup.com/v2/installation/)
> - Ansible - for ansible installation instructions click [here](http://docs.ansible.com/intro_installation.html#installation)

How To Run
-------------
> **The steps to initialize the windows7 vagrant box is as follows:**

  1. Open a terminal window.
  2. **git clone** https://github.com/medullan/starter-stacks.git
  3. **cd** starter-statcks
  4. **cd** windows
  5. **vagrant up**

----------

How To Access the VM
-------------
> **To access the remote desktop protocol(RDP) has to be used. This is done by typing:**

  * **vagrant rdp**
  * The windows environment (GUI) should then be displayed after executing this command

Know Issues
-------------
  * In some instances the **rdp client** may fail to connect. If this occurs you will have to launch the
    windows7 vm from virtual box  and allow remote desktop connections. Click [here](http://windows.microsoft.com/en-us/windows7/allow-remote-desktop-connections-from-outside-your-home-network)
    to find out how to allow a remote desktop connection on windows 7
