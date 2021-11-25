:hide-toc:

********
sungorus
********
*sungorus* is an open source wireless mouse hardware implementation.

State of the project
====================

Planification and part identification stage.

.. admonition:: Roadmap

   - Initial design |:hammer:|
   - First prototype manufactured and assembled
   - Barebones firmware support
   - Documentation |:hammer:|

   ========== ================
   |:+1:|     Done!
   |:hammer:| Work in progress
   ========== ================


Specifications
==============

* Wireless


Hardware
========

* NRF52 MCU (NRF52840)
* Optical sensor [PAW3370 (if we can get our hands on it)]
* onboard conectors:
   * JST PH (2mm pitch) for USB
   * JST SH (1mm pitch) for stellite boards
* M2 mounting hardware

+--------------+
| USB   pinout |
+-----+--------+
| pin | func   |
+=====+========+
| 1 	| VCC    |
+-----+--------+
| 2 	| DM     |
+-----+--------+
| 3 	| DP     |
+-----+--------+
| 4 	| GND    |
+-----+--------+
| 5 	| Shield |
+-----+--------+

Peripheral boards are used for the buttons and encoder, available at generic-mouse-boards.


.. toctree::
   :caption: External Links
   :hidden:

   Source <https://github.com/openinput-fw/sungorus>
   Firmware <https://openinput.readthedocs.io>
   Issue Tracker <https://github.com/openinput-fw/sungorus/issues>


.. _openinput: https://openinput.readthedocs.io
