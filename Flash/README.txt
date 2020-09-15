AMCNF(Audio Moth Custom Naming Firmware) 
Created by: Carter Andrew, Conservation Metrics, Santa Cruz, CA
This program was based off of the "AudioMoth-Firmware-Basic-1.2.1" firmware provided by Open Acoustic Devices
WARNING: This firmware has not been tested for battery performance effects.
For More information on AudioMoths please go to the following link: (https://www.openacousticdevices.info/getting-started)

DESCRIPTION:

	AMCMF is a custom made firmware to provide a more intuitive and easy way to identify the AudioMoth devices. After installing and creating the custom name(described below) the name of the device will appear in the name of each of the files produced by the AudioMoth device in the format below:

	Example:

		Name: YourDevice1, Time: 12/3/2019 000007 seconds

		File Produced: YourDevice1_20191203_000007.wav 

INSTALLATION/FLASH GUIDE:

1) Without the audiomoth connected to the computer. Open up your computer's version of a command line: Terminal on Mac and Linux, Command Prompt on Windows

1.5) On macOS and Linux you must now set the permissions of the file. To do this, open a terminal, navigate to the location of the flash file and run the following command: "chmod a+x flash"

2) Change the directory of the command prompt so you are in the folder this README document was found in

3) Type in "flash.exe" for windows(Look in the folder for the linux and mac versions), this will show you all of the connected USB devices, when you run this function with the audiomoth connected it should have a new port show up. For more information on flashing an audiomoth go to the following link: (https://www.openacousticdevices.info/flashing)

4) Remove all AA batteries from the AudioMoth and place in custom mode

5) Plug the AudioMoth into the computer. Both LED lights should turn on. 

6) Use a paperclip or other small piece of conductive metal to connect the two prongs with the white arch over them and the label "prog". For more information on flashing an audiomoth go to the following link: (https://www.openacousticdevices.info/flashing)

7) Check that the LED lights on the device have turned off. 

8) Run the flash.exe command again and check for a new port. If one does not show up, unplug the device and repeat steps 5-7

9) Now type this in to the command prompt using the port found in step 8:(Replace the YOURPORT with the port you discovered in step 8) "flash.exe -u YOURPORT AMCNF.bin".

10) Wait 5 seconds with the device plugged in. The LED should light back up to display either a red or green light. 

CREATING CUSTOM NAME GUIDE:

1) Open notepad or the linux or mac counterparts. 

2) Type in the custom name you want for the device, make sure it is less than 30 characters. 

3) Save the file as "DeviceName" and make sure that the file is a .txt filetype

4) Place this name on to the Micro SD card that will be used by the AudioMoth

WARNING: This file MUST stay on this SD card and in the AudioMoth at all times for proper functioning of the program

CHECKING FOR SUCCESS:

1) Insert all of the batteries back into the AudioMoth

2) While the switch is on CUSTOM check that the red LED is on. If so, this means you have successfully installed the firmware. 

3) Change the switch location to USB/OFF and then insert the Micro SD card with the DeviceName.txt file on it. 

4) Change the switch back to CUSTOM, the Green LED should now be on. If so, you have successfully finished this setup guide. Your device is ready to be configured for recording dates. If you do not already have the configuration app please head to the following link: (https://www.openacousticdevices.info/config)

UNINSTALLATION GUIDE:

1) Without the audiomoth connected to the computer. Open up your computer's version of a command line: Terminal on Mac, Command Prompt on Windows

2) Change the directory of the command prompt so you are in the folder this README document was found in

3) Type in "flash.exe", this will show you all of the connected USB devices, when you run this function with the audiomoth connected it should have a new port show up. For more information on flashing an audiomoth go to the following link: (https://www.openacousticdevices.info/flashing)

4) Remove all AA batteries from the AudioMoth and place in custom mode

5) Plug the AudioMoth into the computer. Both LED lights should turn on. 

6) Use a paperclip or other small piece of conductive metal to connect the two prongs with the white arch over them and the label "prog". For more information on flashing an audiomoth go to the following link: (https://www.openacousticdevices.info/flashing)

7) Check that the LED lights on the device have turned off. 

8) Run the flash.exe command again and check for a new port. If one does not show up, unplug the device and repeat steps 5-7

8.5) If there is a newer version of the AudioMoth Firmware you wish to install on you should download it from the website and place the .bin file into the same folder as this README file. Then replace "AudioMoth1.2.1" in step 9 with the file name. 

9) Now type this in to the command prompt using the port found in step 8:(Replace the YOURPORT with the port you discovered in step 8) "flash.exe -u YOURPORT AudioMoth1.2.1.bin".

10) Wait 5 seconds with the device plugged in. Both LED lights should light up.

            
