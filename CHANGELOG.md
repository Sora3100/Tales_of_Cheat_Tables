### Changelog

#### 2024/08/07

-	Updated "Allow using Mystic Artes without Overlimit" patch to remove side effects for Xillia 1 and Xillia 2
-	Added Weapons/Armor to the Gem Editor in the Rebirth table.
-	Added Grade Shop options to the Rebirth table.
-	Added Grade to the Rebirth table.
-	Added Encounter, Background, Time until encounter to the Legendia table.
-	Updated frubam's Chloe fight editor to allow editing more than just that fight in the Legendia table.

#### 2024/06/12

-	Added changes suggested by CeruleanSky
-	Added Graces arte slots for u4ick's extra artes patch
-	Added Abyss arte slots for u4ick's extra artes patch

-	Added "Have all difficulties" patch for Xillia 1 and Xillia 2 and Graces F
-	Added "No encounters" patch for Graces F
-	Ported "Unlock Lloyd & Co. for leveling" patch to another version of Symphonia - Dawn of the New World
-	Added "Return Xillia 1 character switch in fights" patch for Xillia 2
-	Added "Disable OVL requirement for Mystic Artes" patch for Xillia 1 and Xillia 2

#### 2024/03/27

-	Fixed game functions not working properly sometimes in Xillia 1
-	Fixed the issue behind the "Something went wrong" message in Xillia 1

-	Made the Symphonia table less dependent on the latest game version

-	Added some accel stats to Graces F table
-	Added Narikiri artes to Graces F table

#### 2024/01/31

-	Added "Save Anywhere" patch for Graces F and Vesperia (PS3)
-	Added "No linking requirement for EX Dungeon" patch for Xillia 2
-	Added "Unlock Lloyd & Co. for leveling" for Symphonia - Dawn of the New World
-	Added "No party lock" for Xillia 1
-	Added "Disable party checks" for Xillia 1 and Xillia 2
-	Added "Disable party changes" for Xillia 1
-	Added "Disable hitstop" for Xillia 1 and Xillia 2
-	Added "Freeze battle timer" for Tales of VS

-	Corrected some mistakes in Destiny DC's difficulty values editor

-	Added On-Hover ability to Rebirth's Gem Editor

-	Gem editor now automatically detects your version
-	Gem editor now supports EU versions
-	Added Base Max HP to Graces table
-	Added some more info about shards
-	Removed leftover hotkey from Weapon editor

-	Added Devil's Arms kills for Xillia 1 and 2
-	Updated Arte List for Xillia 1 and 2 with some QoL

-	Expanded and gave Symphonia - Dawn of the New World's item list some quality of life upgrades
-	Made the Symphonia - Dawn of the New World table more compatible with other game versions

-	Added Overlimit gauges to Innocence R and Hearts R

-	Fixed Arise's Have 1 of every item script
-	The Arte List now generates a list of dropdown options

-	Made Destiny DC's difficulty options savable

#### 2023/11/09

-	Updated Arise to latest game version (10.47.00 according to buildinfo, buildid 12162925)

#### 2023/10/20

-	Corrected some mistakes in Destiny DC's difficulty values editor

-	Made the Graces F table more compatible with other region versions
-	Expanded difficulty values in Graces F
-	Added a (hopefully) future proof Shard/Gem/Weapon/Armor editor

#### 2023/09/16

-	Updated the Auto Control Mode script to be able to pick whether to set to Auto, Semi-Auto or Manual. (default Manual)
	-	Applies to both Phantasia and Destiny

-	Added some backgrounds as a dropdown for Symphonia

#### 2023/07/24

-	Added new table: Destiny (PS1)
	-	Features:
		-	Party Formation Editor
		-	Stats Editor
		-	In-Battle Stats Editor
		-	Equipment Editor
		-	Change Control Modes in and outside of battle
		-	Enable or Disable Dash Modes
		-	Enable or Disable Combo Command Modes
		-	Automatic Manual Control Mode, Dash Mode and Combo Command Mode script

