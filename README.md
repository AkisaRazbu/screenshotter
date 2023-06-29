# Screenshotter
A tool written in shell script, the simplest possible linux screenshotting tool.

Functionality:
- [x] Screenshotting

Dependencies:
- [ ] Scrot 
- [ ] xclip
- [ ] 10+ IQ

Installation:
```bash
git clone https://github.com/akisarazbu/screenshotter.git 
sudo make
```

Usage:
Bind it to a keybinding inside your window manager/desktop enviorment and press it.
Example in my dwm config:
```c
{ Mod1Mask|ShiftMask,           XK_s,      spawn,          SHCMD("screenshotter")}
```
