---
layout: guide
disabled: false
title: All-Out Guide to Vippy
shorttitle: Scanning / Vippy
author: Mussah Yacoub
excerpt: >
    How to quickly and effectively scan a wormhole and record all the relevant info in our wormhole mapping software, Vippy.  Our ability to make good decisions and recognize when content and ISK are available depend on your ability to correctly use this tool.
---

## Introduction

This guide discusses how to quickly and effectively scan a wormhole and record all the relevant info in our wormhole mapping software, Vippy.  Our ability to make good decisions and recognize when content and ISK are available depend on your ability to correctly use this tool.

## Overview

* TOC
{:toc}

## First Time Setup

1. [Register a new Vippy account](http://eve-vippy.com/index.php?register=1).
    - Your username and email will only be visible to All-Out directors; other members will only see your Eve character names.
1. Add your character(s) to Vippy with [a new API key](https://community.eveonline.com/support/api-key/update/).
    - If your All-Out character has *just* entered the corp, you may need a wait a little.
1. Add Vippy to your list of trusted sites in the IGB

Optional but recommended:

1. Set Vippy as your home page in the IGB
1. Set Vippy to remember your login info

This means simply hitting `Ctrl-B` will log you in (which you should be, whenever you're playing).

## Scanning a System Properly

### Before You Begin

1. Make sure you are logged into Vippy in the IGB.

### Before Your Cloak Breaks

1. Jump into the system.  You have 30 seconds starting now.
1. Dscan at max range, 360 degrees for hostiles.
1. Bookmark the wormhole you just came through.  ([Bookmark Guide](http://all-out.github.io/guides/bookmarks/).)
1. Select and copy the *entire* signature list from the probe window. [GUIDE IMAGE]({{site.baseurl}}/img/probewindow.png)
1. In the map, select the box of the system you're by clicking on it.  Then open the signature panel below the map.  [GUIDE IMAGE]({{site.baseurl}}/img/showsigs.png)
1. Paste the sigs into this textbox and hit `Add Signatures`.  [GUIDE IMAGE]({{site.baseurl}}/img/pastesigs.png)
1. This is an example of what a partially completed signature list looks like.  [GUIDE IMAGE]({{site.baseurl}}/img/partiallycompletesigs.png)
1. Decide if you're going to leave the hole or stay in it and scan.

### After Your Cloak Breaks

1. Get to your scanning position, launch your probes and cloak up.
    - If you have a T1 cloak, scan from a safe spot.
    - If you have a covert ops cloak, scan from a 30km orbit around your entry wormhole.
1. To simplify scanning, filter anomalies from your probing window by clicking in it and pressing the `1` key.
    - Pressing it again will unfilter them.
    - Pasting anomalies once is sufficient because they don't update, but it's important that you *do* paste them at least once so that people looking at Vippy can see which holes have sites to run.
1. Begin scanning.  Prioritize to be as lazy as possible.  The following are rules of thumb; scan as much as you want:
    1. **Wormhole sigs** must all be scanned to 100%, *warped to*, and bookmarked.
        - Bookmarks go in the `Wormhole Chains` folder of Corp Bookmarks
        - Wormholes *must* be bookmarked from on grid (not from the probe window), so that "Warp to 0km" lands people exactly on the hole for instant jumping.
    1. **Home hole sigs** regardless of type must be scanned to 100% and bookmarked.
        - Bookmarks go in the `Wormhole Sites` folder of Corp Bookmarks
        - Signatures that aren't wormholes should be bookmarked by right clicking and selecting `Save Location`.  Initiating warp to some sites can "activate" them and cause sleepers to spawn.
    1. **Gas sigs** in C1, C2, C3, C4 space are not usually worth scanning completely.
        - Vital Core and Instrumental Core sites (the best ones) are only found in C5, C6 space.
    1. **Relic/Data** sigs in C4, C5, C6 space are not usually worth scanning completely.
        - Pirate Relic/Data sigs are only found in C1, C2, C3 space (exception is in Shattered holes)
1. As you scan signatures to 100%, continually select your signature list and paste it into Vippy.
    - Don't worry, you're not making duplicate entries - Vippy updates existing sigs with pasted data automatically
    - Pasting *often* is especially important when multiple people are scanning a single hole, in order to avoid wasting time by having more than one person scan a given thing.
1. Recording a fully scanned wormhole sig:
    1. Warp onto grid with the wormhole (warping to 0km can be unsafe).
    1. Bookmark the wormhole from the overview.  (Again: [Bookmark Guide](http://all-out.github.io/guides/bookmarks/).)
    1. In the Eve client, open the wormhole's info window and remember the wormhole type.
    1. In Vippy, click on the wormhole sig to open the editing interface: [GUIDE IMAGE]({{site.baseurl}}/img/wh_recording.png)
        1. Select the wormhole type from the dropdown in the "Type" column.
            - This step is not _essential_ but if you do it, the precise lifetime and mass limits of the connection will be recorded and more info is always good.
        1. Erase `unknown wormhole` from the "Info" column and type in the name of the bookmark you just created, like `0-Ha`
            - Adding the words `frig`, `eol`, `reduced` and `crit` after the name will create the connection with those properties.
        1. Click the save icon to the far right of the sig to exit the sig-editing interface
    1. At this point a dummy system box will appear on the the map, connected to your current hole with the appropriate type of connection and named correctly.
1. Afer you've done all the scanning and recording for the system, you need to *map* the wormholes to assign actual system names to the dummy boxes:
    1. Jump through each wormhole you have recorded, in designation order, from least to greatest (that is, first `1-11`, then `1-12`, then `1-13`, etc).
    1. Perform all the steps listed in [Before Your Cloak Breaks](#before-your-cloak-breaks) before you jump back into your initial system to continue mapping the other connections.

## How to Probe Quickly

Newbies often end up spending ages trying to get their probes to go where they want them and arranging them painstakingly.  With this method, you can center your probe formation on any signature in two motions, which (combined with the new keyboard shorcuts for resizing the bubbles and scanning) vastly cuts the time you need to take.

- Filter anomalies out of the probe window by clicking in the list of sigs and pressing the `1` key.
- Launch your probes in the "pinpoint" formation by pressing this button:

![Pinpoint probe formation]({{site.baseurl}}/img/pinpoint.png)
{: .text-center}

- Double-click the sig you're going to scan to highlight it, hide the others, and center the view on it.
- Zoom out so you can see the whole bubble/circle/pair-of-dots/dot of the sig you're scanning
- Motion 1:
    - Align the camera as close to *horizontal* as you can (look at the horizontal handles of your probes and make them overlap so they are a fine line)
    - Using the up and down handles, align the center of your probe control to be on an imaginary horizontal line that passes through the center of the signature

![Vertical alignment]({{site.baseurl}}/img/vertical_align.png)
{: .text-center}

- Motion 2:
    - Align the camera as close to *vertical* as you can (look at the up and down handles and try to make them as small as you can)
    - Grabbing the square top face of the of the probe control, move your probe control in the horizontal plane so that it's directly centered on the center of the signature

![Horizontal alignment]({{site.baseurl}}/img/horizontal_align.png)
{: .text-center}

After these two probe movements, the probe formation and the signature are now centered on the same point.  If you move the camera around, you can verify this.

- Resizing:
    - You should have the bubble size increase and decrease bound to a hotkey.  I use `PgUp` and `PgDn`.
    - Resize your probes so that the center portion of the pinpoint formation (the part with the most coverage) matches the size of the signature as closely as possible.

![Resizing probe range]({{site.baseurl}}/img/resize.png)
{: .text-center}

- Scan:
    - You should also have the scanning action bound to a hotkey.  I use `Shift-Space`.
- Repeat until fully scanned:
    - Double click the signature in the probe window again to recenter on the updated location of the signature, and continue as before.
    - In the case where the signature isn't a sphere:
        - Circle: keep the circle inside the center portion of the pinpoint formation while keeping the formation as small as possible, just like for the sphere.
        - Two dots: one of the dots is the real sig, one of the dots is false.  Again, make the formation as small as possible while still keeping both dots in the center portion.
        - One dot: reduce the size of your formation at about the same rate you were doing with the others, and recenter as usual.  As your scanning skills train, you will be able to reduce your bubble sizes by more notches at a time.

*[IGB]: In-Game Browser
*[Dscan]: Directional Scanner
