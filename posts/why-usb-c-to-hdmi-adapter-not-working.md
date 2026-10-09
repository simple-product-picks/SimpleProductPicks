# Why Your USB-C To HDMI Adapter Isn't Working

## The tell: it charges, but the screen says no signal

Start with the symptom that gives the game away. If you plug the adapter in and the laptop or phone keeps charging, or the device clearly reacts to being connected, but the television or monitor sits on "no signal", that single detail points away from a dead adapter and towards the port it's plugged into. Power and video do not travel together over USB-C; they run on separate paths inside the same connector. So a healthy charge proves the power path works and tells you nothing about whether a picture was ever going to come out of that port.

Before you blame the adapter or buy another one, it's worth spending two minutes on the port, because that is where most of these failures actually live.

## Does your USB-C port even output video?

This is the cause the generic fix-lists bury near the bottom, and it is one of the most common reasons an adapter shows "no signal". A USB-C port only carries a picture if it supports DisplayPort Alt Mode (or Thunderbolt). The DisplayPort standards body describes the arrangement plainly: "DisplayPort leverages the Alternate Mode Functional Extension of the USB Type-C interface", and that signal is "backward compatible with VGA, DVI, and HDMI 2.0 with CEC using plug adapters or adapter cables". In other words, the port puts out a DisplayPort signal and the adapter converts it to HDMI.

The catch is in the word "alternate": it is an optional extra on top of plain USB-C, so a lot of ports, especially on budget laptops, older machines and many phones, are wired for data and charging only and never output video at all. No adapter can conjure a signal a port doesn't produce.

The honest first step is to check your own device rather than the adapter. Look up your laptop or phone model and see whether its USB-C port lists DisplayPort, "DP Alt Mode", Thunderbolt or "video out"; a port that mentions only USB data speeds and charging is the warning sign. Apple makes the same requirement explicit for its machines, noting that when you connect a display, "the adapter must be compliant with DisplayPort Alt Mode, Thunderbolt 3, or Thunderbolt 4." If the spec sheet is silent on video, assume the port is the problem until proven otherwise.

## The adapter has to be a video adapter, used within its limits

Once you know the port can output video, the adapter is the next link, and two things trip it up. The first is using the wrong kind of adapter: a cheap USB-C dongle built for data, or a hub whose maker never claimed video, is not the same as a USB-C to HDMI video adapter. Apple's guidance is to reach for "the Apple USB-C Digital AV Multiport Adapter or other USB-C to HDMI adapter or cable" for an HDMI display, the point being that it has to be an adapter designed to pass a display signal, not whatever USB-C accessory was in the drawer.

The second is pushing a genuine adapter past what it can carry. Every USB-C to HDMI adapter has a ceiling, often 4K at 30Hz on cheaper ones or 4K at 60Hz on better ones, and if the screen asks for more than the adapter supports you can get a black screen, a dropout or a picture stuck at the wrong resolution. If a 4K television shows nothing, it is worth testing whether the adapter is simply over its limit before writing it off.

## When the port and adapter both check out

Plenty of "not working" cases are a handshake that didn't complete rather than any hardware fault, and these are the quick wins:

- Reseat the USB-C end firmly and unplug then replug both ends. USB-C video negotiation can fail silently on the first connection, and a clean reconnect often brings the picture straight up.
- Select the matching input on the screen. A television in particular has to be switched to the exact HDMI number the lead is in; the right source is not always chosen automatically.
- Update the display driver or the operating system. A Windows graphics driver or a system update can knock out external display on a port that worked last week, and refreshing it restores it.
- Rule out the HDMI lead on the far side. A loose or damaged HDMI cable between the adapter and the screen causes the same flicker or dropout, so try another known-good HDMI lead.

If you have swapped in an adapter and HDMI lead you trust and the port is spec'd for video, but it still fails, the remaining suspect is the USB-C cable or lead feeding the adapter, which is a question in its own right: our guide to [which USB-C cables carry video](usb-c-cable-for-monitor-explained.html) explains how to tell a video-capable lead from a charge-only one.

## So is it the adapter or the port?

The fastest way to tell them apart is the charge test from the top. If the device charges through the connection but nothing reaches the screen, and the port's spec does not clearly promise DisplayPort or Thunderbolt, the port is almost certainly the limit and a different adapter will not help. If the port is spec'd for video and a known-good setup still fails, the adapter or its resolution ceiling is the likely culprit, and a proper one fixes it: our [USB-C to HDMI adapter guide](best-usb-c-to-hdmi-adapter.html) covers models that are built to pass a signal rather than just charge. If your screen takes DisplayPort instead of HDMI, the [USB-C to DisplayPort adapter guide](best-usb-c-to-displayport-adapter.html) is the matching page.

## FAQ

**Q: Why does my USB-C to HDMI adapter charge my laptop but show no signal?**
A: Because power and video run on separate paths in a USB-C connection, so charging proves nothing about video. A "no signal" with a healthy charge usually means the USB-C port does not support DisplayPort Alt Mode, the standard that lets a USB-C port output a picture. Check your device's spec for DisplayPort, Thunderbolt or "video out" before replacing the adapter.

**Q: How do I know if my USB-C port supports video out?**
A: Look up your exact laptop or phone model and read what its USB-C port lists. A port described with DisplayPort, "DP Alt Mode", Thunderbolt 3 or 4, or "video out" can drive a display; a port that mentions only USB data speeds and charging generally cannot. The DisplayPort body calls the video feature an "Alternate Mode" extension of USB-C, which is to say it is optional and not present on every port.

**Q: Do I need an active or a powered USB-C to HDMI adapter?**
A: Usually no. The adapter mainly has to be a real video adapter, compliant with DisplayPort Alt Mode or Thunderbolt as Apple spells out, rather than a data-only dongle. Reaching for an active or powered adapter will not rescue a port that has no video output in the first place, which is the more common cause of a dead screen.

**Q: My adapter works on one laptop but not another. Why?**
A: That is the clearest sign the fault is the port, not the adapter. One laptop's USB-C port supports DisplayPort Alt Mode and the other's is data-and-charge only, so the same working adapter produces a picture on one and nothing on the other. It is the device, not the dongle, that differs.

**Q: Could it just be the cable rather than the adapter?**
A: It can, if the USB-C lead feeding the adapter is a charge-only cable or the HDMI lead on the far side is loose or damaged. Swap in leads you know are good, connected straight through, and see if the picture returns. If you want to be sure a USB-C lead carries video at all, our guide on [USB-C cables that carry video](usb-c-cable-for-monitor-explained.html) walks through how to read the label.
