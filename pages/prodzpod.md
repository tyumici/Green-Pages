# [🌙] prodzpod

<br><br><br><br><br><br><br><br><br>
   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠.   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠.  
  󠀠 ..· 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠.  󠀠  󠀠  󠀠  󠀠  󠀠.  󠀠  󠀠.  󠀠.  󠀠  󠀠'  󠀠  󠀠  󠀠  󠀠 ·: 󠀠  󠀠..  󠀠  󠀠  󠀠.  󠀠  󠀠.  󠀠  󠀠.  
*You feel like you just entered something you'll never return from...*  
  󠀠  󠀠'  󠀠  󠀠  󠀠'  󠀠  󠀠·  󠀠"'  󠀠  󠀠  󠀠'  󠀠  󠀠  󠀠'  󠀠  󠀠  󠀠  󠀠  󠀠 ·. 󠀠  󠀠  󠀠·  󠀠  󠀠'  󠀠'  󠀠  󠀠  󠀠  󠀠'  
   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠'    󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠'   󠀠   󠀠   󠀠   󠀠   󠀠'  

<sup>prodzpod Season 1.5, revision 260205</sup>  
\> [Descend into the darkness](#floor--1)  
\> <s>Toggle Visual Mode</s> **Work in Progress**  
\> <a href="https://prod.kr/audio/20240128-w2.ogg" target="blank_">Toggle Sound</a> (*manual loop via "right-click" required)  
\> [Abscond](../README.md)  
<br><br><br><br><br><br><br><br><br>


## Floor -1
   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠.   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠    󠀠   󠀠   󠀠.  
  󠀠 ..· 󠀠  󠀠  󠀠 󠀠  󠀠  󠀠.  󠀠  󠀠  󠀠  󠀠  󠀠.  󠀠  󠀠.  󠀠 󠀠  󠀠  󠀠 ·: 󠀠 󠀠  󠀠  󠀠.  󠀠  󠀠.  󠀠  󠀠.  
*You have just entered the [caverns of a shifting beast](https://twitch.tv/prodzpod).*  
*The walls are damp and cold to the touch.*  
  󠀠  󠀠'  󠀠  󠀠  󠀠  󠀠  󠀠'  󠀠  󠀠  󠀠  󠀠  󠀠 ·. 󠀠  󠀠  󠀠·  󠀠  󠀠'  󠀠 󠀠  󠀠'  
   󠀠   󠀠   󠀠  󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠'   󠀠   󠀠   󠀠   󠀠   󠀠'  
<br>
&nbsp;&nbsp;Congratulations for discovering *the pod*. This is an online project lead by prod with the goal of pushing the boundaries of livestreaming through interactivity.

&nbsp;&nbsp;Currently, there are a number of "main gimzos" that are operational on the channel. Here are some you can play with right away.

- **What You See is What I See**: prod's gizmo is a custom [Raylib](https://www.raylib.com/)/C# guy that is directly on top of the primary monitor. Anything you summon will be seen by prod and you can very easily block their vision.
- **Everyone is VIP**: Do not fear! *the pod* runs a custom script to make 50 most recent chatters VIP to bypass **duplicate chat cooldown** restriction. This helps other bots (such as ones featured in this repo) thrive on prod's chatroom without fear of getting rate limited randomly.
- **[GreenHeat](https://heat.prod.kr/) Integration**: You can (on PC) click on the screen or (on mobile) tap the green flame icon on top of the chat window to open a panel, then tap anywhere in the panel to create a cursor within the broadcast. this cursor will grab and move around every element of the overlay, from windows, chat messages, even prod themselves.
- `Joel`: When you type "Joel" (**case sensitive**, no other characters), instead of a normal chat a window with a fish ("Joel" 7TV emote) will appear. this window can be moved around at will.
- `!guy`: Summons a "guy": a "guy" is an avatar that roams the screen on your behalf. 
  - you may `!fight` another player (name **without** @) in which you will enter a duel. once you are victorious, you can `!levelup` to increase a random stat of your guy until it perishes. Once your guy perish, your guy will respawn with all combat stats reset. If you have equal or more than your opponent's HP percentage, you can `!peace` a player to cancel the fight.
  - you can customize your "guy" by creating a spritesheet and sending the image to prod. The format is a 3x2 rectangle of any size, with top 3 frames for walking, 1 for falling, 1 for attacking and 1 for getting attacked. See [the default guy sprite](https://prod.kr/data/shimeji/default.3x2.png) for example. This sprite is free to be modified if desired.
  - Every BRB screen (often once per stream), a **Raid Boss** spawns and draws aggro of every spawned "guy"s. Raid boss will have boosted health and damage, and often one-shots un-upgraded "guy"s. After the raid boss is defeated, a big brawl will break out where one chatter will come out on top with a lot of stat points to spend on level-ups. If you somehow aren't fighting the boss, you can `!fight prodzpod` to engage it.
- `!gravity`: Apply gravity to every window and elements on screen. you can also specify a direction (`!gravity up`, `!gravity left`, `!gravity right`).
- **The [Discord Server](https://prod.kr/discord)** and `!irc`: *the pod* offers a custom tube between twitch, discord and irc so that users can chat from any of these places and messages are relayed to everywhere else. In the chat overlay, both discord and twitch emotes are supported. In addition, prod has a `!post` gizmo that links various social media, which powers stream announcements going to [Bluesky](https://bsky.app/profile/prodzpod.bsky.social) and Discord simultaneously.
- Most commands can be used outside of *the pod*, including twitch chats of [LCOLONQ](https://twitch.tv/lcolonq), [BrighterMalphon](https://twitch.tv/brightermalphon), [Lala Amanita](https://twitch.tv/lala_amanita), [SaladForrest](https://twitch.tv/saladforrest), [Tyumici](https://twitch.tv/tyumici) and [KinskyUnplugged](https://twitch.tv/kinskyunplugged).

<br>

*As you travel deeper along the rocky corridor, you start to lose sense of distance. The path ahead gets darker as the light behind you fades into a single point.*

*After a bit of walking, you come across a slope that leads to an opening. the opening is vast and hazy. However, you also notice a strange green glow coming from the opening in the walls. The opening is big enough that you can barely fit through.*

\> [Investigate the glow](#annex-mushroom-crag)  
\> [Proceed downwards](#floor--2)  

## Annex: Mushroom Crag

 󠀠   󠀠   󠀠   󠀠  . 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  . 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  .. 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  . 󠀠   󠀠   󠀠   󠀠.  
 󠀠   󠀠   󠀠   󠀠  .   󠀠   󠀠  ... 󠀠   󠀠   󠀠   󠀠  '. 󠀠   󠀠   󠀠   󠀠  .: 󠀠   󠀠  ' 󠀠   󠀠  . 󠀠   󠀠   󠀠   󠀠  . 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  .  
*Beyond the opening is a room where patch of mushrooms grow.*  
*The mushrooms glow in an unnaturally bright green.*  
 󠀠   󠀠   󠀠   󠀠  ' 󠀠   󠀠   󠀠   󠀠  ''. 󠀠   󠀠   󠀠   󠀠  :' 󠀠   󠀠   󠀠   󠀠  ' 󠀠   󠀠   󠀠   󠀠  ' 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  '  
 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  ' 󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠   󠀠  '  
<br>
&nbsp;&nbsp;**Chungus Game** is a stream engagement farming and cooking simulator anyone can participate. This gizmo was created and interacts with the starting soon/BRB screen for [a different twitch channel](https://twitch.tv/lala_amanita) (my wife), and has no direct relation to *the pod*. Every command can be accessed with `!chungus`. The water status is shown as both text and as images depicting stages of growth, and redeeming model toggles while the screen is active will toggle that element in the drawn version of lala in the screen as well.

- `!chungus water`: Waters the plant. A plant is shared between everybody, and has a threshold of water commands before everyone who participated **for that cycle** obtains the harvest. Each account has one opportunity to water, and it refreshes every time **lala** (not prod) goes live.
- `!chungus inventory`: After you receive the harvest from watering, it will be added to your inventory. You can also see other people's inventory with `!chungus inventory [username]`.
- **[Chungus Dashboard](https://prod.kr/lala/chungus)**: You can check and interact with your inventory here. You can cook ingredients into random food, and then select up to 3 of them to be your "menu". The ingredient you use, the type of food you make, and the quality (denoted by stars) determine the stats (🍏**sweet**/🍋**sour**/🌶️**spicy**) of each food, and the sum of selected foods' stats will be reflected on your profile. You can also sell foods for **lala money**(ణ, currently no use yet), and give money or item to other users here.
- `!chungus leaderboard [sweet/sour/spicy/money]`: Check the leaderboard for most sweetness/sourness/spiciness in an individual profile. You can also check the leaderboard for most cash from sold foods.

&nbsp;&nbsp;In addition to Chungus Game, you can also do `!jdraw` in lala's twitch chat, and have an image of a random "Joel" emote from [The Archive](#floor--4) show up. This is in reference to the command of the same name in [Venorrak](./venorrak.md)'s bot, which is in itself also a reference of `!draw` from [nichepenguin](./nichepenguin.md)'s bot.

<br>

*You decide to take one of the mushrooms. Your lamp was running out of oil after all. The ground shakes a bit, but you manage to step carefully and exit.*

\> [Proceed downwards](#floor--2)  

## Floor -2

 󠀠   󠀠   󠀠   󠀠  .   󠀠. 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠.  .  
 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠.. '. 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠.' 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠  '  
*The cave opens into a large, mostly flat area.*  
*Your breaths gets a little heavy as you walk along the walls.*  
 󠀠   󠀠   󠀠   󠀠'. 󠀠   󠀠   󠀠   󠀠. 󠀠   󠀠   󠀠   󠀠'' 󠀠   󠀠   󠀠   󠀠" 󠀠   󠀠   󠀠   󠀠'" 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠'. 󠀠   󠀠  .  
 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠' 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠 󠀠   󠀠   󠀠   󠀠'  
<br>
&nbsp;&nbsp;**[The Screen](https://prod.kr/v/screen)** is an alternative way of interacting with *the pod*, where much finer control over the redeems are given to you. When you join the screen for the first time, you are asked to log in by typing a specific command in prod's twitch chat. This connects your browser with your twitch account for the screen, and allows to redeem on your behalf. After logging in, the bottom window should become a chat input where you can chat as if you are in twitch chat. Click the **bottom right** icon to access the action menu.
### Cursor Operation
- **Point**: you can point at the screen, affects nothing physically.
- **Click**: you can click on the screen. If you click an element (such as a window), it will rotate upright.
- **Fling**: first select the element, and then press the direction to aim to throw the object towards that direction. When there are multiple objects at that location, all of them are flung with some spread.
- **Pin**: make that element immune to moving via GreenHeat integrations or `!gravity`. You can unpin elements by flinging.
- **Kill**: Removes any objects in that position. Cannot remove some elements such as prod themselves. This action also deals damage to raid bosses, but is not counted towards your guy's kill credit.
### Window Operation
- **Spawn Window**: Create a custom window with title and contents. Contents can contain emotes and [text tags](#floor--4). There are also dropdowns for different layouts of the window, where it can have an "OK" button, or be a yes/no dialogue. Windows can also be kicked by guys, and can be used as a **ranged attack** when in `!fight`s. Guys have a chance to destroy most types of windows on every kick.
- **Furrow the Mare of Eidola**: Spawns a window with your profile picture on it. Can also be triggered outside of The Screen via `!furrowthemareofeidola` command.
- **Spawn Draw Window**: Summons a rectangular window of desired size where everyone can draw. Your drawings will be in your twitch color, and you can draw with either the **Draw** action in The Screen (a sort of line tool) or via GreenHeat integration.
- **Song**: \> [Cast Scroll of Displacement on Yourself.](#floor--5)
### Model Operation
- **Remove Triangle**: Removes a random polygon from prod's 3D model. When all polygons are removed, prod explodes and regenerates all polygons after some time. Can also be called outside of The Screen via `!removetriangle [number]`.
- **Change Palette**: Changes a certain part of prod into a different color. Can also be called outside of The Screen via `!palette [from] [to]` and `!palette reset`. Arguments are hex codes in format `#RRGGBB`, but `[from]` can also be `Black`, `White`, `Blush`, `Hair`, `Skin`, `Mouth`, `Ribbon`, `Ribbon`, `Clothes`, `Arms`, `Socks` or `Transparent`.
- **Change Accessory**: Toggles various accessories for prod's model. Can also be called outside of The Screen via `!accessory [accessory]`. Calling `!accessory` without any argument will print a list of accessories.
- `!randomize`: Randomly changes prod's color and active accessories.
- **Change Camera**: Changes the "camera" that projects prod. Rapid changes of camera can make the overlay unstable!
### Guy Operation
- **Jump**: forces a jump if your guy is summoned. Can also be called by `!jump`.
- **Spawn Fan**/**Anti-Fan**: creates an element that imparts momentum to unpinned objects such as guys or windows. Fans blow away objects, Anti-Fans suck in objects. Requires two clicks to summon, one for the position, another for the direction.
### Information Actions
- **Help**: Displays information.
- **Today**: Displays today's agenda. Can also be called with `!today`.
- **Uptime**: Displays how long the stream has been active for. If the stream is not active, shows when the next stream will be. Can also be called with `!uptime`.

&nbsp;&nbsp;`!volume [number]` can be used to change the overall volume of the overlay. You can also change the volume for a specific category by using `!volume [category] [number]`. You can use `!volume` with no arguments to get a list of audio categories.

&nbsp;&nbsp;Overlay's broken? Do not worry! We welcome and [encourage](#floor--3) this behavior. We take backups of the overlay state every minute, and it will be loaded back within seconds.

<br>

*You come across a forest of crystalline structures. Cold air pours out of the countless sharp edges that points towards the thicket of green and teal. You feel a bit nauseous.*

\> [Head inside](#annex-emerald-node)  
\> [Retrace the steps](#floor--1)  

## Annex: Emerald Node

 󠀠    󠀠   / 󠀠   \ 󠀠  󠀠 /| 󠀠    󠀠   \\\\. 󠀠   . 󠀠    󠀠    /\ 󠀠    󠀠    󠀠   |/ 󠀠    󠀠    󠀠   \\\\ 󠀠    󠀠   /. 󠀠    󠀠    󠀠   . 󠀠    󠀠    󠀠   .  
 󠀠   // 󠀠 .  \ 󠀠   |/ 󠀠    󠀠   / 󠀠      / 󠀠   \ 󠀠  |\ 󠀠    󠀠    󠀠   / 󠀠    󠀠    󠀠..,    󠀠    󠀠   /\ 󠀠    󠀠 .   󠀠    󠀠   || 󠀠    󠀠    󠀠   /..  
*The smaragdine pillars distort your reflection into million pieces.*  
*You lose yourself in the vastness of it all for a moment.*  
 󠀠   \\ 󠀠    󠀠   ./ 󠀠    󠀠 '"   󠀠   /\ 󠀠    󠀠  ''  󠀠    󠀠   |\ 󠀠  " 󠀠    󠀠    󠀠   / 󠀠    󠀠   /|\\\\\\\\\ 󠀠    󠀠    󠀠  
 󠀠    󠀠   \\/ 󠀠    󠀠    󠀠   󠀠    󠀠     󠀠   \\/ 󠀠    󠀠    󠀠   ./ 󠀠    󠀠    󠀠   . 󠀠    󠀠   \ 󠀠    󠀠   \\|////////////// 󠀠    󠀠    
<br>
&nbsp;&nbsp;<sup><s>**[The GreenCircle](https://greencircle.live)** is an integrated platform for strategic research and development. At "greencircle" we search for a disruptive business model that repeatedly and scalably achieves product-market fit. We're tastemakers, embracing creative play-at-work in order to avoid stagnation. "greencircle" enables lateral movement out of the traditional linear system and into nonlinear futures.</s></sup>  
&nbsp;&nbsp;**[The GreenCircle](https://www.twitch.tv/team/green)** is a loose connection of streamers connected to [LCOLONQ](https://www.twitch.tv/lcolonq) (henceforth "Man", "Male" or "Progenitor 1 / Dark Progenitor" for [rea](#annex-firefly-lake)[sons](#annex-emerald-heart)) that mostly consists of programming/creativity oriented VTubers. The name originates from the "mrgreen" emote, which is a random somethingawful forum emote that originates from [this emote pack](https://p.yusukekamiyamane.com/). Many of prod's content and mannerisms are derivative of [The Man's "OVA" era streams](https://www.youtube.com/watch?v=K7tCw6jbOgg), with one of the running jokes during *the pod Season 1: Hypertext Bestiary* being "i am the [SICP JavaScript](https://terrence-ou.github.io/SICP-Website/) of [LCOLONQ](https://www.gnu.org/software/emacs/)".

&nbsp;&nbsp;**GreenFeed** is a system that is currently running in prod's Discord as well as the irc zones, where whenever a GreenCircle member goes live you are alerted with an opt-in role. The role can be obtained by reacting plug emoji ("🔌") to [this message](https://discord.com/channels/1219954701726912583/1219956526794543194/1270499013820547122).

&nbsp;&nbsp;**TealCircle** is a recommendation list created by prod months after the launch of GreenCircle that works very **differently** to its inspiration by design. It is a VTuber recommendation list that is curated by prod that covers creative talents not inducted into the "twitch team" nature of GreenCircle. By definition, it is a superset of GreenCircle. TealCircle members are also featured in the ["prodzpod suggests these streamers" list](https://www.twitch.tv/prodzpod) in prod's twitch profile.
- **[The Hollow Decks](https://prod.kr/v/dex)** predates TealCircle but now features everyone in Teal and also the **Turquoise Circle** (an expanded version of TealCircle containing even more members, more volatile than Teal). It shows every member that are live, can be filtered by different circles, and functions as a multistream client with custom layout, resize and chat support. You can also put arbitrary links in the multistream view if CORS from prod.kr is supported.
- **[Teal Orb](https://prod.kr/v/teal)** is a raid recommendation tool that summons a random TealCircle member currently live. Filtering options are available.
- **TealFeed** works similarly to GreenFeed, except it does not link to IRC and does not have a special role. This feature is more for prod to keep up with members than for public service, and users are expected to use the Discord notification settings set to "All Messages" to receive TealCircle live notifications.
- **Green Pages**, the repository you are seeing now, are also in effort to help bridge the various creative endeavors and collaborations and create a unified document for the TealCircle.
- **Remote Command Usage**: Similar to logging into `!screen`, you can connect your Discord account with your Twitch account using `/login` within prod's discord.
- `!irclogin`: You can also connect your IRC presence to twitch by using this command.

<br>

*Having to walk slouched awkwardly has taken a big toll on your back. It could not have been more welcome to see the rocks clear up around you.*

*Water taps your feet as you begin wading in it. Beyond the mound lies a pocket of water that goes up to your knees. The color of the walls have changed to a darker, blue hue. You feel like you've gone quite deep.*

\> [Proceed downwards](#floor--3)  

## Floor -3
\> <a href="https://prod.kr/audio/20181004-BCRunused2.ogg" target="blank_">Change Sound</a> (*manual loop via "right-click" required) 

 󠀠    󠀠    󠀠    󠀠    󠀠   _ 󠀠    󠀠    󠀠    󠀠    󠀠   _ 󠀠    󠀠    󠀠   - 󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   --_ 󠀠    󠀠   _  
 󠀠   -- 󠀠   \_\_- 󠀠    󠀠   -\_\_\_ 󠀠    󠀠   \_- 󠀠    󠀠   \_\_-\_ 󠀠   ..\_\_ 󠀠   =\_- 󠀠   . 󠀠    󠀠   -- 󠀠    󠀠   \_ 󠀠    󠀠   \_ 󠀠    󠀠   \_\_ 󠀠    󠀠   =  
*A family of algae tangles itself around your legs and stops your movement.*  
*You try to force it apart, but the grip is strong.*  
 󠀠   --\_ 󠀠    󠀠   \_---\_\_ 󠀠    󠀠   \_\_- 󠀠   \_\_ 󠀠    󠀠    󠀠    󠀠   -- 󠀠    󠀠   \_=-- 󠀠    
 󠀠    󠀠    󠀠    󠀠   - 󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   - 󠀠    󠀠    󠀠   -  
<br>
&nbsp;&nbsp;**IU** is the "main currency" / "channel points" of *the pod*, that are required when performing certain actions. On the screen, if an action has a parenthesis (such as `(10)`), it is a cost required to perform that action. Most actions require only a small amount of IU, as it is more to prevent spam than to function as an actual currency.
- You can view your current IU amount via the `!inventory` command. You can also view other people's IU amounts by `!inventory [username]`.
- Every week, your first message awards you **5000** IU. from then on, every chat message awards you **1** IU per every 100 characters or 10 emotes.

&nbsp;&nbsp;**Icons** are the main use for gaining IU and are the little square images that appear in your chat messages. You can change and unlock icons by clicking on the bottom left icon (your twitch profile) in The Screen, and then clicking the "icons" section.
- You can unlock a random icon by clicking the "Unlock Icon" button in The Screen or using `!unlockIcon` command for **4000** IU each.
- There are a list of icons not available from the random unlock, that can only be achieved as a reward for completing various **[achievements](https://prod.kr/v/achievements)** within *the pod*.

&nbsp;&nbsp;**Cursors** are another customizable elements that are shown whenever you interact through GreenHeat or do a pointer action in The Screen. They are not unlockable by normal means, and so far only given as a special reward bundled with prod's business cards for [Offkai Expo](https://offkaiexpo.com).
- A [collection of Cards](https://prod.kr/card) for Offkai Gen 4 are available to view, where it will show the name, rarity, index, owner and credits when clicked.

&nbsp;&nbsp;**Gifts** are an unique way of using and gaining IU, where you can transfer your IU to a random chatter while generating a bunch of objects on the overlay. You can gift people using `!gift [item] [amount]`, with its cost varying depending on the type of item you send.
- The gift system was created as a humorous take on [Twitch Combos](https://www.youtube.com/watch?v=taxnorGjt-4&t=427s), and contains famous items you can gift in TikTok Live, where 1 cent is equated to 1 iu. (`icecream` (**1** IU), `rose` (**1** IU), `hotdog` (**5** IU), `galaxy` (**1000** IU), `lion` (**30000** IU))
- Aside from the TikTok gifts, there are also `fish` (**10000** IU, reference for "Joel"), `seal` (**400** IU, reference to [`!seal`](#asmodeus)) and `meteor` (**3000** IU, reference for ["Meteor Happens"](https://youtu.be/Slq2CUQdjBQ?si=EBjIw13qZbRsREAp)).
- Finally, there are `!bijan` which is a special command separate from `!gift` that gifts a random bread item for **100** IU. This is a reference to a restaurant near the convention center that hosts Offkai, and how everyone would meet up there in the morning.

<br>

*You decide to take a well-deserved break by the bank, drying your pants on the incline. You look back on the journey you've taken. How far you've come, and how far there is to go still. The path ahead is much steeper than before. There are less things to grab on to. One mistake, and all of this might be over. But you already made up your mind.*

*Transcendence awaits you.*

\> [Proceed downwards](#floor--4)  
\> [Fall into the water](#annex-firefly-lake)  

## Annex: Firefly Lake
\> <a href="https://prod.kr/audio/20210211.ogg" target="blank_">Change Sound</a> (*manual loop via "right-click" required)  

 󠀠    󠀠    󠀠   。 󠀠    󠀠    󠀠    󠀠    󠀠   . 󠀠    󠀠 。˚  。.  
 󠀠   o 󠀠    󠀠   .˚ 󠀠 O   󠀠    󠀠   ˚ 󠀠 ·   󠀠    󠀠˚   . 󠀠    󠀠    󠀠   .  
*Somehow, you are still alive.*  
*The moonlight embraces you gently...*  
 󠀠   ' 󠀠   。 󠀠    󠀠   . 󠀠    󠀠   O。 󠀠   ˚  o 󠀠    󠀠   ·. 󠀠    󠀠     ˚  
 󠀠    󠀠    󠀠   .' 󠀠   ˚ 󠀠   󠀠  . 󠀠   󠀠   󠀠  ' 󠀠   󠀠   󠀠   󠀠   󠀠  . 󠀠   󠀠  .   
<br>
&nbsp;&nbsp;prod and [SaladForrest](https://pooltoy.live) are hosting a weekly [Yume Nikki Online](https://ynoproject.net/) tour session, where we bring different guests every week and travel the dream worlds together. The stream is created in a way where the stream features **multiple monitors** in a virtual room, and viewers can look into each of them. Yume Nikki and its fangames hold significant meaning to both prod and forrest. Part of why prod began streaming also has to do with this game and website, as they were dragged into the streaming world by a tour hosted by [Digiko](https://twitch.tv/digiko) (henceforth "Woman" or "Progenitor 2 / Light Progenitor").
- During 2kki streams, prod and forrest's chat become linked, and every prod command becomes available in forrest's chatroom as well.
- GreenHeat integrations also become linked, so you can click on forrest's channel to influence prod's overlay.
- You can change "POV"s via redeems in forrest's twitch channel to see different people's POVs.
- All travels are recorded in **[the repository](https://pub.colonq.computer/~prod/yume/)** where you can see screenshots from past expeditions, even ones before prod began streaming.
- Each blog entry has tags attached for featured VTubers, games played and so on.

<br>

*You start to feel lighter as you sink further into the water. Warmth surrounds you as fatigue sheds away into an unnatural comfort. It's as if you're being embraced by the water itself.*

*Wasn't the puddle knee deep? It feels like you've been sinking for many seconds already. "Am I dying?" you think to yourself. You certainly don't feel like dying, in fact, what you're in doesn't feel like water at all.*

\> [Rise up to the top](#floor--3)  
\> [Let yourself be submerged](#floor--5)  

## Floor -4
 󠀠    󠀠    󠀠    󠀠    󠀠   , 󠀠    󠀠    󠀠    󠀠    󠀠   , 󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   , 󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   ,  
 󠀠   ',| 󠀠    󠀠    󠀠   | 󠀠    󠀠    󠀠   || 󠀠    󠀠    󠀠    󠀠   |' 󠀠    󠀠   ' 󠀠    󠀠   ,, 󠀠    󠀠    󠀠   ,|' 󠀠    󠀠    󠀠    󠀠    󠀠   ' 󠀠    󠀠    󠀠    󠀠   | 󠀠   | 󠀠    󠀠   ' 󠀠    󠀠   '  
*You begin scaling down the surface. Rubble falls everywhere you step.*  
*But transcendence awaits.*   
| 󠀠    󠀠   || 󠀠    󠀠    󠀠    󠀠    󠀠   |''' 󠀠    󠀠   |' 󠀠    󠀠   ''  
 󠀠    󠀠    󠀠   ' 󠀠    󠀠    󠀠    󠀠   '  
<br>
&nbsp;&nbsp;*the pod* features a custom **[Markup Language](https://prod.kr/docs/chat)** that can be used to display text normally impossible through twitch interactions. You can use them like `<tag>text</>`, and tags can be nested. Note that `</>` closes the innermost tag no matter what, and does not need specification such as HTML.
- `<br>`: Creates a newline. Useful for twitch as twitch chat does not support newlines. (If you are chatting from Discord, you can just use the built-in enter.)
- `<b>`, `<i>`, `<u>`, `<s>`: Applies basic word decorations (bold, italic, underline, strikethrough). Only **certain fonts** support bold and italic however.
- `<color=#RRGGBB>`: Changes the text color.
- `<size=26>`: Changes the font size. Default is `26`.
- `<font=name>`: Changes the font family. Type `!font` for a list of supported fonts. 
- `<wave>`, `<shake>`: Applies animation to texts. We recommend using this for emphasis instead of `<b>` as it works for all font families. You can also specify the parameters like `<wave amp=4 period=16 freq=1>` and `<shake amp=1>`.
- `<charspace=0>`, `<lineheight=1>`: Changes the text margins.
- `<tilt=0>`: Makes every letter rotate by a certain amount, in degrees.
- Check the [dedicated docs page](https://prod.kr/docs/chat) for more detail and font previews.

&nbsp;&nbsp;*the pod* also features **emotes** one can use without subscribing to the channel. Every discord and twitch emote will be relayed to the overlay, as well as any 7TV emotes prod has added.
- prod's own emotes are in a form of `:p_emote:`. You can send them anywhere by typing `:p_proon:` and so on.
- In addition to prod's own emotes, prod's 7TV emotes include **every** "Joel" emote on 7TV platform right now in a form of **[The Archive](https://7tv.app/emote-sets/01HXG0MAHG00063MFF82T8437P)**. You can use any of them and it will appear on the on-screen overlay.
- As of Season 1.5, emotes have a spacing issue where it doesn't space properly for the Discord to Twitch, and IRC bridge.

<br>

*Your hands are red. Your legs are bruised. But you are here at last. At the bottom of the cave, lies the temple of myths. One people dare not speak under the daylight, only passed down through hushed voices of the occult. The cult \*loves\* computer. They are normal.*

*Proceed downwards.*

\> [Proceed downwards](#floor--5)  

## Floor -5

 󠀠   󠀠||....||  󠀠    󠀠    󠀠   . 󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   󠀠   󠀠||....||  
 󠀠  ||....||  󠀠    󠀠    󠀠 󠀠     󠀠    󠀠    󠀠    󠀠    󠀠    .   󠀠    󠀠    󠀠     󠀠  󠀠   󠀠 ||....||  
*You have entered the hallowed grounds.*  
*Transcendence awaits.*  󠀠   󠀠   󠀠   󠀠   󠀠   󠀠||....||  
 󠀠   ||....||    󠀠    󠀠   . 󠀠   󠀠   󠀠     󠀠    󠀠   . 󠀠    󠀠    󠀠    󠀠    󠀠   󠀠      󠀠  ||....||  
 󠀠  ||....||  󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠    󠀠   . 󠀠   󠀠   󠀠      ||....||  
<br>
&nbsp;&nbsp;You can play music within *the pod* using a [custom format](https://prod.kr/docs/song). The song format is a superset of ["Bells of Bezelea"](https://pub.colonq.computer/~bezelea/bells/) redeems in the Male zones, and every redeem made for bells (the original version, not [the rusty bells](https://pub.colonq.computer/~the0x539/bells/)) will work here as well. You can play songs with The Screen actions or the `!song [format]` command.
- Each note is represented with `A` to `G`, then the sharp (`#`) mark, then an octave if applicable. The octave can be omitted, where `A#` is equivalent to a `A4#`.
- Each note plays in sequence unless wrapped by a bracket (`[]`), where every note within a bracket is considered a **chord** and will play simultaneously.
- You can use `/` to denote a pause, and `~` to play the previous note 1 beat longer. You can chain multiple `~` to make notes of any length.
- You can specify a **BPM** by adding a number at the beginning (`120|CDEFG`).
- You can divide songs by `|` to play multiple songs at once. They are tracks that run independently from each other.

&nbsp;&nbsp;The following is features explicitly added by prod's song format.
- You can specify the **name** of the song by adding words at the beginning (`my_song.120|ABCDE`). songs with names will **not be deleted** at the end of each stream and can be played at any time with `!song [name]`.
- You can use `@` to specify the note length. `C#5@5.5` plays the note for five and a half beats.
- You can append `<` and `>` to drop the attack and release of each note respectively, allowing for slide type action.
- You can append `!` to stop the note from "advancing the staff line", allowing for notes to overlap with different note lengths.
- You can specify the instrument by writing them after the dot at the beginning of the track, such as `song.drum120|C/C/C/C`. You can type `!instrument` to get the list of instruments available.
- You can write microtonal music by typing `%` followed by the number of notes in an octave at the beginning, such as `song.120%31|ABC`.
- You can change the bpm and equal temperament midway through via using the `?` followed by the BPM in numbers.
- Premade songs are available to be copied and played in [DBKai](https://pub.colonq.computer/~prod/toy/dbkai/): select any song from the dropdown and press **"prod"** where the result will be automatically copied to your clipboard. You can also convert **MIDI** files into `!song` formats by using the top menu.
- More songs that take advantage of `!song`'s expanded system are available in [CrazyKitty's Repository](https://pub.colonq.computer/~crazykitty/).
- At the bottom of DBKai, there are extra compression options in case the text-based compression is not enough. This takes advantage of a modified **Base32768** to nearly halve the character count. Keep in mind that song commands can be pasted to not only Twitch chat (**500** character limit) but also Discord (**2000**~4000 character limit) and The Screen (theoretically **infinite** character limit).
- There are a lot more to the specs, but they do not add more features and are for convenience and compression. check the [dedicated docs page](https://prod.kr/docs/chat) for more detail.

<br>

*At the heart of the temple lies an amulet. Green glassy tendrils lead to behind the temple. You can feel the blood rushing through you. Your head feels heavy. Sweat pours out of your forehead. The cave is patient.*

*Transcendence awaits.*

\> [Grab the amulet](#inferno-1)  
\> [Investigate the tendrils](#annex-emerald-heart)  

## Annex: Emerald Heart
 󠀠  󠀠 󠀠  󠀠   󠀠  󠀠  󠀠 / 󠀠  󠀠  󠀠   \\ 󠀠  󠀠  󠀠  󠀠  󠀠 /./ 󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠 / 󠀠  󠀠 / 󠀠\\   󠀠  󠀠  󠀠  /\\  
 󠀠 .\\ 󠀠  󠀠  󠀠 / 󠀠  󠀠  󠀠 \\// 󠀠  󠀠..  󠀠 |// 󠀠.  󠀠  󠀠 | 󠀠  󠀠  󠀠 \\/// 󠀠  󠀠 . 󠀠  󠀠 \ 󠀠  󠀠  󠀠  󠀠 \\..  
*A thousand tendrils soar to the sky, ground resonating with fear.*  
*You are at the heart of the underground.*  
 󠀠 \\ 󠀠'  󠀠  󠀠 / 󠀠  󠀠 / 󠀠 ' 󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠  󠀠  󠀠 /  󠀠 .   
 󠀠    󠀠  󠀠 / 󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠 . 󠀠  󠀠  󠀠 / 󠀠  󠀠  󠀠 /  
<br>
&nbsp;&nbsp;There was a time before *the pod* where prod was a [librarian tier viewer](https://pub.colonq.computer/~prod/toy/glossary/) of The Man. **docket.org** is a file that regularly appears that lists all the ideas and "stream things to do" for the male cast. It is famous for being evergrowing and some ideas falling into "the abyss". Early contents of *the pod* often involved creating some of these ideas with ["yellow language"](https://www.npmjs.com/package/ws). Sites hosted on [pubnix](https://pub.colonq.computer/) such as DBKai is created during this time.
- `JoelCheck` is one of the Joel emotes that used to be used for "pre gang"s, people that show up before the broadcast begins. When used in the LCOLONQ chatroom, the bot "receive"s your JoelChecks.
- **[Canonize](https://pub.colonq.computer/~prod/toy/canonize/)**: Every chat message in LCOLONQ gets a ["biblicality" score](https://www.youtube.com/watch?v=G5u23bh29hI), which is calculated by the average amount each word appears in [the bible](https://gutenberg.org/). Canonize is a web app that calculates biblicality and translates your sentences into "maximum biblical" versions.
- DBKai also features a list of songs that are available by default in LCOLONQ broadcasts (can be called by redeeming bells with just its name), and all the features also feature original bells conversion.

&nbsp;&nbsp;**Boosting** is a sort of daily check in redeem of LCOLONQ, where you can redeem "BOOST" or "TSOOB" to increment or decrement your BOOST score. Some commands in the zone require more than 3 absolute BOOST value to filter out bad actors, and `!leaderboard` exists to show the boost leaderboard of all chatters who have sent a chat message during that session. BOOSTs were also used as a part of **faction warfare**. Every LCOLONQ chatters are randomly assigned one of three teams: **nate**, **tony** and **lever**, and until Season 3, the total sum of BOOSTs of each faction were displayed at the top of his stream.

&nbsp;&nbsp;**[Geiser.xpi](https://pub.colonq.computer/~prod/toy/geiserxpi/)** is a userscript that displays various [user stats](#beelzebub) by hovering over the username. This userscript includes the **Clonkspotting** module, an attempt to realize the idea discussed in the docket of [LLLL Colonq Goes Bananas 25: Noosphere](https://www.youtube.com/watch?v=bJJGjm-nxlA). The concept was devised as a "secret handshake" between "Clonkheads" to recognize each other, via external programs (such as a browser extension - realized here via the userscript).
- When watching other twitch channels, you may come across users with a "mr blue" icon, this signifies that this person is a "Clonkhead" - who are registered in LCOLONQ's database by talking or interacting once in his channel.
- You can click the "mr blue" to turn it into "mr green" - therefore **spotting** that person. When you spot a person, both you and that person gains 1 "BOOST v2". **BOOST v2**s are unofficial BOOST points that were in the design document of the original LCOLONQ stream, but is not counted towards actual BOOSTs due to the (endorsed)unofficial nature of the userscript.
- Clonkspots reset every **24 hours**, where between that time you cannot spot the same person twice.
- You cannot clonkspot while inside LCOLONQ's twitch chat as the design intent is to encourage spotting people outside of the originating stream. *the pod* is fair game however and often acts as a big congregation of "Clonkheads" to be spotted.
- You can check your BOOSTs and BOOST v2s by typing `!boost` in both *the pod* and LCOLONQ channels.
- `!clonkspotleaderboard` (NOT `!leaderboard`) shows the total BOOST (sum of BOOST v1 and v2) leaderboard. By the nature of the method of gaining BOOST v2s, the numbers are a lot more inflated compared to v1 leaderboard.

<br>

*As the earthen organ breathes, you feel an overwhelming sense of dread. You cannot dare move closer, as the towering structure emanates unimaginable dread from within.*

\> [Head back to the temple](#floor--5)  

<hr>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Inferno ±1
\> <a href="https://prod.kr/audio/20191110.ogg" target="blank_">Change Sound</a> (*manual loop via "right-click" required) 

 󠀠   
 󠀠  󠀠  󠀠  󠀠  󠀠 /\\  
*Your true test begins.*  
 󠀠  󠀠  󠀠  󠀠  󠀠 \\/  
 󠀠   
<br>
&nbsp;&nbsp;Remember `!guy`s? They possess stats of their own. Many stats, in fact. You can check them at the user profile on The Screen, or via `!stats`. If you wish to use the text command, it is recommended that you check in the Discord server or via IRC, as Twitch character limit (500 characters) often cuts off your stats.
- Guys are either in **idle** state, or are in one of few action states. After each action state, guys enter idle state for a random amount of time. This time is determined by **Dexterity** (average) and **Jokerness** (variance).
### Movement Stats
  **Move** state is one of the action states guys can take, which can either be a **walk** or a **jump** action.
- The distance each move action covers is determined by **Agility**.
- The likelihood a guy would choose jump over walk is based on **Jumpness**.
- The height of the jump is determined by **Jump Height** (average) and **Zebraness** (variance).
- The horizontal distance of the jump is determined by **Camelness**.
### Kick Stats
  **Kick** state can only be entered if there are valid targets (such as windows or chat messages), where it kicks the object towards the direction the guy is looking.
- **Aggression** determines the likelihood kick action is chosen over move. It also determines how likely an object will be destroyed upon each kick.
- **Strength** (average), **Luck** (variance) and **Bisonness** determines the horizontal and vertical momentum of the object.

&nbsp;&nbsp;Movement and kick stats are determined by your chatting pattern within *the pod*, such as the amount of capital letters used, the average length of your chat messages and such. Check the [dedicated docs page](https://prod.kr/docs/chat) for more detail.

### Combat Stats
  When `!fight`ing, a set of different stats are used for its combat. These stats are equal upon spawning (unless its a raid boss), and can only be increased via `!levelup`.
- just like **move** or **kick**, **attack** is an action state a guy can take while in combat. It will prioritize attacking when an enemy is overlapped with itself, and will try to approach the enemy if not. **Attack Speed** determines the "cooldown" after each attack, where one cannot do the attack action again for an amount of time.
- **Constitution** represents its max HP, and **Appleness** represents HP regeneration rate.
- **Attack** represents its maximum attack damage. Damage is rolled between this and a fixed minimum.
- **Defense** represents a flat damage reduction on each hit.
- **Critical Attacks** gives you a damage multiplier, and is dependent on **Critical Chance** and **Critical Damage**.
- **Multihits** represent an average hits per attack action.
- **Oxness** represent the chance to approach the enemy when not in attack range versus fleeing away.
- **Hipponess** determine the chance to randomly start `!fight`ing without explicit command.

&nbsp;&nbsp;Right now, only **Constitution**, **Attack** and **Critical Chance** can be upgraded.

### Statistics
  Certain stats of guys are tracked that doesn't influence its behavior.
- **Total Wins** and **Losses** as well as **Max Win Streak** is recorded.
- **Raid Boss Wins** and **Losses** are recorded separately, tracking times your guy landed a **final blow** to the raid boss and times it perished to the raid boss.
- **Damage Dealt** and **Taken** are tracked as well, as well as **Total DPS**.
- **Distance Walked**, **Times Jumped**, **Attacked**, **Kicked**, **Gotten Attacked**, **Times Peaced** are tracked.
- **Total Time Spent Airborne** and **Grounded** are tracked, and you can add them together to get total time existing.

<br>

*The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending. The descent is neverending.*

\> [Forfeit your mind](#inferno-2)  
\> [Challenge the demon](#asmodeus)  
\> [Succumb to the darkness](#-prodzpod)  

## Asmodeus

 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠/ 󠀠 \\  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠 /\\ 󠀠 \\  
*Your vision splits into a million pieces.*  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠 \\/ 󠀠 /  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠 /  

<br>

&nbsp;&nbsp;**Witscord** is a 10 year old Discord server that previously was about [The Witness](https://en.wikipedia.org/wiki/The_Witness_(2016_video_game)). Now, it functions as a semi-public social hub that hosts a bunch of socialist 30 year olds and queer furries (where prod sits at an intersection), talking about 10 year old worth injokes and puzzle games that aren't The Witness. Most of prod's humor comes from this place. There is no way to document the entirety of the WitLore (nor is it in the spirit to), so only the parts that are related to *the pod* is documented here. For more information, see [the Witscord wiki](http://witscord.net/~staz/w/index.php/Main_Page) for dubious amounts of help.
- **[@witscord@mas.to](https://mas.to/@witscord)** is an automated Mastodon account hosted by Witscord member [panic](http://ianhenderson.org/), that posts messages from the Discord based on a starboard-like interaction. For a message to be posted, more than 5 elephant reaction (🐘) needs to be reacted on a message, including one by the message author (as a form of consent to be posted online). Mammoth reactions (🦣) work as a negative elephant (downvote), increasing the elephant reaction by 1 every mammoth. Five ox (🐂) reactions makes the message a Nice Ox message. prod will often repost elephanted message to *the pod* as a form of **witposting** (wp). The Mastodon account is linked to [Bluesky](https://bsky.app/profile/did:plc:2rnuia5r3rwnvweibvzmmq43) as well. There are a set of emotes referencing this fact within *the pod*.
- **[One Day One Puzzle](https://onedayonepuzl.web.app/)** (1D1P) is a "weekly" puzzle jam hosted within Witscord where members try to create puzzles within a short period of time. The tradition has started in 2020 by Witscord user sus1d1p (sus) and [Raz](https://studio369.itch.io/) (Studio369). Many puzzles are in the **lateral** genre, requiring outside-of-the-box thinking and deciphering minimal information. Notable 1D1Ps include [Teeth](https://thejonymyster.neocities.org/Teeth#) by TheJonyMyster and [You Drove Off the Road!](http://ianhenderson.org/you-drove-off-the-road.html) (ydotr) by panic.
- **[Funny Looksy](https://prodzpod.github.io/looksy/)** is a custom The Witness puzzle created made by prod back when the server actually was about The Witness. The editor features dozens of custom symbols and community made tutorial and challenge panels. The software has been forked by **[beesnation](https://beesnation.github.io/witness/)** that fixes some bugs and adds new symbols. Other custom Witness puzzle makers include **[Lopsy](https://thejonymyster.neocities.org/lopsy)** by TheJonyMyster, **[What the Witness?](https://alith.itch.io/what-the-witness)** (wtw) by Alith and **[Seeker](https://justkirb.itch.io/seeker)** by Just Kirb. Version 3 of Looksy is "in the works", and might reappear on *the pod* soon.
- **Cave Adventure** is a project by Witscord user Katelyn Delta (kate) that started as a 1D1P entry. Only the [original](https://onedayonepuzl.web.app/puzzle?week=14&id=Katelyn%20%CE%94) is actually called "Cave Adventure", with later entries getting its own name. **[CA2: Letters](https://katelyndelta.github.io/index.html)** is a minimal feedback puzzle game that is hosted on the static web, and your goal is to figure out the correct configuration of the grid. This idea was then refined in **[0PLAYER](https://caveadventure.itch.io/0player)** (CA3), a static WebP image of a hypothetical sokoban game that involves rule deduction and abstraction. Unlike other two entries 0PLAYER has been advertized to the public and was critically acclaimed, being awarded "Most Innovative Game" at [The 3rd Annual Thinky Awards](https://thinkygames.com/events/awards/).
- **[HOUSE](https://studio369.itch.io/house)** is lateral puzzle book by Raz with exceptional polish and quality. The book is about finding a hidden 5 letter english word in each page, but no ciphers outside of alphanumeric transformation are used. prod will occasionally recommend this to people that are interested.
- **[Jp█g Dirt](https://jpegdirt.tumblr.com/)** is a webcomic written by TheJonyMyster that is "The only webcomic better than Homestuck". The entries appear occasionally as a bit in both *the pod* and LCOLONQ chat.
- **[witscord.net](http://witscord.net)** is a pub unix instance by panic. Witscopedia is hosted here as a part of Witscord member staz's userpage. prod has a [page of their own](http://witscord.net/~prod/) as well, detailing puzzles prod has made. HTTPS/TLS is not supported for Witscord.net due to panic being anti TLS.
- **[0rise](http://ianhenderson.org/0rise.html)** is an experimental way of describing time based on sunrise and sunset by panic. You can use the `!0rise` command to tell the time in 0rise format. You can specify the city by typing `!0rise [city]`, and allow negative numbers by replacing the command with `!-0rise`.

&nbsp;&nbsp;**[Witsend](http://witsend.witscord.net/)** is an alternative messaging website that panic created "in case Discord becomes unusable and Witscord dissolves". For now, Witsend is being used as a "extended Witscord" where Witscord members and people adjacent to the Witscord community (including friends of *the pod*) to chat.
- There is a limited two-way connection between Witsend between the rest of *the pod*. Any Witsend messages will be sent to the Discord in a small letter, but not all messages from prod's chat will be sent. To send messages to Witsend from any of prod's chat, you must use the `!ws` command.
- You are able to use any commands that does not require logging in within Witsend, as Witsend does not offer ways to authenticate yourself.
- Witsend used to feature buttons that sent a "seal gif", this is a form of [nonposting](http://witscord.net/~staz/w/index.php/Nonposting) that was beloved by many. prod, to offer full feature parity with the Witsend client, offers `!seal` to send seal gifs. The seal button was later disabled and all seal images were replaced with "SealBlock". This is still an ongoing bit that happens within *the pod*. See [the relevant Witscopedia entry](http://witscord.net/~staz/w/index.php/Witsend) for more details.

<br>

*-- couldn't get [todays plusword](https://oat.zone/f/sponge-or-lime/) --*

\> [Proceed downwards?](#floor--2)  
\> [Proceed downwards?](#inferno-2)  
\> [Proceed downwards?](#asmodeus)  
\> <a href="https://jpegdirt.tumblr.com/random" target="_blank">Proceed downwards?</a>  
\> [Proceed downwards?](#inferno-1)  
\> [Succumb to the darkness](#-prodzpod)  

## Inferno ±2

  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠/  
  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\/  
*Bones. Bones lie on the floor.*  
  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 /\\  
  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠  󠀠 \\  
<br>
&nbsp;&nbsp;There are a variety of gizmos that are abandoned and or not useful anymore. Commands documented in this section still exists in some fashion, but does not work in an intended way.

&nbsp;&nbsp;You are able to use `!makeclip` to create clips in prod's channel. Originally, this and other Clip suite commands were made for prod's own use to circumvent [the issue of using twitch in korea](https://blog.twitch.tv/en/2023/12/05/an-update-on-twitch-in-korea/), making them unable to see or make any clips or VOD entries. The command is slower than making a clip directly as all requests go through [the pubnix](https://pub.colonq.computer/~prod/cgi-source/api.scm). You can also see the [clip viewer](https://prod.kr/v/clips) we used to use before prod get a proper VPN (also known as being "legally in japan") set up. Only `!makeclip` out of the suite is available to the public.

&nbsp;&nbsp;**Twitch Plays Cheat Engine** was a charity event hosted by prod as a part of [VTubers Against ICE 2025](https://tiltify.com/+vtubers-against-ice/vtubers-against-ice-2025), where prod would play various games and viewers were able to query and manipulate the memory space of the game, corrupting it in whatever fashion. In addition, every dollar donated to the charity would corrupt 100 random bytes in the game, often leading to crashes. The commands will respond to you, but has no real effect on the stream.
- `!scan` were used to query values. It is equivalent to pressing the "scan next" button on the GUI version of Cheat Engine.
- `!scan exact [number]` / `!scan between [number] [number]`: Scans addresses with value in that range. Exact searches permitted small errors for floating point numbers.
- `!scan changed` / `!scan unchanged`: Scans addresses with their values that have remained the same or changed between this and last scan.
- `!scan more` / `!scan less`: Scans addresses with their values increased or decreased between this and last scan.
- `!scan reset`: Reset your query history. This is equivalent to pressing "New Scan".
- `!value [address] [number]`: Manipulate a single space of memory.
- `!value list`: Shows the list of addresses that fit your current set of queries. Only displays if there are less than 10 candidates.
- `!value random`: Randomly flips a single byte of memory.

&nbsp;&nbsp;**[Jesus is Lit](https://www.youtube.com/watch?v=Y8R83Sn8E9U)** is an 2025 easter special live theater production by **Crowd Control Theatre Company**, featuring over 20 VTubers and 4 different POV streams enacting a single play from multiple angles. prod was involved in this production as a POV actor, streaming "the prodcast" - an in-lore business and finance podcast on the "crypto market" that was at the center of the plot. Through prod's chat and the dashboard overlay, you were given **10000\$** (not IU!) by default, and were able to buy and sell **\$JESUS** and **\$JUDAS** throughout the play. The price would fluctuate based on the story, and the mini-goal of the prod POV was to acquire as much "dollars" as you could trading these hypothetical coins. Since the end of the show, all coins has gone to **0\$**, and cannot be purchased anymore.
- `!buy` (later `!buyjesus` and `!buyjudas`): Buys the coin for the listed price. You were able to buy multiple coins at once with `!buy [amount]`.
- `!sell` (later `!selljesus` and `!selljudas`): Sells the coin for the listed price. As with `!buy`, you were able to do `!sell [amount]`.
- `!wallet`: View your dollar amount and crypto portfolio.
- `!bankruptsy`: Only available when you have less than 10000$. Sets your money back to 10000$ and removes all your posessed coins.

<br>
 
*...*

\> [Forfeit your soul](#inferno-2)  
\> [Challenge the demon](#beelzebub)  
\> [Succumb to the darkness](#-prodzpod)  

## Beelzebub

 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠  󠀠 \\ 󠀠  󠀠/ 󠀠  󠀠  󠀠 /  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠  󠀠 \\/ 󠀠  󠀠  󠀠 /  
*Your flesh slowly sheds into dust and nothingness.*  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠  󠀠  󠀠 /\\ 󠀠  󠀠  󠀠 \\  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠  󠀠  󠀠 / 󠀠  󠀠\\ 󠀠  󠀠  󠀠 \\  
<br>
&nbsp;&nbsp;Just like how there are abandoned prod gizmos, there are gizmos that were created specifically for other channels of the TealCircle. Most prominent of them all is commands and websites that exist for the Male zones. You will see references to it and the bits that the commands reference often, but they are mostly retired and reflect an older era of LCOLONQ that focused much more on one-off interactive softwares and not writing a compiler that has nothing to do with twitch interaction for fun and whimsy.
- **mental clarity** is a redeem in the malezone that stops all audio redeems (such as Bells of Bezelea), meant to counter situation where someone spams many audio redeems together. The redeem has become a bit of itself as LCOLONQ would often say its name when the audio gets chaotic, and many offshoot redeems were born from this redeem, the most notable being the 5000-point **[total clarity](https://youtu.be/Rqmx_3Yu6Xg?si=LMtFrTaTi3XfDDsS)** redeem. Total clarity would clear every audiovisual effect, cut his mic, and let a gong sound effect play while water droplets cover the entire screen. `!tranquility` is made as a reference to this redeem, where it would respond with a variation of "omm...".
- **[Global Consciousness Project](https://global-mind.org/gcpdot/)** (GCP) is a ... cult ?? movement ?? that believes that the collective unconscious can be measured by deviations of random number generators placed around the world. If the dot is blue (high percentage), it indicates global shared focus, and if the dot is red (low percentage), it means there are divergence in focus. Being this being very [lain core](https://www.youtube.com/watch?v=A4BUf9ZCgnA), LCOLONQ has adopted this into his streams where the subject arised often during its original run. Later, LCOLONQ purchases [gcp3.net](https://gcp3.net/) and declares the launch of **Green Collective Projectile**, a GreenCircle RNG project that recieves data from all points around the GreenCircle (it is GCP 3 as [GCP2](https://gcp2.net/) exists already). The GCP3 website is made in [Factor](https://factorcode.org/) and only features a mrgreen shifting hue, with the future plans of sourcing RNG from the circle being largely falling in the Abyss. prod has revived this concept as the `!gcp` command you can use in both *the pod* and LCOLONQ. Currently, prod's GCP3, [JCP](./venorrak.md#jcp) by Venorrak, [polish temperature](https://pub.colonq.computer/~kpm/thing/) by krzysckh and [GFP](https://pub.colonq.computer/~nichepenguin/community/community.html#tarot-gfp) by nichepenguin is collected. prod's GCP3 works by every 5 minutes and everytime `!gcp` is called, a random character from the entire stream repo (excluding npm libraries, including user data) is fetched and hashed. Currently, gcp2.net and Venorrak's GCP3 is no longer functional, and skipped in calculation.
- **[Cloning Facility](https://www.youtube.com/watch?v=SlqzsLODk5o)** is a stream project and a 50000 channel point redeem where LCOLONQ would collect "DNA" (chat messages) and create a "clone" of them, which was a ChatGPT agent that sent fake messages as them occasionally. The redeem has been retired and "all the clones has been shot back" as AI became not very cool (according to him). prod had a custom "clone endpoint" that generated messages instead of clonk's default AI prompt, that were more involved. You were also able to use `!clone` to invoke prod's clone. prod's prompts were custom, recent messages were fetched for context, and were able to be affected by [hexes](https://pub.colonq.computer/~prod/toy/glossary/#chatter-hexes). There were also a small chance for the clone to be special, getting a special prompt to [pretend to be someone else](https://pub.colonq.computer/~prod/toy/glossary/#talk-to-friends) or [write a newspaper entry](https://pub.colonq.computer/~prod/toy/glossary/#season-25-lcolonq-2x-rebirth-edition), or forgoing AI altogether and generating a random [ad message](https://diep.io) or posting random [Jp█g Dirt](https://jpegdirt.tumblr.com/random) entries. prod's clone ended much earlier than the overall end of the redeem due to prod running out of ChatGPT credits and not paying for them again.
- **[LCOLONQ Stream Bingo](https://pub.colonq.computer/~prod/toy/bingo/)** is a randomly generated 5x5 bingo that features recurring stream bits in the LCOLONQ broadcast. The website is technically live and you can still play it, but most of the recurring bits have stopped being relevant during the shift to the Compiler Era and LCOLONQ being much better at speaking (to a scary degree).
- **Bless** is a programming language that could have been executed in LCOLONQ's twitch streams. It is a stack-based, FORTH-like language that aims to maximize fun. The stack is global, meaning it persists between calls, and you are able to access the stack someone else has left behind. One of the big goals of bless was being able to hook on to various stream activities (such as being followed) and auto-executing. prod has [documented this language](https://pub.colonq.computer/~prod/toy/blessdocs/) and wrote some extensions to it. The project has been refactored and rebooted into multiple iterations before it fell into The Abyss, but this later becomes an inspiration to *the pod* to create a [version of this idea](#inferno-4) ...
- **[BulletML](https://www.asahi-net.or.jp/~cs8k-cyu/bulletml/index_e.html)** is a markup language for bullet hell patterns that was explored in the LCOLONQ stream. He created a transparent overlay where you can cast spells in bulletML where he had to dodge them with his cursor. The overlay was quite buggy however and ended up getting disabled, and became one of the events that made him realize that he enjoys Building a thing and understanding Compilers but not maintaining it / interaction part. prod has created a [web demo](https://pub.colonq.computer/~prod/toy/yamame/) and compressor for this redeem which also happens to be the only working BulletML demo that doesn't require downloading Java source code and compiling them. You were able to also use the same compression as the `!song` format on it.
- **[The Chambers of L](https://prodzpod.github.io/chambers/)** is a sidescrolling action roguelike created as a part of **LCOLONQ Game Jam 2025**. It is a knowledge-based dungeon crawller with 3 worlds where you obtain a variety of items, fight monsters with varied attacks and get to the end where another player was waiting for you. The game is at first glance quite unbalanced and very hard until you gain enough knowledge to break the game wide open. Each stage has a "wish" chest where you are able to type whatever item or stat you want and get them, and is the key to success in this game. There are also a hidden ELO system in the game, where each time you defeat a boss it goes up and your current run information gets recorded to the online server, to be a boss for future runs for other players around similar ELO range. API endpoints exists to fetch chambers bosses, but are rarely used now.

&nbsp;&nbsp;Just like the prod area contains many residues of LCOLONQ area as this used to be the residing factor, there are various webpages to Witscord doings of the past that are not as relevant now.
- **Woggle** is a daily-type game that combines Boggle and The Witness, where a grid of 16 letters squares with a letter is given. Your goal is to create a path from the bottom left corner to top right that does not cross itself and divide the grid into regions, and make words out of the letters in the regions. All the letters in the region must be used for it to be valid, and must be 4 letters or longer. You gain 1 point for each character used. If the region is more than 6 squares in size, you gain 1 bonus point per region. If you fail to make a valid word in the region, that region gives you 0 points. The grid has a max score of 18 (16 characters and 2 bonus points), which is called "getting a woggle". prod's website hosts an autosolver for woggle, with wildcard support.
- **[Qat](https://www.quinapalus.com/cgi-bin/qat)** is an advanced word search application that was developed for crossword setters. It features a wide set of tools and unique syntax documented in [its website](https://www.quinapalus.com/qat.html). prod has created a command, `!qat [pattern]`, that queries qat within twitch chat.
- **[Octaduction](https://moog-octavia.itch.io/octaduction)** is a lateral puzzle sheet by Witscord user Moog Octavia where you are tasked with figuring out the ciphers based on the examples given. As a part of prod's playthrough, an [autosolver](https://prod.kr/octaduction) was made and published on the web.
- **[JP♠G DIRT OFFICIAL CARDS FOR talbe top SIM█ᵓULATOR](https://jpegdirt.tumblr.com/post/786991956626702336/mar122025)** is a sheet of cards posted as a 500th episode of Jp█g Dirt. During the production, there was a discussion in Witscord for how 7s should look like, with TheJonyMyster expressing dissatisfaction with how traditional playing cards' 7s being not vertically symmetric. prod has created a [helper tool](https://prod.kr/jony) to generate custom symbol layout in a standard size playing card. TheJonyMyster has coined notations for card symbol layouts that are being used in the webapp, consisting of three symbols: `+` for "add a dot in the middle", `*` for "horizontally double all dots", `/` for "add 1 dot in each row a dot is in". Every traditional playing card layouts as well as the final 7 used in Jp█g Dirt 500 can be created.
- **[WitMinis](http://witscord.net/~staz/w/index.php/WitMinis)** are an annual series of 25 miniature crosswords published daily via Crosshare throughout the month of December, so as to emulate a traditional Christmas advent calendar. Each crossword is themed around a prominent Witscorder, with several entries, clues, and/or gimmicks referencing the individual's personality, interests, and/or created works. The project was spearheaded by Witscord user non as early as September 2024 with sus assisting. The 26th of December also happens to be non's birthday, and to celebrate various community members are encouraged by sus to create an unofficial "WitMini #26" featuring non as the prominent witscorder. [prod's 2024 entry](https://crosshare.org/crosswords/xwhNim3EddWdqBjkdgnP/witmini-26) is an involved lateral web puzzle disguised as a cryptic crossword puzzle, featuring non's various nicknames.

&nbsp;&nbsp;**[BrighterMalphon](https://twitch.tv/brightermalphon)** is a friend of our channel that commissioned prod for an interactive starting soon screen. This screen has since been retired. You can still view the screen [here](https://prod.kr/malphon/startingsoon).
- `Spawn Tilly` and `Banish Tilly` redeems could be used during the starting soon screen, where Tilly, malphon's mascot would appear or disappear and make a stack. If enough Tillies are banished, the count would go negative and negative Tilly stack would form going downwards instead of upwards.
- Recent messages and its author were shown in the grass as part of the screen.
- Various events would happen occasionally, such as the moon "opening its eye" every 5 to 10 minutes.

<br>

*-- i'll [take it](https://store.steampowered.com/app/2121980/Void_Stranger/) from here! --*

\> [\_?\_e\_\_\_ \_o??\_\_\_?\_](#inferno-3)  
\> [Succumb to the darkness](#-prodzpod)  

## Inferno ±3

 󠀠  󠀠  󠀠/\\ 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 /\\ 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 /\\  
 󠀠 / 󠀠  󠀠 \\ 󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠  󠀠 \\ 󠀠  󠀠  󠀠  󠀠  󠀠 / 󠀠  󠀠 \\  
*Haze fills your lung as you stop breathing.*  
 󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠 / 󠀠  󠀠  󠀠  󠀠  󠀠 \\ 󠀠  󠀠 / 󠀠  󠀠  󠀠  󠀠  󠀠 \\  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\/ 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\/ 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 \\  
<br>
&nbsp;&nbsp;prod.kr features various [API endpoints](https://prod.kr/docs/api) that starts with `https://prod.kr/api` that can be used to fetch and manipulate data from an automated source.
- `GET api/chat`: Fetches most recent chat messages from prod's Twitch, Discord and IRC. Relevant message IDs and author IDs are given.
    - Input Query Parameter:
      ```json
      {
        count: int // amount of messages to fetch, default = max = 100
      }
      ```
    - Output Example: 
      ```json
      [{
         from: "twitch"|"discord"|"screen"|"irc"|"ws",
         chatter: { // IDs of chatters
            twitch: int | null,
            discord: String | null,
            web: String | null
         },
         message: String | null, // twitch ID of the message
         text: String,
         emote: [{
            position: int, // position in the whole string
            name: String,
            url: String,
            source: "twitch"|"discord"|"7tv"|"prod"|"vanilla",
            format: "png"|"gif"
         }, ...],
         reply: String | null // twitch reply ID
      }, ...]
      ```
- `GET api/screen`: Fetches various metadata about the overlay. You must supply a `subject` query parameter as a subcommand.
  - Output Example for subject `windowcount`, `chatcount` and `pointercount`:
    ```json
    {
        res: [int] | false // number of objects of that type on screen. false if screen is not active at the moment. Note that it returns an array with 1 element instead of the int itself.
    }
    ```
  - Output Example for subject `palette`:
    ```json
    {
        res: [["#RRGGBBAA -> #RRGGBBAA", ...]] | false // list of strings that describe color transformations where source and destination color is given.
    }
    ```
  - Output Example for subject `accessory`:
    ```json
    {
        res: [[String, String, ...]] | false // list of accessory IDs that can be used in `!accessory`.
    }
    ```
  - Output Example for subject `guys`:
    ```json
    {
        res: [[String, String, ...]] | false // list of Twitch usernames that has !guy summoned on the screen at this moment.
    }
    ```
  - Output Example for subject `camera`:
    ```json
    {
        res: ["pixels", int, "width", int, "height", int, "x", int, "y", int, "z", int, "rx", int, "ry", int, "rz", int, "zoom", float] | false // alternative key and values that describes the camera parameters. `rx` to `rz` describes rotation data in degrees, and position data is in pixels. `pixels` describe the amount of pixels one "square" makes up in a shader.
    }
    ```
  - Output Example for subject `volume`:
    ```json
    {
        res: ["system", float, "message", float, "click", float, "window", float, "song", float, "kick", float, "gong", float, "speech", float] | false // alternative key and values that describes the volume parameters. volume goes from 0 to 1.
    }
    ```
  - Output Example for subject `tracker`:
    ```json
    {
        res: [String] | false // Base64-encoded string for OpenSeeFace tracker data.
    }
    ```
- `GET api/stream`: Fetches various metadata about the stream. You must supply a `subject` query parameter as a subcommand.
  - Output Example for subject `title`, `subject` and `category`:
    ```json
    {
        res: String | null // Twitch stream title, category and "subject" that is returned when using `!today`.
    }
    ```
  - Output Example for subject `phase`:
    ```json
    {
        res: int // The "phase" of the stream - `-1` if stream is not active, `0` at the beginning of stream, increases by 1 every time `!marker` or `!brb` is used.
    }
    ```
  - Output Example for subject `uptime`:
    ```json
    {
        res: int | null // number of seconds since the beginning of stream.
    }
    ```
  - Output Example for subject `gcp`, `gcp2`, `gcp3` and `coherence`:
    ```json
    {
        res: float | null // number of GCP values that are returned when using `!gcp`. every call also rerolls prod's GCP3.
    }
    ```
- `GET api/wasd`: Returns the result of `WASD.pack()` and `WASD.unpack()`. **WASD** is a "bootleg JSON" that are designed to be typeless and compact, used for IPC across prod's gizmos.
    - Input Query Parameter:
      ```json
      {
        action: "pack"|"unpack",
        text: String
      }
      ```
    - Output Example for `pack`: `String` (note that the results are **not** JSON form.)
    - Output Example for `unpack`: `[Data]`
- `GET api/tealcircle`: Returns data from the TealCircle database.
    - Input Query Parameter:
      ```json
      {
        random: bool, // whether to return a random person out of the pool, or every qualified entry as an array. false by default.
        live: bool, // whether to only fetch channels that are currently live. true by default.
        circle: "green"|"teal"|"turquoise", // the circle to pull from. teal by default.
        format: "id"|"login"|"name"|"metadata", // determines the output format. login by default
        not: String | null // excludes a specific person from the search. In twitch username.
      }
      ```
  - Output Example for `random: true, format: id`:
    ```json
    {
        res: int | false // Twitch ID of the channel randomly chosen.
    }
    ```
  - Output Example for `random: false, format: metadata`:
    ```json
    [{
        category: String, // internal teal group data.
        id: int, // Twitch ID of the channel.
        login: String, // username without special characters, used for URLs and queries.
        name: String,
        color: "#RRGGBB",
        profile_image: String, // URL for the image
        description: String, // Channel description.
        manual_description: String | null, // Custom description written by prod.
        tags: [String, ...],
        last_category: String, // last stream category/game.
        last_stream: int, // UNIX timestamp of last stream start time.
        title: String, // Stream title.
        thumbnail: String // URL for the image
    }]
    ```
- `GET api/auth`: You can use `!genkey` in Twitch chat or The Screen (**not in Discord** as Discord pre-scans your URLs) where random ID is generated for you. Fetching this ID for the first time returns a password for you to use for `POST api/chat` requests.
    - Example output for `https://prod.kr/api/auth?login=9c41a7ac879683c4`:
        ```json
        {
            res: "your key is
            &id=9c41a7ac879683c4&pw=$2b$10$JdjKV2zUjZXpoyksdGcX7OA5KpK95MTmZBJbwSFK4IRT8cg/JcSA6
            include it at the end of your chat calls to access account specific things", 
            pw: "$2b$10$JdjKV2zUjZXpoyksdGcX7OA5KpK95MTmZBJbwSFK4IRT8cg/JcSA6"
        }
        ```
- `POST api/chat`: sends messages and calls commands as you. Keep in mind that the password gets revoked occasionally to prevent abuse. We recommend setting up the system in a way where if the request fails you generate the key again.
    - Input Query Parameter:
      ```json
      {
        id: String, // ID and PW gotten from `!genkey`
        pw: String,
        text: String // the text content
      }
      ```
- `GET api/user`: Returns data from the user database. Supports a SQL-like query system for customized fetching.
    - Input Query Parameter:
      ```json
      {
        select: Path, rankby:Path, rankby:desc:Path, ... // Comma-separated data path. data paths are similar to accessing dictionaries, but arrays are also accessed with a period. Examples include "twitch.id", "economy.iu" and "economy.icons.0". `rankby` is a special keyword that generates an index based on the target path.
        where: Path, Path = Value, Path > Number, ... // Comma-separated list of conditions. Conditions can be just Path for "Path is Not Null", Path [operator] value where operators can be `=`, `!=`, `<`, `>`, `<=` and `=>`.
        orderby: Path, // orders the list based on this path.
        desc: bool, // whether to order in reverse order.
        count: int, // max number of entries to show. by default fetches all.
      }
      ```
    - Example Output for `api/user?select=rankby:economy.iu,twitch.name,twitch.id,economy.iu&where=economy.iu>0&orderby=economy.iu&desc=true`
      ```json
      [{
        rank: { "economy.iu": int },
        twitch: { id: int, name: String },
        economy: { iu: float }
      }, ...]
      ```

&nbsp;&nbsp;On top of the API, raw database is also available via `prod.kr/data` via a symlink. Your user data is saved as `prod.kr/data/user/[Twitch ID].wasd`, and any custom guy image can be viewed at `prod.kr/data/shimeji/[Twitch Name].3x2.png`. There are more that can be fetched if you know where the save paths are. You can use `!takeout` to get a path of your user data.

<br>

*T\_\_n \_\_ d\_  . a\_\_\_\_\_.*

\> [Forfeit your memories](#inferno-4)  
\> C[h\_\_ \_](./prodzpod.md) \_   [t \_](./prodzpod.md) d..  
\> [Succumb to the darkness](#-prodzpod)  

## Choronzon 
 󠀠  󠀠/\\ 󠀠/\\ 󠀠  󠀠  󠀠  󠀠 /\\  󠀠/\\ 󠀠  󠀠  󠀠  󠀠 /\\ 󠀠 /\\  
/ 󠀠 /\\ 󠀠  󠀠\\ 󠀠  󠀠 / 󠀠  󠀠/\\ 󠀠  󠀠\\ 󠀠  󠀠 / 󠀠 /\\ 󠀠  󠀠\\  
  
/ 󠀠  󠀠  󠀠 \\ 󠀠  󠀠\\/ 󠀠  󠀠/ 󠀠  󠀠 \\ 󠀠  󠀠\\/ 󠀠 / 󠀠  󠀠 \\ 󠀠  󠀠  
 󠀠 󠀠  󠀠  󠀠  󠀠 \\/  󠀠\\/ 󠀠  󠀠  󠀠  󠀠 \\/  󠀠\\/ 󠀠  󠀠  󠀠  󠀠\\/ 󠀠  󠀠  
<br>
<br>
<br>
<br>
<br><i>:::</i>
<br><i>.'.</i>
<br><i>'''</i>
<br><i>'...</i>
<br><i>.'..</i>
<br><i>'''</i>
<br><i>'..'</i>
<br><i>'....</i>
<br><i>''...</i>
<br><i>'.'.</i>
<br><i>....</i>
<br><i>.'</i>
<br><i>.'..</i>
<br><i>.'..</i>
<br><i>.</i>
<br><i>'.</i>
<br><i>''.</i>
<br><i>.</i>
<br>
<br>
<br>
<br>

<br>

*-- are worms [bugs](https://bigbookofbug.com/misc/128)? science as no --*

\> [Descend Downwards](#inferno-4)  
\> [Succumb to the darkness](#-prodzpod) 

## Inferno ±4

=======/  󠀠  󠀠/// 󠀠 . 󠀠 .. 󠀠 ... 󠀠 .... 󠀠 ... 󠀠 .. 󠀠 . 󠀠 \\\\\\\\ 󠀠  󠀠 \\======  
 󠀠  󠀠  󠀠  󠀠  󠀠 /  󠀠 󠀠 / 󠀠 . 󠀠 .. 󠀠 ... 󠀠 .... 󠀠 ..... 󠀠 .... 󠀠 ... 󠀠 .. 󠀠 . 󠀠 \\  󠀠  󠀠\\  
*Your worldly figure separates and spins away with the rest.*  
 󠀠  󠀠  󠀠  󠀠   󠀠\\ 󠀠   󠀠 \\ 󠀠 . 󠀠 .. 󠀠 ... 󠀠 .... 󠀠 ..... 󠀠 .... 󠀠 ... 󠀠 .. 󠀠 . 󠀠 /  󠀠  󠀠/  
======\\  󠀠   \\\\\\\\ 󠀠 . 󠀠 .. 󠀠 ... 󠀠 .... 󠀠 ... 󠀠 .. 󠀠 . 󠀠 ///  󠀠  󠀠/======  
<br>
&nbsp;&nbsp;**BlessScript** is a programming language inspired by the [Bless](#beelzebub) project that allows you to run custom programs inside *the pod*. You can evaluate BlessScript at any time with `!bs [expression]`. BlessScript is modeled to behave like simplified JavaScript, with custom keywords for stream interaction.

### Types
```ebnf
digit = ? 0 ~ 9 ? ;
alpha = ? A ~ Z | a ~ z | "_" ? ;
letter = digit | alpha ;
any = ? any letter ? ;
(* Number type: kind of like JS number but simpler *)
Number = ["+" | "-"], ((digit, digit*, [".", digit*]) | (".", digit, digit*) | "Infinity") ;
(* String type *)
String = '"', (any - '"')*, '"' ;
(* Bool type *)
Bool = "true" | "false" ;
(* Null type (note the lack of `undefined`) *)
Null = "null" ;
(* List type *)
variable = alpha, letter* ;
Any = Number | String | Bool | Null | List | Dictionary | Function | variable;
List = "[]" | "[", Any, (",", Any)* , "]" ;
(* Dictionary type: keys must have quotes like JSON *)
kvpair = String, ":", Any;
Dictionary = "{}" | "{", kvpair, (",", kvpair)* , "}" ;
(* Function type: no `function` keyword like JS, lambdas only *)
param = "()" | variable | "(", variable, (",", variable)*, ")" ;
expression = ? line of BS code ? ;
expressions = (expression | "{", ";"*, "}" | "{", expression, (";", expression)*, [";"], "}") ;
Function = param, "=>", expressions ;
```
There are no official support for classes or `BigInt`.

### Basic Operation
- Basic Arithmetic: `+`, `-`, `*`, `/`. `Number ** Number` for exponentiation. `Number // Number` for integer division.
- Bitwise Operation: `&`, `|`, `^`, `<<` and `>>` is available. All bitwise operations are unsigned.
- Concatenation: `String + String` adds two strings together, and `String * Number` repeats the string.
- List Operation: Operators can be used on lists to manipulate it.
  - `List + Any`: Appends an element to a list.
  - `List | List`: Joins two lists together.
  - `Any in List`: Returns a bool that checks if an element is inside a list.
  - `List & List`: Returns an intersection of two lists.
  - `List ^ List`: Returns a "xor" of two lists.
  - `List - Any`: Removes an element from the list.
  - `List << Number`, `List >> Number`: Shifts the list left or right.
  - `List[Number]`, `Dictionary[String]`: Gets an element from a list or a dictionary.
  - `String / delimiter: String`: Splits a string into a list.
  - `List * String`: Joins a list into a string.
- `typeof Any`: Returns a string with its type name.
- `Any is type: String`: Returns a bool that checks if an element is of this type.
- `bool Any`, `number Any`, `string Any`, `list Any`, `dict Any`: Coerces a value into a type. Parses or stringifies it as necessary. When a dict is converted to a list, returns `Object.entries()` of it. Functions can only be coerced into a string.
- Boolean Operation: `==`, `!=`, `<`, `>`, `<=`, `=>` is given for comparison. No type conversion occurs outside of falsey values (`0` == `null` == `[]`). `&&`, `||` and `!` is given for combinations.
- Comment: `/* ... */` is given for comment. Note that `//` is not used for comment here.
- Variables can be declared without keywords (python style), and the first appearance of that variable determines its scope. (all variables are kind of like `let` basically)
- `=` is used for assignment, and can be combined with any arithmetic operators. (such as `**=` or `&&=`)
- You can declare curried functions (`a => b => a + b`).

### Flow Control
- `if`, `else`, `while`, `for`, ternary operator (`?`, `:`) and nullish coalesing operator (`??`) is supported.
- `continue`, `break` and `return` is supported.
```ebnf
(* Note the requirement for surrounding parens! *)
condition = "(", ? expression that resolves to Bool ?, ")" ;
(* if-statement can be an expression *)
if-statement = "if", condition, expressions, [else-statement] ;
else-statement = "else", expressions ;
(* while and for loop can be an expression *)
while-loop = "while", condition, expressions ;
for-loop = "for", "(", [variable, "=", Any], ";", [? expression that resolves to Bool ?], [expression], ")", expressions ;
```

### Stream Control
- `call String` or `call List`: Sends a chat message on your behalf. Calls commands if string or first element of the list starts with `!`. BlessScript command calls do not produce result replies unless `!!` is used instead of `!`.
- `query String Dictionary`: Sends an API query to prod.kr. String is its subdirectory, and dictionary is its input query parameter. (see `query "api/chat" {"count": 1}`)
- Every isolated BS call has a **fuel** of 5000. Fuel is an anti-infinite loop / chat spam system that decreases every function call, for/while loop (-1 fuel) or `call` / `query` statement (-1000 fuel). When fuel reaches 0 or below, the call immediately ends and an error message is generated as return value.

### Built-in Functions
- `min(...Number)`, `max(...Number)`: Returns the minimum/maximum value.
- `lerp(a: Number, b: Number, t: Number)`: Performs linear interpolation (`a + (b - a) * t`).
- `clamp(x: Number, a: Number, b: Number)`: Clamps the value between minimum and maximum value.
- `between(a: Number, b: Number, c: Number)`: Equivalent to `a <= b && b <= c`.
- `abs(Number)`: Returns an absolute value of the number.
- `sign(Number)`: Returns `1`, `0` or `-1` based on its sign.
- `PI` and `E`: Built-in constants for math variables.
- `sqrt(Number)`: Performs square root, equivalent to `Number ** 0.5`.
- `sin(Number)`, `cos(Number)`, `tan(Number)`, `atan2(y: Number, x: Number)`: Performs trigonometric functions.
- `log(Number)`, `log(Number, base: Number)`: Performs logarithm functions.
- `floor(Number)`, `round(Number)`, `trunc(Number)`, `round(Number)`: Performs rounding.
- `prec(Number, digits: Number = 6)`: Rounds number to a specific decimal digit.
- `toUpperCase(String)`, `toLowerCase(String)`, `trim(String)`: Equivalent to the functions with the same name in JS.
- `map(List, Function)`: Maps over a list. Function is `(current: Any, index: Number, array: List) => Any`.
- `filter(List, Function)`: Filters a list. Function is `(current: Any, index: Number, array: List) => Bool`.
- `reduce(List, Function, initial_value: Any = null)`: Reduces a list. Function is `(previous: Any, current: Any, index: Number, array: List) => Any`.
- `time()`: Returns the number of seconds since `2025/01/01`.
- `random(x: Number = 0, y: Number = 1)`: Returns a random value between x and y.
- `random(x: List)`: Returns a random element in that list.

### Hooking
&nbsp;&nbsp;You can submit BlessScript expressions as hooks on the [`!brain`](https://prod.kr/v/brain) site. Logging in screen style is required. At the top, you can choose the condition to hook on to.
- **Chat Starts With**: Called when a chat message is sent that starts with the condition text.
- **Chat Includes**: Called when a chat message is sent that contains the condition text.
- **Command Called**: Called when a command is executed by a non-BlessScript source. Condition text is the name of the command without `!`.
- **IPC Recieved**: Called when an internal IPC call is recieved. Condition text is text identifiable in `!reload` command. see [the repository](https://github.com/prodzpod/stream) for details.

&nbsp;&nbsp;When using chat or command hook (not IPC), you are given a set of variables that can be used for the function.
- `from: String`: The source of command or chat. Can be `"twitch"`, `"discord"`, `"screen"` and so on.
- `chatter: Dictionary`: Chatter data of the chat author / command caller equivalent to one that you get from `!takeout`.
- `message: Dictionary`: Message data describing message ID that corresponds to this message from each platform.
- `text: String`: Raw text that was sent.
- `emote: List`: List of emotes. Same format as `GET api/chat`.
- `reply: String | null`: Reply ID. Same format as `GET api/chat`.

### Custom guy AI
&nbsp;&nbsp;You can forgo the guy stats and manually program your own !guy AI using BlessScript. There are three conditions without condition text relevant to this process: `guy idle`, `guy attacked` and `guy peaced`. `guy idle` is called before any guy action is taken, and `guy attacked` and `guy peaced` is called whenever `!fight` or `!peace` is declared on you.

&nbsp;&nbsp;The function must return one of the actions below as a String. It is recommended you make a list and join it with spaces at the end.
- `idle Number`: Does nothing, and calls idle hook again after a delay in milliseconds.
- `move Number`: Move towards this x position in pixels (0 to 1920). when arrived, calls idle again.
- `jump Number Number`: Jump towards this position (x and y, in pixels). when landing, calls idle again.
- `kick Number Number`: Kick any window towards this position (x and y in pixels), and calls idle immediately.
- `war`: Declares war on every guy around you, and calls idle immediately.
- `peace`: Attempt to declare peace on all your enemies, and calls idle immediately.
- `attack`: Do a melee attack, and wait for time dependent on your attack speed.

&nbsp;&nbsp;Guy AI related hooks also provides built-in variables that pertains to your guy and the surroundings.
- `position`: `[x: Number, y: Number]`, current pixel position of the guy.
- `speed`: `[x: Number, y: Number]`, current pixel speed of the guy.
- `angle`: Number, current angle in degrees.
- `rotation`: Number, current angluar momentum in degrees.
- `grounded`: Bool, whether the guy is currently on ground.
- `hp`: Number, current hp value.
- `maxhp`: Number, current maxhp value.
- `attack`: Number, current attack value.
- `critchance`: Number, current critical chance value.
- `previousmovement`: String, name of the last guy hook fired.
- `incombat`: Bool, whether the guy has any hostile creatures.
- `hostilenearme`: Number, number of hostile creatures in the hitbox.
- `nearesthostile`: `[x: Number, y: Number] | null`, position of the nearest hostile creature.
- `guynearme`: Number, number of creatures in the hitbox.
- `nearestguy`: `[x: Number, y: Number] | null`, position of the nearest other guy.
- `windownearme`: Number, number of windows in the hitbox.
- `nearestwindow`: `[x: Number, y: Number] | null`, position of the nearest window.
- `ai`: Dictionary, your guy's current ai.
- `memory`: String, a maximum 2000 character string that carries over between hook calls if assigned. if non-string is passed, it gets stringified.

&nbsp;&nbsp;The default guy AI is secretly also written in BlessScript, and can be fetched and edited in the brain editor. Below is default guy AI for `guy idle`.
```js
kick = () => {
    x = position[0] + (sign(speed[0]) * 960 * ai["strength"]);
    y = position[1] + (540 * ai["bisonness"]);
    return "kick " + x + " " + y;
}

if (incombat) {
  if (hostilenearme > 0) return "attack";
  else if (windownearme > 0 && random() < ai["aggression"]) return kick();
  else {
    if (random() < ai["jumpness"]) return "jump " + (nearesthostile[0] * ai["camelness"]) + " " + (nearesthostile[1] * (1 - ai["jumpheight"] * random(ai["zebraness"], 1)));
    else return "move " + nearesthostile[0];
  }
}
else {
  if (random() < ai["dexterity"]) return "idle " + random(10, 1000 * ai["jokerness"]);
  else if (windownearme > 0 && random() < ai["aggression"]) return kick();
  else if (random() < ai["jumpness"]) return "jump " + (position[0] + random(-960, 960) * ai["camelness"]) + " " + (position[1] + random(-540, 540) * (1 - ai["jumpheight"] * random(ai["zebraness"], 1)));
  else return "move " + (position[0] + random(-960, 960) * ai["agility"]);
}
```
&nbsp;&nbsp;The default for `guy attacked` is `attack`, and the default for `guy peaced` is `peace`.

<br>

*It is done.*

\> [Forfeit your body and ascend](#the-astral-plane)  

## The Astral Plane
\> <a href="https://prod.kr/audio/20240731.ogg" target="blank_">Change Sound</a> (*manual loop via "right-click" required) 

 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠----  
 󠀠   󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠----------  
*You have ascended and became a changed being.*  
*Humanity will feel your presense, evershifting from the cave.*  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠 ----------  
 󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠  󠀠----  
<br>
&nbsp;&nbsp;As changes and additions happen to *the pod*, this document will also change with it. In reality, there is no way to truly know everything about *the pod* unless you actively catch up with [the streams](https://www.twitch.tv/prodzpod). We go live every monday at 3PM EST / 12PM PST, where we talk about what happened, and tries to make something new every week.

&nbsp;&nbsp;Especially, once [Startellers](https://prodzpod.itch.io/startellers) releases, there will be a hiatus period, and **Season 2** of *the pod* will begin. When that happens, I expect a large chunk of the document to become obsolete as we cut down on underused/outdatad gizmos in favor of new ones.

&nbsp;&nbsp;I hope you still found the document useful however. The list of projects I have done in and outside of the stream can be found in [the portfolio](https://prod.kr/folio).

<br>

### *Astral Sorcery*
- [Floor -1: Stream Interactions, !guy](#floor--1)
- [Mushroom Crag: Chungus Game, Lala Overlay](#annex-mushroom-crag)
- [Floor -2: The Screen, !volume](#floor--2)
- [Emerald Node: Green and TealCircle](#annex-emerald-node)
- [Floor -3: IU, !gift, Icons](#floor--3)
- [Firefly Lake: Yume Nikki Online Tour](#annex-firefly-lake)
- [Floor -4: Chat formatting, Emotes](#floor--4)
- [Floor -5: !song](#floor--5)
- [Emerald Heart: LCOLONQ & Clonkspotting](#annex-emerald-heart)
- [Inferno ±1: !guy Stats](#inferno-1)
- [Asmodeus: Witscord, Witsend](#asmodeus)
- [Inferno ±2: Abandoned Gizmos](#inferno-2)
- [Beelzebub: Abandoned LCOLONQ, Witscord, Tealcircle Gizmos](#beelzebub)
- [Inferno ±3: prod.kr API](#inferno-3)
- [Inferno ±4: BlessScript](#inferno-4)

\> [Start a new run](#-prodzpod)  