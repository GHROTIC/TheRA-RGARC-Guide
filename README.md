# <p align=center>The Retro Arena Firmware Guide for the RG ARC</p>
#### **<p align=center>Current Version: Beta 10</p>**
<p align=center><img src=https://i.imgur.com/lTJdQyN.jpg width=60%></p>

<br>

## <p align=center>Installation:</p>

*<p align=center>Joey's Retro Handheld's has made a good starter video for installing the Firmware(Beta 9). If you find it helpful be sure to give him a like and a subscribe:</p>*

<br>

 [<img src=https://img.youtube.com/vi/dTAqpZinv2M/0.jpg width=40%>](https://www.youtube.com/watch?v=dTAqpZinv2M)

<br>
<br>

## <p align=center>Known Issues:</p>

- *Attempting to manually scrape in the Edit Metadata section of a Rom causes EmulationStation to crash and restart*
- *Nintendo 64 games in 7z or zip files are not detected. This can be fixed by adding ".zip .ZIP .7z .7Z" extensions to the Nintendo - 64 section of the es_systems.cfg file. This file can be found in ./etc/emulationstation/*
- After opening Arcupdate Select+Start makes the system lock up instead of exiting the program. The only way out is to hold the power button to shut the device down.
+ *Some games may not run correctly with the default settings or they require an analog stick.

<br>
<br>

## <p align=center>FAQ & Troubleshooting:</p>

### 1. What software should I use to flash my Micro SD Card?

###### ***The community considers [Rufus](https://rufus.ie) to be the most reliable.***

### 2. What format should my Micro SD Cards be in?

###### ***Your TF1/SD1 card will have the correct formatting applied when you flash the image with Rufus. Your TF2/SD2 card may be formatted ExFat or NTFS but it is recommended to use NTFS.***

### 3. I've installed TheRA Custom Firmware onto my MicroSD Card but the screen is black when I turn it on. What should I do?

###### ***This can happen if the image didn't properly flash or it has been flashed on a poor quality 16GB Micro SD card that doesn't truthfully have 16GB(i.e. the stock RG ARC OS Card). If it's a known good card then try Re-Flashing the image on a different computer or with a different Micro SD Card Reader.***

### 4. How do I switch my Rom storage to/from SD Card 1 and SD Card 2?

###### ***Go to the Main Menu, select Options -> Advanced. Switch to SD2 for Roms or Switch to main SD for Roms will be in the directory depending on what you already have active.***

### 5. How do I connect to WiFi?

###### ***Go to the Retroarch folder in the Main Menu and open Retroarch. Go to Settings -> Wi-Fi -> Connect to Network.***

### 6. My Networks are missing in the Retroarch Wi-Fi -> Connect to Network Menu. How do I make them appear?

###### ***If Retroarch Scans for Networks and doesn't find your Network you will need to back out with the B button twice and Quit Retroarch. In the Main Menu go to Options -> Advanced -> WIFION(Options -> WIFION if you have folders hidden) and your system will reboot. Once you go back to Connect to Network in Retroarch your Networks should now appear.***

### 7. How do I update the software?

###### ***Once you are connected to Wifi you can go into Options -> Arcupdate to open the OTA Update Software. By default it will have "Updating to the latest Version" highlighted and you will only need to press the A button to confirm. Once the update has completed and you are back at the Main Menu go to Options -> Fix Permissions. After the Fix Permissions script sends you back to the Main Menu press the Start Button and go down the menu to Quit -> Restart.***

### 8. My power button doesn't put the ARC into Sleep Mode and/or my Volume Buttons aren't working. What should I do?

###### ***Go to the Main Menu, select Options -> Fix Permissions. After the Fix Permissions script sends you back to the Main Menu press the Start Button and go down the menu to Quit -> Restart.***

### 9. Scraper tells me to "Refresh update games lists to apply changes" but how do I update the game list?

###### ***Press the Start Button in the Main Menu, go to Quit at the bottom and select to Restart EmulationStation to update your Game Lists. In some cases your games may fail to show the correct images until you Restart System instead.***

### 10. How do I change my Theme?

###### ***Go to the Main Menu, select Options -> Misc -> Thememaster to download new Themes. Some themes are not fully compatible and will have text alignment/size issues(i.e. ES-THEME-EPICNOIR). Avoid ES-THEME-RETRONEON as it is completely broken with missing text. If you happen to get yourself locked on an unreadable theme just press the B Button a bunch of times to make sure you are in the Main Menu. Then press: Start Button, Down, A, A, UP, A, B.***

### 11. How do I open the Configuration Menu while playing a game?

###### ***By default this is set to L2 + R2 for Retroarch based emulators and can be changed within the Retroarch Input -> Hotkeys Settings. For Yaba Sanshiro Standalone(Sega Saturn) you can use the Select Button.***

### 12. Why do I not see the C and Z buttons in the Retroarch controller configuration?

###### ***Within Retroarch the setting for Z will be the L3 button and C will be the R3 button.***

### 13. How do I exit a game?

###### ***By default this is set to F(Function Key on the top of the device) twice.***

### 14. How do I use SSH for file transfers over WiFi?

###### ***[Filezilla](https://filezilla-project.org) is recommended as it's free and easy to use. In Filezilla Select File -> Site Manager. When creating a New Site select the Protocol as SFTP and enter the IP address of your RG ARC. You can obtain this by pressing the Start Button in the Main Menu of your RG ARC(When connected to Wifi it will show at the bottom center of the screen).***

###### ***Logon Type: Normal<br> Login: ark<br> Password: ark***

###### ***After pressing Connect you should now be able to access your RG ARC's file system remotely. For Reference ../roms2 is the directory for the Micro SD Card in the second slot.***

### 15. I want to go back to the stock firmware. Where can I download it?

###### ***You can download the stock firmware at [Anbernic's Website](https://win.anbernic.com/download/289.html).***


<br>
<br>
<br>

*<p align=center> Much thanks to TechToyTinker for bringing this cfw to the fans of the RG ARC. You can find his YouTube Tutorials here:<br> https://www.youtube.com/@TechToyTinkerCompany </p>*

<br>