-	Updated PS1 tables to be more future proof (they might even work on other emulators now, but it is not guaranteed, try your luck!)
	-	Affected:
		-	Phantasia
		-	Eternia
		
-	Phantasia now has a more future proof version of the Automatic Manual Control Mode, Dash Mode and Combo Command Mode + Auto Death Cam script
-	Added Arte Usage for Phantasia

#### 2023/07/11

-	Vesperia's "Arte Properties Editor" will now automatically update itself for the following groups:
	-	Arte learning conditions
	-	Evolve conditions
	-	Characters that can use this arte

-	Changed Xillia 1's Final Boss encounter editor to use the final Wingul encounter instead
	-	If for some reason you still want the old one, it can be found under notes

-	Added "Alisha can armatize" script to Zestiria

-	Updated Arte names and Grade Shop options to reflect the english patch names for Destiny DC

-	Addded a difficulty unlocker for Destiny DC

-	Added Arte Usage to the following games:
	-	Destiny DC
	-	Innocence R
	-	Hearts R
	
-	Added Arte Unlocks to the following games:
	-	Innocence R
	-	Hearts R
	
-	Added Equipment Editor to the following games:
	-	Innocence R
	-	Hearts R
	
-	Added Bonds and Somatic Bonds to the following games:
	-	Innocence R
	-	Hearts R

#### 2023/06/26

-	Added a Skills Editor for Narikiri Dungeon X.

-	Ported over certain things from GameCube:
	-	"No Recoil Time after Tech"
	-	"Walk Through Walls"
	-	"Get on Rheiards any time"
	
-	Updated all PS2 and PSP tables to use a newer and faster enable mechanism.
	Note that this may require newer versions of the emulator(s).
	In case it detects the new method is not available, it will revert to the old method.

#### 2023/06/14

-	Vesperia changes:
	-	Updated Arte Canceller to be able to configure which side is affected.
	-	Added a script that lets you chain artes in any order.
	-	Added a script that lets you use Player artes in the air.

-	Symphonia changes:
	-	Added enemies don't attack script
	-	Added minimum damage script (the numbers shown on screen are still the normal values, though)
	-	Added infinite normal attacks script
	-	Added a script that gives everyone Colette's wings
	-	Added a script that lets you ignore OVL restriction for Lloyd/Kratos/Sheena/Regal,
		and also be able to use Mystic Artes multiple times (applies for all characters)

#### 2023/06/02

