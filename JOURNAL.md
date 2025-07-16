---
title: "RPBoard²"
author: "@valen"
description: "Simple RP2350-based devboard"
created_at: "2025-07-15"
---

### Total time spent: 4h

# July 15: Started reading hardware design guide + basic schematic design

I wanted to get started doing the schematic as I was reading the guide instead of just reading, so that's what I did :D

Here's how my schematic is looking for now: (ik it's really basic but I'm just getting started and following the guide, I'll add a ton of features once I have the basics done. also I spent most of the time trying to understand what I'm doing instead of just copy pasting that's why it took me so long lol)

<img src="assets/schematic-july-15.png" width=500px>

Only thing I changed for now is the USB connector for it to be USB-C, it's not really too different from the micro USB symbol but that's probably because I'm using a 16 pin connector.

As for the flash, it took me quite some time to figure out how to wire it because the guide wasn't really clear but it ended up being easier than I thought, idk why I got so confused lol

Then I also added decoupling caps on the power pins (took me some time to understand what they were and why I should add them but after quite a lot of googling I think I figured it out).

And the last thing I added to my schematic was the external components needed to make the on-chip voltage regulator work properly, I copied that from the guide since I didn't want to mess up and for some reason the guide really insists on using a specific inductor so might as well do that lmao

To finish with the basics of the schematic I'm only missing the crystal oscillator, a debug connector (optional but I'll add it anyways for convenience) and a reset button (optional too but obviously nice to have).

As for additional features, for now I'm planning on adding lipo battery support, a Qwiic connector, a microSD card slot and maybe even a small OLED depending on how much space I have left

Well hopefully tomorrow I'll finish with the basics and start adding some actually interesting features!! :D

**Time spent this session: 4h**
