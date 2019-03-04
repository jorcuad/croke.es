+++
banner = "banners/placeholder.png"
categories = ["3D Printing", "Cryptography", "DIY"]
date = "2019-03-02T21:00:00+01:00"
menu = ""
tags = []
draft = false
title = "[DIY] How to make a cryptex [I]"
+++

In my spare time I enjoy to start this kind of freak/crazy projects with my 3D printer. Particularly, I love to print locks in order to learn how they work. If I have time, I will try to post some other locks I printed, but by now, I prefer to write about my last project of this kind. During the last week I had some extra remote working days. That allowed me to start printing a cryptex.

![Example cryptex](/images/cryptex/cryptex.jpg)

## What the hell is a cryptex?

Probably most of you will know what is a cryptex, anyway, a cryptex is (more or less) popular locked cage which appeared in the film: *__"The Da Vinci Code" (2006)__*, directed by Ron Howard. I tried to look for a bit of its history but i couldn't find anything more than the [wikipedia page](https://en.wikipedia.org/wiki/Cryptex) and, in this case, that wasn't so helpful...

At the end, this device is some kind of box where you can protect your stuff with an __alpha-numeric password__. The mechanism of a cryptex is easy to understand and it works following the same principles as a __regular door lock__.

First, We have __two cylinders__, one goes inside the other. The external cylinder has a groove which cut vertically its face. The other one has several teeth (one for each password character) which fits the groove, this one is the place where our stuff is kept. Then, We have some __gears, one for each character of the password__. The gears are composed by two concentric rings. The external ring, where the characters are written, and the internal ring, where there is a gap in the position corresponding to the right character of the password. When the password of the cryptex is not the right one, __the gears of the corresponding wrong character in the password will hold the teeth of the internal cylinder, keeping it locked__. When We turn the gears to the right position they will release the corresponding teeth and there will compose a groove with all the gaps in the internal rings, releasing the entire internal cylinder of the cryptex.

## Printing all the parts

I got the cryptex files from [Thingiverse](https://www.thingiverse.com/), a free repository of things ready to print. I really love this page, it has almost everything you need. I used the design from [Mason Stonehenge](https://www.thingiverse.com/MasonStonehenge/about).

![Parts of the cryptex](/images/cryptex/parts.jpg)

The official summary has all the information, but I will try to tell my experience and how build it step by step. First of all, you will need:

* 10 Letter rings (External ring).
* 10 Letter encoder rings (Internal ring).
* 30 springs (It's used to stop the movement of the gears in each letter).
* 1 Outer core (External cylinder).
* 1 Inner core (Internal cylinder).
* 1 Retainer.
* Outer and inner decorators (The inner one its mandatory although the official summary).

I printed them with my Ender-3 Pro 3D printer. The designs are pretty accurate, they fit well without escalate any of them. My settings for this project were:

* Infill: 80% (20% is enough)
* Temperature: 200 ºC
* Material: PLA
* Supports: No
* Resolution: 0.4mm
* Adherence: Raft (Only for the springs)

### Time needed

* Gears: 10 hours.
* Springs: 2 hours.
* Cores: 12 hours.
* Decorations & Retainter: 5 hours.

__Total: 29 hours.__

*I'm not counting the time spent in failures due to bad calibration of the bed. (Another 20 hours...)*

## Assembling

This was the challenging part.
