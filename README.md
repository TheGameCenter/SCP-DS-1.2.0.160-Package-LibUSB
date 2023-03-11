# SCP-DS-1.2.0.160-Package

I use the SCP DS Driver Package for using my PS2 controller on my PC using a PS2 to USB adapter.
To install the SCP DS Driver Package, follow the following Instructions:

1. Install and Extract the ZIP file 
2. Go to te following directory: \ScpServer\bin\ScpDriver.exe and run the file.
3. Check the following boxes: "Force Install", "Configure Service", "Bluetooth Driver", and click "Install"
4. Let the drivers install then exit the application. 

Done! You now on have the SCP driver installed! (If you are having issue with LIBUsb, go to \ScpServer\bin\SCPServer.exe and let it run in the background)

# LibUSB

I don't like SCPServer.exe to run in a minimized window, so I just use LibUSB instead. 
To install LibUSB, follow tthe following instructions:

1. Run "LIBUsb_x32_1.2.7.3.exe" and accept any licnese agreements, etc. and install.
2. In the LibUSB filter installer, select "Install a device filter" then click next.
3. Plug and unplug your USB device until you find your connected USB device, select it and install the filter.

Done! Now LibUSB will keep the USB device active!
