# Maverick Storm 4 Profile

## Software Versions

[V2.240709 - Maverick Storm 4 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM4PROFILE/blob/7cd15a668b87e582e9020f2c3ff591d070c6e8be/firmware/V2.240709.zip)
- Added Sunshield On/Off in the Control channel
     * When the Sunshield is in the light path, dimmer will be off, and zoom and focus are uncontrollable. Power cycle will keep the same settings before power off.

[V2.240217 – Maverick Storm 4 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM4PROFILE/blob/433e131667b0a525a6a6005bc9e8c485840a63d0/firmware/V2.240217.zip)
-	Updated Sky Tracker Mode
-	Fixed IGMP subscription issues
  
[V2.231005 – Maverick Storm 4 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM4PROFILE/blob/433e131667b0a525a6a6005bc9e8c485840a63d0/firmware/V2.231005.zip)
-	Fixed Sunshield locate bug

&nbsp;

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
