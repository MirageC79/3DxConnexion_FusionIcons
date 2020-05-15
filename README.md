# Customizing your SpaceMouse radial menus.
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/3dx_KeyMapping.png?raw=true)


## 1 - Create new Icons for your radial menus
I have prepared a set of Icons that I use on a regular basis.  If the Icons you want are not in there, feel free to create your own.  They have to be .png files of 24x24 pixels max.

- Download 3DxIcons.zip from this repository to your computer.
- Extract the content (new set of icons) to: "C:\Program Files\3Dconnexion\3DxWare\3DxWinCore64\Cfg\Images\3DxService"


## 2 - Link the icons to function names
You will need to modify the following .xml file to make the link between the added icon and a function name in fusion. 
I also prepared for you a modified .xml with linking the icons from previous step to function name.

- Dowload Fusion360.xml from this repository to your computer.
- On your computer at this location: C:\Program Files\3Dconnexion\3DxWare\3DxWinCore64\Cfg, make a copy of the existing Fusion360.xml file to somewhere safe in case something goes wrong.
- Copy and paste the new Fusion360.xml to that location and overwrite the existing one. 


## 3 - Creating shortcuts in Fusion360
Many of the functions I have assigned to my radial menus did not have native keyboard shortcut.  I had to create them manually.
- In Fusion 360 Locate the function for which you want to create a short cut, click on the three vertical dots to its right.
- Select: "Change Keyboard Shortcut ... "
- Assign a key combination by physicaly pressing the desired keys on your keyboard.
- OK

![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/FusionKeyboardShortcut.png?raw=true)
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/FusionKeyboardShortcutAssign.png?raw=true)


## 4 - Assigning short cuts to the SpaceMouse radial menus
From your 3DConnexion application, ensure the focus is on Fusion360 (the app will show Fusion 360 as shown below)
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/3dxapp.png?raw=true)
- Select the device you want to modify, spacemouse, cadmouse etc...
- Select Buttons
- Click the arrow from one of the device buttons and navigate to: Macro/New Macro
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/3dxappNewMacro.png?raw=true)
- Create one new macro per desired function.  ** MAKE SURE ** to name the macros as per the name you gave into the XML file.
- Assign same keyboard shortcut as defined in Fusion360.
- Repeat for all functions.


## 5 - Create New Radial Menus
You can now create specific radial menu for each of your device button.  I prefer 8 sections radial menus as they offer more shortcut place holders.
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/3dxappRadialMenu.png?raw=true)
![alt text](https://github.com/MirageC79/3DxConnexion_FusionIcons/blob/master/3dxappRadialMenuMAcro.png?raw=true)


# Have fun!
