Heated Bed Filament Dryer for Klipper is a simple macro set that allows you to utilize your 3D printer's heated bed to dry moisture-absorbed filament. Built upon NameOfTheDragon's original concept, this version is highly optimized for a better UX: it allows time input directly in "Hours" (e.g., 4.5 hours) and features a clean HH:MM:SS countdown display on your Mainsail/Fluidd dashboard.

♨️ Klipper Macros: Heated Bed Filament Dryer
This macro set allows you to utilize the heated bed and chamber (if available) of a 3D printer running Klipper firmware as a filament dryer.

This project was customized and optimized for a better UI experience (inputting time in Hours, displaying an HH:MM:SS countdown) based on the original filament_dryer.cfg macro by NameOfTheDragon. A huge thanks to the original author for the idea!

⚙️ Installation Guide
To integrate this feature into your printer, simply follow these steps:
- Download the filament_dryer.cfg file from this repository and copy it to your Klipper configuration folder (in the same directory as your printer.cfg).
- Open your printer.cfg file and add the following line:
[include filament_dryer.cfg]
- Save the file and select Save & Restart in Klipper.

🚀 How to Use
Once installed, your Mainsail/Fluidd interface will display the following macros:

START_DRYER: Starts the drying process. You can input the Bed temperature, Chamber temperature, and Drying Time (in Hours, decimals like 4.5 are accepted).

STOP_DRYER: Instantly stops the drying process and turns off all heaters.

DRY_PLA / DRY_PETG / DRY_ABS: Quick preset buttons configured with optimal temperature and time for each filament type. (You can modify these parameters in the .cfg file to match your specific needs).

⚠️ Disclaimer
This macro set was customized for my personal use and is shared freely for anyone who might find it helpful.

Please note that using the heated bed to dry filament for extended periods may pose thermal risks to your equipment. Therefore:
This code is provided "as-is".
I disclaim all liability for any risks, accidents, or equipment damage (e.g., damaged print surfaces, melted parts, machine failures, or fire hazards) that may arise from using this code.

Always supervise your 3D printer while it is operating.
