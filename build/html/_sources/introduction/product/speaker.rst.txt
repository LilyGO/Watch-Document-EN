==================
T-Watch Max98357A
==================

.. image:: ../../_static/max98.png


Description
==================

The T-Watch Max98357A is an ESP32-based programmable watch kit consisting of a Core PCB and Max98357A backplane.
You can even program the T-Watch Max98357A with Arduino, ESP-IDF or MicroPython.



.. image:: ../../_static/model4.jpg



Feature
==================

- Main chip: ESP32, dual core MCU (integrated dual mode Bluetooth/wifi), PMU power management
- Display: 1.54 inch LCD capacitive touch screen
- Sensor: BMA423 three-axis accelerometer, built-in step counting algorithm, activity recognition / tracking, advanced gesture recognition, etc.
- Combination kit: lithium battery, design open mold, and thick strap, and black and white
- Development platform: ESP-IDF (native SDK), Arduino, Lua, MicroPython, Scratch
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

Max98357A
+++++++++++++++++
=============== ==============  ====================================
 ESP32            Attribute      Description
=============== ==============  ====================================
 GPIO25           LCK            SX1276_LCK 
 GPIO26           BCK            SX1276_BCK
 GPIO33           DIN            SX1276_DIN
=============== ==============  ====================================



Demo program 
==================

 - `Github Source code <https://github.com/Xinyuan-LilyGO/twatch-series-modules/blob/master/twatch_s7xg/twatch_s7xg.ino>`_