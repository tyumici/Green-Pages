# [🪭/📠] meisaka

## TABLE OF CONTENTS
- [Links](#links)
- [See Also](#see-also)
- [Commands](#commands)
    - [Information](#informational-suite)
    - [Assorted](#interaction-suite)
    - [Counters](#counter-suite)
    - [Wave2 VM](#wave2-suite)
    - [StreamElements specific](#streamelements-suite)
    - [for Moderators](#meisaka-moderation-suite)
- [Interactions](#interactions)
    - [Sadness](#sadness)
    - [Prisms](#prisms)
    - [Bad Apple Meisaka](#bad-apple-meisaka)
    - [Message Hex Colour](#message-hex-colour)
    - [Chatbox Style System](#chatbox-style-system)

## LINKS

- [Twitch](www.twitch.tv/meisaka)
- [GitHub](https://github.com/meisaka)
- [KoFi](https://ko-fi.com/meisaka)
- [YouTube](https://www.youtube.com/@meisakayukara8058)
- [Discord](https://discord.gg/AJaZrCY9aQ)
- [Wave 2 VM Docs](https://raw.githubusercontent.com/Meisaka/MeiVM2/refs/heads/main/vm.txt)

## SEE ALSO

 - [NichePenguin](./nichepenguin.md)
 - [Tyumici](./tyumici.md)

## COMMANDS

Commands listed here are currently only available on the Meisaka twitch channel

Prefix: **!**

### Informational Suite

- !youtube / !yt
- !discord
- !github
- !greg
    - [Gregtech server info](https://gregtech.ell.dev/) hosted by [@ellg](https://twitch.tv/ellg)
- !factorio
    - information about factorio, when relavent
- !etheria
    - blurb about meisaka's ancient (maybe shelved) MMO project
- !fei
    - blurb about one of meisaka's custom programming languages
- !ffxiv
    - Info about Meisaka's FFXIV character
- !house
    - Info about Meisaka's FFXIV house
- !font / !fonts
    - What fonts used on stream
- !commands / !help
    - get a [link to the documentation](https://github.com/tyumici/Green-Pages/blob/wiki/pages/meisaka.md)
    - also displays the NightBot command list
- !theme / !colourscheme / !colorscheme
    - show the active neovim theme. (it's melange btw)
- !version
    - Query the current meisaka versions.
- !project / !projects
    - Complain about too many projects
- !rust - 🦀btw
- !cake - Cake is delicious!

### Interaction Suite

#### !uptime

Current stream runtime

> Provided via NightBot

#### !localtime / !time

Display a timestamp in meisaka local time, whatever that means

> Provided via NightBot

#### !weather

Uses a 3rd party service to lookup and display weather for a location

Requires a parameter:
- *US City*
    - Fuzzy find by city name
- *City*, *US State*
    - Fuzzy find by city name and state
- *City*, *Country*
    - Fuzzy find by city name and country
- *US Postal Code*
    - Zip 5 of a location

> Provided via NightBot

#### !ping

Respond with a `PONG`

#### !song / !music / !playing / !nowplaying

Display information from VLC about the current song.

- artist and/or title, or file name
- usually includes a link

#### !today

> Rarely set correctly.

#### !meisaka

Display a random meisaka quote.

#### !tts

Abuse pipertts (but really... please don't)

Parameter:
- message to read

#### !error / !logon

> Available to active twitch subscribers on the meisaka channel

play Windows XP themed sound effects

#### !forgotusername (meme command)

> This command is a meme, do not actually provide information to it

#### !age / !accountage / !accage / !created

Displays when the user's twitch account was created

#### !followage / !howlong / !followsince / !followfor

Displays how long have you been following meisaka

#### !chibi / !css / !light / !woah / !eepy

Change the Chibi model

> Changes apply even if the Chibi is not visible on stream

### Counters Suite

#### !nom / !crunch / !crumch / !cromch / !cronch

Increment and display the crunch counter
All commands use the same counter with different flavour text

- Use when meisaka crunches on a snack

#### !ohmygah

Increment and display the "oh my gah" count, along with a sound effect

- matches regex `^!ohmyga+h` so additional `a` can be stacked on to it.

#### !sip / !slurp

Increment and display the number of meisaka slurps

- Use when meisaka has audibly slurped a drink

#### !sneeze

Increment and display the number of meisaka sneezes.

- Use if meisaka sneezes for best results.

#### !yawn

Increment and display the number of meisaka yawns.

- Use whenever meisaka happens to yawn


### Wave2 Suite

#### !guy / !littleguy / !summon

meme / alias for "vm summon" with reply

#### !vm

Wave 2 virtual machine commands

> Meisaka Wave2 Vector RISC CPU
> An emulated multi-user environment and physics simulation.
> Providing every user their own emulated "CPU" with multiple 16 bit SIMD cores

This is an emulated CPU that controls an on stream "spaceship",
each ship is rendered as a coloured triangle.
All VMs also have access to a shared 256x32 RGB565 pixel buffer that is rendered on stream

`!vm` is a prefix for interacting with the Wave 2 VM and overlay

- !vm help
    - get a link to [the Wave 2 specification and help document](https://github.com/Meisaka/MeiVM2/blob/main/vm.txt)
- !vm summon
    - cause the ship to appear if it has not, and resets it to match your twitch chat colour
- !vm color / !vm colour
    - requires a parameter: CSS colour name or 6 digit CSS hash colour
- !vm ident
    - put a box around your ship to make easier to find
- other !vm commands control the CPU, or provide code and data to upload

> All valid !vm commands will summon a ship if it does not exist

#### !ident

Alias for `!vm ident`

#### !dump

Alias for `!vm dump` a debugging command that is usually not visible


### StreamElements Suite

#### !quote

Display random or manage quotes

> StreamElements quotes module, see the SE docs

Parameter:
    - add `text`
    - remove `quote number`

#### !queue

> StreamElements queue management, see the SE docs

Parameter:
- close|open
- pause|unpause
- remove|pick|position
- join
- list


### Meisaka Moderation Suite

#### !update-7tv / !update-ffz / !update-bttv

run after changes to emotes in the respective servie to update the overlay cache

#### !settoday

set the text displayed by the `!today` command

Parameter:
- text to set and display

#### !repeat / !continue / !nextsong / !prevsong

music playback controls

#### !docs / !documentation

get a link StreamElements docs (also sends the stream !help link)

#### !bot

control the StreamElements bot

Requires parameter:
- mute | unmute | part

#### !setgame / !settitle

change the game/category or stream title

#### !permit

StreamElements will say a user is permitted

> StreamElements moderation is not used, so this is not too useful ;))))))

## INTERACTIONS

### (text match) wafers / TSMC

Change the Chibi model if either word occurs in a message

### (text match) CSS / \<space\>css

Displays 3x meisakCSS emote if CSS appears in a message

### Sadness

Plays a sound effect and changes the active Chibi model to "sadness"

### Prisms

These hue-shift (aka change the colour) of Meisaka

- Each prism lasts 3 minutes

> Effects are all stackable

### Bad Apple Meisaka

Switches Meisaka's model into a silhouette that displays video

- by default the video is a stackup of Bad Apple and Project HAL
- select songs in the media player have video that can display instead.

### Message Hex Colour

Any chat messages containing/matching
- `#hhh`  - short RGB
- `#hhhh` - short RGBA
- `#hhhhhh` - long RGB
- `#hhhhhhhh` - long RGBA
where `h` is any hexadecimal nibble, are translated into CSS hex colour codes
this sets the background colour of the matching text,
and any text connected to the matching text via non-space (`&sp;`) characters
when displayed on the in-stream overlay.

### FrankerFaceZ and BetterTTV emote transforms and effects

- messages prefixed with BTTV emote modifiers
- messages suffixed with FFZ emote modifiers
- FFZ subwoofer status is respected and grants a few extra FFZ modifiers

Applies the effects to the related emote
most effects and stacking emotes are supported

### FFZ / BTTV / 7tv Emotes

These provide 3rd party emotes and are all displayed by the on-stream chatbox

### Chatbox Style System

Every user can have a font style or CSS text transform connected to their twitch user ID
these style tags can change:

- Font Family
    - meisaka can add these by special request
    - compatible fonts must be TTF, OTF, WOFF
    - only vector/outline fonts are supported
- Text transforms (i.e. ALL UPPERCASE)
- message Text colour
- other CSS/web effects

