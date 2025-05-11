# OTG-DungeonTrain-Alpha_Build

Welcome to Off-Track Games' Dungeon Train. Here are instructions for the current build:

1) Initialization: 

	a) Packaged Game: Download the folder and extract if it is zipped. Everything should be ready to go from here, so simply run the .exe file.
	b) In-Engine: Download the contents and extract if it is zipped. Open the .uproject, resize the viewport as desired, and play the game in Unreal Engine!

2) Gameplay Mechanics: In a future version we plan to have a tutorial, but it isn't in currently. Here are the key gameplay mechanics:

	a) Movement: WASD
	b) Attacks: Swipe (left-click), Heavy Attack (right-click), Energy Projectile (R-key)
	c) Dash: L-Shift Key
	d) Interact: For interacting with shopkeeper, picking up items, and entering the boss hatch
	e) Pause: P-key
	f) Inventory: Tab-key

3) Gameplay Loop:

	a) After selecting play on the starter screen, the player will spawn in a starter-car with no enemies. This is a good chance to feel out the movement/attack systems.
	b) All levels have a door on the right side of the level. The player must defeat all enemies to be able to continue to the next level.
	c) Levels will get more difficult, with more and stronger enemies. Gain items by playing and discover what they do to get stronger and prepare for the boss fight.
	d) On the fourth level and every four levels thereafter, a boss hatch will spawn near the exit door. The player can choose to interact with this hatch to face the boss if they dare.
	e) Once the player decided to face the boss, a brutal fight will occur. If the player defeats the boss, they have won the game.

4) Current State of the Game: At the current state, our game achieves all of our initial goals. We also went beyond that and continued to add content, some of which is still in the works: Here are some features that may not be complete:

	a) Shopkeep: The shopkeep in the starter car is not complete yet, but can be seen and gives insight into how the red coins will be used.
	b) Main Menu: The main menu can be buggy. It is recommended for now to only click either the start game or quit buttons.

5) Debugging/Error Scenarios: There are still chances for gameplay bugs to creep in at this point. We will work to eliminate these in the future, but for now here are some remedies:

	a) Movement: If the character is unmovable with WASD, press the Pause (P-key), exit the game, and re-enter.
	b) Missing Enemies: If a level is incompletable because an enemy is not showing up, exit the game and quit out from the title screen. Then, re-click the .exe file and start from scratch.
	c) Unknown Errors: If some other bug appears, restarting the game like outlined in 4b (above) may be necessary. 

6) Extra Info: Here is some extra info that will be added with future tutorial/help options in the game:

	a) The Grease Man is an enemy only found in the jungle! He will stay at a comfortable distance and shoot projectiles at the player. His slimy outer shell protects him from light attacks, so use your heavy attack to defeat him.
	b) The Golem is a tough enemy that will slam the ground if the player gets too close. Make sure to dodge their attacks if their hands go in the air!
	c) Enemies won't spawn close to you. Running around too much will allow hordes of enemies to cluster, so be strategic in managing the space of the levels.
	d) The boss is very strong! Make sure to pick up enough items and recharge health before facing him.
