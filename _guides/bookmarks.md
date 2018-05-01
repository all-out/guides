---
layout: guide
disabled: false
title: All-Out Guide to Bookmarks
shorttitle: Bookmarks
author: Mussah Yacoub
excerpt: >
  Details of our wormhole chain bookmark naming system.  If you learn to
  recognize and name systems quickly and correctly, you will be able to
  navigate through our chains with very little effort.
---

Adapted from Oruze Cruise's [Guide to Naming WH Maps & Bookmarks]({{site.baseurl}}/img/oruze_bookmark_guide.png).

## Overview

* TOC
{:toc}

## Bookmark Naming

Every wormhole bookmark is named after the system you will land in if you jump through the wormhole.

To keep you oriented, bookmarks on wormholes that lead *back* up the chain to our home are prefixed with `!`.  This means in any given wormhole in our chains, you will see one bookmark that starts with `!` (going home) and one, some or no bookmarks that don't (going outwards).


## Wormhole System Name Components

All wormholes are named with this form: `(chain name).(wormhole class)(occurance)`

Remember: when you add a new wormhole system to Siggy, use the map and use `right click > edit` in order to set the wormhole's name.  Also set the destination name of wormhole signatures in the signature list below the map.


### Chain Name

Our home hole has two static chains, named `s3` and `h` for the C3 and Hisec chains respectively.  Any incoming wandering chains will be named `a`, `b`, `c`, etc.

The name of the chain starts the name of every wormhole in that chain.  This means that when the chain's connection to home closes, we can easily archive all bookmarks that start with that chain's name.


### Wormhole Class

Possible values: `C1`, `C2`, `C3`, `C4`, `C5`, `C6`, `HS`, `LS`, `NS`.

Note: all letters are capitalized.

### Occurance

This is a single letter that distinguishes the hole from other holes in its chain that are the same class.  Our static wormholes have the occurance `s`.  All other wormholes have occurances `a`, `b`, `c`, etc.

The important thing is that no two wormholes on the map have the same full name.  As long as that is true, the exact occurance code doesn't matter too much.  In order to deal with large maps, it's simpler to only consider other holes in the *same* chain when figuring out the next occurance code to use.


## Examples

### Standard Examples

#### s3.C3s

This is the name of our C3 static **system**.  It is the first wormhole of the `s3` chain.  It is a class 3 wormhole and one of our statics, so it has the `s` occurance.

#### s3.HSa

This is a highsec **system** in the `s3` chain.  It was the first highsec system on the map, so it has the `a` occurance.

#### b.C6c

This is a class 6 wormhole **system**.  The `b` chain name means it's in the second wandering chain attached to home, and the `c` occurance means it's the third C6 found in that chain.


### Weird Examples

#### !s3.C3s

This is what you would name the **bookmark** on the connection that, when you enter it, takes you into our class 3 static (the first system in our `s3` chain) from the system one jump further down the chain.  The jump brought you closer to home, so there is a `!` prefix.

#### !a.home

This is the name of the **bookmark** on the connection that takes you from the 'a' chain wandering into home itself.  Including the chain name means, again, that this bookmark can be archived when the chain closes.  If you simply use `!home`, that's harder to do.

### Map Example

![Example Siggy map with named systems]({{site.baseurl}}/img/example_siggy_map.png)
{: .text-center}
