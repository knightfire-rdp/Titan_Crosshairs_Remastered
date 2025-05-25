# Titan_Crosshairs_Remastered
Mod that changes crosshairs from Tone, Ion, Northstar, Monarch, and Legion for better 

This mod aims to change mainly the primary weapons of said 5 titans, though legion also gets a powershot change to look more accurate.
It's optimized for 110 FOV, might look different on lower or higher FOV.

Legion's powershot actually fires a circular shotgun like cone that hits everything within that cone. 
The ingame default crosshair for powershot is innacurately displayed as a square. Have 2 images in the folder for reference, 
one by dinorush using ms paint(dinorush.png) and one by me using my mod and mspaint (powershot Shot illustration.png).

Following crosshairs are affected:
| Weapon/Ability                                | Crosshair Type                                                               |
|-----------------------------------------------|------------------------------------------------------------------------------|
| Splitter Rifle (Ion) 1                        | 5% smaller crosshair + dot on hipfire only                                   |
| Splitter Rifle (Ion) 2                        | 10% smaller crosshair + circular crosshair inside                  (disabled)|
| 40mm Cannon (Tone)                            | Circular EPG crosshair that becomes smaller on ADS                           |
| xo-16 (Monarch)                               | 15% smaller crosshair + dot                                                  |
| Railgun (Northstar)                           | Default crosshair + dot                                                      |
|-----------------------------------------------|------------------------------------------------------------------------------|
| Predator cannon close range (Legion)          | 25% smaller crosshair to match spread better                                 | 
| Predator cannon close range Powershot (Legion)| Scorch crosshair accurately matching powershot shot size                     | 
| Predator cannon long range (Legion)   1       | Circular wingman B3 crosshair that changes size greatly when adsing          |
| Predator cannon long range (Legion)   2       | Alternator diamond crosshair, smaller than B3 wingman crosshair    (disabled)|

ADS = aim down sights

Predator cannon long range mode and Splitter Rifle have 2 different crosshairs that be alternated between in the script file, the secondary crosshairs are disabled by default,
despite that can be enabled in the script files.


Long Range Crosshair 2: (take off the "//" infront like here to enable the line, don't forget to apply "//" on the other crosshair) 
/Alternator diamond crosshair with a dot
"ui"						"ui/crosshair_alternator"					
"base_spread"				"-1.33"								

(Apply the "//" infront of the 1st crosshair like this if you want to disable it when using the crosshair above )
//B3 Wingman circular crosshair with a dot
//"ui"						"ui/crosshair_wingman"						
//"base_spread"				"-0.5"									


Splitter Rifle Crosshair 2: (take off the "//" infront like here to enable the line, don't forget to apply "//" on the other crosshair) 
//EPG circular crosshair
"ui"						"ui/crosshair_circle2"			
"base_spread"				"0"								

(Apply the "//" infront of the 1st crosshair like this if you want to disable it when using the crosshair above) 
//Wingman elite dot crosshair (not visible in ads)
//"ui"						"ui/crosshair_wingman_n"		
//"base_spread"				"0"								

(also gotta change the base_spread in the crosshair above to allign the crosshair better with the circle, comment and uncomment the two lines like this)
//"base_spread"				"-0.2"
"base_spread"				"-0.5"

If you wish to disable any crosshair, just remove the file, by legion, you should disable the crosshair and enable the default crosshair in the file, 
unless you want to disable all legion crosshairs

With any questions regarding the mod, dm me on discord https://discord.com/users/375616010402922498
