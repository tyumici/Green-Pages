# [💚/💜] nichePenguin

[Home](../README.md)
- [\[💚/💜\] nichePenguin](#-nichePenguin)
    - [LINKS](#links)
    - [COMMANDS](#commands)
        - [Cards, Swords and Needles suite](#cards-swords-and-needles-suite)
            - [!draw](#draw)
            - [!armory](#armory)
            - [!needle](#needle)
        - [Misc Commands](#misc-commands)
            - [!sbob-ad](#sbob-ad)
            - [!rice](#rice)
            - [!voidstranger](#voidstranger)
            - [!ping](#ping)
        - [Non-Commands](#non-commands)
            - [hmmm](#hmmm)
            - [mmmm](#mmmm)
    - [INTERACTIONS](#interactions)

## LINKS

[Webring](https://pub.colonq.computer/~nichepenguin/)

[GitHub](https://github.com/nichePenguin)

## COMMANDS

Available in channels: [bigbookofbug](https://www.twitch.tv/bigbookofbug), [BrighterMalphon](https://www.twitch.tv/brightermalphon), [KinskyUnplugged](https://www.twitch.tv/kinskyunplugged), [lala_amanita](https://www.twitch.tv/lala_amanita), [LCOLONQ](https://www.twitch.tv/lcolonq), [Meisaka](https://www.twitch.tv/meisaka), [MyriadMinds](https://www.twitch.tv/myriadminds), [nichePenguin](https://www.twitch.tv/nichePenguin), [PippinFool](https://www.twitch.tv/pippinfool), [prodzpod](https://www.twitch.tv/prodzpod), [SaladForrest](https://www.twitch.tv/saladforrest), [Tyumici](https://www.twitch.tv/tyumici),

<hr>

### Cards, Swords and Needles suite

<hr>

#### !draw

Draws a random tarot card (uniformly) or sword. Chances are as follows:
| Outcome  | Probability % |
| -------- | ------------- |
| Upright  | 81.32%        |
| Reversed | 5.79%         |
| Sword    | 12.89%        |

If sword is drawn, its quality is rolled:
| Quality         | Conditional % | Overall %   |
| --------------- | ------------- | ----------- |
| `Common`        | 40.00%        | **5.156%**  |
| `-WellCrafted-` | 25.00%        | **3.2225%** |
| `+Fine+`        | 15.00%        | **1.9335%** |
| `*Superior*`    | 10.00%        | **1.289%**  |
| `≡Exceptional≡` | 6.00%         | **0.7734%** |
| `☼Masterful☼`   | 3.00%         | **0.3867%** |
| *`Artifact`*    | 1.00%         | **0.1289%** |

Presence of handle decorations is determined after the quality:
| Quality      | Conditional % |
| --------     | ------------- |
| `Common`     | 0.00%         |
| *`Artifact`* | 100.00%       |
| Other        | 49.61%        |

All materials (handle decorum and main material of the sword), as well as the sword type are rolled uniformly, with following exceptions:
- Sword of type `needle` is never rolled and is instead obtained by [!needle](#needle) command. Needles are considered to always have a handle decoration of the same material as the needle.
- Sword of type `tooth` is never rolled and is instead obtained by unknown means of beating enough bandits and claiming the spoils. Material and quality of `tooth` are determined by the presence and skill level of the closest dentist in the town closest to debauchery occurred (calculated with consideration to both dentist office position and the approach vector).
- Material `lost rosewood` is no longer obtainable, as it was bestowed upon the portion of the ancient swords (swords drawn before the beginning of times) which had regular wood in their composition.

Moreover, *`artifact`* swords are guaranteed (unless cache failed to load) to be unique in composition - their material, type, and handle decorations, as well as the name bestowed in both [Elven](https://dwarffortresswiki.org/index.php/Elven_language) and [English](https://en.wikipedia.org/wiki/English_language) languages.

#### !armory

***Optional Parameters:*** sword_id

Displays a random sword from your armory or one specified by the `sword_id` parameter, which can be prefixed with '#'

#### !needle

***Aliases:*** !haystack

Rolls for a chance to find a needle in a haystack, which is roughly 1.95% percent of the times. It is then added to your [!armory](#armory)

<hr>

### Misc Commands

<hr>

#### !sbob-ad

Prints the current advertisement for the [Small Book Of Bug](https://pub.colonq.computer/~nichepenguin/kno/sbob.html), where you can look at various bugs, as well as submit your own!


#### !rice

Prints the current status of rice (it is always burned to charcoal)

#### !voidstranger
***Warning:*** excluded from LCOLONQ channel, as he has his own !voidstranger command

Prints the link to the game Void Stranger on steam


#### !ping

Prints a "pong" message, followed by anything that was prepended to the "!ping" command

<hr>

### Non-Commands

Are executed if the message starts with string provided

<hr>

#### hmmm

Displays ![limesHmm](https://static-cdn.jtvnw.net/emoticons/v2/305153339/default/dark/3.0) emote


#### mmmm

Displays a ![meisakNoM](https://static-cdn.jtvnw.net/emoticons/v2/emotesv2_1f8aeae7b9c24ea7a731a3fecdb0fd94/default/dark/2.0) emote

## INTERACTIONS

Swords (as well as needles and teeth) can be fetched with the following api, which is currently dead slow and might require some retries (especially on timeouts and bad gateways)

Base url: https://pub.colonq.computer/~nichepenguin/cgi-bin/

### GET /armory?id=*sword_id*

Returns a json representation of a sword with id = *sword_id*

### GET /armory?name=*twitch_username*

Returns a json array with swords that *twitch_username* owns, empty array if not found.


