====================
T-Watch Introduction
====================

.. image:: ../_static/image3.jpg

Product introduction
====================

.. toctree::
   :maxdepth: 1

   Introduction <introduce>

============== 

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


- T-Watch onboard:

  - 1.54 inch LCD capacitive touch screen: ST7789V
  - Touch screen chip: FT5206
  - Three-axis accelerometer: BMA423
  - PMU Power Management: AXP202
  - RTC clock module: PCF8563

  - Expand the interface:

    - Support microphone: MSM261S4030H0
    - Support SPI TF memory card
    - 2 digital I/Os: GPIO25, GPIO26 (supports ADC, DAC)
    - Support I2C, UART, SPI communication protocol

.. important::
  
  The expansion function is the upgrade model and the expansion module. The basic model does not have the following functions.

- Extended features:

  - Lora module: SX1276
  - GPS communication module: NEO M8N/6M
  - GPRS communication module: SIM800L
  - Heart Rate Oxygen Sensor: MAX30102
  - Capacitive touch sensor: MRP121Q
  - Six-axis sensor: MPU6050
  - Wireless charging
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
