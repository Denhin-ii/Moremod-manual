# TooManyEmotes

## There are never Too Many Emotes!
<strong>This mod adds a ton of new emotes to the game, which can be purchased in the store.</strong><br>
If you hate progression and just want to dance, you set all emotes to be unlocked in the config. All clients will sync to the server's settings.<br><br>
With this mod, you will be able to break dance over your teammates' corpses!<br>
Currently, there are There are currently over 200 emotes, and (likely) more on the way!<br>
These include common emotes, such as waving, taunting, crying, etc.<br>
Various dances are also included! You can see a preview of them in the gif down below!
<br>

### Now supports InputUtils

- Any relevant hotkeys for this mod can be managed in the in-game keybind menu.
- InputUtils is not a dependency, but is recommended!
<br>

## Over 200 Emotes!

- Though there are a lot of emotes, existing emotes will be continued to be polished in future updates when needed.<br>
- Emotes can be purchased in the terminal shop by typing "Emotes". You can read more about it below.
- (This count may actually be just under 200 as I had to remove some emotes to fix some animations at the time of typing this message)
<br>
### Here's a preview of some emotes!

![Emotes Preview](https://i.imgur.com/d21cmPX.gif)

## Emote Radial Menu

- Emote radial menu is included!
- By default, you can open the radial menu by pressing the backtick/tilde key. This can be changed in the config.
- Not shown in the gif below, but you can have multiple pages of emotes now! (1.3.5)

![Radial Menu](https://i.imgur.com/jf6z3NS.gif)

## Music and Props! (new in 2.0.0)

- Various emotes may include music and external props. (props are not in-game items... yet?)
- By default, music will only be played if a boombox is nearby, and if it's not already playing music from an emote.
- You can mute, or adjust the emote audio volume in the emote menu. More audio settings can be tweaked in the config.
- The boombox requirement can be disabled in the config.
- Select emotes with audio have exceptions to the boombox requirement, such as musical instruments, whistling, referee whistle, etc.
- Only the player who initiated an emote will play music from an audio source.
- Emote music volume increases with the number of players syncing with that emote. (slightly)
- Potential future idea: Make certain musical instrument props, such as the Saxophone, (or those from the Jug Band emote?) a scrap item that can be found on level 3 moons instead of being able to purchase the emote from the store.
<br><br>

## Jug Band

- The Jug Band emote has been added to the game! (Added in 2.0.0)
- Jug Band is a 4-in-1 emote, that when played, plays 1 of 4 instruments in the Jug Band song from Fortnite.
- These instruments are the Jug (duh), Banjo, Guitar, and Fiddle.
- You can press [E] on another player performing this emote, and you will sync with their emote, but with a different instrument!
- Get three of your friends to perform the Jug Band with you! (I dare you)
- For now, this is a complementary emote. This may change in the future.
- [Emote preview](https://youtu.be/tWsCQk6ODEk)
<br><br>

## Emote Store

- You can view the emote store in the terminal, either at the bottom of the "store" section, or by typing "emotes".
- Three emotes will be available at a time in the store, and rotate per-quota.
- The number of emotes in the rotation can be changed in the config.
- Each game, you will start off with 100 free emote credits.
- Type "Emotes" in the terminal to view all and future emote commands.
- Everyone will start off with a set of complementary emotes each game!
<br><br>

## Rarity System

- Emotes will be categorized into 4 tiers based on "rarity".
- This will affect the likelyhood of an emote for a given tier to appear in the emote store rotation.
- This will also affect their price.
- All emotes are color coded in the terminal!
- Colors are configurable in the accessibility section in the config.
- NOTE: This system can be ignored by setting the weights for each rarity tier to the same number in the config.
<br><br>

## Third Person Emotes

- To help prevent weird camera movements for certain emotes, and to help lower motion sickness, you will perform custom emotes in third-person.
- While emoting, you can freely move your camera without turning your character, or interrupting your emote.
- Upon moving, or canceling the emote, you will revert back to your normal view.
- While emoting, you can now rotate your character while holding the Alt key. This key can be changed in the config.
- You can now scroll to zoom in and out while emoting. The min and max distance is clamped at 1.5 and 5.
<br><br>

## Everyone is Synced

- When you buy an emote, everyone on the server unlocks the emote.
- When players join the server, already unlocked emotes will be synced with them.
- All unlocked emotes will be reset upon starting a new game, disconnecting, or will be synced with future servers you join.
- When performing a custom emote, all players will see the same emote.
<br><br>

## Everyone is not Synced! (optional)

- Sharing everything can be disabled in the config.
- If disabled, each player will have their own rotation of emotes in the store.
- Purchasing emotes will only unlock for you.
- Each player will have their own reserve of emotes credits. The amount of emote credits you earn will NOT be reduced.
- You will still be able to see other players' emotes, and even sync with them! (if you enabled syncing emotes that are not unlocked in the config)
- <strong>This feature may currently have bugs, as it changes the organization of unlocked emotes and emote credits, and how the game saves/loads unlocked emotes during the session.</strong><br> If you do run into any bugs, please post the issue(s) on the Lethal Company Modding Discord, or on the Github!
<br><br>

## Emote Loadouts

- Emote loadouts are included on the left side of the radial menu.
- Currently, there are two loadouts. "Favorites" and "All".
- Favoriting emotes will persist throughout multiple sessions, or upon closing/relaunching the game.<br>
Favorited emotes will only be available if they have been unlocked in your session.
<br><br>

## Sync Emotes with other Players

- When other players perform an emote that loops, there will be a prompt when looking at them to perform and sync with their emote.
- Syncing with another player's emote will perform the same emote, and match their time in the animation.
- After syncing with a player, you can then rotate your character to look elsewhere by holding the Alt key.<br>
(You can rotate your character regardless of if you synced with a player's emote or not)
<br><br>

## Masked Enemies Emoting

### &nbsp;&nbsp;&nbsp;<strong>Trust no one!</strong><br>
![Masked Enemy Emotes](https://i.imgur.com/FqmLJ64.gif)
<br>
- The [MaskedEnemyOverhaul]("https://thunderstore.io/c/lethal-company/p/HomelessGinger/MaskedEnemyOverhaul/") by HomelessGinger plays very nicely with this. You should check it out!
- Masked Enemies will now be able to perform any emote that the player they're looking at has unlocked.
- When Masked Enemies stop and stare at the player, they will have a chance to emote after a short delay for a few seconds.
- Masked Enemies will ALWAYS emote during each player's first encounter with a Masked Enemy. This will happen for each new level.
- The stop and stare duration has been increased by a bit to ensure that the emotes play at a reasonable duration, and do not end very quickly.<br>
If you do not want to increase the vanilla stop and stare time, or if this conflicts with other mods, you can disable overriding this duration in the config.
- You can sync emotes with Masked Enemies!
- All settings can be edited in the config.
- <strong>This feature is currently in beta, as I have no had the chance to extensively test this.</strong><br>
If you run into any bugs, please post this issue in the Lethal Company Modding Discord, or on the Github. Thank you!
<br><br>

## Saved Progression

- All emotes are unlocked for each saved game.
- When you close your game, or stop the server, all unlocked emotes during that session will be saved.
- This means, you will reload your previously unlocked emotes upon loading an existing save, provided that they were already unlocked.
- Unlocked emotes will still reset upon restarting, or starting a new game.
<br><br>

## Integrates well with Unmodded Clients

- Playing custom emotes will just look like the regular Dance1 for other clients without the mod.
- This mod is designed to let you unlock emotes (or have them all unlocked by default) if the host does not have the mod.<br>
This will allow all clients to use emotes regardless of the mods the host is running.
<br><br>

## Future Plans

- Adding more emotes! More emotes are already on the way!
- Continue polishing existing emotes that need love!
- Adding random emote sales. This will be similar to the random sales for items in the store.
<br><br>

## Mod Compatibility

- Supports InputUtils (soft dependency)
- Compatible with More_Emotes!
- Compatible with MirrorDecor!
- Compatible with MoreCompany Cosmetics! (maybe not for non-host clients)
- Third person camera mods may or may not play nice. Who knows?
<br><br>

## Special Thanks for Beta Testing!

- YandereKat<br>
- InfamousThunder<br>
- m0nst3r<br>
- UFTaco<br>
<br>