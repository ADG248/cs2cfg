# Counter-Strike 2 Configuration File - cs2cfg

**Counter-Strike 2 Configuration File (autoexec)**<br/>
This repository contains two autoexec.cfg files.<br/>
One file contains my personal settings.<br/>
The other is a base autoexec file for an easier setup from scratch.<br/>

### Place autoexec file in \Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
```
\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
```
### Enter +exec autoexec in CS2's Launch Options
```
+exec autoexec
```
### Additional Notes
- In CS2's Lauch Options, the name of the Config File must go after "+exec". If the .cfg file is named "autoexec.cfg", put "+exec autoexec"<br/>
- You can change the file name if you want as long as you put the same file name after +exec<br/>
- You can change the autoexec_base.cfg file to autoexec.cfg or a custom file name.<br/>
- If you change something in the Config File, you can type "exec autoexec" in your console so your game recognizes the changes. You can bind a key too "bind *key* exec autoexec".<br/>
- Each time CS2 loads the Config File, it will load it's values. If you change a setting in game and it is set in the Config File, it will reset back to the Config File's value.<br/>
- This Config also includes things such as PracticeMode On/Off Keybinds, Delete Grenade Keybind (Delete Smokes, etc.), Refresh autoexec Keybind<br/>
