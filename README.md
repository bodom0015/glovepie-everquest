# glovepie-everquest
This script is designed to allow the user to play an EverQuest Necromancer using an Xbox 360 Controller to interface with the keyboard. A list of available commands can be found below, as well as inside comments in the script itself.

While this was a fun side-project and totally works,  it is not very practical. Don't expect to be attending raids with a controller anytime soon. Furthermore, it is highly specific to my character/AAs/Items/Hotkeys/etc. I have done my best to list out everything below.

# DISCLAIMER
This script **DOES NOT** enable the user to do anything that wouldn't be possible with a normal keyboard and mouse.
It simply enables you to use a controller instead of keyboard/mouse (except for chat/speech, obviously).

This is no different than using a mouse/keyboard with macro buttons.

# Usage
0. Follow [the steps provided by Xbox Support to use an Xbox 360 controller with your PC](http://support.xbox.com/en-US/xbox-on-windows/accessories/xbox-controller-for-windows-setup)
1. install [GlovePIE](https://github.com/deftflux/descent-glovepie/wiki/Setting-up-GlovePIE)
2. Download [EQ.pie](EQ.pie?raw=true)
4. Start EverQuest, log in, and choose your character
5. Open GlovePIE
6. At the top-left, choose File -> Open..., select EQ.pie, and click Open
7. At the top in the middle of the screen, click Run. The script will automatically Alt-Tab back to the game
8. Enjoy the fruits of my wacky experimentation!

# Features
* Move your character with the `Left Analog Stick`, hold `Left Trigger` to strafe
* Walk by pressing the `Left Analog Stick` forward only slightly, or you can down hold `Right Trigger`
* `Right Analog Stick` controls the mouse
  * `LT + Click the Right Analog Stick` will left-click
  * `RT + Click the Right Analog Stick` will right-click
* `LT + RT + Right Analog Stick` controls the camera
* Cast spells with `X` / `B` / `Y` and combinations of Left Trigger and Right Trigger
* Clicking the `Right Analog Stick` will duck and cancel spell casting if you're not on a mount
* When you FD/Fade, you should be able to press any button to stand up again
* If you're not moving, `LT + A` will summon a mount.
* If you are moving, `LT + A` will cast Whisperwind instead.


# Global Hotkey List
```
   Xbox Input     <=>    Keyboard/Mouse Equivalent    <=>        Action              Implemented
   LT                                None                      Strafe Mode                x
   RT                                None                       Walk Mode                 x
   LT + RT                           None                      Camera Mode                x

   Left Stick                   W / A / S / D                  Run / Walk                 x
   LT + Left Stick                  Q / E                        Strafe                   x

   Click Left Stick                    2                      Army of the Dead            x 
   LT + Click Left Stick               5                     Guardian of Blood            x
   RT + Click Left Stick               3                       Rise of Bones              x
   LT + RT + Click Left Stick          4                     Swarm of the Dead            x

   Right Stick                  Mouse Movement                 Cursor Moves               x 
   LT + RT + Right Stick        Camera Movement                Camera Moves               x

   Click Right Stick                   X                           Duck                   x
   LT + Click Right Stick       Left Mouse Click                Clicks Mouse              x
   RT + Click Right Stick      Right Mouse Click             Right Clicks Mouse           x
   LT + RT + Click Right Stick         7                        Death Bloom               x

   A                               Spacebar                       Jump                    x 
   LT + A                             -               Warp Forward / Mount / Dismount     x
   RT + A                      Execute Sub-Script               Levitate                  x
   LT + RT + A                       End                          Drop                    x

   B                               Alt + 2                     Short DoT 1                x
   LT + B                          Alt + 3                     Short DoT 2                x
   RT + B                          Alt + 4                     Short DoT 3                x
   LT + RT + B                     Alt + 9                Medium DoT 5 / Debuff(s)        x

   Y                               Alt + 5                     Medium DoT 1               x
   LT + Y                          Alt + 6                     Medium DoT 2               x
   RT + Y                          Alt + 7                     Medium DoT 3               x
   LT + RT + Y                     Alt + 8                     Medium DoT 4               x

   X                               Alt + =                      DD: Lifetap               x
   LT + X                          Alt + 0                      DD: Turn Undead           x
   RT + X                          Ctrl + 9                     Slow (Undead)             x
   LT + RT + X                     Alt + 1                    DD: Venin / Blood           x
          
   LB                                 1                           Snare                   x
   RB                              Ctrl + 1                       Root                    x
   LT + LB                            8                        Invisibility               x
   LT + RB                            9                     Invis Versus Undead           x
   RT + LB                            0                Death Peace (FD) / Stand Up        x
   RT + RB                            =              Death's Effigy (Fade) / Stand Up     x
   LT + RT + RB                    Ctrl + 0                    Levant (Succor)            x
   LT + RT + LB                    Ctrl + =                      Gate                     x

   D-pad: Window toggles
   Up                               Backspace                       Map                   x
   Left                                I                         Inventory                x
   Right                            Shift + B                   Open All Bags             x
   Down                              Alt + Q                      Quests                  x

   LT + D-pad: Targeting
   LT + Up                      Ctrl + Shift + Alt + Tab         Cycle XTargs             x
   LT + Left                            Tab                      Cycle NPCs               x
   LT + Right                     Shift + Alt + Tab              Cycle PCs                x
   LT + Down                      Ctrl + Shift + Alt + Tab       Target Pet               x
   
   RT + D-pad: Pet commands
   RT + Up                         Ctrl + Alt + 9               Pet Attack                x
   RT + Left                       Ctrl + Alt + 5                 Pet FD                  x
   RT + Right                           Alt + -                 Shield Pet                x
   RT + Down                       Ctrl + Alt + 8              Back Pet Off               x

   LT + RT + D-pad: Camera controls
   LT + RT + Up                   Mouse Wheel Up               Zoom camera in             x
   LT + RT + Left             Left Click and Drag Left       Rotate camera left           x
   LT + RT + Right            Left Click and Drag Right      Rotate camera right          x
   LT + RT + Down                 Mouse Wheel Down             Zoom camera out            x

   Micellaneous: Start / Back / Modes
   Any button (while feigned)   Ctrl + Shift + 6                 Stand Up                 x
   Back                             Esc                       Close Extra Windows         x
    
   Start                                                    Reluctant Benevolence         x
   LT + Start                                                  Curse of Muram             x
   RT + Start                                             Third Spire of Necromancy       x
   LT + RT + Start                                              Funeral Pyre              x
   LT + Back                                                     Harmshield               x
   RT + Back                                                 Embalmer's  Carapace         x
   LT + RT + Back              Shift + P + I + E            Halt Script Execution         x
```
