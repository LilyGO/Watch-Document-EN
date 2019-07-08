====================
T-Watch Introduction
====================


.. image:: ../_static/image3.jpg

Product Categories
===================

==================  ==================  ==================
|Standtrd|_           |SIM800L|_         |GPS|_
------------------  ------------------  ------------------
`Standtrd`_           `SIM800L`_         `GPS`_
------------------  ------------------  ------------------
|MPR121|_              |Lora+GPS|_      |To be continued|_
------------------  ------------------  ------------------
`MPR121`_              `Lora+GPS`_      `To be continued`_
==================  ==================  ==================

.. |Standtrd| image:: ../_static/std1.png
.. _Standtrd: ../introduction/standtrd.html

.. |MPR121| image:: ../_static/basic01.png
.. _MPR121: ../introduction/mpr4.html

.. |SIM800L| image:: ../_static/SIM02.png
.. _SIM800L: ../introduction/sim02.html

.. |GPS| image:: ../_static/GPS3.png
.. _GPS: ../introduction/gps8m03.html

.. |Lora+GPS| image:: ../_static/s76g05.png
.. _Lora+GPS: ../introduction/s76g05.html

.. |To be continued| image:: ../_static/tobe06.png
.. _To be continued: ../introduction/tobe06.html



Hardware overview
==================

Category
--------------

* :ref:`technical-parameters`
* :ref:`appearance-specification`
* :ref:`component-layout`
* :ref:`pin-definition`


.. _technical-parameters:

1.Technical Parameters
========================


- T-Watch onboard:

  - 1.54 inch LCD capacitive touch screen: ST7789V
  - Touch screen chip: FT5206
  - Three-axis accelerometer: BMA423
  - PMU Power Management: AXP202
  - RTC clock module: PCF8563


.. figure:: ../_static/get_started2.jpg 
   :scale: 40
   :align: center


- **ESP-32** Master control：

  - Processors:

    - CPU: Xtensa dual-core 32-bit LX6 microprocessor, operating at 240 MHz
    - Ultra low power (ULP) co-processor
  - Memory: 520 KiB SRAM

  - Wireless connectivity:

    - Wi-Fi: 802.11 b/g/n
    - Bluetooth: v4.2 BR/EDR and BLE

  - Power supply：Type-C USB/Lithium battery
  - Operating Voltage：3.3V
.. note::
  
  ESP32 was created and developed by Lexin Information Technology, a Shanghai-based Chinese company, and manufactured by TSMC using 40-nanometer technology.
  It is the successor to the ESP8266 microcontroller.

Boot demo video
-----------------
.. figure:: ../_static/gif4.gif
  :scale: 100
  :align: left

Interface switching video
-----------------------------
.. figure:: ../_static/gif5.gif
  :scale: 100
  :align: left



.. _appearance-specification:

2. Appearance specifications
=============================

.. image:: ../_static/model1.jpg

.. _component-layout:

3. Component layout
=============================

.. image:: ../_static/model2.jpg

.. image:: ../_static/model3.jpg
.. _pin-definition:

4. Pin definition
=============================

.. image:: ../_static/model4.jpg
