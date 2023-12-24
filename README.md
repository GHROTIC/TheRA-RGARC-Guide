# <p align=center>The Retro Arena Custom Firmware Guide</p>
#### **<p align=center>Current Version: Beta 9</p>**
<p align=center><img src=https://i.imgur.com/lTJdQyN.jpg width=60%></p>

<br>

## <p align=center>Installation:</p>

*<p align=center>Joey's Retro Handheld's has made a good starter video for installing the Firmware(Beta 9). If you find it helpful be sure to give him a like and a subscribe:</p>*

<br>

 [<img src=https://img.youtube.com/vi/dTAqpZinv2M/0.jpg width=40%>](https://www.youtube.com/watch?v=dTAqpZinv2M)

<br>
<br>

## <p align=center>Known Issues:</p>

- *The colors on some systems are inverted (i.e. Dreamcast, Naomi and Atomiswave)*
- *Attempting to manually scrape in the Edit Metadata section of a Rom causes EmulationStation to crash*
- *Some games don't run correctly with the default settings or they require an analog stick. This list can be found on the [Compatibility Page](../main/Compatibility.md).*

<br>
<br>

## <p align=center>FAQ & Troubleshooting:</p>

### 1. Scraper tells me to "Refresh update games lists to apply changes" but how do update the game list?

###### ***Press the Start Button in the Main Menu, go to Quit at the bottom and select to Restart Emulation Station to update your Game Lists. In some cases your games may fail to show the correct images until you Restart System instead.***

### 2. What software should I use to flash my Micro SD Card?

###### ***Rufus has been found to be the most reliable by the community: https://rufus.ie***

### 3. What format should my Micro SD Cards be in?

###### ***Your TF1/SD1 card will have the correct formatting applied when you flash the image with Rufus. Your TF2/SD2 card may be formatted ExFat or NTFS but it is recommended to use NTFS.***

### 2. How do I connect to WiFi?

###### ***Go to the Retroarch folder in the Main Menu and open Retroarch. Go to Settings -> Wi-Fi -> Connect to Network.***

### 3. My Networks are missing in the Retroarch Wi-Fi -> Connect to Network Menu. How do I make them appear?

###### ***If Retroarch Scans for Networks and does not find your Network you will need to back out with the B button twice and Quit Retroarch. In the Main Menu go to Options -> Advanced -> WIFION(Options -> WIFION if you have folders hidden) and your system will reboot. Once you go back to Connect to Network in Retroarch your Networks should now appear.***

### 4. How do I update the software?

###### ***Once you are connected to Wifi you can go into Options -> Arcupdate to open the OTA Update Software. By default it will have "Updating to the latest Version" highlighted and you will only need to press the A button to confirm. Once the update has completed and you are back at the Main Menu go to Options -> Fix Permissions. After the Fix Permissions script sends you back to the Main Menu press the Start Button and go down the menu to Quit -> Restart.***

### 5. How do I change my Theme?

###### ***Go to Options -> Misc -> Thememaster(Options -> Thememaster if you have folders hidden) to download new Themes(Warning: a few themes are not compatible and will be partially broken or will be completely missing text - will note at a later time).***

### 6. How do I open the menu while playing a game?

###### ***By default this is set to L2 + R2 for Retroarch based emulators. For Yaba Sanshiro Standalone(Sega Saturn) you can use the Select Button.***

### 7. How do I exit a game?

###### ***By default this is set to F(Function Key on the top of the device) twice.***

### 8. Why do I not see the C and Z buttons in the Retroarch controller configuration?

###### ***Within Retroarch the setting for Z will be the L3 button and C will be the R3 button.***

### 9. How do I use SSH for file transfers over WiFi?

###### ***Default login and password is:<br> Login: ark<br> Password: ark***

###### ***If your SSH client (for example Filezilla [recommended] ) asks you for a port, introduce "22". Now you can browse through the complete file system and transfer files at will. Backup your files before doing any changes this way, highly recommended, almost obligatory if you ask me. - (Credit to Foxtochop on Discord)***

### 10. My power button doesn't put the ARC into Sleep Mode and/or my Volume Buttons aren't working. What should I do?

###### ***Go to the Main Menu, select Options -> Fix Permissions. After the Fix Permissions script sends you back to the Main Menu press the Start Button and go down the menu to Quit -> Restart.***


<br>
<br>
<br>

*<p align=center> Much thanks to TechToyTinker for bringing this cfw to the fans of the RG ARC. You can find his YouTube Tutorials here:<br> https://www.youtube.com/@TechToyTinkerCompany </p>*

<br>
