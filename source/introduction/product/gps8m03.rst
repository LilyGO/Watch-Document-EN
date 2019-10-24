==================
T-Watch GPS
==================

.. image:: ../../_static/gps01.png


Description
==================

T-Watch GPS is an ESP32-based programmable watch kit consisting of Core PCB and GPS-M8N backplane.
You can even program T-Watch GPS with Arduino, ESP-IDF or MicroPython.

.. image:: ../../_static/model4.jpg

Feature
==================

- Main chip: ESP32, dual core MCU (integrated dual mode Bluetooth/wifi), PMU power management
- Display: 1.54 inch LCD capacitive touch screen
- Sensor: BMA423 three-axis accelerometer, built-in step counting algorithm, activity recognition / tracking, advanced gesture recognition, etc.
- Combination kit: lithium battery, design open mold, and thick strap, and black and white
- Development platform: ESP-IDF (native SDK), Arduino, Lua, MicroPython, Scratch
- Support **GPS Positioning** Function: * Latitude, Latitude, Altitude * Data Acquisition
- Support **TF card read and write**
- Support for expandable module use

Pin details
==================

Display
++++++++++++++++++

=============== ==============  ====================================
 ESP32            Attribute      Description
=============== ==============  ====================================
 GPIO05           CS             TFT_CS
 GPIO18           SCLK           TFT_SCLK
 GPIO19           MOSI           TFT_MOSI
 GPIO27           DC             TFT_DC
 GPIO12           BL             TFT_BL
=============== ==============  ====================================


TF Card
+++++++++++++++++

=============== ==============  ====================================
 ESP32            Attribute      Description
=============== ==============  ====================================
 GPIO13          CS              TF_CS
 GPIO15          MOSI            TF_MOSI
 GPIO02          MISO            TF_MISO
 GPIO14          SCLK            TF_SCLK
=============== ==============  ====================================

NEO GPS M8N
+++++++++++++++++
=============== ==============  ====================================
 ESP32            Attribute      Description
=============== ==============  ====================================
 GPIO33           TX             UART_GPS_TX 
 GPIO34           RX             UART_GPS_RX
=============== ==============  ====================================

Demo program 
==================

 - `Github Source code <https://github.com/Xinyuan-LilyGO/TTGO-T-Watch>`_


