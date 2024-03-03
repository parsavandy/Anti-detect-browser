Important Note: Run This on a Virtual Machine and turn off antivirus and firewall
This a soft work the best and without bugs on Windows XP. So get the VmWare/VirtualBOX soft (better not the newest version), and put OS Windows XP VMware virtual machine. 

*****************************************************************************************************************************************

After you make a virtual machine on VMware with Windows XP on it, just copy the folder name to it. 

If you need to work on Windows 7, you can experience some bugs (especially with Flash), and I don't see the need for Windows 7, cause Windows XP is the same.

Part 1: Browser and flash

1. Unistall flash from your system and make sure that in folder C:/Windows/System32/Macromed/Flash is nothing. So, the folder must be empty
2. Now in the folder name, find the folder "browser" and copy it to C:/. The folder must be in disk C and it must look like this C:\browser. This is an important step, so be sure you copied it exactly to disk C

3. Now you can go to the folder "Antidetect" and click on the application Antidetect5 to open it, but don't hurry, there are a few things to make.

********************************************************************************************************************************************


Part 2: Canvas fingerprint plugin

1. Go to the folder "canvas".

2. There you will see the file anticanvas.xpi

3. Open Firefox, click CTRL+O, select this anticanvas.xpi, and install it. 

4. In the right-up corner you will see a black pictogram. Click on it.

5. Next it's simple and u can set random color, font, and font size. Now click "Save" and "Test". 

********************************************************************************************************************************************

Part 3: Changing flash system information

1. Go to browser/Data/plugins, and click on config.ini. There you can set your own information for parameters like Screen resolution, Flashver, Windows version, Language, and so on.

2. For example if in the Antidetect software you set a 1360*768 resolution, you must go to config.ini to change the resolution also to 1360*768. And like this, you must do for all the parameters. If you set in Antidetect that OS is Windows 8, you must go to config.ini and at [Winver] also must put Windows 8. As a conclusion, your Antidetect parameters must be the same like parameters in config.ini

3. To make clear why you must do it: You can change all system info, but if you have Flash enabled, flash will reveal your real info.

********************************************************************************************************************************************

Part 4: How to work with my ready workprofiles

1. Open antidetect5 application. Click on the button "Load" and from the folder "Workprofiles" select the workprofile you need.

2. You workprofile will load and on the right you will see the "JavaScript Config" window. There you can edit all the info you want (for example BuildID), and after that click below it on "Save all configs" to save it. To open the new customized browser, look at "Shortcut to browser" and click on Firefox icon.


Now you can check your system information on sites like whoer.net or ipscore. If you have any questions, don't hesitate to contact me.
