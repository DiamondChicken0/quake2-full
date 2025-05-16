			
			+==========================================+
			|                                          |
			|               Quake 2 Mod                |
			|             By Simon Ogorek              |
			|              IT 266 - SP25               |
			|                                          |
			+==========================================+

Instructions to Install:

This process requires you to overwrite two files from quake 2
The original files are in a folder called "original files" in the mod folder
Additionally, you can simply delete the files that got replaced and use
steam verification to return the files.

Move the ref_gl.dll file into the root of Quake II
Move the quake2.exe file into the root of Quake II 
Launch the mod by using the provided exe (should be ~327Kb in size)

Note:

Rebuilding the .exe has broken compatability between the two rendering
pipelines, only a solution for openGL has been provided, software 
rendering will crash.

Instructions to play:

As a Survivor:

Before the game starts you will have to input what class you want to be
Each class has a specific max health, weapon, increased ammo for that weapon,
and a ability with a cooldown (f key). Your class will get improved over time by
killing enemies. You can change your class anytime (level will be reset) and
it will take effect when you die.

Pressing f1 will select the warrior class who has a super shotgun, 150 hp,
a leap ability. As you level up your leap puts you into rage, increasing
speed and providing some hp

Pressing f2 will select the tactical class who has assault rifle, 100 hp,
a dodge ability. As you level up you gain access to different alt-fires
accessible using right click. Your first alt-fire is a single grenade launcher
round, afterwhich its get replaced with 3 rockets.

Pressing f3 will select the tank class who has a chaingun, 200 hp, and a
tank mode. Your tank mode initially gives you 50 armor but removes all armor
after 10 seconds. As you level up you gain an additional 200 ammo with each
use of tank mode, your last level up gives you double fire rate while in tank
mode. Additionally, as you level up your armor cycles through Jacket Armor,
Combat Armor, Body Armor with the use of tank mode.

General Controls:
F1 - Select the Warrior Class
F2 - Select the Tactical Class
F3 - Select the Tank Class
F4 - Select the Sniper Class
F5 - Select the Medic Class
F6 - Become a host

Player Controls:
f - use ability
Mouse Right - tactical alt-fire

Host Controls:
, - Change selected monster (descending point value)
. - Change selected monster (ascending point value)

Deliverables:


Common:

Shortcut that Auto-Launches your Mod

Mod in a Separate Folder

README file in GIT that explains HOWTO install and play / test your mod

UI updates reflecting your Personal Deliverables

Help Screen to detail how to play your mod in game


Personal:

Dungeon Player able to place various monsters around the map ( 10 Monsters ) 

	1: Light Guard (1 pt)
	2: Shotgun Guard (2 pts)
	3: Machine Gun Guard (2 pts)
	4: Flyer (2 pts)
	5: Enforcer (3 pts)
	6: Parasite (3 pts)
	7: Gunner (3 pts)
	8: Brains (4 pts)
	9: Iron Maiden (5 pts)
	0: Gladiatior (6 pts)
	
5 Bonuses can use on the monsters

	Assigning a bonus to an enemy 1.5x its cost truncated
	
	Speed Upgrade
	Health Upgrade
	Damage Upgrade
	Explode on Death
	?

5 Player Classes (Primary Weapon, Secondary Ability)

	Class A (Shotgun, Big Leap)
	Class B (Machine Gun, Weapon Upgrades)
	Class C (Chain Gun, Tank Mode)
	Class D (Railgun, Sniper Mastery)
	Class E (Blaster, Battle Medic)

Players Gain from killing monsters
	
	Class A:
		Level 1 - You can press f to leap relative to where you are aiming (12 second cooldown)
		Level 2 - Enter Rage when you leap for 5 seconds, Rage means increased speed
		Level 3 - Entering Rage Heals you for 25 HP
		
	Class B:
		Level 1 - You can do a dodge move by pressing f
		Level 2 - You can right click to shoot a grenade launcher round 
		Level 3 - Your right click gets replaced with 3 rockets in a horizontal spread
		
	Class C:
		Level 1 - You can press f to enter Tank Mode, which reduces damage by 50% for 5 seconds
		Level 2 - Tank Mode now gives you 200 ammo when activating
		Level 3 - The Chaingun's attack rate is now doubled in Tank Mode
		
	Class D:
		Level 1 - You can press f to leap backwards in the air
		Level 2 - Your next shot after leaping does bonus damage
		Level 3 - Upon killing an enemy they have a chance of exploding
		
	Class E:
		Level 1 - Pressing f heals all players in vicinity by 50 HP
		Level 2 - Your Blaster now has multishot 
		Level 3 - When you are below 10% HP heal for 70% one time
		

Monsters can be Upgraded