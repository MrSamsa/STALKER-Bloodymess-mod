10/22/2008

Bloody mess mod v1.0 (made for S.T.A.L.K.E.R. Clear Sky v1.504) by Detroit_Vigilanty

This mod takes What I consider the best of an old blood mod for SoC (Shadow of Chernobyl) Called HUD & Blood MOD v1.2 and Hades Real Gore Mod for CS v1.5.04.  

I have only combined the two together because I liked the old blood effects I have for SoC and the new ones from Hades mod(Which unfortunatly was uploaded completely broken and was unplayable due to a missing Bloody_marks value)

Most of the credit is theirs.


-What this mod does-

This mod will make it so blood splatter will appear more often and more realistic. Also the blood splatter has longer range and works properly at short distance. Blood coming out of gunshot hits is better looking also.

In Vanilla when you shoot a person and they are in certain positions or too close to the ground (like a dead guy) no blood splatter will appear behind the gunshot wound. Shooting bodies under you will now produce a blood splatter under them and in the other tricky spots around edges such as a truck door or tire.

The pfx textures and wm blooddrops are from Hades Real Gore mod 1.504 CS
The wm textures are pseudoant's from HUD & Blood MOD v1.2 SoC

The settings for blood splatters and distances in the system.ltx are the work of pseudoant.



-INSTALLATION-

You dont need to start a new game for this mod.

If you havent done so already, you must change the fsgame.ltx file in \Program Files\Deep Silver\S.T.A.L.K.E.R. - Clear 	Sky\ folder so that the line with the gamedata value reads like this-

$game_data$             = true|  true|  $fs_root$| --------right :)

$game_data$             = false|  true|  $fs_root$| -------wrong :(



A. Install this way if you dont need to worry about compatability with other mods 

-Copy all files from "gamedata" into..\Program Files\Deep Silver\S.T.A.L.K.E.R. - Clear Sky\gamedata


B. Install this way if you are using some other mod and dont want to overwrite the system.ltx file or any of the pfx and wm textures.

-Open your system.ltx file in the STALKER\gamedata\configs folder and edit the line that says [Bloody_Marks] and copy it to this - (this might look messy if your using notepad but its ok) 

[bloody_marks]
wallmarks			= wm\wm_blood_1,wm\wm_blood_2,wm\wm_blood_3
dist				= 7.0  ;2.0 ;2.4	;(м) max рассто€ние отлета крови
max_size			= 0.42 ;0.4 ;0.3	;(м)радиус п€тна при хите силой nominal hit по большому объекту (по маленькому *0.5)
min_size			= 0.18 ;0.15 ;0.06			;(м)минимальный радиус п€тна
nominal_hit			= 0.35 ;0.38 ;0.4 ;0.5			;величина номинального хита, при котором разлетаетс€ максимум крови (max_size)

(remember if you are using extra blood textures you need to add them in under the wallmarks value)

-Take the textures from the \gamedata\textures folder that you want in your game.




Thats all.

Do what you will with this mod but if you change it and/or release it somewhere else you had better show credit to pseudoant, Hades and Me.

Im very solitary so dont contact me unless its important.

Detroit_Vigilanty
Opiurn@yahoo.com





