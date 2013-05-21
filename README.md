Android I2C Bus Scanner
=======================

An improved I2C bus scan utility for Arduino based upon i2c_scanner from:
    http://playground.arduino.cc/Main/I2cScanner

This utility is meant to replicate the basic functionality of the
Linux i2cdetect tool (familiar to Raspberry Pi users, etc.)

Note: By default we use the "quick-write" mode to scan the I2C device bus.
If using the "read-byte" mode beware that write-only devices may hang the
bus when read is requested from them.


