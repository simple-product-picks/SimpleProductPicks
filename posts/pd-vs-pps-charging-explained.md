# PD vs PPS Charging Explained

## PPS is part of PD, not a rival to it

The usual way these two get explained is also the most misleading: as two competing charging standards you have to choose between. PPS, short for Programmable Power Supply, is an optional feature defined inside USB Power Delivery itself. A charger that lists PPS is a PD charger that happens to support one extra mode, so every PPS charger is also a PD charger, while most PD chargers never do the PPS part at all.

That one fact clears up most of the confusion. You are never really choosing PD or PPS. You are choosing a PD charger, and then checking whether it also does the extra trick that a handful of phones want.

## What a plain PD charger does

USB Power Delivery is the quick negotiation your charger and your device run the moment you plug in. It is the phone that leads: the USB-IF designed Power Delivery so a device draws only the power it needs from whatever the charger can supply, requesting the voltage it wants rather than having one forced on it.

In its ordinary form, that offer is a short menu of fixed steps. The engineering primer at EDN lists the standard voltages a PD charger provides as 5, 9, 12, 15 and 20V. Your phone reads the menu, takes the highest step it can safely use, and charges at that voltage. It is a solid system, and it is what the large majority of chargers and phones rely on every day.

## What PPS adds

PPS turns that short menu into something closer to a slider. Instead of jumping between fixed voltages, a PPS charger lets the phone dial in a voltage in tiny increments and keep changing it as charging goes on. EDN's primer puts figures on it: PPS arrived with "the USB PD 3.0 specification", and its "output voltage can be programmatically adjusted in increments of 20 mV" across a 3.3 to 21V range, where a plain PD charger would only offer the fixed steps.

The reason a phone maker cares is precision. A battery's ideal charging voltage shifts as it fills, and PPS lets the phone keep asking for close to the exact voltage it wants at each moment, instead of settling for the nearest fixed step. Just as importantly, PD 3.0 still keeps those fixed voltages too, so a PPS charger behaves like any other PD charger for everything that never asks for the programmable mode.

## Which phones actually ask for PPS

For most people, PPS only earns its place if they own a phone that uses it, and the clearest example is Samsung. Android Authority describes Samsung's Super Fast Charging as "based on the newer USB PD Programmable Power Supply (PPS) standard", and notes that without it "a standard USB PD charger will be capped at 18W" whatever the phone can otherwise manage. So on a Galaxy, whenever it charges faster than a plain PD charger allows, it is PPS the phone is reaching for.

Google's Pixel phones sit in the same camp. Google's support page tells Pixel owners to use "any Programmable Power Supply (PPS) power adapter rated for 30W or more" for fast charging, and treats an ordinary "USB Power Delivery (PD) adapter rated for 15W or more" as the slower fallback. Apple's iPhones are the notable absence from this list: neither Samsung's PPS requirement nor Google's applies to them, so our [iPhone charger guide](best-charger-for-iphone-17-uk.html) never goes looking for PPS at all.

## What it means when you are buying a charger

The takeaway is small but real: read the spec line, not just the wattage. If you have a recent Samsung Galaxy or Pixel, a charger that says only "PD 45W" is not the same promise as one that says "PD 45W with PPS". The first can quietly hand your phone a slower charge while looking identical on the box. That single detail is what our [Samsung charger guide](best-charger-for-samsung-s24-uk.html) is built around.

For everyone else, PPS is a nice-to-have rather than a must, and plain wattage still sets your charging speed. That is a separate axis from the protocol: how many watts you need is what our [65W GaN charger guide](best-65w-gan-charger-uk.html) and [100W GaN charger guide](best-100w-gan-charger-uk.html) sort out, while what the block is physically built from is the subject of our [GaN chargers explainer](gan-chargers-explained.html). PD versus PPS sits apart from both, because it is only about the deal the two ends strike, and it rarely needs explaining alongside them.

## FAQ

**Q: Is PPS better than PD?**
A: It is not really a fair comparison, because PPS is a part of PD, not an alternative to it. A PPS charger is a PD charger with one extra mode. The honest question is not "PD or PPS" but "does this PD charger also support PPS", and that only matters if your phone asks for it.

**Q: Do I actually need a PPS charger?**
A: Only if you have a phone that uses PPS for its fastest charging, which today mainly means recent Samsung Galaxy and Google Pixel models. Android Authority notes a Samsung phone drops to a capped speed on a plain PD charger, and Google steers Pixel owners to a PPS adapter for full speed. If you have neither, an ordinary PD charger of the right wattage is all you need.

**Q: Will a PPS charger still charge a phone that does not use PPS?**
A: Yes. Because a PPS charger is a PD charger underneath, it falls back to the normal fixed voltages for any device that never requests the programmable mode, iPhones included. Buying PPS never costs you compatibility, it just adds a feature some phones will use and others will ignore.

**Q: How can I tell whether a charger supports PPS?**
A: The wattage alone will not tell you, so look at the spec sheet. A PPS charger states it explicitly, usually alongside a voltage range such as 3.3 to 21V, while a plain PD charger only lists its fixed outputs. If the listing never mentions PPS, assume it does not have it.
