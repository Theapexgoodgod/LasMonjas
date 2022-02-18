# Las Monjas
![LasMonjas_banner](./gitHubImages/LasMonjas_banner.png)

Las Monjas is a Spanish mod (translated and published on English) for Among Us made by fans for fans without being affiliated with Among Us or Innersloth Team, all rights reserved to them. This mod features the following:

  1. [40 roles](#roles)
  2. [11 modifiers](#modifiers)
  3. [1 custom map](#modifiers)
  4. [2 custom gamemodes](#gamemodes)
  5. [2 new colors](#settings)
  6. [Custom Music](#settings)
  7. [Custom Lobby](#settings)

-----------------------

[<p align="center"> <img src="./gitHubImages/LasMonjas_discord.png" width="640" height="320"> </p>](https://discord.gg/UPCSqnD4NU)

-----------------------

# Installation

  1. Download the latest [Release](https://github.com/KiraYamato94/LasMonjas/releases) of Las Monjas.
  2. Find where your Among Us game is installed (make sure to have a clean game installation)
  3. Extract the files on the game folder (where the Among Us.exe file is)
  4. Open Among Us.exe, the first time takes a bit to load, don't worry.

-----------------------

# Custom Servers
I recommend to play this mod only on custom servers (for example [Impostor](https://github.com/Impostor/Impostor), note that modded handshake is required to play the mod [Example Modded Handshake by js6pak](https://github.com/NuclearPowered/Reactor.Impostor)), if you own an Impostor server, make sure AntiCheat and BanIpFromGame are set to false in the config.json file. This mod has [Unify by Daemon](https://github.com/MoltenMods/Unify) implemented, which you can use to select the custom region to join a custom server by entering the IP or domain name and the port of the server.

-----------------------

# Settings
This mod adds a custom lobby which I won't spoil to you, it also adds two colors (Lavender and Turquoise) and three setting to the client option tab:
- **Hide Room Code:** More like streamer mode, activating this option will hide the room code and replace it with "Las Monjas"
- **Game Summary:** Activating this option will create a list containing which role and task progress had the players after the game ends.
- **Activate Music:** Music pack containing 7 songs from Kevin MacLeod (1 for Lobby, 3 for Tasks and 3 for Meeting depending of how many players are alive)

-----------------------

# Roles

Roles can be activated by putting them at 100% spawn rate (there's only 0% and 100%). Activated roles will be in the game by two possible ways, you can set the role assignment system in the lobby to be random or by list order. Setting to random will put the activated roles in a list which will be assigned randomly to the players. There's a total of four teams and there can be only be 1 Neutral and 1 Rebel per game.

| Impostors | Crewmates | Neutrals | Rebels | Modifiers |
|-----------|-------------|-----------------|----------------|---------------|
| [Mimic](#mimic) | [Captain](#captain) | [Joker](#joker) | [Renegade](#renegade) | [Lovers](#lovers) |
| [Painter](#painter) | [Mechanic](#mechanic) | [Role Thief](#rolethief) | [Bounty Hunter](#bountyhunter) | [Lighter](#lighter) |
| [Demon](#demon) | [Sheriff](#sheriff) | [Pyromaniac](#pyromaniac) | [Trapper](#trapper) | [Blind](#blind) |
| [Janitor](#janitor) | [Detective](#detective) | [Treasure Hunter](#treasurehunter) | [Yinyanger](#yinyanger) | [Flash](#flash) |
| [Ilusionist](#ilusionist) | [Forensic](#forensic) | [Devourer](#devourer) | [Challenger](#challenger) | [Big Chungus](#bigchungus) |
| [Manipulator](#manipulator) | [Time Traveler](#timetraveler) |  |  |  |
| [Bomberman](#bomberman) | [Squire](#squire) |  |  |  |
| [Chameleon](#chameleon) | [Cheater](#cheater) |  |  |  |
| [Gambler](#gambler)  | [Fortune Teller](#fortuneteller) |  |  |  |
| [Sorcerer](#sorcerer) | [Hacker](#hacker) |  |  |  |
|  | [Sleuth](#sleuth) |  | |  |
|  | [Fink](#fink) |  |  |  |
|  | [Kid](#kid) |  |  |  |
|  | [Welder](#welder) |  |  |  |
|  | [Spiritualist](#spiritualist) |  |  |  |
|  | [The Chosen One](#thechosenone) |  | |  |
|  |  [Vigilant](#vigilant) |  |  |  |
|  |  [Performer](#performer) |  | |  |
|  |  [Hunter](#hunter) |  | |  |
|  |  [Jinx](#jinx) |  | |  |

-----------------------

# Mimic
| Team and Options  | Description |
|----------|-------------|
| Impostors | Mimic the appearance of a player for a set amount of time |
| Cooldown | Ability Cooldown | 
| Duration | Time the Mimic mimics a player |

**Additional Ability Notes:**
- Player's name remains red for other Impostors.
- Detective's footprints color change accordingly from the start to the end of duration.
- It adapts to the size of the mimiced player.
- Admin table updates the new color for the Hacker.
- If he mimics the shielded player, the Mimic gains the shield indicator but not the shield itself accordingly to the configured option on the Squire role.
- Fortune Teller can still see the Mimic original name.

-----------------------

# Painter
| Team and Options  | Description |
|----------|-------------|
| Impostors | Hide everything the players have and paint them with a random game color for a set amount of time |
| Cooldown | Ability Cooldown | 
| Duration | Time the players are painted |

**Additional Ability Notes:**
- Detective's footprints color change accordingly from the start to the end of duration.
- Player's size sets to normal size.
- Admin table updates the new color for the Hacker.
- Shields still work but aren't visible.
- Fortune Teller can still see the player names.

-----------------------

# Demon
| Team and Options  | Description |
|----------|-------------|
| Impostors | Bite players to delay their deaths |
| Cooldown | Ability Cooldown | 
| Delay Time | Delay Time for Kill | 
| Can Kill near Nuns | Set this to true to allow the normal kill near a Nun |

**Additional Ability Notes:**
- If there's a Demon ingame, all players will have a Nun button to place one Nun per game on the map.
- The nun stays the whole game and nullifies the bite if the player stays near it.
- If the Demon kills near a Nun, the next kill will have an additional 20 seconds cooldown.
- A bitten player will die if someone reports a body or make a meeting if he's not near a Nun.
- Time Traveler and Squire shields block the bite even if the shields activated after being bitten.
- On the special game condition called 1vs1, it can kill even if the targed in near a Nun and the option disabled.

-----------------------

# Janitor
| Team and Options  | Description |
|----------|-------------|
| Impostors | Clean and move dead bodies |
| Cooldown | Ability Cooldown | 

**Additional Ability Notes:**
- Kill and Clean ability cooldown are shared to prevent killing and cleaning at the same time.
- The cleaner can still drag and drop a body right after killing.
- The drag and drop button always has 10 seconds cooldown.
- While dragging a body, the Cleaner will move slower and can't kill, clean or use vents.

-----------------------

# Ilusionist
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can make his own vent network and turn off the lights from anywhere |
| Hats Cooldown | Place Vent Ability Cooldown | 
| Lights Cooldown | Lights Ability Cooldown | 
| Blackout Duration | Ability Duration | 

**Additional Ability Notes:**
- Can place 3 Hats on the map to make his own vent network.
- The hats become visible for everyone right after placing the third one.
- The hats are an exclusive vent network for Ilusionist.
- After placing the third hat, he gains the Blackout ability to turn of the lights for a set amount of time.
- Blackout ability can't be fixed and warns the other impostor with a message saying there's a blackout.

-----------------------

# Manipulator
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can manipulate a player to kill his adjacent from anywhere |
| Cooldown | Ability Cooldown | 

**Additional Ability Notes:**
- Can kill himself or other impostor with his ability.
- Using his ability to kill will increase his next cooldown for additional 20 seconds.
- Kill and Manipulate ability cooldown are shared to prevent double killing.

-----------------------

# Bomberman
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can use a new sabotage, place bomb on the map |
| Cooldown | Ability Cooldown | 
| Duration | Bomb Duration | 

**Additional Ability Notes:**
- Can't place the bomb if he's too close to another player or a sabotage is happening.
- The bomb will be placed right below where the Bomberman is at that moment.
- Anyone can defuse the bomb by touching it except Bomberman.
- The Mechanic can use one of his repairs to defuse the bomb from anywhere.
- While the Bomb is active, custom music will play and a custom message with the time left for defusing it will display to the players.
- Bomb duration is fixed to 60 seconds for Skeld, MiraHQ, Dlesk and the custom map, 90 for Polus and 180 for Airship.
- An additional 5 seconds will be added to the bomb duration for every crewmate dead player.

-----------------------

# Chameleon
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can become invisible for other players |
| Cooldown | Ability Cooldown | 
| Duration | Ability Duration | 

**Additional Ability Notes:**
- While invisible, he can still be killed by roles who has kill button like the Sheriff.
- He'll see himself half transparent while invisible but the other won't see anything from you (hats, pets..)
- Detective will still see his footprints even if he's invisible.
- He can't use vents.

-----------------------

# Gambler
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can Shoot a player choosing their role during the meeting |
| Shoot Number | Time he can shoot per game | 
| Can use emergency button | His ability depends on calling meetings, define if he can or not use the button | 
| Can Shoot multiple times | He's able or not to shoot multiple times on the same meeting | 
| Ignore shields | If set to true, shoots will ignore the Squire shield | 

**Additional Ability Notes:**
- Only the roles present on the current game will appear to choose during the meeting.
- Impostor roles, Kid, Big Chungus and Lover can't be choosen.
- If he choose the wrong one, he'll die instead.
- If ignore shield is set to false and shoots the shielded player, the shield indicator will sound but he won't lose a shoot chance.

-----------------------

# Sorcerer
| Team and Options  | Description |
|----------|-------------|
| Impostors | Can cast Spells on a player |
| Cooldown | Ability Cooldown | 
| Addicional Cooldown per Spell | Addiciontal ability cooldown per spelled player | 
| Spell Duration | Time needed near the player to cast the spell | 
| Can use emergency button | His ability depends on calling meetings, define if he can or not use the button | 

**Additional Ability Notes:**
- Kill and Spell button have their cooldown shared to prevent spelling a player and killing right after to report a body
- Spelled player will have a purple pumpkin icon near their names during the meeting and will die after finishing it (the shielded player survives)
- Exiling the Sorcerer save the spelled players.
- He can't spell other impostors.
- If he gets killed after spelling players, the pumpkin icon will be displayed but the players won't die.

-----------------------

# Renegade
| Team and Options  | Description |
|----------|-------------|
| Rebel | Can recruit a minion and have to kill everyone to win |
| Cooldown | Kill Cooldown | 
| Recruit Minion Cooldown | Cooldown for recruit a minion | 
| Can use vents | Define if they can use or not vents | 
| Can recruit a Minion | Define if he can recruit a Minion to help him | 

**Additional Ability Notes:**
- Both can make tasks to disguise themselves but won't count for the tasks progress.
- Can recruit any player to be his Minion, but only one time per game.
- Recruiting a Minion will make the screen green exclusively for both and trigger a sound to indicate that the recruitment has been done.
- Renegade and Minion see their names green and can't kill between them.
- They have impostor vision but can't make sabotages.
- He can't be in the same game as Bounty Hunter, Trapper, Yinyanger and Challenger.
- If they can use vents and are inside them, Impostors will see the vents highlighted on green.
- Fink can reveal them if the Reveal Rebel option is set to true.

-----------------------

# BountyHunter
| Team and Options  | Description |
|----------|-------------|
| Rebel | Have to kill a specific player to win |
| Cooldown | Kill Cooldown | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- He can't use his kill button before using the find target one.
- His target is assigned randomly pressing the Find Target button and can't be the Kid, Big Chungus, Lovers or himself.
- Find Target button can be use whenever he wants, but if it assign a dead target the Bounty Hunter dies.
- If his target is exiled or killed, Bounty Hunter also dies.
- If his target gets revived, Bounty Hunter also revives.
- He can't be in the same game as Renegade, Trapper, Yinyanger and Challenger.

-----------------------

# Trapper
| Team and Options  | Description |
|----------|-------------|
| Rebel | Have to kill everyone with traps and mines |
| Cooldown | Ability Cooldown | 
| Mine Number | Number of mines placed at the same time | 
| Mine Duration | Separate duration for every placed mine | 
| Trap Number | Number of traps placed at the same time | 
| Trap Duration | Separate duration for every placed trap | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- Mines and Traps are only visible to him but become visible if other player collides with them.
- Mines and Traps can't be placed near other mines and traps or other players.
- Colliding with a mine will trigger a sound and stops the player for one second, the mine becomes visible and kills that player. Afterwards the mine dissapear.
- One mine can kill multiple players if they collide with it at the same time or during the second the mine appears.
- Mines only kill if the Trapper is alive.
- Traps don't kill players but colliding with it will trigger a sound and stops the player for 5 seconds.
- Shields block the mine kill and destroys it.
- He can't be in the same game as Renegade, Bounty Hunter, Yinyanger and Challenger.
- There's a special game condition called 1vs1, when the remaining alive players are the Impostor and the Trapper. On this condition he can't place any mines or traps, instead the normal Kill button will appear. The Impostor can't make sabotages on the 1vs1 condition so this will be the fasted click in the west.

-----------------------

# Yinyanger
| Team and Options  | Description |
|----------|-------------|
| Rebel | Have to kill everyone marking two players |
| Cooldown | Ability Cooldown | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- Can mark a player with the Yin and another one with the Yang, if they collide both die ignoring any shields they could have (can't mark the same player for both buttons)
- After marking one player, he can't make the other one if the already marked is too close to him.
- Both Yin and Yang button shared their cooldown.
- Can only mark 1 time per round and can mark again after a meeting.
- If a marked player disconnects, he recover the button use.
- If a marked player is shielded, he won't die even if the other one dies.
- He can't be in the same game as Renegade, Bounty Hunter, Trapper and Challenger.
- There's a special game condition called 1vs1, when the remaining alive players are the Impostor and the Yinyanger. On this condition he can't mark any player, instead the normal Kill button will appear. The Impostor can't make sabotages on the 1vs1 condition so this will be the fasted click in the west.

-----------------------

# Challenger
| Team and Options  | Description |
|----------|-------------|
| Rebel | Have to kill everyone challenging players to a rock-paper-scissors duel |
| Cooldown | Ability Cooldown | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- One a player is selected, the duel will happens after 10 seconds.
- The duel cancels if there's a sabotage, the challenger dies, the selected player dies or is shielded.
- If there's a Demon in game and a player is bitten, if that player isn't the challenger of the selected player, he will die before starting the duel.
- Performing the duel will teleport all the players to the duel arena, with custom music and divided by Challenger zone, selected player zona and spectators.
- Everyone will be grey color during the duel without anything distinctive.
- The duel have a 30 seconds duration, the loser will die, if there's a draw both survive and if nobody choose any attack option both will die.
- If one of the duelist selects and attack and the other doesn't select anything, automatically he will die and the other player wins the duel.
- Nobody can use his abilities, or make sabotages or report a body during the duel.
- After the duel, everyone gets teleported to the position where they were before the duel starts, the same goes with the corpses.
- He can't be in the same game as Renegade, Bounty Hunter, Trapper and Yinyanger.
- There's a special game condition called 1vs1, when the remaining alive players are the Impostor and the Challenger. On this condition he can't duel, instead the normal Kill button will appear. The Impostor can't make sabotages on the 1vs1 condition so this will be the fasted click in the west.

-----------------------

# Joker
| Team and Options  | Description |
|----------|-------------|
| Neutral | Have to get voted out to win |
| Can Sabotage | Define is he can or not sabotage | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- If he can sabotage, he can only do while being alive.
- He can't be in the same game as Role Thief, Pyromaniac, Treasure Hunter and Devourer.
- If Can Sabotage is enabled, Joker needs to open the map 1 time to activate the Sabotage button

-----------------------

# RoleThief
| Team and Options  | Description |
|----------|-------------|
| Neutral | Can steal the role of other players |
| Cooldown | Ability Cooldown | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- He doesn't have any win condition, think about his role like a hot potato, if you're the Role Thief when the game ends, you lose.
- If he tries to steal an Impostor or Rebel role, he'll die.
- He can't be in the same game as Joker, Pyromaniac, Treasure Hunter and Devourer.

-----------------------

# Pyromaniac
| Team and Options  | Description |
|----------|-------------|
| Neutral | Have to ignite everyone to win |
| Cooldown | Ability Cooldown | 
| Ignite Duration | Time needed to spray a player | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- He has to be near a player in order to spray them.
- Once he sprayed everyone he can press the Ignite button to trigger the win sound.
- Ignite duration for a player resets if the player moves far away.
- Dead players won't be needed to spray.
- He can't be in the same game as Joker, Role Thief, Treasure Hunter and Devourer.

-----------------------

# TreasureHunter
| Team and Options  | Description |
|----------|-------------|
| Neutral | Have to find treasures to win |
| Cooldown | Ability Cooldown | 
| Treasures to Win | Number of needed treasures to win | 
| Can use emergency button | His ability depends on calling meetings, define if he can or not use the button |  

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- He can spawn one treasure randomly on the map one time per meeting.
- Treasures stays the whole game and only dissapears when the Treasure Hunter touch them.
- Treasures are only visible for Treasunte hunter.
- He can't get treasures or spawn them if he's dead.
- He can't be in the same game as Joker, Role Thief, Pyromaniac and Devourer.

-----------------------

# Devourer
| Team and Options  | Description |
|----------|-------------|
| Neutral | Have to eat corpses to win |
| Cooldown | Ability Cooldown | 
| Devours to Win | Number of needed corpses to win | 

**Additional Ability Notes:**
- Can make tasks to disguise himself but won't count for the tasks progress.
- When a player dies, a sound will be played only for Devourer, indicating him there's a body somewhere.
- He can't devour if he's dead.
- He can't be in the same game as Joker, Role Thief, Pyromaniac and Treasure Hunter.

-----------------------

# Captain
| Team and Options  | Description |
|----------|-------------|
| Crewmate | His vote counts double |

**Additional Ability Notes:**
- There's a special game condition called 1vs1, when the remaining alive players are the Impostor or Rebel and the Captain. On this condition he gains the ability to make a emergency meeting from anywhere which fix any active sabotages, so he can exile the remaining player with his double vote. The Impostor can't make sabotages on the 1vs1 condition.
- There's another special game condition called 2vs2, when the remaining alive players are a crewmate + Captain vs Impostor and Rebel or Two Impostors or Two Rebels. On this condition he gains the ability to make a emergency meeting from anywhere which fix any active sabotages, so he can work with the other crewmate exile the remaining players with his double vote. The Impostor can make sabotages on the 2vs2 condition.

-----------------------

# Mechanic
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can fix sabotages from anywhere |
| Repairs Number | Number of sabotages he can repair |

**Additional Ability Notes:**
- He can fix Bomberman's Bomb, but he can't fix Ilusionist's Blackout.
- Remaining uses will be displayed above the repair button.

-----------------------

# Sheriff
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can try to kill other players |
| Cooldown | Kill Cooldown |
| Can Kill Neutrals | Define if he can or not kill neutral roles |

**Additional Ability Notes:**
- If he tries to kill another crewmate, he will die instead.
- If he tries to kill a shielded player, he won't die but will trigger the shield.
- He can kill Rebel roles.

-----------------------

# Detective
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can see player's footprints |
| Anonymous Footprints | This sets the footprints color to grey |
| Footprint Interval | How often the footprints appear |
| Footprint Duration | Time it takes the footprints to disappear |

**Additional Ability Notes:**
- He can only see footprints if he's alive.
- Footprints won't spawn near vents.


-----------------------

# Forensic
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can get clues about who is the Impostor by reporting bodies or asking their ghosts |
| Time to know the name | Time limit to report a body to obtain the killer's name |
| Time to know the color type | Time limit to report a body to obtain the killer's color type ||
| Time to know about the killer's appearance | Time limit to report a body to obtain if the killer has hat, outfit, pet or visor |
| Cooldown | Ability Cooldown |
| Question Duration | Time need to talk to a ghost |
| One question per Ghost | Limits the question to one per ghost |

**Additional Ability Notes:**
- If he reports the Bounty Hunter after failing his hunt, the suicided Lover, the Sheriff who tried to kill a crewmate or the Role Thief who tried to steal an Impostor or Rebel role, he will get a suicide report.
- The clues he can get reporting bodies are: Killer's name, killer's color type and something about the killer's appearance.
- Lighter color types are: pink, orange, yellow, white, cyan, lime, rose, coral, banana and lavender, detailed with a (L) on the report and meeting.
- Darker color types are: red, blue, green, black, purple, brown, maroon, grey, tan and turquoise, detailed with a (D) on the report and meeting.
- If he gets a clue about the killer's appearance, he can get the same clue again (for example the killer has a hat)
- The clues he can get asking ghosts are: Which role killed the ghost, Killer's color type and how many time he has been dead before reporting his body.
- The obtained information only appears in the Forensic chat during the meeting.

-----------------------

# TimeTraveler
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can rewind the time two times per game |
| Cooldown | Ability Cooldown |
| Shield Duration | Time shield duration time ||
| Rewind Time | Time the game goes back in time ||
| Revive player during Rewind | Define if going back in time revive players |

**Additional Ability Notes:**
- Rewind and Shield button shared their cooldown.
- Rewind button can be used only 1 time per game and only if there's no sabotages at the moment.
- Shield button can be used whenever the player wants until a successfull use of the shield.
- Trying to kill the Time Traveler while the shield is active will trigger the rewind time.
- He can't use Vitals on Polus and Airship.
- He doesn't hear the Performer's music.

-----------------------

# Squire
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can put a shield to protect a player |
| Show Shield Player to | Who sees the shield, Squire only, Squire + Shielded or All players |
| Murder attempt sound | Play a sound to alert the players someone tried to kill the shielded ||
| Can shield again after meeting | Remove the current shield so he can choose other player ||

**Additional Ability Notes:**
- The only way to break the shield is killing or exiling the Squire.
- Murder attemp sound will be hear by the shielded player, Squire, Sheriff, all Impostors and all Rebels.
- He can't shield himself.

-----------------------

# Cheater
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can switch the votes of two players |
| Can use emergency button | His ability depends on calling meetings, define if he can or not use the button |  
| Can swap himself | Prevents himself from being switched ||

**Additional Ability Notes:**
- If he switchs votes, and one of the switched player is exiled and turns out to be a crewmate, the Cheater will also be exiled.
- Rebels and Neutrals counts as Impostors, so the Cheater won't be exiled in this case.

-----------------------

# FortuneTeller
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can reveal which player is good or bad |
| Cooldown | Ability Cooldown |  
| Reveal Time | Time needed near the player to reveal it |  
| Reveal Number | Times he can reveal players |  
| Revealed Information | Reveals if the player is good or bad, or their role name |  
| Show Notification to | Select who recieves the notification, impostors, crewmates, all or nobody |  

**Additional Ability Notes:**
- Revealing a player will trigger a sound and the screen for that player and Fortune teller will turn blue based on the Show Notification option.
- If a player goes far away, the reveal time resets.
- Show Notificacion will turn the player name into blue if he's good and red if he's bad.
- Rebels and Neutrals roles counts as bad.

-----------------------

# Hacker
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can use admin and vitals from anywhere |
| Cooldown | Ability Cooldown |  
| Duration | Ability Duration |  
| Battery Uses | Times he can use his admin and vitals ability |  
| Tasks for recharge Batteries | Tasks to do for recharge 1 battery |  

**Additional Ability Notes:**
- His Hack button reveal the player's color on Admin table and how much time someone has been dead in Vitals.
- His Admin and Vitals buttons uses 1 battery but doesn't share battery uses.

-----------------------

# Sleuth
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can track one player position and corpses |
| Track Interval | How often the arrow updates its position |  
| Can Track again after meeting | Let's the Sleuth select a new player to track, removing the old one |  
| Track Corpses Cooldown | Ability Cooldown |  
| Track Corpses Duration | Ability Duration |  

**Additional Ability Notes:**
- Player's position arrow is blue.
- Corpses's arrows are green.
- The arrow is the same as the vanilla sabotages one.

-----------------------

# Fink
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can reveal who the Impostors are after finishing all his tasks |
| Tasks for being revealed to Impostors | When the Impostors will know who is the Fink |  
| Can Reveal Renegade and Minion | Define if Renegade and Minion are revealed too |  

**Additional Ability Notes:**
- Impostor's reveal arrow for Fink are red.
- Renegade and Minion arrows for Fink are green.
- Impostors and Renegade see the Fink with a maroon arrow.

-----------------------

# Kid
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Immortal crewmate, if he gets voted out or killed everyone lose |

**Additional Ability Notes:**
- He's smaller than the other players.

-----------------------

# Welder
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can seal vents |
| Cooldown | Ability Cooldown |
| Seal Number | How many vents can be sealed |

**Additional Ability Notes:**
- Vent seal happens after a meeting.
- He can't seal the same vent multiple times.
- A sealed vent can't be entered or exited, but can still be used as a tunnel.

-----------------------

# Spiritualist
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can revive another player at the cost of his own life |
| Revive Player Time | Time needed for reviving the player |

**Additional Ability Notes:**
- Ghosts know who the Spiritualist is by looking at the player's name, it will be pink.
- To revive someone, he has to stay near the corpse for the setted amount of time. This time resets if you move far away from the corpse.
- If he's trying to revive someone and a meeting or body report is called, he will fail the revive and die instead.
- If he manages to revive the player, Spiritualist's body will disappear and the revived player will be revealed to Impostors and Rebel with a pink arrow targeting him.
- Time Traveler is the only role who can revive the Spiritualist if he rewind the time right after the Spiritualist revives someone.
- The revived player spawms where his body was after a pink screen flash, if he was doing a tasks in ghost form it won't be canceled.
- Reviving a Lover will also revive the other Lover, the same goes with the Bounty Hunter and his target.

-----------------------

# TheChosenOne
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Uppon death will force his killer to report his body |
| Report Delay | Delayed report time after being killed |

**Additional Ability Notes:**
- Is the only role Spiritualist can't revive.
- Time Traveler can manage to revive him before the report delay fills in, this will cause that the next time the Chosen One dies it will be reported before the full delayed time since a few second already passed on his first death.

-----------------------

# Vigilant
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can place 4 additional cameras on the map |
| Cooldown | Ability Cooldown |
| Camera Number | Fixed to 4 |
| Remote Camera Duration | Can check cameras from anywhere during a set amount of time |
| Battery Uses | Times he can check the cameras |
| Tasks for recharge batteries | Tasks needed to recharge 1 battery |

**Additional Ability Notes:**
- A placed camera become avaliable for everyone after a meeting at last the whole game.
- Remote Camera ability become avaliable for Vigilant after placing the 4 cameras.
- A special Vigilant will take place on MiraHQ, since on that map there aren't any cameras. The Vigilant can use the Doorlog anytime he wants by changing the Use button with the Q key while being alive.

-----------------------

# Performer
| Team and Options  | Description |
|----------|-------------|
| Crewmate | His death triggers an alarm and an arrow reveals his corpse position |
| Duration | Ability Duration |

**Additional Ability Notes:**
- Time Traveler and Spiritualist don't hear the alarm, they also can't see the arrow pointing to his body.
- Music will stop after the setted amount of time if nobody found him or someone made a meeting, the Janitor cleans his body or the Devourer devoured his body.
- A special sprite will appear after killing the Performer so the killer will know he just messed up.


-----------------------

# Hunter
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can mark other player who will die if the Hunter gets killed |
| Can mark again after meeting | Lets him select a new target removing the old one |

**Additional Ability Notes:**
- The marked player won't be exiled if the Hunter gets voted out.
- A revived Hunter can mark again without calling a meeting.

-----------------------

# Jinx
| Team and Options  | Description |
|----------|-------------|
| Crewmate | Can block other player abilities |
| Cooldown | Ability Cooldown |
| Jinx Number | Times he can block abilities |

**Additional Ability Notes:**
- He can't block an already blocked player.
- If he gets killed, blocked abilities still remain blocked until the player tries to use it.
- Blocking an ability makes that player ability to enter cooldown triggering an humorous sound when he tries to use it.
- Works for Kill and custom abilities buttons.

-----------------------

# Modifiers

This mod also features some game mechanic modifiers, one of them being a custom map that I won't spoil to you, some of them aren't considered as a separate role, instead they're added as a player attribute which can be good or bad. To activate them, Modifiers spawn rate has to be 100%.

| Modifier Type  | Description |
|----------|-------------|
| Activate Mod Roles | Activate this option to play mod roles and deactivate it to play with vanilla ones |
| Role Assignment | Choose if mod roles are assigned randomly or by list order |
| Activate Custom Skeld Map | If enabled and Skeld is selected as the game map, the custom map will load instead the normal Skeld |
| Remove Swipe Card Task | I hate this task so I made an option to remove it |
| Remove Airship Doors | After reading what is written above this, you can guess why this option is here |
| Modifiers Number | How many role modifiers will be on the game |

### Lovers
  - Two player linked, can be Impostor + Crewmate or both Crewmates, they also die and gets exiled together.
### Lighter
  - Player with more vision than the others.
### Blind
  - Player with less vision than the others.
### Flash
  - Player faster than the others.
### BigChungus
  - Player bigger and slower than the others.
  
-----------------------

# GameModes

This mods adds two gamemodes, which can be played on everymap including the custom one. Mod roles won't spawn and map abilities (admin, sabotage, reports, emergency button...) can't be used on custom gamemodes.

## CaptureTheFlag

Match between red and blue team where each team has to steal the enemy flag and take it to their base while listening to custom music. Among us support 15 players, which is an odd number. On this gamemode blue team will always have an extra player if you're playing with an odd player number, in order to balance this, red team will win if the match results in draw when the blue team have one more player.

| Option  | Description |
|----------|-------------|
| Match Duration | From 3 to 5 minutes |
| Score Number | Points needed to win, from 3 to 5 |
| Kill Cooldown | Everyone can kill with the same cooldown |
| Revive Time | Everyone revives on his team base after a setted amount of time |

**Additional Gamemode Notes:**
- Each player name color will be the same as the team color.
- Everyone can use vents.
- You can't kill your teammates.
- The player who has the flag can't kill or use vents.
- Killing the player who has the flag makes the flag teleport back to his base.
- There are custom messages for match duration, stolen flag and scored point, also the game score is always displayed.
- Flags positions are marked by a team color corresponding arrow.
- If the player who has the flag disconnects from the match, the flag stays where that player was.

-----------------------

## PoliceAndThiefs

Match between cyan (Police) and brown (Thiefs) team. This gamemode adds a new map room, the Prison. Police team have to capture all the Thiefs by sending them to Prison, while Thief team have to steal all the jewels on the map without being captured. The player assignment is 2 Thief per 1 Police, being the max 10 Thiefs and 5 Polices.

| Option  | Description |
|----------|-------------|
| Match Duration | From 5 to 7 and half minutes |
| Jewel Number | Jewels needed for Thief team to win, from 10 to 15 |
| Kill Cooldown | Everyone can kill, Thief team cooldown is multiplied by 1.5 |
| Arrest Cooldown | Police ability to arrest a Thief |
| Arrest Duration | Police needed time near a Thief to arrest it |
| Revive Time | Everyone revives on his team base, Thief revive time is multiplied by 1.5 |

**Additional Gamemode Notes:**
- Police team always win on match time out and capturing all the Thiefs.
- Thief team only win if they manager to steal all the Jewels.
- Each player name color will be the same as the team color.
- Capturing a Thief teleports him to the Prison, another Thief have to push the button outside the prison to release it.
- Releasing a Thief only release the one who's been more time in Prison, that Thief gets teleported to the Thief spawm base.
- Everyone can kill, but the Thiefs can also use vents.
- You can't kill (or arrest if you're Police) your teammates.
- After taking a Jewel, the Thief can't put it back, he has to deliver it and can only take 1 Jewel per time.
- While taking a Jewel, the Thief can't kill or use vents.
- Killing or capturing a Thief who has a Jewel makes the Jewel teleports back to its original position.
- There are custom messages for match duration, delivered jewel, captured Thief and released Thief, also the game score is always displayed.
- If a Thief who has a Jewel disconnects from the match, the Jewel stays where that player was.
- Also if a Thief disconnects, the required captured Thief updates too.

-----------------------

# Credits and Code snips
[Reactor](https://github.com/NuclearPowered/Reactor) - The main framework used\
[BepInEx](https://github.com/BepInEx) - Used to hook game functions\
[KevinMacLeod](https://www.youtube.com/user/kmmusic) - For the music used\
[Enterbrain Inc.](https://www.rpgmakerweb.com/) - For some of the sound effects used\
[Essentials](https://github.com/Eisbison/TheOtherRoles) - Custom game options by TheOtherRoles team

[tomozbot](https://github.com/tomozbot) - Original idea for the Mayor (Captain) and Lighter\
[NotHunter101](https://github.com/NotHunter101) - Original idea for the Medic (Squire and Forensic) and Engineer (Mechanic)\
[Woodi-dev](https://github.com/Woodi-dev) - Original idea for the Sheriff, Lovers mod and the Jailer mod reference\
[Hardel-DW](https://github.com/Hardel-DW) - Original idea came for the Investigator (Detective) and Time Master (Time Traveler)\
[TheOtherRoles](https://github.com/Eisbison/TheOtherRoles) - Original idea for Medium (Forensic), Time Master (Time Traveler), Seer (Fortune Teller), Hacker, Tracker (Sleuth), Mini (Kid), Security Guard (Welder and Vigilant), Bait (The Chosen One), Pursuer (Jinx),  Vampire (Demon), Trickster (Ilusionist), Warlock (Manipulator), Guesser (Gambler) and Witch (Sorcerer)\
[Town-Of-Us](https://github.com/eDonnes124/Town-Of-Us-R) - Original idea for Swapper (Cheater), Altruist (Spiritualist), Flash, Giant (Big Chungus), Shifter (Role Thief), Arsonist (Pyromaniac) and Undertaker (Janitor)\
[ottomated_](https://twitter.com/ottomated_) - Original idea for Morphling (Mimic), Camouflager (Painter) and Snitch (Fink)\
[Wunax](https://github.com/Wunax/Among-Us-Chameleon-Mod) - Original idea for Chameleon\
[dhalucard](https://www.twitch.tv/dhalucard) - Original idea for Jackal and Sidekick (Renegade and Minion)\
[Lunastellia](https://github.com/Lunastellia/Challenger-Among-Us) - Original idea for Hunter\
[Maartii](https://github.com/Maartii) - Original idea for Jester (Joker)\
[Cheep](https://cheep-yt.com/home.php) - Original idea for Capture the Flag mod\
[Allul](https://github.com/KiraYamato94/LasMonjas) - Coded the gamemodes, custom map, Bomberman, Bounty Hunter, Trapper, Yinyanger, Challenger, Treasure Hunter, Devourer, Performer and Blind and some more that weren't original ideas

-----------------------

# Known Bugs
- On the custom map, you can see player names and do some tasks across the walls (this is a vanilla game bug)
