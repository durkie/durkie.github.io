---
layout: post
title:  "When you accidentally blow up your USB ports"
description: "Ouroboros"
date:   2017-09-12 17:56:00
image: assets/images/usb-blaster-1.jpg
---

So I accidentally plugged +12VDC in to my USB ports and blew them up. This made me sad because my computer is from 2009 and had nothing wrong with it until that point.

And it turns out there's not an easy way to fix this: there aren't really Ethernet-USB adapters, nor Firewire-USB adapters. I began looking at new logic boards on ebay.

And one day I happened to notice that when I attached an externally-powered Arduino to the Mac's USB ports, it worked fine! So the data lines were still good, just the 5V regulator was blown.

So I made this silly thing: it pulls 12V from the Firewire port, and regulates it down to 5V to revive my USB ports again. Altogether cost was probably around $15, with $9 of that being the fancy right-angle Firewire cable.

![USB Blaster]({{ site.url }}/assets/images/usb-blaster-2.jpg)
![USB Blaster]({{ site.url }}/assets/images/usb-blaster-3.jpg)