-	Added Grade Shop options to Graces, Hearts R and Innocence R.
-	Added Arte Canceller for Vesperia.
	Some notes regarding it:
	-	Mystic Artes are harder to activate.
	-	Arte order still applies (base -> arcane -> altered, more with skills, and OVL allows free chaining)
	-	During OverLimit, certain actions that require mashing do not work, as they will be instantly canceled.
	-	Burst Artes activate instantly upon holding the button.
	-	Any action can be canceled, except for Mystic Artes. (this includes normal attacks, artes, Fatal Strikes, Burst Artes, activating OVL and spell casting)
	-	The Burst Arte/Fatal Strike tutorials may softlock the game. Please turn them off while doing them.
		(if you do get in this state, just set the character's HP to 0 to be able to reload a save)
	-	I have also included tools regarding Fatal Strike to help you incorporate them into combos, if you wish to.

#### 2023/04/26

-	Added a new script for Vesperia, where enemies don't activate Over Limit.
-	Added a secondary script to Xillia 1/2 in case the first linking script doesn't work
-	Added Samu's Jude transform script

#### 2023/02/24

-	Added a rudimentary Ludger -> Victor script

#### 2023/01/03

-	Fixed some possible crashes in the linking scripts for Xillia 1 and Xillia 2.

#### 2023/01/02

-	Updated Xillia 1 and Xillia 2 scripts to more recent rpcs3 builds (Arte Editor/Multiplayer linking)
-	Backported Version 2 of the linking script to Xillia 1.
-	Minor table cleanup.

#### 2022/12/06

-	Updated Eternia table to be compatible with the current version of DuckStation.

#### 2022/11/28

-	New features: Symphonia
	-	Added a script that allows you to save anywere.
	-	Added a field run speed modifier (overworld is unaffected)
	
-	Fixed a case where the Graces table wouldn't enable under a certain condition	

#### 2022/08/10

-	Added Alisha DLC for the all enemy entries viewer in Zestiria.
-	In addition, added seperate scripts if you don't have certain DLC installed.

#### 2022/07/27

-	Fixed Destiny DC's BGM and Enemy Group Mod not being accurate.
-	Expanded Destiny DC's Difficulty values

#### 2022/07/13

-	New features: Hearts R
-		Added the ability to freeze encounter timer.
-		Added the ability to enable the airship.

-		An Encounter Editor has also been added, but it involves some work from the end-user to use.

#### 2022/06/29

-	New features: Innocence R
-		Added the ability to freeze encounter timer.
-		Added the ability to enable the airship.

-		An Encounter Editor has also been added, but it involves some work from the end-user to use.

#### 2022/06/01

-	Added a workaround for the Japanese version of Xillia 2, where looking at Bisley's artes in any form would result in a crash.
-	Fixed one of Ludger's weapons not working under Inventory Editor.

-	Fixed Field Run Speed not working in the Japanese version of Xillia 1.
-	Added 3 missing entries under Inventory Editor.

-	New feature: Zestiria
	-	Show all entries in Enemy Book

-	New table: Berseria
	Feature:
	-	Show all entries in Enemy Book

-	Minor cleanup of some tables

#### 2022/05/18

-	New feature: Xillia 2
	-	You can now play as bosses! This took some time to make.
		Please read the readme inside the script.
		Mystic Artes are not supported, don't use them, or you'll softlock your character.
		Supported characters:
			-	Wingul
			-	Agria
			-	Presa
			-	Jiao
			-	Ivar
			-	Nachtigal
			-	Celsius
			-	Maxwell
			-	Volt
			-	Rideaux
			-	Chronos
			-	Bisley
			-	Stahn
			-	Cress
			-	Rutee
			-	Mint
	
-	New features: Vesperia
	-	Added a Skill Properties Editor
	-	Added an Item Properties Editor
	-	In addition, expanded on Arte Properties and Enemy Book Data.

#### 2022/05/05

-	New table: Hearts (DS)
	-	Features:
		-	Stats Editor
		-	Party Formation Editor

-	New table: Hearts R
	-	Features:
		-	Stats Editor
		-	Party Formation Editor

-	New table: Innocence R
	-	Features:
		-	Stats Editor
		-	Party Formation Editor
	
-	New table: Tempest
	-	Features:
		-	Stats Editor
		-	In-Battle Stats Editor
		-	Party Formation Editor

#### 2022/04/21

-	New table: Rebirth (PSP)
	-	Has all the same features as the PS2 version!
	
-	New features: Vesperia
	-	Added an Enemy Data Editor
		-	In addition, a script that allows you to view hidden entries.
	-	Added an Arte Properties Editor
	
-	New features: Legendia
	-	Added a Stats Editor
	-	Added an In-Battle Stats Editor
	-	Added an Equipment Editor
	
-	New feature: Xillia 1
	-	Added an Arte Usage Editor
	
-	Updated Xillia 1's Enemy List dropdown to be more convenient.
-	Updated Xillia 2's Arte List dropdown to be more convenient.
-	Updated Xillia 2's Enemy List dropdown to be more convenient.

-	Ported over some features from frubam's Abyss and Legendia table to work with newer PCSX2 versions.

#### 2022/04/07

-	New feature/table: Destiny 2
	-	Added an Equipment Editor
	-	In addition, there is now a table for the PSP version! It has all the same features!
	
-	New table: Innocence
	-	Features:
		-	Party Formation Editor
		-	Stats Editor	

-	Fixed an issue in the Arise table's Run Speed script where running with keyboard wouldn't make the values show up.

#### 2022/03/30

-	Updated Arise table to Update 3 (2022/03/30)

#### 2022/03/22

-	New feature: Graces f
	-	Added an Arte List Editor

-	Fixed Vesperia's Save Anywhere script requiring you to touch save points, now it should work from the moment you activate it!

#### 2022/03/08

-	New feature: Xillia 1
	-	Added an inventory editor.
		-	As an added bonus, the equipment editor is no longer based on Xillia 2!

-	New feature: Xillia 2
	-	Added an inventory editor.

#### 2022/02/22

-	New features: Xillia 1
	-	Added the ability to force on Overlimit for any character.
	-	Added the ability to change field movement speed.

-	New features: Xillia 2
	-	Added the ability to force on Overlimit for any character.
	-	Added the ability to change field movement speed.
	
-	New features: Symphonia
	-	Added the ability to enable/disable Union Attacks.
	-	Added the ability to enable/disable the Devil Arm's power.
	-	Added the ability to change Colette's Angel state

#### 2022/02/08

-	New feature: Xillia 2
	-	Added a new version of the linking script. This version will change the link 
		depending on your character's control mode. Unfortunately, this still
		only works for the listed RPCS3 version in the readme.
-	Removed Sandy Bridge support. This should make the script section more
	user friendly.

-	New features: Graces
	-	Added a rudimentary stats editor
	-	Added In-Battle Stats editor
	
-	New feature: Destiny 2
	-	Added an Arte Usage editor.
-	Revised Stats a bit

#### 2022/01/25

-	New features: Xillia 1
	-	Added the ability to enable/disable any artes.
	-	Added the ability to enable/disable any skills.
	-	Added the ability to enable/disable Grade Shop options anytime.
	-	Revised the Status Effects part of the table to be less confusing.
	-	Revised the game functions part of the table to be less confusing.

-	New features: Xillia 2
	-	Added the ability to enable/disable any artes.
	-	Added the ability to enable/disable any skills.
	-	Revised the Status Effects part of the table to be less confusing.
	-	Revised the Unlocks part of the table to be less confusing.
	
-	New feature: Vesperia
	-	Added a Save Anywhere script
	
-	Added a dropdown list to Graces F battle BGM changer

#### 2022/01/11

-	Updated Graces table to be more future proof.
-	New features: Graces
	-	Change field movement speed
	-	Change difficulty values	
	-	Change battle BGM

#### 2021/12/14

-	Updated Arise table to Update 2

#### 2021/10/29

-	Expanded Arte Unlocks/Usage with Cosmic Ensemble

#### 2021/10/05

-	New features: Xillia 2
	-	Play as bosses scripts for Cless and Stahn!  (WIP, By Just_Samu)

#### 2021/10/03

-	New features: Arise
	-	Arte Usage/Unlock Editor
	-	Change Run/Swim Speed
-	Fixed Arte List Editor not working for every arte.

#### 2021/09/22

-	New features: Arise
	-	Arte List Editor
	-	Unlock/lock any title

#### 2021/09/16

-	New table: Arise
	-	Features:
		-	Party Formation Editor
		-	Stats Editor
		-	Arte Proficiency Editor
		-	Devil's Arms kill Editor

#### 2021/09/07

-	New feature: Destiny DC
	-	You can now change the amount of Lens you have in your inventory.
	
-	Made the Symphonia 2 table more future-proof.

#### 2021/08/28

-	New features: Destiny DC
	-	You can now immediately unlock/max swordian skills and use them!
	-	Ability to change difficulty values

-	New features: Abyss
	-	Stats Editor
	-	Equipment Editor
	-	Arte List Editor
		
-	New features: Eternia
	-	Ability to disable encounters
	-	Arte Usage Editor

#### 2021/08/20

-	New table: Rebirth
	-	Features:
		- Party Formation Editor
		- Stats Editor
		- In-Battle Stats Editor
		- Arte List Editor
		- Equipment Editor
		- Gem Editor
		- Encounter Editor
		- Difficulty Modifier
		- Gald Editor

-	New table: Eternia
	-	Features:
		- Party Formation Editor
		- Stats Editor
		- In-Battle Stats Editor
		- Equipment Editor
		- Arte List Editor
		- Gald Editor
		- Battle camera zoom Editor (useful for co-op)
		- Unlock Hardcore difficulty
		
-	New feature: Symphonia
	-	Advanced Encounter Modifier ported over from the GameCube version
	
-	Updated all PS2 tables to be more future-proof.
-	Cleanup of all tables

#### 2021/08/06

-	New feature: Vesperia
	-	Change Field Run Speed
	
-	Bug fix:
	-	Fixed an issue where sometimes the Chromatus Gauge Finder would fail in certain cases.

#### 2021/08/02

-	New table: Symphonia
	-	Features:
		- Party Formation Editor
		- Use different character's EX Skills
		
-	Bug fix:
	-	Fixed an issue where sometimes the Region Check would fail on Quick Loads in Xillia 1

##### 2021/07/15
-	New feature: Xillia 1
	-	You can now edit the Gaius/Muzét Final Boss encounter.
	
The Gaius and Muzét playable boss scripts have been mostly merged into 1 script.
-	Bug fixes:
	-	You can now use Gaius' upper strong attack.
	-	Fixed the Xillia 2 table still using old symbol names.

##### 2021/06/17

-	New features: Xillia 1
	-	Arte Editor
	-	Arte List is no longer based off of Xillia 2
	-	Backend changes

-	New features: Xillia 2
	-	Arte Editor
	-	Change Grade Shop options at any time
	-	You can now change the Event of the Chronos (Canaan) fight
	-	Backend changes

##### 2021/06/03

-	New features: Xillia 1
	-	WIP Jude to Gaius character modifier by Just_Samu.
	-	Updated Muzét character modifier with more features.
	
-	Minor typo fixes in the Xillia 1 and Xillia 2 tables.
-	Added missing Bonds of Shadow item in the Equipment Editor list.

##### 2021/05/22

-	The Xillia 1 and Xillia 2 tables are now mostly region free. (Notes may not work on other versions)
	Legacy versions will be stored in case something went/goes wrong.
	
-	New feature: Xillia 1
	-	WIP Milla to Muzét character modifier by Just_Samu
	
-	New feature: Xillia 2
	-	Arte Usage by Cultevel81

##### 2021/05/13

-	New feature: Xillia 2
	-	Expanded on Chronos (Canaan) Fight Editor: You can now change the background music and the stage of the fight.
	
-	New feature: Phantasia: Narikiri Dungeon X
	- You can now lock/unlock any and all costumes for Dio and Mell.

##### 2021/04/17

 - New features: Phantasia: Narikiri Dungeon X
	 - Expanded on Arte List and Control Modes
	 - Added Arena Editor
	 - Fixed Party Formation Loadouts labels
	 
##### 2021/04/08

- New table: Phantasia: Narikiri Dungeon X
	- Features:
		- Party Formation Editor
		- Stats Editor
		- Equipment Editor
		- Arte List Editor
		- Control Enemies
		- Control Monsters
		- Turn off Ally/Enemy AI
		
- New features: Xillia 2
	-  Expanded Chronos (Canaan) Fight Editor
		You can now add as many enemies as you'd like, and even change if they are allied to each other.

- New feature: Vesperia
	- Ported aanpsx's character pointer table to 1.2

- New features: Destiny DC
	- Expanded Stats section
	- Change what Stage you fight on
	- Arena Editor
	- Change the size of the party (including beyond 4)

##### 2021/03/02

- New table: Legendia 
   - Features: Party Formation Editor
  
 - New feature: Phantasia
	 - Automatic Control Enabler
		This is mainly a Quality of Life script for multiplayer environments. It lets you enable/disable Control Mode/Dash Mode and Combo Command Mode for each player. Death Cam makes the game automatically change a player's Control Mode to Auto if they die, and then reverts it back to whatever it was before death. Death Cam can be turned on/off on a per-player basis. May be unstable. Spaghetti code.
		
- Bug fixes:
	 - Xillia 1 and 2's Multiplayer Linking code wasn't working properly on the Newer CPUs version. Enemy linking now works as intended.