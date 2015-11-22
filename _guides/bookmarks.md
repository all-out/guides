---
layout: guide
title: All-Out Guide to Bookmarks
shorttitle: Bookmarks
author: Mussah Yacoub
excerpt: >
  Details of our wormhole chain bookmark naming system.  If you learn to
  recognize and name systems quickly and correctly, you will be able to
  navigate through our chains with very little effort.
---

## Basic Concepts

Every **system** is named with a sequence of digits.  Our **home system** is
named `0`.  Examples of other system names might be `112`, `3`, or `132`.

Every **bookmark** is named using the `name of the system you are in`, a
`hyphen`, and the `name of the system you are going to`.  Example bookmark
names: `112-1123` and `0-3`.  The bookmarks on the other side of those
particular connections are naturally the reverse: `1123-112` and `3-0`.

Every **connection** inside a given system has a **designation** (a digit or
letter code) that is not shared by any other connection *in that system*.
Example designations: `1`, `2`, `3`, `Ha`, `La`, `Lb`

A **child system name** is created by sticking together its `parent system’s
name` and the `designation of the parent-to-child connection`.  Examples: given
a system named `12` and a connection designated `4`, the child system through
that connection is named `124`.  A system named `2` and connection designated
`La` gives a child named `2La`.

---

## How Connections are Designated

### J-space Connections

If the connection is the J-space static, it’s designated `1`.  (Note: `1` never
designates *anything* but a J-space static connection)

For all subsequent J-space connections (both second static or wandering),
designations are assigned with the next unused digit from the sequence `2-9`.

### K-space Connections

In place of digits, letter codes are used.  `Ha`, `Hb`, `Hc`, etc. for high
sec; `La`, `Lb`, `Lc`, etc. for low sec; `Na`, `Nb`, `Nc`, etc. for null sec.

If the connection is the K-space static, it’s designated either `Ha`, `La`, or
`Na` depending on security.  (Note: the fact that the designation ends in “a”
is *not* a sure indication that the connection is a static.)

For all subsequent K-space connections (both second static or wandering),
designations are assigned with their security letter and the next unused letter
of the alphabet for that security.  (If there is already just a `Ha` and a
`Hb`, the next high sec is `Hc`.  If a null sec is found next, it’s `Na`.)

---

## More Examples

### System Names

- Home system: `0`
- Our C3 static system: `1`
- Our high sec static system: `Ha`


- If our C3 static’s static was in null sec, the null system would be named: `1Na`
- If our C3 had a single wandering connection and it was a C5, the C5 would be named: `12`
- And then that C5’s static system (has to be a wormhole) would be named: `121`

- If home had a wandering high sec connection, it would be named `Hb`
- If home had a wandering null sec connection, it would be named `Na`
- If home had three wandering wormhole connections, they would be called `2`, `3`, and `4`
- If `2` also had three wandering wormhole connections, they would be called `22`, `23`, and `24`

### Bookmark Names

- Home > our C3 static: `0-1`
- Home > our high sec static: `0-Ha`

- Our C3 static > its null sec static: `1-1Na`
- Our C3 static > its wandering C5: `1-12`
- That C5 > that C5’s static: `12-121`

- Home > three wandering wormholes: `0-2`, `0-3`, `0-4`
- 2 > three wandering wormholes: `2-22`, `2-23`, `2-24`

--- 

## Benefits Of This System (or, Why The Hell Are You Doing This To Us; It Hurts)

- It is more concise than other systems we’ve used (less typing, more scanning)
- There is no need to indicate the “home direction” with special characters (the bookmark that goes towards home is always at the top in the right click menu because of alphabetical sorting)
- When a connection despawns, all of the now-useless bookmarks below that point in the tree can be identified and removed easily - by sorting the bookmarks by name and removing all bookmarks starting with the sequence of digits of the last valid bookmark.
- Each system name contains all of the information needed to get to it in the chain without needing to refer to the map
- Vippy, our mapping software, automatically names the systems in our map according to this system, meaning there is one less data entry step to get right.
