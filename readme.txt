			
			+==========================================+
			|                                          |
			|               Quake 2 Mod                |
			|             By Simon Ogorek              |
			|              IT 266 - SP25               |
			|                                          |
			+==========================================+

Instructions to Install:

This process requires you to overwrite two files from Quake 2
You can delete the files that got replaced and use
steam verification to return the files.

Move the ref_gl.dll file into the root of Quake II
Move the quake2.exe file into the root of Quake II 
Launch the mod by using the provided exe (should be ~327Kb in size)

Note:

Rebuilding the .exe has broken compatability between the two rendering
pipelines, only a solution for openGL has been provided, software 
rendering will crash.

Instructions to play:

In game instructions can be brought up by typing help into the console

As a Survivor:

Before the game starts you will have to input what class you want to be
Each class has a specific max health, weapon, increased ammo for that weapon,
and a ability with a cooldown (f key). Your class will get improved over time by
killing enemies. You can change your class anytime (level will be reset) and
it will take effect when you die.

Pressing f1 will select the warrior class who has a super shotgun, 150 hp,
a leap ability. At Level 3 you are provided some HP for leaping

Pressing f2 will select the tactical class who has assault rifle, 100 hp,
a dodge ability. 

Pressing f3 will select the tank class who has a chaingun, 200 hp, and a
tank mode. Your tank mode initially gives you 50 armor but removes all armor
after 10 seconds. As you level up you gain an additional 200 ammo with each
use of tank mode, your last level up gives you double fire rate while in tank
mode. Additionally, as you level up your armor cycles through Jacket Armor,
Combat Armor, Body Armor with the use of tank mode.

Pressing f4 will select the sniper class who has a railgun, 75 hp with a backflip
ability. This backflip is inverse to where you are are currently facing with some
upwards velocity. At level 2 this ability applies a 4x damage boost to your next
shot making it such that you can one shot the stronger enemies.

Pressing f5 will select the medic class who has a blaster and 75 hp with a healing
ability which heals yourself and people on your side for 50 hp or whatever their
max health is, whichever value is lower. At level 2 the blaster becomes multishot,
shooting 7 projectiles at once. 

As a Host:

Pressing f6 will allow you to become a host, as a host you have a 100 points to spend
on monsters. You at all times have a monster selected and you can index through the list
available to you by pressing , to decrement and . to increment the current selection is
shown in the top left. The spawning mechanic is linked to your blaster when you fire,
creating a trace from your gun to the point of impact creating an enemy that will only
target non host targets. Your new balance is repeated to you on the center of the screen.

General Controls:
F1 - Select the Warrior Class
F2 - Select the Tactical Class
F3 - Select the Tank Class
F4 - Select the Sniper Class
F5 - Select the Medic Class
F6 - Become a host

Player Controls:
f - use ability

Host Controls:
, - Change selected monster (descending point value)
. - Change selected monster (ascending point value)

Deliverables:
✔ - Done
✖ - Not Done

Common:

✔ Shortcut that Auto-Launches your Mod

✔ Mod in a Separate Folder

✔ README file in GIT that explains HOWTO install and play / test your mod

✔ UI updates reflecting your Personal Deliverables

✔ Help Screen to detail how to play your mod in game

Personal:

✔ Dungeon Player able to place various monsters around the map ( 10 Monsters ) 

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
	
✖ 5 Bonuses can use on the monsters

	Assigning a bonus to an enemy 1.5x its cost truncated
	
	Speed Upgrade
	Health Upgrade
	Damage Upgrade
	Explode on Death
	?

✔5 Player Classes (Primary Weapon, Secondary Ability)

	✔Class A (Shotgun, Big Leap)
	✔Class B (Machine Gun, Weapon Upgrades)
	✔Class C (Chain Gun, Tank Mode)
	✔Class D (Railgun, Sniper Mastery)
	✔Class E (Blaster, Battle Medic)

Players Gain from killing monsters 
	Total ✔ : 9 / 15
	
	Class A:
		✔ Level 1 - You can press f to leap relative to where you are aiming (12 second cooldown)
		Level 2 - Enter Rage when you leap for 5 seconds, Rage means increased speed
		✔Level 3 - Entering Rage Heals you for 25 HP
		
	Class B:
		✔ Level 1 - You can do a dodge move by pressing f
		Level 2 - You can right click to shoot a grenade launcher round 
		Level 3 - Your right click gets replaced with 3 rockets in a horizontal spread
		
	Class C:
		✔ Level 1 - You can press f to enter Tank Mode, which provides limited time armor
		✔ Level 2 - Tank Mode now gives you 200 ammo when activating
		Level 3 - The Chaingun's attack rate is now doubled in Tank Mode
		
	Class D:
		✔Level 1 - You can press f to leap backwards in the air
		✔Level 2 - Your next shot after leaping does bonus damage
		Level 3 - Upon killing an enemy they have a chance of exploding
		
	Class E:
		✔Level 1 - Pressing f heals all players in vicinity by 50 HP
		✔Level 2 - Your Blaster now has multishot 
		Level 3 - When you are below 10% HP heal for 70% one time
		

✖ Monsters can be Upgraded
