---
layout: guide
disabled: true
title: All-Out Guide to Vippy
shorttitle: Vippy (placeholder)
author: Mussah Yacoub
excerpt: >
    Overview of our wormhole mapping software.  Our ability to make good
    decisions and recognize when content and ISK are available depend on your
    ability to correctly use this tool.
---


* TOC
{:toc}


## First Time Setup

1. [Register a new Vippy account](http://eve-vippy.com/index.php?register=1).
 - Your username and email will only be visible to All-Out directors; other members will only see your Eve character names.
1. Add your character(s) to Vippy with [a new API key](https://community.eveonline.com/support/api-key/update/).
 - If your All-Out character has *just* entered the corp, you may need a wait a little.

## Scanning a System Properly (Step by Step)

### Before Your Cloak Breaks (under 30 seconds)

1. Enter the system.
1. Dscan at max range and 360 degrees for hostiles.
1. Bookmark the wormhole you just came through [correctly](#).
1. Select and copy the *entire* signature list from the probe window. [PROBEWINDOW]
1. Toggle open the Vippy signature panel below the map and click the box of the system you are in. [SHOWSIGNATURES]
1. Paste the sigs into this textbox and hit `Add Signatures`. [PASTESIGNATURES]
1. This is an example of what a partially completed signature list looks like. [PARTIALLYCOMPLETESIGNATURES]
1. Decide if you're going to leave the hole or stay in it and scan.

### After Your Cloak Breaks

1. Get to your scanning position, launch your probes and cloak up.
    - If you have a T1 cloak, scan from a safe spot.
    - If you have a covert ops cloak, scan from a 30km orbit around your entry wormhole.
1. To simplify scanning, filter anomalies from your probing window by clicking in it and pressing `1`.
    - Pressing it again will unfilter them.
    - Pasting anomalies once is sufficient because they don't update, but it's important that you *do* paste them at least once so that people looking at Vippy can see which holes have sites to run.
1. As you scan signatures to 100%, continually select your signature list and paste it into Vippy like before.
    - Don't worry about making duplicate entries; Vippy will update the signatures automatically according to sig ID
    - This is especially important when multiple people are scanning a hole in order keep everyone on the same page and to avoid duplicating effort.
1. Prioritize signatures to do as little work as possible.  The following are rules of thumb.  Scan as much as you want:
    1. All wormhole sigs must be scanned to 100%, *warped to*, and bookmarked.
        - Wormholes must be bookmarked from grid, not from the probe window, so that "Warp to 0km" lands people exactly on the hole for instant jumping.
    1. All signatures in the home hole regardless of type must be scanned to 100% and bookmarked.
        - Signatures that aren't wormholes should be bookmarked by rightclicking and selecting `Save Location`.  Initiating warp to some sites can "activate" them and cause sleepers to spawn.
    1. Gas sigs in C1, C2, C3, C4 space are not worth scanning completely.
        - Vital Core and Instrumental Core sites (the best ones) are only found in C5, C6 space.
    1. Relic/Data sigs in C4, C5, C6 space are not worth scanning completely.
        - Pirate Relic/Data sigs are only found in C1, C2, C3 space (exception is in Shattered holes)
