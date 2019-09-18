******
Pinout
******

Here you can find all the connectors pinout. 

.. note:: All the part number are for the female connector!

Top view
========

.. figure:: _img/pinout/pinout_top.jpg
   :align: center
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   1, `Micro USB`_,
   2, SD_,
   3, Contactor_, Wurt Elektronik - 662008113322
   4, `Power input`_, Wurt Elektronik - 662004113322
   5, `Current sensors`_, JST - PHR-6

Bottom view
===========

.. figure:: _img/pinout/pinout_bottom.png
   :align: center   
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   6, `Ethernet`_, 
   7, AUX_, JST - PHR-10
   8, AUX2_, JST - PHR-3
   9, `RCD`_, JST - PHR-4
   10, `I2C`_, JST - PHR-5

Front view
==========

.. figure:: _img/pinout/pinout_front.png
   :align: center   
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   11, `Front Panel`_, JST - PHR-5

Connectors
==========

Micro USB
---------
Useful for USB host device

.. warning:: Max 250 mA


SD
--
Micro SD slot to expand storage space 

Contactor
---------

.. figure:: _img/pinout/contactor_connector.jpg
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1,
   2,
   3,
   4,
   5,
   6,
   7,
   8,

Power input
-----------

.. figure:: _img/pinout/pwr_connector.jpg
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, L3, Third phase
   2, L2, Second phase
   3, N, Neutral
   4, L1, First phase

Current sensors
---------------
.. figure:: _img/pinout/curr_sensor_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, A_P, Phase A TA input 1
   2, A_N, Phase A TA input 2
   3, B_P, Phase B TA input 1
   4, B_N, Phase B TA input 2
   5, C_P, Phase C TA input 1
   6, C_N, Phase C TA input 2

Ethernet
--------
TODO little description

AUX
---
.. figure:: _img/pinout/aux_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1,
   2,
   3,
   4,
   5,
   6,
   7,
   8,
   9,
   10,

AUX2
----
.. figure:: _img/pinout/aux2_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, VCC, 5V
   2, LEDOUT, "Programmable digital output, internally pulled up" 
   3, GND, Ground

RCD
---
.. figure:: _img/pinout/rcd_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, GND, Ground
   2, +12V, 12V
   3, TEST, RCD test output
   4, RCD_FAULT, RCD fault input

I2C
---
.. figure:: _img/pinout/5x1_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, NC, "\-"
   2, SCL, I2C SCL
   3, SDA, I2C SDA
   4, 3V3, "3.3V"
   5, GND, Ground

Front Panel
-----------
.. figure:: _img/pinout/5x1_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, RST, Reset
   2, RX, Serial receive
   3, TX, Serial transmit
   4, 5V, 5V
   5, GND, Ground
