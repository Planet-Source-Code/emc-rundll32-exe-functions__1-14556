<div align="center">

## RUNDLL32\.EXE functions


</div>

### Description

You might find the following code useful in complicated tasks that require a lot of code in other methods. I have not tested all of them, but they should work.
 
### More Info
 
Be sure to know how to enable the mouse or keyboard if you use the functions to disable them -- or you'll have to reboot your computer.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[EMC](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/emc.md)
**Level**          |Beginner
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/emc-rundll32-exe-functions__1-14556/archive/master.zip)





### Source Code

```
'To use the following functions simply write:
'shell "RUNDLL32.EXE _________"
'For example,
Shell "RUNDLL32.EXE user,setcursorpos" '(sets the
'mouse pointer to the upper left corner of the
'screen)
'
'---OTHER FUNCTIONS---
'
'-- Shut down Windows
'RUNDLL32.EXE KRNL386.EXE,exitkernel
'-- Sort open windows on desktop
'RUNDLL32.EXE user,tilechildwindows
'RUNDLL32.EXE user,cascadechildwindows
'-- Open Hardware manager
'RUNDLL32.EXE sysdm.cpl,installDevice_Rundll
'-- swap mousebuttons
'RUNDLL32.EXE user,swapmousebutton
'-- Disable Keyboard
'RUNDLL32.EXE keyboard,disable
'-- Disable Mouse
'RUNDLL32.EXE mouse,disable
'-- Opens the Network connect window
'RUNDLL32.EXE user,wnetconnectdialog
'-- Set mouse pointer to the upper left corner
'RUNDLL32.EXE user,setcursorpos
'-- Open a Explorer window
'RUNDLL32.EXE shell,shellexecute
'-- Reboot Windows 98
'RUNDLL32.EXE shell32SHExitWindowsEx 0
'-- Shut down Windows 98
'RUNDLL32.EXE shell32SHExitWindowsEx 1
'-- Reboot PC
'RUNDLL32.EXE shell32SHExitWindowsEx 2
'-- Restart Windows Explorer ( Desktop)
'RUNDLL32.EXE shell32SHExitWindowsEx -1
```

