*********************************
Windows platform Arduino installation steps
*********************************

1. Download
============

.. image:: ../../_static/w_install2.png 

From the `download page <https://www.arduino.cc/en/Main/Software?setlang=en>`_ for the latest version. You can choose the installer (.exe) and Zip package.

.. note::

 We recommend that you use the first to directly install everything you need to use the Arduino software (IDE), including drivers. To use the Zip package, you need to install the driver manually. Zip files are also useful if you want to create a portable installation. After the download is complete, continue the installation. When you receive a prompt from the operating system, allow the driver installation process.

Arduino-IDE download
~~~~~~~~~~~~~~~~~~
If you cannot access the webpage due to network reasons or other factors, in order to facilitate downloading, you can directly click the link below.

Of course, for security reasons, there may be some hesitation. It can be seen from the Source code in the upper right corner , but the hyperlink points to the latest version of the IDE on the official website, which can be downloaded with confidence.

From a long-term perspective, we certainly recommend going to the Arduino official website for a brief look. Whether it is for work or study, it will be of great benefit.

* :download:`Windows Installer Exe <https://downloads.arduino.cc/arduino-1.8.9-windows.exe>`。
* :download:`Windows Installer Zip <https://downloads.arduino.cc/arduino-1.8.9-windows.zip>`。

2. Installation 
============

.. figure:: ../../_static/DRV_Capture1.png 
   :scale: 100
   :align: center

   Choose the components to install

.. figure:: ../../_static/DRV_Capture2.png 
   :scale: 100
   :align: center

   Select the installation directory

.. figure:: ../../_static/DRV_Capture3.png 
   :scale: 100
   :align: center

   click close after installation is commplete

3. Configuration
============
.. figure:: ../../_static/das2.gif 
   :scale: 100
   :align: left

..

Preference configuration:
~~~~~~~~~~~~~

* Before writing the software, we need to configure some things (working folder and language, etc.)
* Open File->Preferences and change directory.
* Can change the language, Chinese, English, Japanese, German and French, all supported.



.. note::

 Documents will save to the C drive by default. Since many expansion libraries we need in the future will be produced in this folder by default, we better set the path to a non-system disk. After setting the language, you need to restart the software to take effect.
4. Test
=========

Open the LED Blink sample code: File>Example>01.Basics>Blink.

.. figure:: ../../_static/blink.gif
   :scale: 100
   :align: left

..
