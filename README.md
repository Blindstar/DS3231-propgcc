DS3231-propgcc
==============

A propgcc i2c driver for the DS3231 real time clock

This code runs in a single cog.  It was desigened to be started buy a process runing in the xmmc kernel.  It reads the DS3231 and updates a time/date buffer in shared hub memeory.  It does its own i2c bit banging becaue the propgcc libaries were too large.
