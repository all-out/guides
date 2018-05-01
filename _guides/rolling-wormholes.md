---
layout: guide
disabled: false
title: All-Out Guide to Rolling Wormholes
shorttitle: Rolling Wormholes
author: Mussah Yacoub
excerpt: >
    What is 'rolling a wormhole' and how do I do it?
---
## Introduction

Wormholes collapse if enough mass jumps through them.  We can ram our holes with massive ships in a controlled way to close them safely.  We do this to secure our hole, get better kspace exits, or get new wormhole chains.

## Overview

* TOC
{:toc}

## General Information

Rolling mass amounts are  discussed in very large units. You will probably see both m (million), b (billion) and kT used when reading guides and talking to people.  Ship mass is usually given in kilograms in fitting programs like Pyfa and EFT, so you might need to move a decimal around at some point.

Activating a prop mod increases the mass of your ship.  An AB and a MWD of equal size give an equal mass increase.

## All-Out Rolling

### Numbers

#### Home Statics

All-Out's statics both have 2b total mass plus or minus another 200m. They "mass" or "reduce" after approximately 1b and "crit" after 1.8b.  The heaviest ship that can enter them is 300m.

Please note the variation above, this can get you rolled out so keep your brain switched on.

#### Ship Masses
We use specially-fit Megathrons for most rolling, and cheap Thoraxes for "threading" critted holes:

- Hot Higgs Mega - 300 m
- Cold Higgs Mega - 200 m
- Hot Unrigged Mega - 150 m
- Cold Unrigged Mega - 100 m
- Hot Higgs Thorax - 125 m
- Cold Higgs Thorax - 25 m

### Procedures

#### "Flawless" Way to Roll a Fresh Home Static:

This fails about 5% of the time due to random mass variation and there's nothing you can do about it.  However, most fuckups on *fresh* holes are due to human error.

All bets are off once a few ships of unknown mass have jumped through.

*Starting from inside the home hole:*

- Cold Hot
- Cold Hot *(now massed)*
- Cold Hot
- Cold *(now crit)* Hot *(now rolled)*

OR

- Cold Hot
- Cold Hot *(not massed)*
- Hot Hot
- Hot *(now crit)* Hot *(now rolled)*


#### Someone Messed Up and I Just Realized the Regular Jumps Will Roll Me Out if I Keep Doing Them

Best plan is to do some envelope-math with masses to figure out exactly where you stand and what to do, but if you don't want to do that here are rules of thumb:

- Do Hot passes until the hole masses.
- Then do Cold passes until the hole crits (if you feel lucky do Hot return passes).
- If it rolls you out without critting, bad luck. Try to get the Mega home safe and tear out the Higgs if you need to.
- If it crits and you're outside, coming in Hot will roll it.
- If it crits and you're inside, use a threading Thorax and a pilot in a cheap clone. Go out Cold and come in Hot until you close the hole or you get rolled out (your choice to self destruct or scan out at that point).


#### Shoot, I Just Lost a Corp Mega, Now What?

It should have been insured so you should get a payout for the loss.

Preferred option is to go ahead and buy another one, platinum insure it and bring it back to our hole.

If you're a bit spacepoor and a director is around, you can ask them to reimburse you from the corp wallet for, say, the insurance cost of the new ship.  Or if you can't afford the ship at all but still want to help, you could ask for reimbursement for the ship price but still bring it into the hole yourself.

If you're spacepoor *and* you have no time to offer, you can at least give the insurance payout back to the corp wallet (into the Rent division) so we can use it to offset the cost of a new one later.


### Fits

#### Megathron (~220m)

~~~
[Megathron, Rolling Neut Mega]
Damage Control II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II

500MN Y-T8 Compact Microwarpdrive
Large Micro Jump Drive
Warp Scrambler II
Heavy Electrochemical Capacitor Booster I, Navy Cap Booster 3200

Heavy Gremlin Compact Energy Neutralizer
Heavy Gremlin Compact Energy Neutralizer
Heavy Gremlin Compact Energy Neutralizer
Heavy Gremlin Compact Energy Neutralizer
Heavy Gremlin Compact Energy Neutralizer
Medium Gremlin Compact Energy Neutralizer
Medium Gremlin Compact Energy Neutralizer

Large Higgs Anchor I
Large Transverse Bulkhead I
Large Transverse Bulkhead I

Navy Cap Booster 3200 x2

### Gun Megathron

[Megathron, Megathron import 2]
Damage Control II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II

Warp Scrambler II
500MN Y-T8 Compact Microwarpdrive
Large Micro Jump Drive
Heavy Karelin Scoped Stasis Grappler

Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L
Modal Mega Ion Particle Accelerator I, Caldari Navy Antimatter Charge L

Large Higgs Anchor I
Large Transverse Bulkhead I
Large Transverse Bulkhead I

Hobgoblin II x1
Hammerhead II x2
Federation Navy Ogre x2
Sisters Core Scanner Probe x8
Caldari Navy Antimatter Charge L x2000
Standard Drop Booster x1



#### FC I CAN'T USE A MEGATHRON; I'M A ROLEPLAYER/SPECIAL SNOWFLAKE; MY ROLLING FIT IS BETTER

Again, the only essential parts of rolling fits are the Large Higgs Anchor I rig, and a 100mn/500mn (large) propulsion module.

Feel free to experiment. And die.
~~~


#### Thorax (~13m)

~~~
[Thorax, All-Out Threading Thorax]

Damage Control II
[Empty Low slot]
[Empty Low slot]
[Empty Low slot]
[Empty Low slot]

100MN Y-S8 Compact Afterburner
[Empty Med slot]
[Empty Med slot]
[Empty Med slot]

Core Probe Launcher I, Core Scanner Probe I
[Empty High slot]
[Empty High slot]
[Empty High slot]
[Empty High slot]

Medium Higgs Anchor I
[Empty Rig slot]
[Empty Rig slot]
~~~

*[Gg]: Gigagram
*[kT]: Kiloton
*[AB]: Afterburner
*[MWD]: Microwarpdrive
*[Cold]: Prop mod OFF
*[Hot]: Prop mod ON
*[Pyfa]: Python Fitting Assistant
*[EFT]: Eve Fitting Tool
