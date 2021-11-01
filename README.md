# Qwiic Power Switch

A power switch for your Qwiic system.

[![Qwiic Power Switch (SPX-16740)](https://cdn.sparkfun.com//assets/parts/1/5/6/2/8/16740-Power_Switch-01.jpg)](https://www.sparkfun.com/products/16740)

[Qwiic Power Switch (SPX-16740)](https://www.sparkfun.com/products/16740)

The Qwiic Power Switch is a simple little board which can be used to switch the power to your Qwiic
system. Many Qwiic boards draw very little current when not being used, but there are some that draw
significantly more. The power switch allows you to switch the power to those boards, so you can minimize the
current draw and extend your battery life when you need to.

When the Qwiic Power Switch is turned off, the I2C wires are isolated too which prevents the pull-up
resistors from feeding parasitic power to your Qwiic boards. The power switch can also be used to
isolate a 400kHz bus from a 100kHz bus; the slower bus can be disconnected during fast-mode communication
without disabling the power.

The heart of the Qwiic Power Switch is the TI PCA9536 4-Bit I2C I/O Expander. We have broken out GPIO pins
1 and 2 so you can use them as general purpose inputs or outputs.

## Repository Contents

- **/Documents** - Datasheets etc.
- **/Hardware** - Eagle design files
- **LICENSE.md** contains the licence information

## Library

- **[Arduino Library](https://github.com/sparkfun/SparkFun_Qwiic_Power_Switch_Arduino_Library)** - Library for the power switch

## License Information

This product is _**open source**_!

Please review the LICENSE.md file for license information.

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=123).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
