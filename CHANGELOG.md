# Demo v0.6.2 - May 28 2024

## Added
- 56 new keys to Level 6 Fighting Inputs
- Level 6 Health Drain/Gain
- Locked Levels
- Turning Title Screen Logo

## Changed
- Level 6 Arrow Key Names
- Level 6 Warning Screen
- Level 6 Fighting Inputs 5 - 8
- Level 6 Player and Opponent Animation turning to idle
- Level 6 Key Display Input and Animation: Split now
- Level 6 Health Damage Amount
- Level 6 Health Gain Amount
- Variables with Emojis (no Emojis now)
- Variables without a - (- now)

### Removed
- Pressing B to change legacy mode (Debug Keybind I forgot about)

# Demo v0.6.1 - May 27 2024

## HaxenFilp Work
- Reorganized Change-logs (they are all now in different comments)
- Removed Non-Scratch Extensions from the code (I'm pretty sure, the project should be able to run on regular scratch now!)
- Removed Medals (they were broken, might be re-added in the future?)
- Removed 30+ fps setting from turbowarp compiled versions
- Added Experiment Map for Experiment Level
- Added Warning screen for Nugget Bot level
- Removed Warning Text for nugget Bot Level
- Added Rank System

# Demo v0.6 - May 27 2024
## HaxenFilp Work
- Removed Microphone option stuff
- Removed Start screen Scratch or Turbowarp Mode stuff
- Modified Pause Menu
  - Fade out is more quick
  - Faded more
- Changed Freeplay “Corrupt” stage opponent image
- Modified Freeplay Select Y change variable (code thing)
- Removed Default Pause Alt Keybind
- Added Ability and Ability Alt Option
- Renamed Leave and Leave Alt Keybinds in options menu to Leave/Pause and Leave/Pause alt
- Modified Title Screen Layout
- Changed Watermark Brightness
- Fixed Typo in Options Menu
- Fixed Character Swap Menu Selection
- Added HaxenPX Character Swap Character (its there now but now its useless)
- Modified Character Swap Menu  "Layout"
- Added the ability to dash down when jumping
- Removed Player ability to crouch mid-air
- Fixed bug where Spikes could spawn in the air (about time I did this)
- Added Game Over Screen
- Optimized Level Creation scripts into a Custom Block
- Optimized Watermark script a little bit
- Fixed Issue with Freeplay where nothing would happen if you held one of the controls used in freeplay
- Added Experiment Level (Freeplay)
- Added Medals and Medal System (Gamejolt and New-grounds only)
- Fixed Level Select Gradient Timer Check (uses the new Variable now)
- Removed Levels Played Rounding
- A is now automatically a left arrow alt (don't ask me what happened it just wasn't there)
- Added Folders
- Added Level 6 (boxing)
  - Added Warning Screen
  - Added Key Display
  - Added Boxing Mechanic
    - Its in KeyDisplay Sprite
  - Added Phase 1 Health Bar
  - Added Phase 2
  - Added Phase 2 in-game Cutscene
  - Added Phase 2 Time Bar
  - Added Health 
- Added Warning Screen for Mechanics
- Added Event: Win
- Fixed Bug in Story Mode and Freeplay where you could hold space and when its released a level would play
- Removed HaxenPX Unlock able (not the character, just the ability to unlock the character)
- Made Watermark Smaller
- Re-branded Versions before v1.0.0 into Demo Versions (this is what versions before v1 be identified as, demo versions)
- Added Tutorial to Title Screen
- Fixed Issue where when leaving level Select, 48 clones total would be on the title screen
- Changed Turbowarp FPS to 60

## LittleBlueGamer Work
-Added warning sound effect for Nugget bot hands
-Added sound effect for when boss throws the hand

# Demo v0.5 - March 30th, 2024
## HaxenFilp Work:
- Added number inputs to Outline and Shadow Stamp Scripts
- Added Saving and Loading to Options Menu: it would help so much
- Added Hit boxes to bombs and clocks: the glow would've messed up the collisions
- Added SFX for selection an Option with the mouse pointer
- Added Save Settings Option in Options Menu
- Added Load Settings Option in Options Menu
- Added Title Screen Button Bop
- Removed LINK LEN: unused variable from v0.4
- Fixed Custom Keybinds not working in Character Swap Menu
- Added default Alt Keybind for Left
- Added Freeplay Menu
- Added Hunched down Sprite to gao in the Level 1 Cutscene
- Added FREEPLAY variable to check if you entered a level from freeplay
- Added Freeplay Cutscene Option to Options Visuals Menu
- Added Leave Option in Options Menu: yes
- Added Checks in level Editor for Legacy Mode (difficulty)
- Added checks in Level Outline for Legacy Mode
- Fixed Positions for Legacy Opponents
- Added Legacy Sounds for the Player Jumping
- Added Mirror Event (flips controls)
- Fixed Display Opponent Rotation Style
- Added Mirror Event to Level 2
- Added Smooth Freeplay SELECTED LEVEL Transition
- Added Freeplay Camera Scroll
- Added CANSPACE Variable
- Fixed Opponent Hands getting stuck on level ceilings
- Fixed Level 5 True End being 0.1 seconds long and added a fade to it
- Removed Hand Bouncing (annoying af)
- Removed Legacy checks for difficulty visibility
- Moved Character Swap Menu button from Level Select to Title Menu
- Fixed Character Swap Issue where you could hold your mouse on a character and it would keep selected them even if they were already selected
- Moved Title Menu Up
- Smoothed up the Freeplay level Select scroll
- Added Opponent Stare at player script (Nugget bot level)
- Added Nugget-Bot Opponent Hands: a consistent style makes everything feel good
- Added BACKDROP Color: do I need to explain?
- Added Freeplay backdrop
- Added Outline Hands to serve as target position visibility (only for Player Target hands)
- Added Hand Move Custom Block to Opponent Hands (no more copy paste in here)
- Connected Player Target Opponent Hand Scripts to a variable
- Added Nugget Bot Skin to Bombs
- Separated the Gameplay timer from the actual timer
- Added Pause Menu
- Added Looping to Nugget bot BG Music
- Level 4 Force Move is connected to the Mechanic Option now
- Level 4 Force Move is moved to the Events Sprite instead of the Levels sprite
- Added Direction Flip Flash
- Added Corrupt Level
- Added Character Unlocking
- Added HaxenPX
- Added HaxenPX Unlocking
- Added Custom Hitbox Support
- Added Custom Opponent Hand Outline Support
- Added Custom Outline to Nugget bot stage
- Added Custom SFX for Corrupt Level
- Added Custom Intro for Corrupt Level
- Freeplay Cutscenes are disabled by default
- Fixed Opponent Hands getting stuck on the walls

## LittleBlueGamer Work:
-Added outline to the level: ORIGINALLY GONNA USE PEN BUT THE OP IN THE BACKGROUND GOT IN THE WAY (edit: had a solution)
- Overhauled Jump Sound
- Added Glow to Bomb and Clock explosions:
- Added Timmy from Roltycore and Roltycore 2: no reason
- Added Nugget Bot Level Cutscene
-Added steel rolty boss music for nugget bot: cuz idk
-Added Player Target Scripts for the Opponent Hand
-Fixed some coding mistakes that haxen made
    note from haxen: sad emoji
-Made Nugget-Bot Throw Bombs
- Added Turbowarp Default Settings

## Combined Work:
- Added PenEngine: Sprite to help with Pen stuff
- Made Timmy fast and the levels are a bit harder as Timmy
- Overhauled Selection, Accept, and Leaving SFX: Why not?
- Changed Most Menu buttons: replaced distance to mouse pointer with touching mouse pointer
- Added Turbowarp Warning Screen
- Added Console Screen (related to the TW Warning screen)
- Added Level Nugget-Bot

# Demo v0.4.5 - March 25th, 2024
- Added Cutscene Object Types: neutral, fade
- Fixed Bug in level 3 Cutscene: If sounds were disabled the opponent Cutscene obj would stay around
- Removed LINK LEN Variable: unused variable
- Added Cutscene - Player Sprite broadcast: basically the default cutscene player position stuff with the fade n stuff
- Separated Intro and Gameplay Opponents: Fixed another bug
- Fixed Bug were opponent clone wouldn't be deleted after your death and would appear as a double opponent: this was here since like v0.2 and no matter what I did it wouldn't be fixed
- Removed Redundant Checks and Sets: They are just a waste
- Removed Opponent Movements: Weren't needed and they were screwing me up and weren't needed anyway
- Modified Level 4 Gradient Position: Dunno when I changed this or why but it was screwed up
- Added Broadcast for Enabling Opponent Hands: better than going in the code to do it.
- Added Broadcast for Disabling Opponent Hands: better than going in the code to do it.
- Added Broadcast for Disabling Opponent Clocks: wasn't in v0.4
- Fixed Bug where Controls Menu wouldn't detect Arrow Key input: I don't know why it doesn't work, I'm just fixing it
- Added Double check to controls Menu where it checks if you are sure about your key choice: Why not? Also you can see what it actually received In case you might've did something and got the wrong key.
- Added Legacy Check to mechanics: wasn't in v0.4
- Added Option to disable Mechanics (except opponent hand): Make it just a bit easier lol.

# Demo v0.4 - March 25th, 2024
- Changed Microphone Icon Costume
- Microphone Icon changes color depending on how loud it is
- Added Mic Visualizer Pixels Option
- Changed Hand Limit to 20
- Fixed v0.3 changelog with 1 change
- Added Easy way of changing Player Costume to another Player
- Fixed Opponent Hand Bug where it would stay in a pit
- Added Character Swap Button in Level Select
- Added Character Swap Menu
- Added Haxen Character Swap Option
- Added TJ Character Swap Option
- Added Djotta Character Swap Option
- Added a Sprite for Gameplay Events
- Removed Level 5 "True End" (it didn't get played anyway)
- Fixed Bug related to Level 5's Second part. (its related to decimals, don't worry its not that big a deal)
- Renamed #️⃣ HAND CLONES to #️⃣ OBSTACLE CLONES
- Added spikes to Level 1
- Reused Old Intro Sound as a warning for the level 1 spikes
- Added Broadcast to Enable Spikes
- Added Broadcast to Disable Spikes
- Added Custom block for waiting on a specific level in the hand
- Added Custom block for waiting on a specific level in the spikes
- Player no longer can Jump when crouching
- Added a Down Charge (inspiration from SMB2)
- Added a Jump Charge (Connected to Down Charge)
- Added Down Charge SFX
- Added Pitch changing for the Down Charge SFX
- Added some more Randomization to the Background Boss Sprite
- Added TJ Sprites
- Added Djotta Sprites
- Added Cutscene System
- Added Level 5 End "Cutscene"
- Added Background Music Track named "Hyperactive Creativity"
- Optimized Option Menu Clones to be a Custom Block
- Added Graphics and Visuals Menu in the Options Menu
- Added Back Option to the Option Menus
- Overhauled Options Menu Look
- Overhauled Options Menu Functionality
- Added Sounds and Music Menu in the Options Menu
- Added Background Music Option
- Added Keyboard control to Options Menu
- Modified Mouse Controls
- Added Keybind Functionality
- Added Controls Menu
- Added Keybinds
- Added Sound Option
- Added Bombs to Level 3
- Added Clocks to Level 5
- Added Time Flash (its a Random Color)
- Added Level 1 Cutscene
- Added Level 2 Cutscene
- Added Level 3 Cutscene
- Added Level 4 Cutscene
- Added Level 5 Start Cutscene
- Minor Optimize how Title Buttons Work
- Fixed Title Screen Bug where you couldn't put your mask on a button while using the keyboard
- Changed Title Screen Layout

# Demo v0.3 - March 21st, 2024
- Made Level 3 Backdrop Slightly Brighter
- Optimized Gradient Initialization into one Custom Block
- Added Gradient to Level Select
- Added Shaking to Intro Character
- Modified Player Running Animation Start Condition
- Added Main Menu
- Added “Destroy Gradient” Broadcast
- Modified Opponent Hand-Bouncing
- Added Arrow Key control to Level Select for the level
- Changed some Level Select Level Begin Conditions
- Added More Mobile friendly controls for Level Select
- Added variable for KEYBOARD CONTROL
- Difficulty Selector now loops when using KEYBOARD CONTROL (consistency)
- Added Arrow Key control to Title Screen for the buttons
- Changed Intro Sound effect to a Synth.
- Change Level Select Gradient to Red when you lose.
- Change Level Select Gradient to Green when you win.
- Slightly Optimized Fade Coloring
- Removed Level 2 Gradient "Intro"
- Moved Level 4 Infinite Player Movement scripts from Gradient to Levels
- Put Gradient "Animation" Scripts into a custom block.
- Modified Some Layers
- Removed the Separate SELECTED and SELECTION Variables
- Added Emojis to the Variables
- Added Options Menu
- Added Legacy Mode Option
- Added Legacy Mode
- Added Watermark Checks
- Added Easy Way of adding Options (OPTIONS LIST)
- Added Setting Reset Option (press R when enabled)
- Added Easier Way to change Level Select World Distance
- Added Level 5
- Changed Level Select Icon Y position
- Fixed Bug with selections: you would play but it would send you nowhere
- Increased size change of selected personality/world
- Added Lists of levels you've played
- Added Visualizer for the Player
- Added Keybind to reset options: R
- Added Visualizer Speed Multiplier to Options Menu
- Added Visualizer Option to Options Menu
- Changed Hand Limit to 299

# Demo v0.2.1 - March 18th, 2024
- Rebrand
- Fixed v0.2 date
- Fixed Names of previous version changelogs (it was cruel worlds but i said cruel world)

# Demo v0.2 - March 17th, 2024
- Improved Opponent Sprites in game play
- Changed Watermark Brightness
- Centered Intro Card Opponent Display
- Modified Player Movement Sprite Change Math
- Added Gradient to Level 4
- Added Background Opponent Movement
- Put player in the center  when they spawn in
- Player now is forced to the left side of the screen in level 4
- Level 4 now has a pit to the left
- Modified Level 2-3 Levels
- Multiple Hands Spawn in Level 4
- Modified Hand Spawning code for other levels
- Added Gradient to Level 2
- Multiple Hands Spawn in Level 2
- Fixed Bug where Jump sound would play even if you didn't jump
- Player can now Jump off the Hand while its going up
- Added the ability for Opponent hand to change depending on a variable
- Added Limitations to Opponent Hands (only 10 clones can be onscreen now)
- Added Difficulty Selector (Easy, Normal, Hard)
- Added Death Sound Effect
- Added Selection Sound Effect
- Added Difficulty Selection Sound Effect
- Added Intro Sound Effect
- Added Difficulty Selection Fail Sound Effect
- Fixed Issue where Opponent Hand would spawn on you and never reach the floor
- Rerecorded Thump Sound Effect for Opponent Hand
- Removed the ability to crouch in Level 4 (too op)
- Added Limitation to Player Hand Bounces
- Added Hand Bounce Sound Effect
- Fixed Level Intro Transition Lines

# Demo v0.1 - March 17th, 2024
- Level Select
- Intro Card
- Fade
- Levels
- Platformer Controls
-  Sprites
- Opponent Sprites
- Opponent Attacks
- Watermark
- Backdrops