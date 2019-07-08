***************
Basics
***************



1. Introduction
================

Welcome to Arduino! Before you start your programming journey, you need to set up the software.

To write your board Arduino software (IDE) allows you to write programs and upload them to your board. In the Arduino Software page you will find two options:

1. If you have a reliable Internet connection, you should use the online IDE (Arduino Web Editor). It allows you to save sketches in the cloud, get them from any device and back them up. You will always have the latest version of the IDE without having to install an update or a community-generated library.

2. If you want to work offline, you should use the latest version of the `Desktop IDE <https://www.arduino.cc/en/Main/Software?setlang=cn>`_ 

.. important:: It is recommended to install the desktop IDE
.. image:: ../_static/w_install1.png

..
 .. image:: ../_static/das.gif
 
 

2. Arduino installation
=========================

.. toctree::
    :hidden:
    
    2.1 Windows <windows-setup>
    2.2 Linux <linux-setup> 
    2.3 MacOS <macos-setup>

+-------------------+-------------------+-------------------+
| |windows-logo|    | |linux-logo|      | |macos-logo|      |
+-------------------+-------------------+-------------------+
| `Windows`_        | `Linux`_          | `Mac OS`_         |
+-------------------+-------------------+-------------------+

.. |windows-logo| image:: ../_static/windows-logo.png
    :target: ../basics/windows-setup.html

.. |linux-logo| image:: ../_static/linux-logo.png
    :target: ../basics/linux-setup.html

.. |macos-logo| image:: ../_static/macos-logo.png
    :target: ../basics/macos-setup.html

.. _Windows: ../basics/windows-setup.html
.. _Linux: ../basics/linux-setup.html
.. _Mac OS: ../basics/macos-setup.html


3. Arduino-ESP32 construction
==============================

Please follow the detailed steps below to complete the installation process.

Setting up the development environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* :ref:`basics-install-git`
* :ref:`basics-build-config`
* :ref:`basics-git-clone`
* :ref:`basics-setup-toolchain`


.. _basics-install-git:

3.1 Install Git
=======================


Download steps:
~~~~~~~~~~~~~~~~~~~

Download the installation package Git.exe from the `Git official website <https://git-scm.com/downloads>`_

.. image:: ../../_static/git_install.png 

Steps:
~~~~~~~~~

After the download is complete, double click to open,
Always click Next until you are done.

.. figure:: ../../_static/git.gif 
   :scale: 100
   :align: center

   Installation process

Inspection steps:
~~~~~~~~~~~~~~~~~~~

After the installation is complete, click the right mouse button. You will see **Git Bash Here**
The description has been successfully installed.
We will use this software later

.. _basics-build-config:

3.2 Pre-build configuration
=============================

.. figure:: ../../_static/git_clone1.png 
   :scale: 100
   :align: center

   Open the folder where Arduino is located

.. note::

    Click on the icon, then right click and select ``Open folder where `` 

Steps：
~~~~~~~~~

* Select **hardware** ->
* Mouse ** Right click ** ->
* Click **Git Bash Here**

.. figure:: ../../_static/git_clone2.gif 
   :scale: 100
   :align: center

* ``hardware``: Arduino stores folders of supported hardware
* ``Git Bash Here``: can open Git Bash terminal in the current folder

.. _basics-git-clone:  

3.3 Cloning a remote repository
================================

The purpose of this process is to clone a remote repository from the GitHub website.

In order to make the construction process easier and prevent the problem of incomplete files, it is not appropriate to use the direct download zip here.

Create a folder:
~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

    mkdir espressif
     
Enter the folder：
~~~~~~~~~~~~~~~~~

.. code-block:: bash

    cd espressif

.. note::

    - ``mkdir``：make directory,Program function -> create a folder
    - ``espressif``：ESP32, ESP8266 and other devices are set in this folder
    - ``cd``：change directory,Program function -> change the current path

    Bash is a shell, and ``mkdir`` ``cd`` is a built-in bash command.   
Clone a remote repository:
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

    git clone --recursive https://github.com/espressif/arduino-esp32.git esp32

.. note::

    - ``git clone``：One of the git action instructions to clone a remote repository
    - ``--recursive``：One of the git action instructions to download the repository submodule directly
    - ``esp32``：Write ``esp32`` at the back of the link to change the name of the cloned repository folder. The default is Arduino-esp32.

    This must be set to esp32, because arduino will read ``arduino/hardware/espressif/esp32`` by default.
Demo video
~~~~~~~~~~~~

.. figure:: ../../_static/git_clone3.gif 
   :scale: 100
   :align: center

.. _basics-setup-toolchain:
 
3.4 Installing the Compilation Toolchain
======================

Next, install esptool, compile toolchain and other tools.

**Congratulations, this is the last step of arduino-esp32, and the victory is in sight! **

We just click on get.exe and the script will automatically download the tool for us.

Steps
~~~~~~~~~~~~
- Enter ``arduino/hardware/espressif/esp32``
- Click ``tools``
- Double-click ``get.exe`` to automatically download dependencies
- Waiting for download, cmd is automatically closed after the download is complete

Demo video
~~~~~~~~~~~~
.. figure:: ../../_static/git_clone4.gif 
   :scale: 100
   :align: center
