# Qwiic Power Switch

A power switch for your Qwiic system.

![Top](https://github.com/sparkfun/Qwiic_Power_Switch/blob/master/img/Top.PNG)
![Bottom](https://github.com/sparkfun/Qwiic_Power_Switch/blob/master/img/Bottom.PNG)

![Dimensions](https://github.com/sparkfun/Qwiic_Power_Switch/blob/master/img/Dimensions.PNG)

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
- **/Hardware** - Eagle schematic and PCB design files
- **LICENSE.md** contains the licence information

## Library

- **[Arduino Library](https://github.com/sparkfun/SparkFun_Qwiic_Power_Switch_Arduino_Library)** - Library for the power switch

**_Your friends at SparkFun_**
