# Does A KVM Switch Add Lag

## KVM, hub or dock?

A KVM switch isn't a hub or a dock. A hub gives one computer more ports, and a docking station gives one laptop a one-cable desk. A KVM lets two or more computers share one keyboard, one mouse and often one monitor, so with a single computer no KVM will help. Our [USB-C hub versus docking station](usb-c-hub-vs-docking-station.html) explainer sorts out those two, and the [USB-C docking station](best-usb-c-docking-station-uk.html) guide covers the one-cable desk.

## The handshake behind a slow swap

When a monitor connects to a computer, it sends EDID, the set of display information that tells the computer which resolutions and refresh rates it supports. A KVM swap can make that handshake happen again.

On a switch without EDID emulation, the computer you've just left can behave as if the monitor was unplugged, and the operating system then re-detects the display when you come back. After that re-detection, TESmart notes, the computer "may not always restore the original display mode correctly". A switch with EDID emulation reads and stores the monitor's information and feeds it to every connected computer, so no machine sees the screen vanish. If a clean swap matters to you, EDID emulation is the line to look for.

## Cables and refresh rate

A KVM can only carry what its ports and cables allow, and this is where a real limit hides. A switch rated for 4K at 60Hz will cap a 4K 120Hz monitor at 60, and a lead that isn't built for the higher mode does the same.

So match three things: your monitor's mode, the switch's stated video ceiling, and the cables. Whichever tops out lowest decides your picture, so read the switch's own resolution and refresh figures rather than the headline, and judge the bundled cables as you would any display lead. Our guide on [how to tell if an HDMI cable is 2.1](hdmi-2-1-cable-how-to-tell-explained.html) covers the certification that proves a cable can carry the full mode.

## When a USB-only switch is all you need

If both of your computers already have their own screen, you don't need video switching at all, and the EDID question goes with it. A USB-only switch shares just the keyboard, the mouse and whatever else is plugged into it, while each monitor stays connected to its own machine. That suits a work laptop and a personal machine that each drive a display, where the only annoyance is two keyboards and two mice on one desk. If you do need video switching too, our [best KVM switch guide](best-kvm-switch-uk.html) covers the picks.

## FAQ

**Q: Why did my refresh rate drop after switching?**
A: If the switch and cables are rated for your monitor's mode, look at the handshake. TESmart says a computer that loses stable display information "may fall back to a lower refresh rate ... or temporarily hide high-refresh-rate options", which is the fault EDID emulation is there to stop.
