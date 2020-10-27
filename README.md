# Table of Contents 

### [1.](#introduction) Introduction
### [2.](#system-requirements) System Requirements
### [3.](#installing-livesplit) Installing LiveSplit 
### [4.](#configuring-livesplit) Configuring LiveSplit
 1. ##### Map Controller
 
 
 2. ##### Set Game Path
### [5.](#faq) FAQ
### [6.](#license) LICENSE


## Introduction


## System Requirements
 * OS: Windows 7 or later, OSX 10.12 or newer
 * Network: Broadband Internet connection
 * Storage: 30 MB available space
 * Sound Card: Windows compatible sound card, Mac compatible
 
## Installing LiveSplit
 * Navigate to the LiveSplit [homepage](https://livesplit.org/)
 * Click the _download_ button on the homepaage
   * this will lead you to the different LiveSplit downloads
  ![download](https://github.com/ChaseAlll/P2/blob/main/P2_pictures/downloa.png)
  * Click on the most recent version of LiveSplit to download the application
  ![down2](https://github.com/ChaseAlll/P2/blob/main/P2_pictures/down1.png)
  * Open your _Downloads_ folder to locate the application
  * Extract the LiveSplit zip folder
    * send it to your prefered location
  * Open your extracted LiveSplit folder
  * Click On LiveSplit.exe to open up LiveSplit
    * Once you do this the application should open and look like
  ![exe](https://github.com/ChaseAlll/P2/blob/main/P2_pictures/exe.png)

## Configuring LiveSplit
 * Navigate into the extracted folder and run the Dolphin Program
   * _This will open the program in it's own window_
 * Click the Controllers Button
   * _This will open a small window containing the general controller configuration options_
 ![DolphinStart](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/DolphinHomeSmall.png)
 * Under GameCube Controllers, Port1, select Standard Controller from the drop-down menu
 * Click the Configure button for Port 1
   * _This will open a window for with specific configuration options for a single controller_
  ![DolphinControllerSelect](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/ControllerSettingsSmall.png)
 * Ensure your Controller is connected
 * Under Device select Xinput/… from the drop-down menu
   * _If Xinput is not displayed, ensure the controller is connected and click refresh_
  ![DolphincontrollerMapping](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/ControllerMappingSmall.png)
   
    

 * Map controller inputs to your preference
 * Under Profile give this controller a name
 * Save the profile
 * Close both controller windows 
 * Click the Config button
   * _This will open a multi-tabbed window with the general configuration options_ 
 ![DolphinStart](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/DolphinHomeConfigSmall.png)
* Navigate to the Paths tab
![DolphinPaths](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/PathsArrowSmall.png)
 * Click add
   * _This will open a windows navigation window_  
![DolphinAdd](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/PathsAddsmall.png)
 * Navigate and select folder where Rom’s are stored
   * _If rom’s are sorted in someway into different folders. Ensure they are all put into a single roms folder and check the search subfolder option._ 
 * Click close
 * Choose a Rom to run and play it!

## FAQ
 * Are there any performance settings that need changed?
   * New versions of Dolphin come with the most optimized settings preselected. If you are having trouble, try lowering the resolution or choosing a different renderer in the graphics settings under the options toolbar. 
 * "This application has failed to start because XINPUT1_3.dll was not found"
   * This only occurs on systems using an older version of Windows (below 10). Like how we installed the VS C++ redistributable install the Latest DirectX Runtime from [here](https://support.microsoft.com/en-us/help/179113/how-to-install-the-latest-version-of-directx) 
 * “Im using a PS3/4 controller and it is not recognized.”
   * Install the SCPToolkit from [here](https://github.com/nefarius/ScpToolkit) this will allow windows to recognize the controller as a Bluetooth device and retry adding the controller. 

## LICENSE
 * This project is licensed under the terms of the MIT license.
 * [LICENSE](https://github.com/RobertGageStroud/Portfolio/blob/master/LICENSE)

