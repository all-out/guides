---
layout: guide                       
disabled: false                     
title: All-Out Guide to Pathfinder and Wormhole Mapping   
shorttitle: Pathfinder and Wormhole Mapping               
author: A Jung Mann / Syco Phantic           
excerpt: > 
  Instructions on everything you need to know to survive day-to-day wormhole-life with All-Out:
  How to keep track of your scanning, navigate your way around the wormhole chain, share bookmarks with the rest of the corp, get a GF, etc.              
---

## Pathfinder
Find the URL to All-Out's own Pathfinder intallation in Corp MOTD / Corp Bulletins

Pathfinder is your one true friend in wormhole space. All-Out uses it to map out wormhole chains, mark dangerous holes, keep track of sites in each system, and much more. 

### Initial Setup

Getting started with Pathfinder is easy:   

1. Go to the URL mentioned above
2. Click on "LOG IN with EVE Online"  
3. Log into the account that has your All-Out Character on it, and log in with that Character   
4. You did it, good job :tada:


## Mapping Wormholes

Now that you have access to our map, you should be able to see something like this. How do you read all this information? 

<img src="/guides/img/pathfinder.png" alt="pathfinder" width="1000">

You should find the home system of All-Out somewhere in the central window, and connected to it there should be more wormholes linking it to other systems.

### Naming Systems
The naming system we utilize gives each wormhole system a unique name, following this format:   
*(chain name).(wormhole class)(occurrence)*.

For clarity, let's take the example case of a system designated *s3.C5b*:

+ The first letter and number (*s3*) describe which hole inside All-Out's home the chain starts with, in this case it starts with the class 3 static.  
+ The next letter and number (*C5*) tell you the class of the wormhole system, in this case a class 5.
+ The final letter is used to uniquely identify each system of the same class within a chain. The first class 5 wormhole to be scanned down in any chain would be *C5a*, the next would be *C5b* and so on.

Knowing all this you can tell that *s3.C5b* is the second class 5 wormhole system that was found in the chain starting with our class 3 static.

**IMPORTANT NOTES:** 

+ Nullsec systems are classified as *NS*, Lowsec systems are classified as *LS*, and Highsec systems are classified as *HS*. 
+ The occurence count for the final letter only takes into account systems that are found within the same chain, i.e. there can be a *s3.C3a* and *s4.C3a* at the same time.
+ To find more about the naming scheme and how to save boomarks take a look here: [Bookmarks]({{site.baseurl}}/bookmarks/)


### Adding and Removing Systems
To add new systems to the map yourself, simply jump into the system while being logged into Pathfinder. Pathfinder will then automatically add the system and connect it appropriately. **Always have Pathfinder open in the background while you are logged in!** You will still have to rename the wormhole system manually according to our system, and move the wormhole system on the map so everything is clearly legible.

Please put some thought into the arrangement of the systems you scanned down. When looking at the map, you should be able to quickly and easily tell what's connected to what. 

If you need to manually add a system or a connection between systems for any reason, you can just drag an connection from one system to another. To delete a connection or system, right click it.

### Static Chains
All-Out's home has two statics, a C3 and a C5. These are exempt from the occurence count and are always denoted as *s3.C3s* and *s3.C5s*. You can tell the difference between a static wormhole and other types of wormhole by looking at its ID: the *s3.C3s* will always be *C247* and the *s5.C5s*  will always be *H900*. If a wormhole has any other ID (like *K162*) it is a wandering wormhole or the exit of another system's static.

### Wandering Chains
If there is a non-static wormhole connection in All-Out's home, its chain is named with a letter depending on its order of discovery, starting with *a*, then *b*, and so on. A wandering chain is identified by a wormhole in All-Out's home having any ID other than *C247* and *H900*.

