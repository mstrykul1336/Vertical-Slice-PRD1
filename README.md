# Vertical-Slice-PRD1
Vertical Slice PRD1 of Shadows Over Suburbia. 
Full Project Here: https://github.com/mstrykul1336/Shadows-Over-Suburbia-Prototype-
Play: https://mstrykul1336.github.io/Vertical-Slice-PRD1/****
10/14:

**What was done**
- Health system has been fixed so all players are correctly assigned health based on their roles.
- Added controls, how to play, and roles + abilities to title screen. These are all still works in progress for UI, but the function is there.
- Fixed time between winning and losing, added fancy screen to show what players won along with what side with a cute picture. It'll send you to the main screen after 10 seconds.
- 3 abilities are in the game: Mayor's basement, Heal, and Poison.
   - Mayor's basement: (only for mayor) take a player to the basement (currently a weird looking jail) and disable all their night functions. Keep them there for a night.
   - Heal (only for medic): select a player to heal for one heart
   - Poison (only for baker): select a player to poison, where they will lose 1/4 heart over 3 nights duration.
- Added in Old Man and made him always neutral. Added in win condition for if he is killed, he wins.
- Added in the ability to be able use items in inventory (potion to heal, shield to shield for a night, and knife to attack someone.) (these are still buggy and need testing)
- Added in new UI for half a heart, quarter heart, and three-quarters hearts. Added in new health counter to incorporate these.
- assassin role was changed for just detective
- new shop items have been added (shield and knife)
- fixed properly giving gold to players every day
- attack was replaced with abilities.
- added in the mayor's basement area to spawn to.

**To do**
- Get abilities added and working, with basic UI during the night phase. Each role should get a different ability and some abilities should change based on the alignment. 
- Fix attack, but since attack will be replaced with abilities, it's not a huge deal. 
- Fix time between winning and losing, adding in a UI screen or separate scene that plays a temporary UI to show what side and what players on that side won.
- Fill shop with more items (I think I want to have 3 total):
      -  Potion of Life: Restore one heart (max 2 per player, single use)
  -  Shield: Wear for a night to prevent an attack (max 1 per player, single use, only use at night)
    - Cthulhu's knife: Deal an extra half heart damage with an attack (max 1, single use, only use at night)

- Make it so you can actually use items in your inventory and lose the item after using it. 
-Need UI for half a heart and 1/4 of a heart because abilities add this in. 
- Change assassin role name to just detective (can be a bad detective) 
- Get neutral alignment in the game, just for if the old man is there. Also add in the win condition if the old man is killed or voted out, they win.
- Add options to the main menu to include: "Controls", "Roles + Abilities" and possibly sound control. 
- Additionally, I need to figure out why it randomly will set health wrong and sometimes set it right. Also including why sometimes it properly disconnects a player and sometimes it doesn't.

  
Backlog:

- For more variety, I want some of the roles to have special passives. Such as the medic is immune to bleeding or poison and the Clairvoyant is immune to dying at night (must be voted out).
- Eventually implement voice chat (photon has apparently a plugin for this). 
- Add in characters and assign them randomly to players. Give the buff that each character gives to players and make a temporary UI for what that looks like. (Later on, that white box will be the player's character icon). I am still debating this as it is might just be feature creep. For this one, I don't think I am going to worry about adding characters unless I have extra time. 
