---
layout: guide
disabled: false
title: All-Out Guide to Relic/Data Exploration
shorttitle: Exploration (Relic/Data)
author: Mussah Yacoub
excerpt: >
  In-depth coverage of how to make money off relic and data sites in dangerous space as a young character.  You don't have to risk much, you learn a lot in the process, and the money is very good compared to most other new-player friendly professions.
---

## <a name="introduction"></a>Introduction

It's possible for a newbro to make excellent money by exploring nullsec and wormhole space, and if you know what you are doing you don't have to risk very much.  Hopefully this guide helps you know what you are doing a little better.

Exploration's not without some drawbacks - some people find it boring, others find it too risky.  Others run into bad RNG and give up before they see good payouts.  All I can say is, I'm very happy with the return I get out of it.  At least the ships used are cheap and there are no rats to deal with, only players.  And learning to deal with players is really the only tricky part, and what you learn here applies everywhere else in the game.

As for how much money you can expect to get from exploring, it's hard to pin down for sure because it's fairly RNG as well as dependent on the persistance of the player.  But here are some data points:  I funded 200m seed capital for my market character with it easily, and later a starter incursion battleship (~650m).  A few days ago I pulled 120m from a single wormhole site (26 Intact Armor Plates lol).  I know at least one person who has gotten 600m before their character was 7 days old, and at least two people who have PLEX'ed their trial accounts with exploration (in the 1b+ PLEX price days).

## Overview

