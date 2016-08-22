PokeSweep - with Compass & Notifications
===================

Download:  [Latest Version](https://github.com/DooieNinja/PokeSweep/releases)

PokeSweep's primary focus is to run in the background and notify the player of items of interests.  Its secondary focus is to direct the player to the item of interest.  As such, PokeSweep does NOT do remote scanning -- this is by design.  It is intended to be a lightweight assistant who will wake up at pre-configured interval and "look around" the player's present location for potential Pokemons or Pokestops.  PokeSweep is created to be a companion app for the official Pokemon GO game.  It is NOT intended to ever become anything automated such as catching Pokemon or looting Pokestops.

The Active Hunt Mode is intended to cater to players who are out hunting Pokemons.  When this mode is enabled, it will prevent the phone from going to sleep.  This will remove the player's concern to keep the phone on while tracking Pokemon.  It is best used in conjunction with a secondary device used to run the main Pokemon GO game.

>**DO NOT USE YOUR MAIN ACCOUNT WITH POKESWEEP.  YOUR ACCOUNT MAY RECEIVE A BAN.  YOU HAVE BEEN WARNED.**

-------------

####Feature Highlights

  - Supports PTC only -- Please use an unimportant account
  - Background service to perform scans periodically
  - Compass arrow directing to item of interest -- GPS style
  - Active Hunt Mode
  - Single persistent Notification receiving updates -- doubles to signify background service is running
  - Searchable filter list
  - Keep track of caught Pokemon -- Activate by swiping it away
  - Light and Dark theme (for night hunting)
  - Support Android 4.4+
  - Light weight and battery conscious -- as a background service can be

-------------

####Features NOT supported -- by design

  - Remote scanning
  - Pokemon catching
  - Pokestop looting
  - Egg walking
  - Multi-account

-------------

####Change Logs

**v1.0.4**

- Added Lured Pokemon marker for clarify
- Fixed moving fast detection
- Fixed caught state pruning -- again...
- Minor text edit ;)

**v1.0.3**

- Added pausing scan if moving above 30mph/48kph -- pointless if you're not around to catch
- Added option to disable pause scan when moving too fast -- enable by default
- Better at pruning
- Better error handling during login

**v1.0.2**

- Rewrite Compass to be smoother
- Added Pokestop looted countdown -- Activate by long pressing a Pokestop
- UI fix the settings
- Made Status text non-overlapping
- Handled crashing exceptions better
- Better pruning of despawned pokemon
- Misc fixes for state tracking of Pokemon catch state
  
-------------
####Screenshots
<p align="center">
<img src="https://cloud.githubusercontent.com/assets/21098060/17766706/4c097e08-64e1-11e6-9f74-466b27efd01c.png" width="300"/> <img src="https://cloud.githubusercontent.com/assets/21098060/17766704/4c0832b4-64e1-11e6-9ee7-f3adfb99bd5a.png" width="300"/>

<img src="https://cloud.githubusercontent.com/assets/21098060/17766735/6882074e-64e1-11e6-920c-49de5b6e0e92.png" width="300"/> <img src="https://cloud.githubusercontent.com/assets/21098060/17766708/4c0c53b2-64e1-11e6-973a-ad2489ff7ea2.png" width="300"/>

<img src="https://cloud.githubusercontent.com/assets/21098060/17766707/4c0a346a-64e1-11e6-9e6f-801cf370e8c1.png" width="300"/> <img src="https://cloud.githubusercontent.com/assets/21098060/17766705/4c0920ca-64e1-11e6-84a7-fc752118257d.png" width="300"/>
<img src="https://cloud.githubusercontent.com/assets/21098060/17766709/4c107abe-64e1-11e6-908b-e3f8795ac514.png" width="300"/> <img src="https://cloud.githubusercontent.com/assets/21098060/17832968/2f7a5d66-66c6-11e6-983a-4c68e8664793.png" width="300"/>
</p>

-------------

####Credits

PokeSweep was created using various open source libraries.

- PokeGOAPI-Java  (https://github.com/Grover-c13/PokeGOAPI-Java)
- Material Drawer (https://github.com/mikepenz/MaterialDrawer)
- Material Dialogs (https://github.com/afollestad/material-dialogs)
- Secure-preferences (https://github.com/scottyab/secure-preferences)