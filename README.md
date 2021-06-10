# CNC3018Bluetooth
 HM-10 based bluetooth module for CNC 3018 (Pro). Works with Woodpecker 3.4 and other compatible CNC controller boards.
 
 [Video introducing/testing this project](https://youtu.be/gbWO2Mq1XHM)

## HM-10 configuration
 This add-on module is ment to be used with HM-10 based USB dongle.
 Starting from HM-10 default configuration, CNC add-on module works as is, but USB-dongle needs to be set as Central/Master with "AT+ROLE1".
 
 It's recommended to use firmware version V700 or newer, which has correct baud rate and possibly other configurations as default. Hm-10 modules with older firmware may or may not work.
 
 ## Changes
 Following fixes were made after the video, but before initial commit:
 * Ground pour removed behind the antenna
 * HM-10 ground pads are actually connected to the circuit :)