- [Introduction](#introduction)
- [Choosing Your Ship](#choosingship)
- [Exploration in Different Kinds of Space](#exploration)
  - [High Security](#hisec)
  - [Low Security](#lowsec)
  - [Null Security](#nullsec)
  - [Wormhole Space](#wspace)
- [Flying Tips](#flying)
  - [Finding Your Way Around](#way)
    - [Null Security](#nullsecnav)
    - [Wormhole Space](#wspacenav)
- [The Different Kinds of Sites](#sites)
  - [General Relic Sites](#relics)
  - [General Data Sites](#data)
  - [Wormhole Sites](#wormholesites)
  - [Rogue Drone Sites](#dronesites)
- [Fitting Your Ship](#fitting)
  - [High Slots](#highs)
  - [Mid Slots](#mids)
  - [Low Slots](#lows)
  - [Rig Slots](#rigs)
- [Recommended Ship Fits](#recommended)
  - [T1 Exploration Frigs](#t1fits)
    - [Amarr - Magnate](#magnate)
    - [Caldari - Heron](#heron)
    - [Gallente - Imicus](#imicus)
    - [Minmatar - Probe](#probe)
  - [T2 Covert Ops Frigs](#t2fits)
    - [Amarr - Anathema](#anathema)
    - [Caldari - Buzzard](#buzzard)
    - [Gallente - Helios](#helios)
    - [Minmatar - Cheetah](#cheetah)


## <a name="choosingship"></a>Choosing Your Ship

There are

- Four t1 exploration frigates (one for each race) that you can fly in under a day and fit a basic cloak to in about a week that cost about 2m-4m fully fitted. (**Magnate**, **Heron**, **Imicus**, **Probe**.)
- Four covert ops frigates with excellent exploration bonuses and capabilities (one for each race) that take two to three weeks to train and cost about 22m-30m fully fitted, depending on bling. (**Anathema**, **Buzzard**, **Helios**, **Cheetah**.)
- A pirate frigate that takes two or three days to fly and a week and a half or so to fit a covert cloak, with better exploration bonuses than the covert ops frigs that costs about 70m-75m fully fitted. (**Astero**.)

The 8 racial exploration frigates have the same bonuses within their classes and only differ in their slot layouts:

- Caldari t1 **Heron** and t2 **Buzzard** both have the most midslots (five) but the fewest lowslots (two).
- Gallente t1 **Imicus** has a normal four mids, but the t2 **Helios** has five mids like Caldari and the fewest highslots (two).
- Amarr t1 **Magnate** has the most lowslots (four) but t2 **Anathema** has a normal three.
- Minmatar t1 **Probe** and t2 **Cheetah** have a dead average three high, four mid, three low.

If you don't have any race's frigate trained to V yet and are going to be doing a lot of exploring (or scanning in general), I'd recommend using the Caldari **Heron** and later on the **Buzzard**.  They have extra mids to fit scan bonus mods in order to scan faster.  This also applies to the Gallente t2 **Helios**, but you have to train while using the Gallente t1 **Imicus** which doesn't have that mid.

Later on in this guide there's more information about [Fitting Your Ship](#fitting) as well as [Recommended Fits](#recommended) for each of these hulls.


## <a name="exploration"></a>Exploration in Different Kinds of Space

<a name="hisec"></a>High Security
: The cans are very low value.  The competition to find sites is fierce, because hisec is full of explorers who are afraid to leave it and are fighting to make a living with the available resources.  At least you won't get shot.

<a name="lowsec"></a>Low Security
: The cans are medium value.  The competition is less, but the danger is very high because losec is full of people who are actively looking for kills.  At least you won't have to worry about bubbles so **Warp Core Stabilizers** are a big help.  There will almost always be people in local, which, in known space, is always more dangerous than if there are no people in local (which is not uncommon in nullsec).

<a name="nullsec"></a>Null Security
: The cans are great value.  The competition is usually low because nullsec is HUGE, the population is comparatively tiny and most explorers are afraid to go there.  Ironically, it's safer than losec because there are less people around.  You have to watch out for bubbles, though.  Each region in nullsec has a specific pirate faction (you can see that information here: [Dotlan Region Details](http://evemaps.dotlan.net/region)) and all the exploration sites in a given region will belong to that faction.  Sansha sites have the best loot by a significant margin (intact armor plates ftw) but because of this Sansha regions probably the most dangerous regions for explorers (explorer hunters know the area is attractive and will look for kills there).  Drone regions have no relic sites, only data sites (more on this later in the section on [Rogue Drone Sites](#dronesites)).

<a name="wspace"></a>Wormhole Space
: The cans are the same as nullsec cans (in value).  The competition is the very lowest, because every wormhole has the same chance to be visited (some null areas are easier to get to than others and so sites that spawn in those places are more likely to be taken before you arrive).  The danger is about the same as nullsec; it's harder to see people coming because people don't show up in local until they say something, but the population is even lower than null so you're less likely to run into people.  This might make no sense to you if you've never messed with wormholes, but because of the way wormholes connections work, it's easier to get away because you might have a chain of wormholes already scanned that your pursuer hasn't mapped.  Once you get into that chain, he can't follow you without spending time scanning each signature.  The flip side is you spend MUCH MUCH more time scanning in wormhole space compared to nullsec, because you need to scan every "gate" (wormhole) and because there is a buildup of gas sites everywhere because the population is so low and people who live in wormholes don't often clear gas sites - so you spend a lot of time scanning sigs that turn out to be not things you're interested in. 

## <a name="flying"></a>Flying Tips

- Learn to make secure safe spot bookmarks and use them frequently.  Eve University has an excellent guide about [safe spots and how to make them](http://wiki.eveuniversity.org/Safe_Spot).
- Map your directional scanner (dscan) refresh button to a hotkey.
- In wormholes, you should be refreshing dscan at LEAST twice a minute and preferably about every 5 seconds during all the time you are uncloaked.  This is not exaggerating.
- Set up a preset for your dscan that displays only ships and force fields so you can easily see if a system is occupied.
  - Overview/dscan customization is another topic but still - my preferred method is the [Eve Online Overview Generator](https://io.evansosenko.com/eve-overview/).
  - Another option is the wildly popular SaraShawa Overview; join the in-game channel `SaraShawa-Overview` for more information about that.
- Always cloak (if flying a t1, preferably in a safe spot) while scanning to avoid getting combat probed.
- If you have no cloak and **Combat Scanner Probes** appear on dscan, you need to gtfo.  As long as you are in a safe spot, **Core Scanner Probes** cannot find you.
- If you are in a site and probes of *any* kind appear on dscan, mash dscan more often and watch your overview in case dscan-immune ships start warping in.
- Avoid hacking sites while there are people in local (or on dscan) until you have more experience.
- If there are ships on dscan and you want to run a site anyway, it's pretty safe to set your dscan to 1-2 AU and keep mashing it as usual.  You'll see arriving ships in time for you to enter warp and escape.

### <a name="way"></a>Finding Your Way Around

<a name="nullsecnav"></a>Nullsec
: - Start the [Dotlan Radar Map](http://evemaps.dotlan.net/radar) in the ingame browser and then open the "following map" link out of game.  It'll track where you've been for you, so you can avoid backtracking over the same systems by accident.
  - Color the map by jumps or kills to find quiet areas to check out.  Keep in mind that dead-end systems are popular ratting systems.
  - One of the big drawbacks of exploring in nullsec is getting there and back without dying to a camp on the way.  You can avoid this by using wormholes.
    - You can scan a wormhole from hisec and just follow your nose scanning more holes until you find a one that puts you in nullsec somewhere.
    - Alternatively use [https://www.eve-scout.com/](https://www.eve-scout.com/) to find a connection to Thera near you, go scan it and jump through, and then find a Thera-nullsec connection near where you want to go, and scan it and jump through to it.
    - It's rare to find a "camped" or a bubbled wormhole (aside from Thera connections lol) because holes don't last more than a day.  If you do find people or a bubble on a hole, it's either because they were hunting someone just before you or they know you are coming and are waiting specifically to kill you.  It's not something people do "just because".

<a name="wspacenav"></a>Wormhole Space
: If you are solo, use [tripwire.eve-apps.com](tripwire.eve-apps.com) to map your wormhole chains.  It's free.  Make an account (needs an API key with exactly two things checked; no need to worry that it's snooping on you).  Keep the site open and logged in in the ingame browser to map the wormholes you jump through, paste signatures into it as you scan and NEVER FORGET TO BOOKMARK BOTH SIDES OF A WORMHOLE.  There's a bit of a learning curve, but it's well worth it compared to just trying to remember what your chain looks like.  (If you join All-Out, we have a mapping tool with several more features we'll teach you how to use.  It's not recommended here because it's invite-only and not free.)

## <a name="sites"></a>The Different Kinds of Sites

<a name="relics"></a>General Relic Sites
: - These usually have payouts in the tens of millions (bad luck is a couple mil, good luck is 20m, really good luck is 50m+) and their loot is very small volume-wise.
  - If you only were going to hack one kind of site, most people would choose relics.

<a name="data"></a>General Data Sites - NOTE: needs updating as of Frostline expansion (Data site buffs)
: - These usually have payouts of around 5m, and their loot is bulkier than relic loot.
  - Many people don't bother hacking data sites, and even remove data analyzers from their ships in order to fit more scanning upgrades.  However, data sites can contain BPCs for faction items.  Most are worthless, but some of them are very valuable.  The classic example is the BPC for the True Sansha Control Tower, which people tell me can be sold for a billion ISK.  I've never found a really good blueprint personally, but I think it's worth the shot and I hack all data sites I find.

<a name="wormholesites"></a>Wormhole Sites
: - There are *two kinds* of relic and data sites in wormholes: (**Important! Newbros keep getting this wrong!**)
    - **Pirate sites** contain nothing hostile at all.  Pirate site names always contain the name of one of the New Eden pirate factions.  A site named "Blood Raider Crystal Quarry" is safe to enter.  These are the pirate faction names you will see:
      - Angel Cartel
      - Blood Raider
      - Guristas
      - Sansha
      - Serpentis  
    - **Sleeper sites** contain have rats that will instantly destroy an exploration frig.  A site called "Unsecured Frontier Relay" has no pirate name in it, so it's a sleeper site and will kill you (even though it's called "Unsecured").
  - Pirate sites *only spawn* in C1, C2, and C3 class wormholes.  All exploration sites in C4, C5, and C6 holes will be sleeper sites.
    - There is one exception to this!  "Shattered" wormholes (you can tell these because all the planets will be "shattered" planets) can have pirate sites regardless of their class.
  - The sites in wormholes belong to random pirate factions - you are as likely to find a Sansha site as a Serpentis site in a given hole, etc.  This means that your average return from wormholes will be greater than if you were exploring a non-Sansha null region, but less than if you were exploring a Sansha null region.

<a name="dronesites"></a>Rogue Drone Sites
: - The drone regions in null have no relic sites at all, and their data sites are the only place where you can get 'Integrated' and 'Augmented' drone BPCs (worth a few mil and hundreds of mil, respectively).
  - Rogue Drone sites don't spawn in wormholes.
  - They aren't like other sites.  Most of the ones I've found (though I haven't explored a lot in drone space) will look like this:  There will be three cans, two thin and one fat.  The two thin cans will be fairly easy to hack, and usually hold drone poop of various kinds and BPCs.  The fat can is usually empty, and is very hard to hack.  If you fail it (can't remember if it's once or twice), two or three drone frigates spawn and attack you.  They are very very weak, though and they don't point you. The drones on a Heron can kill them.  I've heard that successfully hacking the hard can gives a rare chance of getting an escalation (drone data sites are the only relic/data sites that can escalate) but I haven't been able to figure out what the escalation does or how to reliably trigger it.  More research is needed.

## <a name="fitting"></a>Fitting Your Ship

### <a name="highs"></a>High Slots

Core Probe Launcher I
: This takes a set of 8x **Core Scanner Probe I**.  Once you're not losing ships all the time, upgrade to using **Sisters Core Scanner Probes**.  Once you're totally comfortable in dangerous space, you might upgrade to a **Sisters Core Probe Launcher**.  Training into a **Core Probe Launcher II** isn't something a lot of people do on their main accounts.

Prototype Cloaking Device I
: Note: This cannot be trained on a trial account.  However, this is invaluable on a t1 explo frig and should be trained ASAP (though you can explore without it while it's training).  For a covops-capable frig, you *need* a **Covert Ops Cloaking Device II** (this one is not optional).  While cloaked you can scan if your probes are out, but you can't activate any of your modules (prop mod, hacking mods, etc.)  You can't warp with an activated t1 cloak, but you can with an activated covops cloak.  Warping cloaked massively cuts down on the risks you need to take.  It's great.

Salvager I
: Most of the exploration frigs have a free high slot that you can do whatever you want with.  I usually put a salvager in it and salvage wrecks I find on gates and elsewhere (this is completely legal as far as CONCORD is concerned).  The other common high slot mods - guns and neuts - are not usually useful to exploration frigs.

### <a name="mids"></a>Mid Slots:

5MN Microwarpdrive
: Data sites are 50km across; if you don't have a MWD it means you're vulnerable at the site longer while you burn between cans.  Which one doesn't matter too much; I recommend one of the meta versions.  Pick on based on your skills, available fitting, and cost.  For reference: **Compact** uses the least fitting space, **Enduring** uses the least cap per cycle and **Restrained** has the least impact on your total cap capacity.  t1 is fine if money is tight.  t2 is terrible, never use it.

Relic Analyzer I and/or Data Analyzer I
: Of course you need these to do the actual hacking of the site.  The t2 versions of these are quite good, but take a bit under a month to train each, so don't worry about them at this point.

Cargo Scanner I
: Scan cans before hacking them and paste their contents in [http://evepraisal.com/](http://evepraisal.com/) to see if they're worth hacking.  Personally, I don't hack anything under 500k in value; your threshold will depend on how much you need cash.  If you don't want to hack a can, be nice and blow the can up by activating the analyzer on it and closing the window twice.  Leaving any unhacked cans means the site will remain active for a couple of hours after you leave, reducing the chance of more sites spawning in that system and disappointing other explorers who find it.

If you have any more open mids
: Fit any of these: **Scan Acquisition Array I**, **Scan Pinpointing Array I**, or **Scan Rangefinding Array I**.  They will make scanning less painful if you have low skills.  Keep in mind that the **Scan Rangefinding Array** has stacking penalties with the **Gravity Capacitor** rigs discussed in the rigs section.

### <a name="lows"></a>Low Slots

There are three commonly used mods to fill lowslots, and because none of them are *essential* people will argue all day about which are the best choices.  I'll try to break down what cases might best serve each one:

Warp Core Stabilizer I
: These give you +1 warp core strength each, of course, but increase the time it takes you to lock things and decrease the distance from which you can lock things.  I DON'T LIKE THESE.  Stabs are most useful in hisec/losec because they only work on targeted points and scrams - they don't work on bubbles, and bubbles aren't allowed in hisec/losec.  But you shouldn't be exploring in hisec/losec because the payout is terrible! You should be in nullsec/wormhole space where the money is good - and in nullsec/wh, bubbles are allowed and stabs are useless.  You might use stabs on a **Magnate** because it has 4 lows and if you fill them all with stabs hardly anyone without a bubble can catch you, but many explorer hunters fit enough points to catch the other frigs with only 3 lows.  Note: **Warp Core Stabilizer II**s simply have slightly lower locking time and range penalties.

Inertial Stabilizers II
: These make your ship turn and align quite fast (more than **Nanofibers**, below) - but make your signature bigger (making you easier to lock and shoot).  I THINK THESE ARE DECENT.  Exploration ships are good at running and bad at fighting.  You should notice when someone is approaching you (you're refreshing dscan, right?) and enter warp ASAP, and these help with that. But, unless you can "instawarp" - align in under 2.0 seconds - istabs bloom your signature a lot and make you easier to lock.  **Asteros** can instawarp with enough istabs, and I'm totally down with putting istabs on Asteros.  But I don't think any of the covops ships can, so I don't usually put istabs on them.

Nanofiber Internal Structure II
: These make your ship burn, turn, and align all a bit quicker - but weaken your structure HP.  I LIKE THESE A LOT.  It's a good tradeoff - you can use them to align and warp fairly fast, but they also help you get around inside a site faster which means you're vulnerable for a shorter time.  If you're taking structure damage in an exploration frigate, you're probably dead already.

### <a name="rigs"></a>Rig Slots

Small Gravity Capacitor Upgrade I
:  These reduce the time needed for you to scan a site down.  I usually use two of these.  Turns out this is a better scanning bonus than one of the t2 version of the rig (and there isn't enough calibration to fit two t2 Gravity rigs).

Small Emission Scope Sharpener I
: These increase the strength of your relic hacking.

Small Memetic Algorithm Bank I
: These increase the strength of your data hacking.

Deciding what combination of rigs you want to use comes down to which you hate more: the time you spend scanning or the feeling of failing a can worth 50m or more.

## <a name="recommended"></a>Recommended Exploration Fits:

(Here be nanofibers.)

### <a name="t1fits"></a>Tech 1 Racial Exploration Frigates

These all cost around 2m-3m at Jita prices and require minimal training.

#### <a name="magnate"></a>Amarr (Magnate)

~~~
[Magnate, T1 Explo Magnate]

Nanofiber Internal Structure I
Nanofiber Internal Structure I
Nanofiber Internal Structure I
Nanofiber Internal Structure I

5MN Quad LiF Restrained Microwarpdrive
Relic Analyzer I
Data Analyzer I

Prototype Cloaking Device I
Core Probe Launcher I, Core Scanner Probe I
[Empty High slot]

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
[Empty Rig slot]
~~~

#### <a name="heron"></a>Caldari (Heron)

~~~
[Heron, T1 Explo Heron]

Nanofiber Internal Structure I
Nanofiber Internal Structure I

5MN Quad LiF Restrained Microwarpdrive
Relic Analyzer I
Data Analyzer I
Scan Rangefinding Array I
Scan Acquisition Array I

Prototype Cloaking Device I
Core Probe Launcher I, Core Scanner Probe I
Salvager I

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
[Empty Rig slot]
~~~

#### <a name="imicus"></a>Gallente (Imicus)

~~~
[Imicus, T1 Explo Imicus]

Nanofiber Internal Structure I
Nanofiber Internal Structure I
Nanofiber Internal Structure I

5MN Y-T8 Compact Microwarpdrive
Data Analyzer I
Relic Analyzer I
Cargo Scanner I

Prototype Cloaking Device I
Core Probe Launcher I, Core Scanner Probe I
Salvager I

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
[Empty Rig slot]
~~~

#### <a name="probe"></a>Minmatar (Probe)

~~~
[Probe, T1 Explo Probe]

Nanofiber Internal Structure I
Nanofiber Internal Structure I
Nanofiber Internal Structure I

5MN Cold-Gas Enduring Microwarpdrive
Relic Analyzer I
Data Analyzer I
Cargo Scanner I

Prototype Cloaking Device I
Core Probe Launcher I, Core Scanner Probe I
Salvager I

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
[Empty Rig slot]
~~~

### <a name="t2fits"></a>Tech 2 Racial Covert Ops Frigates

These all cost around 22m-25m Jita prices.  You need to train Racial Frigate Level V and Covert Ops Level I.

#### <a name="anathema"></a>Amarr (Anathema)

~~~
[Anathema, T2 Explo Anathema]

Nanofiber Internal Structure II
Nanofiber Internal Structure II
Nanofiber Internal Structure II

5MN Y-T8 Compact Microwarpdrive
Relic Analyzer I
Data Analyzer I
Cargo Scanner I

Covert Ops Cloaking Device II
Core Probe Launcher I, Sisters Core Scanner Probe
Salvager II

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
~~~

#### <a name="buzzard"></a>Caldari (Buzzard)

~~~
[Buzzard, T2 Explo Buzzard]

Reactor Control Unit II
Nanofiber Internal Structure II

5MN Y-T8 Compact Microwarpdrive
Relic Analyzer I
Data Analyzer I
Cargo Scanner I
Scan Acquisition Array I

Covert Ops Cloaking Device II
Core Probe Launcher I, Sisters Core Scanner Probe
Salvager II

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
~~~

#### <a name="helios"></a>Gallente (Helios)

~~~
[Helios, T2 Explo Helios]

Nanofiber Internal Structure II
Nanofiber Internal Structure II
Nanofiber Internal Structure II

5MN Y-T8 Compact Microwarpdrive
Relic Analyzer I
Data Analyzer I
Cargo Scanner I
Scan Acquisition Array I

Covert Ops Cloaking Device II
Core Probe Launcher I, Sisters Core Scanner Probe

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
~~~

#### <a name="cheetah"></a>Minmatar (Cheetah)

~~~
[Cheetah, T2 Explo Cheetah]

Nanofiber Internal Structure II
Nanofiber Internal Structure II
Reactor Control Unit II

5MN Y-T8 Compact Microwarpdrive
Relic Analyzer I
Data Analyzer I
Cargo Scanner I

Covert Ops Cloaking Device II
Core Probe Launcher I, Sisters Core Scanner Probe
Salvager II

Small Gravity Capacitor Upgrade I
Small Gravity Capacitor Upgrade I
~~~

### <a name="otherfits"></a>Other Exploration Fits

#### <a name="astero"></a>Sisters of Eve (Astero)

The Astero is a very expensive investment in exploration ships at approximately 200million ISK, but it can pay off quite nicely. The fit below isn't designed to fight at all, but istead with the warp core stabilizers and inertial stabilizers it's designed to just be able to get away from everything with 1.89s Align time it's almost impossible to catch.

Covert Ops Cloaking is fantastic for wormhole Data and Relic sites as you can warp cloaked. And the Zeugma Integrated Analyser is a strong hacking tool for both Data and Relic sites, which also allows you to add a Cargo Scanner to see if the cans are even worth the effort.

This fit is great for doing C1-C3 pirate faction sites in relative safety.

~~~
[Astero, Explo Astero]

Inertial Stabilizers II
Inertial Stabilizers II
Warp Core Stabilizer I
Warp Core Stabilizer I

5MN Microwarpdrive II
Zeugma Integrated Analyzer
Cargo Scanner II
Scan Rangefinding Array II

Covert Ops Cloaking Device II
Sisters Core Probe Launcher, Sisters Core Scanner Probe

Small Cargohold Optimization II
Small Hyperspatial Velocity Optimizer II
Small Hyperspatial Velocity Optimizer II
~~~
