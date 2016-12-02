# smashbox-AHK

This is a autohotkey script that lets you set up your keyboard to act like the smashbox in dolphin. Since dolphin does not let you bind keys to specific joystick values, I wrote this script.

The script works by using autohotkey to read the keyboard inputs, then converts them into a virtual joystick called vjoy. Vjoy is then used to control the inputs in dolphin.

# Requirments
1. Windows. Autohotkey only works on windows. This script was tested on widows 10.
2. Ishurka v 4.3. Otherwise known as faster melee. Other dolphin versions might work, but I tested with dolphin version 5 and the control stick values work slightly differently. https://www.smashladder.com/download/dolphin/fm
3. A keyboard with high n-key rollover. This is how many keys can be pressed at the same time without errors. Most gaming and mechanical keyboards will allow atleast 6 keys which should be enough for every advanced technique.
4. Autohotkey. This is a scritping language for remapping keyboard keys. Download the installer here: https://autohotkey.com/
5. Vjoy: a joystick emulator. Download and install here: http://www.headsoft.com.au/index.php?category=vjoy
6. AHK-CvJoyInterface: a library for linking Autohotkey and Vjoy. Download CvJoyInterface.ahk from https://github.com/evilC/AHK-CvJoyInterface Place CvJoyInterface.ahk inside the Lib folderwhere you installed autohotkey (for me C:\Program Files\AutoHotkey\Lib) You may have to make the Lib folder if it is not already there. 

# Setup
1. Place the smashbox.ini file inside your dolphin-folder-name\User\Config\Profiles\GCPad folder. 
2. In dolphin, open up controller config. Set player 1 to a standard controller, then hit configure. Set device to vjoy. Under profile, select smashbox and hit load. Then hit ok.
3. Run the smash.ahk script. You should be able to do this by double clicking on the file after installing autohotkey.
