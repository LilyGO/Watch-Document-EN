================
Getting Started
================

This document is intended to guide users on how to use T-Wath

.. figure:: ../../_static/get_started1.jpg
   :scale: 100
   :align: center

Restore factory procedures
============================

Setting up the operating environment
+++++++++++++++++++++++++++++++++++++
* :ref:`get-stared-build`
* :ref:`get-stared-config`
* :ref:`get-stared-download`
* :ref:`get-stared-use`

.. _get-stared-build:

1. Environmental construction
===============================

Install Flash Download Tools 
++++++++++++++++++++++++++++++

ESP Flash Download Tool: :download:`Download <https://www.espressif.com/sites/default/files/tools/flash_download_tools_v3.6.5_0.zip>`
  

.. figure:: ../_static/firmware2.png 
   :scale: 100
   :align: center


Install the CP2104 driver
+++++++++++++++++++++++++++

* :download:`CP2104-Win10 <https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip>`

Download firmware
++++++++++++++++++++

The firmware can be obtained by going to :ref:`resource download/firmware<firmware_download>`.

.. _get-stared-config:

2. Download settings
====================
.. figure:: ../_static/firmware3.png 
   :scale: 100
   :align: center

The ``ESP Flash Tool`` setting operation is as follows:

* ``COM``: Burn device port selection, if there is only one device, you can choose directly.
* ``BAUD``: Download the baud rate, suggest 921600
* ``SPI SPEED``: 40MHz
* ``SPI MODE``: DIO
* ``FLASH SIZE``: 128Mbit


============================= =========================================================   
 File                          Address                                                   
============================= =========================================================    
 boot_app0.bin                    0xe000
 bootloader_dio_80m.bin           0x1000
 T-Watch.ino.partitions.bin       0x8000
 T-Watch.ino.bin                  0x10000
============================= =========================================================   


.. _get-stared-download:

3. Download firmware
======================
.. figure:: ../_static/flash_firmware1.gif
   :scale: 100
   :align: center

.. important::
    Please wait until the lower left corner of the interface displays Finish, then close the software.

.. _get-stared-use:

4. Normal use
==============


