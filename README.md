# Archer_C20_V5_US
If you planned to go back from custom ROM to Stock ROM, use this to flash your router.

You need to use TFTPD method to flash.

Step 1: download tftpd64 from here https://bitbucket.org/phjounin/tftpd64/downloads/
Step 2: Connect your router to PC/Laptop using ethernet cable.
Step 2: open RUN dialogue box (Windows Key + R) and type ncpa.cpl
Step 3: right click on your adapter and click properties
Step 4: Select Internet Protocol Version 4 and click on properties
Step 5: click on Use the following IP address
Step 6: Type 192.168.0.66 in IP address, 255.255.255.0 in Subnet mask field, then 192.168.0.1 in Default gateway.
Step 7: click OK.
Step 8: Download the tp_recovery.bin and save it to a new folder name "TFTPD" on desktop.
Step 9: Open TFTPD64 and click browse on current directory then select the folder TFTPD from desktop.
Step 10: Click on server interface drop down menu then select 192.168.0.66.
Step 11: Use a toothpick to press and hold reset button on router, while holding reset button connect the power cord.
Step 12: open RUN dialogue box (Windows Key + R) and type ncpa.cpl
Step 3: right click on your adapter and click properties
Step 4: Select Internet Protocol Version 4 and click on properties
Step 5: click on Obtain an IP address automatically.

Viola !!! you are back to stock ROM.
