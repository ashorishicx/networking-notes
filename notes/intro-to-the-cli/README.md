# Intro to the CLI
"Cisco IOS" is the operating system used on cisco devices (like Windows on a PC, or MacOS on a iMac) that allows you to make configurations to the cisco device. Making configurations means making changes to the settings of the device, such as enabling or disabling the AUTO-MDIX feature of a switch. The Cisco IOS is a command line interface (CLI), meaning you enter commands.

## Table of Contents
- [How do you access the CLI?](#how-do-you-access-the-cli)

## How do you access the CLI?
There are several methods to access a cisco device's CLI:
- via Console
- remotely via SSH or Telnet (we will cover these methods in later lessons)

### Console Connection
- you will need a laptop to type the commands on the CLI
- you will need a **rollover cable** (DB9 serial to RJ45 OR a DB9 Serial to USB) that connects the laptop to the cisco device's console port
- after plugging in, you need a **terminal emulator** app on your laptop (ex. PuTTy is a popular choice) and select connect via "Serial"

<img src="images/console-port.png" width="32.1375%"><img src="images/rollover-cables.png" width="60%">\
The blue cable is the rollover cable. Most laptops today don't have a serial port, so you will likely also need to use that black cable on the left to that connects to the serial connector of the rollover cable, and have the USB connector connect to the laptop. 

On the right is an image changes you can make to your console connection. You rarely will need to make changes to these and you do not need to know what it means, but you should memorize the default settings.
