# Factory-Monitoring-Expanded
![expanded](https://user-images.githubusercontent.com/61538051/218508893-b6412c34-e172-4fd8-90a4-00b6801f20c7.png)
<br>
An expanded version of my [Factory Monitoring Screen](https://github.com/BartasRS/Factory_monitoring_screen) for people with crazy big factories. Basic version resulted in text overlaps and eventually script crash due to 50k characters limit per screen.
<br>
This version displays Metalworks, Electronics and Glass industry on screen 1, 3D Printers, Chemical Industry, Refiners, Honeycombs and Smelters on screen 2 and, finally Assemblers on screen 3. I figured out it should be a proper setup for most big factories tho I know some of you are crazy :P<br>
There is also a version for 9 screens which displays each type of industry on a separate screen.
<br><br>
## Installation
Copy [3 screen version](https://github.com/BartasRS/Factory-Monitoring-Expanded/blob/main/PB.json) or [9 screen version](https://github.com/BartasRS/Factory-Monitoring-Expanded/blob/main/pb-9_screens.json) into PB <br><br>
Simply connect core and 3( or 9) screens (in any order) to Programing Board and run the script. I humbly suggest setting refresh rate (In Lua settings) to 3 or above to avoid possible laggy situations with a lot of industry running.<br><br>
<b>Lua Parameters</b><br><br>
Refresh rate - value in seconds, set above 3 for really big factories<br>
border - bottom display line position, use to fine tune (increments of 10) if some headers are at the bottom. Maximum is 600.<br>

<br><br>
Script comes with industry locator. Type <i>help</i> in Lua Tab to see available commands.

<hr>
The script is made so it should be fairly easy to shuffle contents between screens or add more screens to it (up to 9) if you wish so. If you need any help with customising it reach me in game (Bartas) or on Discord (BartasRS#2742).
<hr>
<br>
<b>BIG thanks to Credence#1983 for help with testing and code improvements!</b>
