MooresCloud Holiday Hardware
==============

The Holiday controller is an open source hardware design, originally inspired by the [Olimex OlinuXino] (https://www.olimex.com/Products/OLinuXino/iMX233/) - a Freescale iMX233 based embedded linux development board.

We used the OlinuXino iMX233 Maxi and Micro boards during development and testing of both the Light and Holiday, before designing our own custom PCB layout to suit the form factor and specific requirements.  The Holiday also incorporates an ATmega328 (running the "Arduino" environment) that communicates with the Linux environment for handling control during Linux boot-up and providing the tight timing requirements of sending data to the WS2812 LEDs.

These designs are in Altium Designer (v13) format, and the Altium files along with the BOM, PDF, and gerber outputs are now available under the [Creative Commons Attribution Share-Alike license] (http://creativecommons.org/licenses/by-sa/2.0/au/)

Controller r2a changes crystal Y2 from 16MHz to 20MHz
- this is the version that shipped in 2013/2014, with ECO001 applied

Controller r3 incorporated ECO001 changes and some other minor improvements noted in the schematics, and should be used with Globe r4 for signal integrity and EMC

The MooresGlobe used by Holiday went through several revision for prototyping and DFM review.

Globe r2b uses the WorldSemi WS2812 (6 pin 5050 footprint)
- this is the version that shipped in 2013/2014, with ECO002 applied

Globe r3 incorporated ECO002 and some other minor improvements

Globe r4 incorporated further improvements following discussions with WorldSemi and additional signal integrity and EMC measurements. This revision uses the newer WS2812B (4 pin 5050 footprint)
