# Does A KVM Switch Add Lag

## What a KVM switch is actually doing

A KVM switch is a switch, not a processor. It takes the keyboard, mouse and video from whichever computer you have selected and routes them to one shared keyboard, one mouse and often one monitor. It doesn't decode the picture, scale it or re-draw it, so the box itself isn't adding the frame-by-frame delay you would get from a device that reworks the video, like a wireless extender, a capture card or a scaler. The signal it passes to your screen is the signal your computer sent.

That matters because "does a KVM add lag" is usually really three separate questions wearing one coat: what happens to the keyboard and mouse, what happens to the display when you swap, and whether the cables can carry your monitor's full mode. Take them one at a time and the honest answer to almost all of it is no, with a couple of things worth checking on the spec sheet.

It is also worth naming what a KVM is, because a lot of people arrive here having bought, or nearly bought, the wrong box. A hub gives one computer more ports. A docking station turns one laptop into a desk. A KVM does the opposite of both: it lets two or more computers share one set of peripherals. If you only have one machine, no KVM will help you, and that is the single most common mix-up in this category.

## The keyboard and mouse: emulation versus pass-through

A KVM can hand your keyboard and mouse to each computer in one of two ways, and the choice is a trade-off rather than a speed setting. In pass-through mode the switch, as KVM makers describe it, makes the keyboard and mouse behave more like they are connected directly to the active computer, which favours native device behaviour. In emulation mode the switch presents a more standard keyboard and mouse to every connected computer, which favours stable, predictable control; the idea is that each machine keeps seeing a steady keyboard and mouse even when you switch away from it.

Neither mode is inherently laggy, but they behave differently, and this is what some people are actually reacting to when they say a KVM "feels off". A gaming keyboard's onboard macros, a mouse's extra side buttons or its DPI software can go quiet under emulation, because the switch is presenting a plain, standard device to the computer rather than your specific one. That is a feature-compatibility question, not input delay. If those extras matter to you, check the spec sheet for pass-through, or for a stated gaming mode, before you buy.

## The handshake that makes a screen go black

Here is where most of the felt "lag" on a swap actually lives, and it is not the picture running behind. When a monitor connects to a computer they exchange EDID, the small set of display information a monitor sends to tell the computer which resolutions and refresh rates it supports. Switch a KVM and that handshake can happen again.

On a switch without EDID emulation, the computer you have just left can behave as if the monitor was unplugged. That temporary disconnect can make the operating system re-detect the display when you come back to it, and re-detection is what you see as a black screen for a moment, windows shuffling to a new arrangement, or a refresh rate that quietly drops. A switch with EDID emulation reads and stores the monitor's information and feeds it to every connected computer, so no machine ever sees the screen vanish and there's nothing to reinitialise on the swap. If a fast, clean switch matters to you, that one line on the spec sheet is the one to look for.

## Cables and refresh rate

A KVM can only carry what its ports and the cables allow, and this is the other place a real limit hides. A switch rated for 4K at 60Hz will cap a 4K 120Hz monitor at 60, and a lead that is not built for the higher mode does the same thing. That's not the switch adding lag; it's a bandwidth ceiling, the same certification question any display cable has to answer.

So match three things: your monitor's mode, the switch's stated video ceiling, and the cables. If any one of them tops out below the others, that one decides your picture. It is worth reading the switch's own figures for resolution and refresh rather than trusting the headline, and treating the bundled cables with the same eye you would give a display lead. Our guide on [how to tell if an HDMI cable is 2.1](hdmi-2-1-cable-how-to-tell-explained.html) covers the certification that proves a cable can carry the full mode.

## When a USB-only switch is all you need

If both of your computers already have their own screen, you don't need video switching at all, and skipping it removes the EDID question entirely. A USB-only switch shares just the keyboard, the mouse and whatever else is plugged into it, and leaves each monitor connected to its own machine the whole time. It is the cheapest honest answer for the common case of a work laptop and a personal machine that each already drive a display, where the only real annoyance is two keyboards and two mice cluttering one desk.

This is also where the hub, dock and switch confusion is worth settling. If you have a single computer, the box you want is almost certainly a hub or a dock instead: our [USB-C hub versus docking station](usb-c-hub-vs-docking-station.html) explainer sorts those two out, and the [USB-C docking station](best-usb-c-docking-station-uk.html) guide covers the one-cable desk. A KVM only earns its place once there are two or more machines to switch between.

## FAQ

**Q: Does a KVM switch add input lag?**
A: A hardware KVM routes the signals rather than processing them, so the switch itself isn't adding the frame-by-frame delay of a scaler or a wireless extender. What people feel on a swap is usually the display re-detecting itself, or a gaming keyboard and mouse behaving differently under the switch's emulation, rather than the picture running behind. For gaming, check the spec sheet for pass-through or a stated gaming mode, and match the cables to your monitor's refresh rate.

**Q: Why does my screen go black for a moment when I switch?**
A: That's the display handshake, and it is harmless. It happens when the switch lets the computer you left treat the monitor as unplugged, so that machine re-detects the screen on the way back. The setting that prevents it is EDID emulation: a switch that lists it holds the monitor's details for every computer, so nothing has to re-detect on a swap. If clean, instant switching matters to you, that's the line to look for on the spec sheet.

**Q: Do KVM switches need drivers?**
A: A basic hardware KVM is generally plug and play, because it presents a standard keyboard, mouse and display to each computer and the operating system treats them as ordinary USB devices. Software only comes in for extras like an on-screen switching utility or a gaming peripheral's own app, and a switch running in emulation mode may hide some of those device-specific features.

**Q: Will a KVM switch lower my refresh rate?**
A: Only if you let it, and the limit is bandwidth rather than the switch's electronics. Match three things: your monitor's resolution and refresh, the switch's stated video ceiling, and the cables between them; whichever is lowest sets your picture. Buy a switch and leads rated for your monitor's full mode and nothing drops. Our guide on [how to tell if an HDMI cable is 2.1](hdmi-2-1-cable-how-to-tell-explained.html) covers the certification that proves a cable can carry it.

**Q: Is a KVM switch the same as a USB hub or a docking station?**
A: No, and it's the most common mix-up. If a single computer just needs more ports or a one-cable desk, that is a hub or a docking station. A KVM only earns its place when two or more computers have to share one keyboard, mouse and screen: it switches between machines rather than expanding one.
