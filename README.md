# Innocent Tears (XBOX) - August 2026 #

## Intro ##
A fallen angel scours the ruined streets of Tokyo, searching for the
woman he once loved. She and many others have awoken as man-eating angels
that now threatens mankind. Will he save her? Or will he cut her down?

Innocent Tears is a Japanese-exclusive RPG for the original Xbox.
Play as a band of fallen angels and humans in 3-dimensional grid
combat as you soar onto buildings or over obstacles to reach the deadly
angels swarming Tokyo.

No AI was used for this patch. Only genuine stupidity.

## Compatibility
This translation patch has been completed from start to finish on both a
softmodded original Xbox and Xbox 360. The later used the "Bad Avatar" method
to easily load an exploit and the game on to a flashdrive.

You can find two tutorials here:  
Original Xbox: https://consolemods.org/wiki/Xbox:Getting_Started  
Xbox 360 - Bad Update: https://consolemods.org/wiki/Xbox_360:Bad_Update  
Xbox 360 - Other Methods: https://consolemods.org/wiki/Xbox_360:Getting_Started

For emulating, we recommend XEMU. The latest developer release build includes
proper support for Innocent Tears with a fix by Yuvi to have fully working
sound.

**Please ensure you are using a version of at least V0.8.136!**  
Latest Dev Build: https://github.com/xemu-project/xemu/releases

## Patching ##
Compatible ISO MD5: `642114625A09CF9C85D02D8124995CDC`

This ISO should be around 1.6GB. If your ISO matches the above, then
skip to "Applying the Patch."

### Large REDUMP
If your locally-sourced from your own disc copy happens to be in the REDUMP
format, you will need to use `extract-xiso` to remove the padding.

`extract-xiso.exe -r <path_to_iso_file.iso>`

### Applying the Patch
#### Web GUI
We recommend using a web patcher to simplify the patching process, such as:  
https://kotcrab.github.io/xdelta-wasm/

#### Command Line
    xdelta -d -s original_game.iso InnocentTears_ENG_V1.0.xdelta InnocentTearsENG.iso

## FAQ
* I'm on emulator but I hear no sound!
  * Make sure you're on the bleeding edge developer build of XEMU! Yuvi had to
  fix a bug to make Innocent Tears work.

## Tips ##
### World
* Yellow circles indicate a level will have no more story encounters.
* Blue circles mean plot can still happen.
  * If it cuts straight to a battle, then you haven't met the conditions for
  that story section.

### Combat
* Attacking will use all remaining action points, but unused points will increase
the damage output.
* Back and side attacks deal more damage, even though the enemy will always
turn to face you.
* The ascend command can be used twice for a total of 3 floors to each encounter.
  * Humans cannot fly, as they don't have wings.
* Attacking from in the air with a descending blow will deal extra damage.
* Make sure to equip new weapons when you find them!
* Items, on the other hand, will take effect by simply holding them.
* Running out the turn count is a viable strategy in some cases.
* If you're stuck on *that* fight; AoE magic can hit every square an enemy
occupies, resulting in extra attacks.

### Endings
Your actions will affect which of two endings you will get. Stages with a red
description indicate a high chance of diverging events.
  
## Credits ##
- Yuvi      - Programming
- SnowyAria - Translation
- Niche     - Image Editor

## Special Thanks ##
- QA Testers
  - Renne_m
  - Shentok
  - Blueskyrunner

## Contact ##
Have any issues or run into any problems? Feel free to drop by our Discord here:
*  https://discord.gg slash YbbqZ67dhQ

Alternatively, you can message SnowyAria on Romhack.ing or on
Bluesky at @snowyaria.goodorevengreat.games
