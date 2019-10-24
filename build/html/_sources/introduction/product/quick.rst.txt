==================
T-Watch Quick
==================

.. image:: ../../_static/quick11.png


Description
==================

The T-Watch Quick Car is an ESP32-based programmable watch kit consisting of a Core PCB and Car backplane.
You can even program the T-Watch Quick with Arduino, ESP-IDF or MicroPython.

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

Quick
+++++++++++++++++
=============== ==============  ====================================
 ESP32            Attribute      Description
=============== ==============  ====================================
 GPIO26,25        PWM             MotorA_wheel 
 GPIO13,15        PWM             MororB_wheel
 GPIO2            Enabled         Drv8833_EN
=============== ==============  ====================================

Demo program 
==================

 - `Github Source code <https://github.com/Xinyuan-LilyGO/twatch-series-modules/blob/master/twatch_s7xg/twatch_s7xg.ino>`_