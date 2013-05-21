Arduino i2cscanner
==================

An updated i2cscanner utility for Arduino based upon the i2cscanner at:
    http://playground.arduino.cc/Main/I2cScanner

This utility is meant to replicate the basic functionality of the
Linux i2cdetect tool.

Note: By default we use the "quick-write" mode to scan the i2c device bus.
If using the "read-byte" mode beware that write-only devices may hang the
bus when read is requested from them.


