
#C-GM Counter - Connected Geiger-Müller Counter (IoT)
by AdNovea (c)2018

**************************************************************************************
C-GM Counter (IoT) continuously monitors Beta/Gamma radiation levels acquired from Geiger-Muller Counters.

This project is aimed for providing real-time monitoring of the radioactivity level on Smartphones, Tablets or Desktops. It is made of an Open-source QNAP IoT application written in Node-RED running on QNAP servers connected to a DIY C-GM Counter device (Open-source Hardware). This project has been developed and is provided AS IS by AdNovea®.

**C-CGM Counter:** - Device (IoT) hardware and firmware for measuring radioactivity levels.

[Alt text](images/C-GM_Counter_01.png?raw=true "C-GM Counter device")

**C-GM Manager:** - A QNAP IoT application for real-time monitoring of Beta/Gamma radiation levels acquired from DIY C-GM Geiger-Muller Counters.
[Alt text](images/CGM_Node-RED.png?raw=true "C-GM Counter device")


**A-GM Manager:** - There is also a classic QNAP QPKG installation available provifing a web application for long-term continuously monitoring and storing on local servers. (https://sourceforge.net/projects/a-gm-manager/)

**************************************************************************************
  
 
**C-GM MANAGER SPECIFICATIONS**

 - 	Language support for English only
 - 	Support for low-cost home-made C-GM Counters (see PDF building instructions)
 - 	Monitor radioactivity levels over last hour
 - 	Display current radiation level in µSv/h and maximum level over the retention period (recording)
 - 	Support Desktop computers, Tablets and Smartphone screens.

 -  Written in Node-RED (requires firmware C-GM v1.1+)

 **************************************************************************************


**NOTES**

This project demonstrates how to use JSON query data replies for IoT integration


 **************************************************************************************


**FILES**

 -  C-GM.pdf      : User manual (with building instructions)
 -  C-GM_vx.x.hex  : Firmware for Arduino Nano (keep existing bootloader)
 -  C-GM_vx.x_with_bootloader.hex : Firmware for Arduino Nano (replace existing bootloader)
 -  C-GM_x.x.json : Node-RED basic interface (flux and dashboard)
 -  A-GM_1.0.qpkg : Package for QNAP servers (automatic installation)

 **************************************************************************************


**A-GM SOFTWARE VERSIONS**

 -  **1.1** Add JSON decoding for device parameters
 -  **1.0** Initial release

**C-GM HARDWARE VERSIONS**

 -  **1.2a**  2018-12-15  EEPROM Code optimization
 -  **1.2.0** 2018-10-28  Add JSON support for IoT, change OPTIONS cmd messages
 -  **1.1.0** 2018-10-09  Fix missing Remote server IP in EEPROM, Add user define A-GM URL, Add JSON IoT support
 -  **1.0.1** 2018-09-29  Add Version in the Options list
 -  **1.0.0** 2018-08-30  Initial release


**************************************************************************************