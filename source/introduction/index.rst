====================
T-Watch Introduction
====================


.. image:: ../_static/image3.jpg

Product Categories
===================

==================  ==================  ==================
|Standard|_           |SIM800L|_         |GPS|_
------------------  ------------------  ------------------
`Standard`_           `SIM800L`_         `GPS`_
------------------  ------------------  ------------------
|MPR121|_              |Lora+GPS|_      |To be continued|_
------------------  ------------------  ------------------
`MPR121`_              `Lora+GPS`_      `To be continued`_
==================  ==================  ==================

.. |Standard| image:: ../_static/std1.png
.. _Standard: ../introduction/standtrd.html

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

Expansion module
====================

====================  ====================  ====================
  |Button|_             |Buzzer|_               |WS2812_RGB|_
--------------------  --------------------  --------------------
  `Button`_             `Buzzer`_               `WS2812_RGB`_
--------------------  --------------------  --------------------
|DHT12_Sensor|_        |Pir|_                |Photoresistance|_
--------------------  --------------------  --------------------
`DHT12_Sensor`_        `Pir`_                `Photoresistance`_
--------------------  --------------------  --------------------
|Relay|_                |Raindrop|_           |Door_Contact|_
--------------------  --------------------  --------------------
`Relay`_                `Raindrop`_           `Door_Contact`_
--------------------  --------------------  --------------------
|Microphone|_           |Servo|_              |Dou_Function|_
--------------------  --------------------  --------------------
`Microphone`_           `Servo`_              `Dou_Function`_
--------------------  --------------------  --------------------
|Potentiometer|_        |Soil_Moisture|_      |To be continued|_
--------------------  --------------------  --------------------
`Potentiometer`_        `Soil_Moisture`_      `To be continued`_
====================  ====================  ====================

.. |Button| image:: ../_static/button1.png
.. _Button: ../introduction/button1.html

.. |Buzzer| image:: ../_static/buzzer2.png
.. _Buzzer: ../introduction/buzzer2.html

.. |DHT12_Sensor| image:: ../_static/dht3.png
.. _DHT12_Sensor: ../introduction/dht3.html

.. |WS2812_RGB| image:: ../_static/rgb4.png
.. _WS2812_RGB: ../introduction/rgb4.html

.. |Pir| image:: ../_static/pir5.png
.. _Pir: ../introduction/pir5.html

.. |Photoresistance| image:: ../_static/photo6.png
.. _Photoresistance: ../introduction/photo6.html

.. |Relay| image:: ../_static/relay7.png
.. _Relay: ../introduction/relay7.html

.. |Raindrop| image:: ../_static/raindrop8.png
.. _Raindrop: ../introduction/raindrop8.html

.. |Door_Contact| image:: ../_static/door9.png
.. _Door_Contact: ../introduction/door9.html

.. |Potentiometer| image:: ../_static/poten10.png
.. _Potentiometer: ../introduction/poten10.html

.. |Soil_Moisture| image:: ../_static/soil11.png
.. _Soil_Moisture: ../introduction/soil11.html

.. |To be continued| image:: ../_static/tobe06.png
.. _To be continued: ../introduction/tobe06.html

.. |Microphone| image:: ../_static/mic.png
.. _Microphone: ../introduction/mic12.html

.. |Servo| image:: ../_static/servo.png
.. _Servo: ../introduction/servo13.html

.. |Dou_Function| image:: ../_static/dou.png
.. _Dou_Function: ../introduction/dou14.html

.. toctree::
   :hidden:
   :maxdepth: 2
   :numbered:
   
   Button <button1> 
   Buzzer <buzzer2>
   WS2812 <rgb4>
   DHT12_Sensor <dht3>
   Pir <pir5>
   Photoresistance <photo6> 
   Relay <relay7>
   Raindrop <raindrop8>
   Door_Contact <door9>
   Microphone <mic12>
   Servo <servo13>
   Dou_Function <dou14>
   Potentiometer <poten10>
   Soil_Moisture <soil11>

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
