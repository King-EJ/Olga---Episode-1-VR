# Olga---Episode-1-VR
VR Mod for Olga - Episode 1


OLGA VR  -  VR mod for "Olga - Episode 1" (Unity 2022.3.5, Mono x64, built-in renderer, BepInEx 5)
=================================================================================================
Version 0.1.2 (test build)

<img width="768" height="1024" alt="Olga - Episode 1vrx" src="https://github.com/user-attachments/assets/ba533d71-6af8-4723-9d7f-ff05aff50d2a" />


INSTALL
-
1. unzip to game folder, only tested with virtual desktop XR,
2. Start your OpenXR runtime first (Virtual Desktop / SteamVR / Quest Link), then the game

"to disable Mod rename winhttp.dll to winhttp.dll.bak"

VIEW
  * FIRST PERSON: your head is Olga's head. Look around freely; Olga's body turns to where you look, so the
    left stick walks where you LOOK (or where the left controller points - setting).
  * Right stick left / right = snap turn (30 degrees; smooth turning in the settings).
  * Sitting (in the car...): look around with your head; the right stick turns you, your view turns with the car.
  * The game's head bob is off (setting "No head bob").
  * Cut-scenes / scripted moments: you stand where the game's camera is; your view turns with it when the shot
    changes.
  * Examining an object and the journal: the game's normal picture on a flat screen in front of you.
  * Menus / pause: on a screen in front of you. HUD and subtitles float in front of you in play.

CONTROLS (Quest buttons = the same Xbox buttons)
-
  Left stick ............ move    
  Right stick ......... turn (in play)
  
  A ..................... interact / jump 
  
  B ................... crouch / back / exit
  
  Y (tap) ............... journal / read 
  
  X (tap) ............. X
  
  Right trigger ......... sprint 
  
  Left trigger ........ zoom
  
  Right grip (RB) ....... drop / throw 
  
  Left grip (LB) ...... LB
  
  Right stick click ..... R3 (reset examined object) Left stick click .... L3
  
  X + Y together ........ Start (pause menu)  
  
  A + B together ...... View (inventory)

  
  X (hold 1.3 s) ........ hide / show the HUD
  
  Y (hold 1.3 s) ........ FLAT-SCREEN VIEW on / off: the game's normal picture on a screen in front of you, for
                            any moment that is awkward in VR
                            
  Menus: left stick / right stick = choose, A or the right trigger = select, B = back.
  
  Examining: right stick turns the object, left stick zooms.
  
  Both stick clicks: tap = re-centre the view, hold 1.2 s = VR settings menu
  INTERACTING / PICKING UP: point at the thing with your RIGHT controller (a thin laser shows where; it turns
  green on something you can use) and press A. Setting "Interact with": Head = look at it instead.
  
  The prompt text ("Pick up", the item's name) floats by your RIGHT HAND, and the interaction icon floats in 3D
  over the thing you point at (settings: "Prompt by your right hand", "Icon over the thing you point at", sizes).

IN THE WORLD
  * Item markers (hand / magnifying glass icons) float in 3D over their items.
  * Control hints ("(R) To look around"...) float over your LEFT hand.
  * Picked-up items are carried in your RIGHT hand (settings: HeldItemOffset / HeldItemRotation in the config
    if an item sits oddly in your hand).
  * Option "Swap triggers": left trigger = RT (sprint), right trigger = LT (zoom).

KNOWN LIMITS
  * The zoom (left trigger) does not zoom the VR view.
  * Menus are used with the sticks (no laser pointer for menus yet).

CHANGES
-
  0.1.2  Item markers (hand / magnifying glass) float in 3D over their items; control hints float over your left
         hand; held items are carried in your right hand; new option to swap the triggers (VR menu / config
         SwapTriggers).
  0.1.1  Sitting / limited look (the car ride) now counts as play: your head looks around (the game camera follows
         it), the right stick turns you, the view turns with the car, the laser and interacting work there.
         Interaction prompt text floats by your right hand; the interaction icon floats over the thing you point
         at; the dot in the middle of the screen is hidden while you point with the laser.

