5.3 SiPy
========

Pinout
------

The pinout of the module is available as a `PDF file <../_downloads/Sipy_v01_1_pinout_rc.pdf>`_.


.. image:: images/pinout_sipy_screenshot.png
    :align: center
    :scale: 70 %
    :alt: LoPy Pinout
    :target: ../_downloads/Sipy_v01_1_pinout_rc.pdf


.. warning::

    DO NOT connect anything to Pins ``P5``, ``P6`` and ``P7``, as this pins are used byt the SPI bus that controls the Sigfox radio.
    These pins should be treated as ``NC``. Wiring connections to these pins will cause incorrect behaviour of the Sigfox radio.


Specsheets
----------

The specsheet of the SiPy developer version is available as a `PDF file <../_downloads/sipySpecsheetGraffiti.pdf>`_.
The specsheet of the **S01** which is the OEM version of the SiPy can be found in the following `link <../_downloads/s01SpecsheetGraffitiOEM.pdf>`_.