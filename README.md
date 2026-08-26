Releases  https://github.com/VVmImo/Dolphin-for-MuOS---Increase-FPS/releases/tag/Dolphin-for-MuOS
------------------------------
## Introduction to Dolphin Core for muOS
The Dolphin Core for muOS is an advanced optimization project focused on fine-tuning Nintendo GameCube and Nintendo Wii emulation for handheld consoles powered by the H700 chipset. Integrated into the V0iD Project by SPDW Factory, this repository serves as the definitive hub to squeeze every drop of performance out of ARM hardware, turning budget pocket-sized devices into capable emulation machines.
## 🔧 Key Features & Performance
Emulating GameCube and Wii titles on an H700 chipset requires surgical precision and custom configuration profiles. The project applies title-by-title game profiles, graphic flag management, and strategic techniques like underclocking to prevent audio stuttering and improve frame rates, delivering a genuinely playable experience.
## 🤝 Community Credits & Acknowledgments
This repository is not a core built from scratch; it represents a dedicated optimization and repository management effort built upon the community's foundation. The project is currently maintained by SilverCrow2323 and was created by Sir Pips of SPDW Factory.
Full credit for pioneering and porting GameCube/Wii emulation to muOS belongs to the original community developers:

* @Speedrun: Original author of the Dolphin port for muOS (V9).
* @FireBattleInMtl: Contributed crucial permission fixes and scripts to add Dolphin to the system launch routine.
* @Snow: Provided the newly compiled Dolphin binary file.
* @bitter_bizarro: Adopted the core to make it compatible with the muOS Goose firmware version.
* muOS Development Team: For their ongoing firmware maintenance and structural support.



------------------------------
## Installation Guide: Dolphin Core for muOS
⚠️ ATTENTION (Mandatory Pre-requisite): Before running the new installer, you must completely remove all previous versions of the core to prevent file conflicts and read errors.
## 🗑️ Step 1: Cleaning Previous Folders
Connect your SD card to your PC or use the built-in File Manager on your console to permanently delete the following folders and files before running the new installer:

   1. \opt\muos\share\info\assign
   2. \opt\muos\share\emulator\dolphin 
   3. \opt\muos\share\emulator\gptokeyb\ext-dolphin.gptk

------------------------------
## 📥 Step 2: Installation Process
After ensuring that the system is clean of legacy files, follow these steps:

   1. Download the File: Fetch the updated installation package (file with the .muxupd extension).
   2. Transfer to the Card: Place the copied .muxupd file inside the ARCHIVE folder on either your SD1 or SD2 card.
   3. Access the Manager: Turn on your console, go to the muOS main menu, and navigate to Applications ➔ Archive Manager.
   4. Execute Installation: Select the Dolphin Core update file and confirm to start the automatic extraction and installation process.

------------------------------
## 🎮 Step 3: Setup and Launch Games

   1. Open Content Explorer from the muOS main menu.
   2. Navigate to the directory where you store your Nintendo GameCube or Nintendo Wii ROMs.
   3. Press the options button on the game (or folder) and match it with the corresponding Dolphin Core profile.
   4. Launch the title and enjoy the optimized emulation!




