DragonBits
==========

&copy; Rolf Michelsen, 2013.

All rights reserved.



Introduction
------------

*DragonBits* is a collection of tools and utilities for the 1980's family of Dragon home computers.



List of tools
-------------

*   **VDKDump** (Dragon 64, DragonDos)

    Read the DragonDos diskette in drive 0 and send it in the VDK virtual diskette format to the
    serial port to a host computer.  The host computer can save this file and use it directly in
    any of the popular Dragon emulators that exist.  The program is hardcoded to communicate at
    9600 baud using 1 start bit, 8 data bits, 2 stop bits and no parity.  Hardware flow control is
    supported through the Dragon DTR and CTS signals.  Only single-sided 40 track diskettes is
    supported.
