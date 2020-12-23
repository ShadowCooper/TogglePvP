# TogglePvP


This Datapack allows players to toggle pvp on and off using command blocks or commands.

 

All players who have pvp off will be protected, while all players who have pvp on can attack each other.

Note: A player who has pvp off can stop players who have pvp on from attacking each other, by going near them. I could not find a way to bypass this without making a mod.

Note: Projectiles other than arrows can still hit if a player that has pvp off, comment if you want a version that also nullifies other projectiles.

 

Pvp must be set to "true" in the server properties file.

Note: All players will have PVP on by default.

 

To turn pvp off for a player, use this command:

/execute at (player) run function togglepvp:joinpvpoff

 

To turn pvp on for a player, use this command:

/execute at (player) run function togglepvp:leavepvpoff

Note: You can turn off the flame particles by using this command (Use this every time the Datapack is (re)loaded to turn it off completely)

/schedule clear togglepvp:particle

You can create a redstone clock with a command block for this if you don't want to use the command every time the Datapack is (re)loaded.

 

I recommended having a setup like this:
https://imgur.com/a/y3hGmnj
 

How to Download:

1. Press the Download button in the top right to get the latest version of this Datapack.

2. Take the TogglePvP folder out of the .zip file.

3. Find the folder for your world, it should be in User/AppData/Roaming/.minecraft/saves/

4. Go into your world folder, and put the TogglePvP folder into the folder that says "datapacks".

5. Now, you're done!!!!

 

 

Please leave feedback in the comments :)

