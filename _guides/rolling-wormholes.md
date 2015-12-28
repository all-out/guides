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

Wormholes collapse if enough mass jumps through them.  We can ram our holes with massive ships in a controlled way to close them safely.  We do this to secure our hole, get better kspace exits, or get new wormhole space chains.

## Overview

* TOC
{:toc}

## General Information

Rolling mass amounts are  discussed in very large units. You will probably see both Gg and kT used when reading guides and talking to people - these are both one million kilograms (1,000,000 kg).  Ship mass is usually given in kilograms in fitting programs like Pyfa and EFT, so you might need to move a decimal around at some point.

Activating a prop mod increases the mass of your ship.  An AB and a MWD of equal size give an equal mass increase.

## All-Out Rolling

### Numbers

#### Home Statics

All-Out's statics both have 2,000 Gg total mass. They "mass" or "reduce" after 1,000 Gg and "crit" after 200 Gg.  The heaviest ship that can enter them is 300 Gg.

#### Ship Masses
We use specially-fit Megathrons for most rolling, and cheap Thoraxes for "threading" critted holes:

- Hot Higgs Mega - 300 Gg
- Cold Higgs Mega - 200 Gg
- Hot Unrigged Mega - 150 Gg
- Cold Unrigged Mega - 100 Gg
- Hot Higgs Thorax - 125 Gg
- Cold Higgs Thorax - 25 Gg

### Procedures

#### "Flawless" Way to Roll a Fresh Home Static:

This fails about 5% of the time due to random mass variation and there's nothing you can do about it.  However, most fuckups on *fresh* holes are due to human error.

All bets are off once a few ships of unknown mass have jumped through.

*Starting from inside the home hole:*
- Hot Hot
- Hot Hot *(now massed)*
- Cold Hot
- Cold *(now crit)* Hot *(now rolled)*

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
[Megathron, All-Out Rolling Mega]

Damage Control II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II
Reinforced Bulkheads II

500MN Cold-Gas Enduring Microwarpdrive
J5 Prototype Warp Disruptor I
X5 Prototype Engine Enervator
[Empty Med slot]

Heavy Infectious Scoped Energy Neutralizer
Heavy Infectious Scoped Energy Neutralizer
Large EMP Smartbomb I
Large Graviton Smartbomb I
Large Proton Smartbomb I
Prototype Cloaking Device I
Core Probe Launcher I, Core Scanner Probe I

Large Transverse Bulkhead I
Large Transverse Bulkhead I
Large Higgs Anchor I

Acolyte II x2
Warrior II x3
Hornet EC-300 x10
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

[Empty High slot]
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
