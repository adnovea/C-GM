
#C-GM Counter - Connected Geiger-Müller Counter
by AdNovea (c)2018

**************************************************************************************
C-GM Counter is a very low cost Ethernet DIY Geiger-Müller counter (radioactivity).

The overall A-GM project is aimed for providing a long-term continuous measurement of the radioactivity level. It is made of an open-source Web application running on a SOHO server (e.g. QNAP sells Small Office Home Office servers) connected to a C-GM Counter device or a compatible GMC-320 Geiger-Muller Counters from GQ Electronics LLC. Other compatible or DIY Geiger-Muller counters could also be used.  This project has been developed and is provided AS IS by AdNovea®.

**C-CGM Counter:** - Device (counter) hardware and firmware for recording radioactivity levels compatible with A-GM Manager. (https://sourceforge.net/projects/c-gm-counter/)

**A-GM Manager:** - A web application for long-term continuously monitoring and storing on local servers the Beta/Gamma radiation levels acquired from Geiger-Muller Counters.
(https://sourceforge.net/projects/a-gm-manager/)


**************************************************************************************
 
 
 
**DEVICE SPECIFICATIONS (preliminary)**

 - 	Radiation detection : beta, gamma, X-ray
 - 	GM tube : STS-5 (CTC-5) / SBM-20  (400 V operating voltage)
 - 	Language support : English only
 - 	Maximum value 65 535 CPM / 425 µSv/h (theoretical)
 - 	Display values : Current CPM, Current µSv/h, Maximum µSv/h since startup, Average µSv/h since startup, Elapsed time since startup, Level on bar graph
 - 	Alarm: User defined threshold, LCD backlight blinking, Alarm messages on LCD
 -	LED flash for each beta/gamma radiation pulse: LED blink every second if GM tube is detective, LED still on when Network connection fail
 - 	Audio sound: Beep for each beta/gamma radiation pulse, Audible sound alarm
 - 	Device control from : Device internal menu, USB (require a serial console such as Termite) or Ethernet (using a web browser)
 - 	Network connection using DHCP
 - 	Support for A-GM Manager web interface
 - 	User defined parameters (from Menu or through web interface)
 - 	GM tube conversion factor (CPM to µSv/h): Alarm threshold in CPM, Buzzer On or Off, Display timeout, Enable Network for communication to A-GM Manager, A-GM server IP definition (through USB or A-GM Manager), Internal H.V. voltmeter calibration  (through USB or A-GM Manager), 
 -  Connect to A-GM Manager for storing data and graphic display.
 -  Parameters can be permanently saved into EEPROM

 Physical Parameters:

 -  Ethernet and USB ports
 - 	Size (L x W x H) : 	158mm x H: 90mm x D: 60mm
 - 	Net weight  (w/o battery): 	76 g
 - 	Total  weight: 	315 g  (w/o probe, cable and DC pack)
 - 	Power: 	5V DC pack (~2Watts)
 -  Interface: English only

 **************************************************************************************



**FILES**

 -  CGM.pdf : User manual (with building instructions)
 -  CGM_vx.x.hex : Firmware for Arduino Nano (keep existing bootloader)
 -  C-GM_vx.x_with_bootloader.hex : Firmware for Arduino Nano (replace existing bootloader)

 **************************************************************************************



**VERSIONS**

 -  **1.2a**  2018-12-15  EEPROM Code optimization
 -  **1.2.0** 2018-10-28  Add JSON support for IoT, change OPTIONS cmd messages
 -  **1.1.0** 2018-10-09  Fix missing Remote server IP in EEPROM, Add user define A-GM URL, Add JSON IoT support
 -  **1.0.1** 2018-09-29  Add Version in the Options list
 -  **1.0.0** 2018-08-30  Initial release

**************************************************************************************