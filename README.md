# Table of Contents 

### [1.](#introduction) Introduction
### [2.](#system requirements) System Requirements
### [3.](#installing-emulator-and-dependencies) Installing BO2 With Plutonium 
 1. ##### Download Resources
 
 
 2. ##### Install Resources
 
### [4.](#configuring-emulator) Configuring Emulator
 1. ##### Map Controller
 
 
 2. ##### Set Game Path
### [5.](#faq) FAQ
### [6.](#license) LICENSE


## Introduction
Dolphin is a flexible and accessible program that emulates the GameCube and Wii consoles. This document will give an in-depth
walkthrough on the first-time installation and configuration of the emulator on a Windows 64-bit machine. 
This documentation is intended for individuals who have little experience with emulators in general or have never installed
this emulator before. Anyone has experience with this emulator or is going to use a version that is different than
the one used should look for information more curated to their use case. Once read, this documentation will give the user the
knowledge to install the emulator and to configure it to use the settings most efficient for a general use case.

## System Requirements
 * Minimum System Requirements
    * OS: Windows 7 64-Bit / Windows 8 64-Bit / Windows 8.1 64-Bit or later, Mac OS X 10.13.6 (High Sierra) or later
   * Processor: Intel® Core™ i3-530 @ 2.93 GHz / AMD Phenom™ II X4 810 @ 2.60 GHz, Intel® Core™ i5 (4 Cores) @ 2.3 GHz
   * Graphics: NVIDIA® GeForce® GTX 470 @ 1GB / ATI® Radeon™ HD 6970 @ 1GB, ATI® Radeon™ M295X @ 2GB
 * Network: Broadband Internet connection
 * Storage: 100 GB available space
 * Sound Card: DirectX Compatible
 
## Installing Emulator and Dependencies
 * Navigate to the Dolphin [homepage](https://dolphin-emu.org/)
 * Click either download link on the homepage
   * _This will lead to a page with the different versions of Dolphin_ 
  ![DolphinHomePage](https://raw.githubusercontent.com/RobertGageStroud/Portfolio/master/P2Pictures/DolphinWebsiteSmall.png)
 * Download the latest version of Dolphin for Windows (Current - 5.0-11827)
 * Navigate to the Visual Studio C++ Redistributable [page](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)
 * Download Visual Studio 2015, 2017, and 2019 based on your system.
  
 * Navigate to where you downloaded the above files
 * Run the vc_redist.x--.exe file
   * _This will open an install wizard_
   
   * _If the install fails it means it was already installed on your system_
 
* Extract Dolphin from its .7z file to where you want the program
 
## Configuring Emulator
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