### Wormhole Status
Wormholes that are *End of Life*, *Reduced*/*Critical* or are special wormholes like *Frigate Only* holes need to be indicated appropriately on Pathfinder. Do this by right-clicking the link between the two systems and clicking the appropriate option.

## Signatures/Anomalies

You can, and should, add all of a system's signatures to pathfinder:

  + Click *CTRL+A* in the probe scanner window and then *CTRL-C* to copy all the system's signatures.
  + Select the wormhole you are currently in on Pathfinder.
  + Scroll down to just under the map and paste everything in the box next to *Signatures* and hit enter.
  + If you check the *lazy 'delete' signatures* button in signatures box nonexistent signatures of your current system list will be automatically deleted. This can be useful to quickly clear up systems that still have old signatures listed from when you previously encountered this system, or to quickly delete any signatures that might have died since you were last in that system.

<img src="/guides/img/pathfinder2.png" alt="pathfinder2" width="1000">

An example of a properly maintained signature list.

**IMPORTANT NOTES:**

  + Do not paste the system's anomalies into pathfinder. Only signatures should be tracked. You can set a filter on your probe window.
  + Make sure to indicate which wormhole signature corresponds to which wormhole in the *leads to* field.
  + You can simply paste any signatures into pathfinder when there are already scanned down signatures added, as pathfinder will not overwrite anything and destroy information on its own unless you check the *lazy 'delete' signatures* checkbox.
  + Always delete old signatures and bookmarks if you notice them dying naturally, or after you clear the corresponding site, or notice them disappearing for any other reason. Pathfinder should ideally only contain live signatures.

## Wormhole Identification
With some experience you can quickly tell which class a wormhole system belongs to just by looking at the wormhole that leads into that system. This helps you in properly bookmarking the wormhole and fully updating the information in Pathfinder, as you can finish scanning an entire system without having to jump the adjacent systems to get all the information you need for proper bookmarking and Pathfinder upkeeping.  

![siggy_guide3]({{site.baseurl}}/img/siggy_guide3.jpg)

To do this look at the wormhole in game (default is ''alt-click'') and compare the visual effect with the linked graphic. You might have to spin the wormhole around a bit to get a good view of the effect and definitively tell the class of the system. 

Hot tip: You can also tell which region of k-space a wormhole leads to by comparing the visual of the wormhole with the nebulae listed on [this website](https://evetravel.wordpress.com/visible-nebulae-in-new-eden/).

## Additional Intel
Under the Structures tab below the system map in Pathfinder you can also add any POSes or Citadels that you find in a system, including location and owner of the structure.  

You might find this worth your time as it can come in handy in quickly telling you where exactly a POS is located when you need that information, or immediately letting you know who lives in a system if you jump into a system that you already gathered intel for when you previously came across it.

You can also indicate that a system is empty, occupied, or active. To do this, right click the system itself, click edit, and select the appropriate option in the drop-down menu.

+ Systems with no inhabitants and/or activity should be marked *empty*. 
+ Systems with inhabitants (Citadel or active POS) should be marked as *occupied*. Ideally you indicate the occupants under the intel tab as well.
+ If you have any reason to believe there might be activity in a system, it should be marked as *hostile*. This one is the most important, as it lets others know to tread carefully and will frequently save your own lives, as well as make sure you don't needlessly waste content opportunities. 

## Bookmarking

### Bookmarking  Wormholes 
All wormholes are simply bookmarked with the name of the system they lead into, i.e. if jumping through a wormhole would take you to the system designated *s4.C5b*, that wormhole would be bookmarked as *s4.C5b*.

The wormhole that leads back into All-Out's home itself is designated as *home* in place of its class and occurence, i.e. the wormhole leading into home from the s3-chain would be called *!s3.home*, the wormhole leading back home from the a-chain would be called *!a.home*, and so on.

**IMPORTANT NOTES:**

  + Be sure to always bookmark the wormhole itself, and not the scanned down wormhole's signature.
  + Wormholes that lead back towards All-Out's home are additionally denoted with a *!* before the name, i.e. *s3.C5b* would lead you further away from home, while *!s3.C3s* would take you closer to home.

### Bookmarking Sites

Any combat/hacking/gas sites that you scan down while exploring should be bookmarked with the proposed default bookmark text. i.e. *MZJ-310 Vast Frontier Reservoir*

Always bookmark the scanned down signature in the probe scanner window, and not something within the site itself, as warping to the site may trigger a timer that will lead to the site despawning. 

## Scanning and Exploring

Now that you know how to track all sorts of intel with Pathfinder, here are some more tips on how to acquire that intel in the first place. Ideally the scanning process you should get used to is something like this:

  + Jump into a new system
  + Bookmark the wormhole exit behind you
  + D-scan the entire system (may require warping around)
  + When you are sure there is no one to be spooked by your scanning probes, drop probes
  + Start scanning, updating signatures in Pathfinder along the way

You should aim to show as little as possible on D-Scan. Always be cloaked, and don't drop probes when you think someone might see them, unless you want them to.

For more tips and reasons to scan, check out this guide on [probing technique](https://all-out.github.io/guides/probing-technique/) and [how to stop being a faggot](https://all-out.github.io/guides/stop-being-a-faggot/).

The most important is Nootkin's hot Tip:  
WHEN YOU JUMP INTO A SYSTEM, IMMEDIATELY DSCAN AT 14.3 AU AND SEE WHAT YOU FIND. PLEASE DO NOT DROP PROBES THE SECOND YOU ENTER SYSTEM, THAT'S THE EASIEST WAY TO SCARE OFF PREY.
