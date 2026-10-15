# Docking Station Not Detecting Your Monitor? Here's Why

## Start with the laptop, not the dock

Two things on the laptop decide what a dock can show before any setting comes into it.

The first is whether the USB-C port carries video at all. Anker's own dock guide says that if the port lacks DisplayPort Alt Mode or Thunderbolt, the laptop may not find a monitor through a dock, and suggests checking the icon beside the port, where a Thunderbolt lightning bolt or a DisplayPort "D" marker points to video. If your port has no marking, your laptop maker's specification page is the certain answer. Our explainer on [which USB-C cables and ports carry video](usb-c-cable-for-monitor-explained.html) covers that side in depth.

The second is how many external displays the laptop can drive. A dock can offer two or three video outputs, but Anker notes that "some laptops can only drive one external display through USB-C or Thunderbolt". The same specification page lists how many external displays your exact model supports.

## The DisplayLink question: a dock that needs its own driver

A DisplayLink dock is driver-based, and Anker lists "DisplayLink software, if your dock uses it" among the things to install when a dock isn't detecting a monitor.

So if the laptop's limits check out and the screen is still dark, find out whether your dock is a DisplayLink model from its box or product page, and install the current driver from the dock maker or from DisplayLink directly.

## The ordinary checks, in the order worth doing them

Start at the monitor: a screen will sit on a blank input even when the dock is sending a good signal, so open the monitor's own menu and, in Anker's words, "select the input that matches the cable connected to your dock, such as HDMI 1, HDMI 2, DisplayPort, or USB-C".

If the monitor shows your laptop's screen rather than a desktop of its own, press Windows and P and choose Extend. Anker adds that you should "make sure the dock supports dual extended display mode" when you want separate content on each screen. If Windows isn't seeing the monitor at all, Microsoft's guidance for a docked monitor that stays black is to "use the keyboard shortcut Win+Ctrl+Shift+B" or to open Display Settings and "click the Detect button".

Next, update the laptop's graphics driver through Windows Update or the laptop maker's support page. If none of that moves it, power-cycle the dock rather than just unplugging the laptop. Anker's sequence is to "unplug the docking station from your laptop", "disconnect the monitor cables from the dock", "unplug the dock's power adapter from the wall outlet" and "wait 30 to 60 seconds", then reconnect everything.

## When it is the dock's own ceiling

A dock has a rated monitor count and a maximum resolution and refresh rate, and asking for more leaves a screen blank or quietly capped. A dock sold for two 4K screens won't light a third, and a dock rated for 4K at 60Hz won't run a monitor faster than that even if the monitor can. The figures are on the dock's own listing; match them to your monitors and to your laptop's limit from the first section.

If you're still choosing a dock, our [best USB-C docking station guide](best-usb-c-docking-station-uk.html) covers the picks, and if you're not sure you need a full dock rather than a compact hub, our [hub versus docking station explainer](usb-c-hub-vs-docking-station.html) settles that first.

## FAQ

**Q: My dock detects one monitor but not the second, what now?**
A: That pattern can point at a limit rather than a fault: either the laptop drives only one external display over USB-C, or the second screen goes past the dock's rated monitor count. Check both figures before you replace anything.

**Q: Will a DisplayLink dock work on a Mac?**
A: Yes, once Synaptics' DisplayLink Manager app is installed. Synaptics, which makes DisplayLink, calls it "a new way to enable your DisplayLink dock, adapter or monitor on macOS platforms" that "combines our latest driver with features that streamline the setup of multiple displays up to 4K".
