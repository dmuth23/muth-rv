---
layout: default
title: "Working Remotely From the Rig: Internet, Power, and a Desk That Survives the Highway"
nav_order: 7
---

# Working Remotely From the Rig: Internet, Power, and a Desk That Survives the Highway

For most families shopping a used Class A, internet is a nice-to-have. For yours, it's a hard requirement: Doug's paycheck depends on a stable connection every workday, from campgrounds with full hookups and, just as often, from spots with no hookups at all. That changes the shopping list. You're not buying "RV WiFi" — you're building a small, redundant home-office network that happens to live in a vehicle, plus a desk sturdy enough to survive 55 mph on the Garden State Parkway and quiet enough for a 9 a.m. stand-up. This piece covers both halves: the connectivity stack, and the physical workspace.

## Why redundancy, not just "get Starlink"

The [Mobile Internet Resource Center (MIRC)](https://www.rvmobileinternet.com/guides/starlink-rv-boat/) is the closest thing this hobby has to a canonical, non-affiliate-driven source — run by full-time RVers/tech journalists (the Technomadia team) who've tested this gear for over a decade. Their core finding, repeated across their [Starlink guide](https://www.rvmobileinternet.com/guides/starlink-rv-boat/) and [Peplink + Starlink guide](https://www.rvmobileinternet.com/guides/peplink-starlink/), is simple: **Starlink and cellular fail in different places, so pair them.** Starlink struggles under tree canopy, in narrow canyons, and during brief outages or firmware updates. Cellular struggles where there's no tower coverage at all, or in dead zones behind terrain. Combine them and each covers the other's blind spots. For someone whose job depends on being online at a specific hour, MIRC treats this pairing as the standard, not the deluxe option — and that's the right frame for your family.

## The satellite half: Starlink

**Which hardware.** Three current Starlink kits matter for RV use (prices and specs current as of mid-2026, and Starlink reprices and revises hardware often, so treat these as a snapshot, not gospel):

| Kit | Price | Weight | Power draw | Best fit |
|---|---|---|---|---|
| **Mini** | $249 | ~2.4 lbs | ~18–20W average (drops further after a 2026 firmware update cut power draw roughly 25% on both Mini and Standard) | Portable, set-up/tear-down at each stop |
| **Standard (v4/4X)** | $349 | ~6.4 lbs | ~25–35W | Portable kickstand or semi-permanent mount |
| **Performance (Gen 3)** | $1,999 | ~11.5 lbs | ~70W | Heaviest-duty conditions; supports both portable and permanent mounts |

Source: [MIRC Starlink hardware and pricing guide](https://www.rvmobileinternet.com/guides/starlink-rv-boat/).

For a 35-ft gas Class A, most owners land on the **Standard dish**, not the Performance model — mainly on cost and weight, not because the Performance dish is roof-locked. Per MIRC's own guide, the current Performance (Gen 3) dish supports a variety of mounts, including portable flat and wedge mounts, not just permanent installation — that "not intended for repeated setup/teardown" caveat applied to the now-discontinued Gen 2 Flat High Performance dish, not the current model ([MIRC Starlink guide](https://www.rvmobileinternet.com/guides/starlink-rv-boat/)). Even so, the Performance dish still eats more roof space and cost than most families need, which is the real reason it's overkill here. The Standard dish sets up on its kickstand in a couple of minutes and stores in a basement bay when you're driving. If you want it semi-permanent on the roof, the [Winegard RS-3000](https://www.trioflatmount.com/blogs/news/how-to-install-starlink-mini-on-your-rv-roof-no-drill-required) (~$79–99) and similar Pace International mounts are the common no-drill options for the Standard dish; the lighter Mini can go on VHB landing pads, rubber-coated magnets, or heavy-duty suction cups instead of a permanent bracket. Either way, budget the mounting hardware ($70–100) as a separate line item from the dish itself — it rarely comes bundled.

**Which plan.** Starlink's RV-specific service is called **Roam**. As of mid-2026 the tiers are roughly:

- **Roam 100GB** — ~$55/month, full speed to the cap then throttled
- **Roam 300GB** — ~$80/month
- **Roam Unlimited** — ~$175/month, no hard cap, higher priority than the capped tiers
- (For comparison, Starlink's home-style **Residential Max** plan runs ~$130/month but isn't designed for mobile use)

Source: [MIRC](https://www.rvmobileinternet.com/guides/starlink-rv-boat/), cross-checked against [MIRC's Roam 300GB plan announcement](https://www.rvmobileinternet.com/new-starlink-roam-300gb-plan-for-80-mo-international-changes-coming/).

Do the math before picking a tier: a single hour of HD video calling runs roughly 0.5–1.5 GB depending on resolution and how many cameras are on. A full workday of back-to-back meetings, screen shares, and normal web/email traffic can easily clear 3–5 GB a day. Multiply that across a 20-workday month and you're at 60–100+ GB from video calls *alone*, before the kids stream a movie during a rain day or a software update runs in the background. **The 100GB plan is genuinely tight for a full-time remote worker with a family also online** — this is exactly the scenario Roam Unlimited exists for. Most full-timers who work from the road choose Unlimited for that reason, even though it's the most expensive tier. Note that "unlimited" carries a fair-use clause: Starlink can deprioritize accounts using several terabytes a month, which a single working adult's household traffic won't come close to.

There's also a **$5/month standby mode** for weeks the rig is parked and unused — useful for a family that isn't full-timing, since you won't want to pay $175/month year-round for a rig that goes out on selected weekends and a few longer trips.

**One caveat, and it's a real one:** in early 2026, Starlink's standby/paused plan tightened its terms around in-motion use — read the current fine print at signup rather than assuming last year's rules still apply ([5gstore's writeup](https://5gstore.com/blog/2026/03/07/starlink-standby-mode-no-motion-2026/)).

## The cellular half: carrier plans and routers

**Carrier plans (mid-2026 snapshot).** No single carrier wins everywhere in the U.S., which is the whole argument for redundancy:

- **T-Mobile** — Go5G Next includes 100GB of hotspot for ~$100/month; Experience Beyond bumps that to 250GB high-speed. T-Mobile's dedicated 5G Home Internet gateway is genuinely uncapped for ~$50/month where available, though "where available" is the catch for a mobile rig.
- **Verizon** — Unlimited Ultimate includes 200GB of premium hotspot for ~$90/month, with another 100GB addable for ~$10/month.
- **AT&T** — its flagship unlimited plan includes 250GB of high-speed hotspot; cheaper tiers include little to none, so check the fine print before assuming hotspot is included.

Source: [US Mobile carrier comparison](https://www.usmobile.com/blog/best-cell-phone-plans-february-2026-att-vs-verizon-vs-t-mobile-vs-us-mobile/).

MIRC's [top-pick data plans page](https://www.rvmobileinternet.com/planpicks/) is the best place to check current plan terms before you buy, since carriers change hotspot allowances and throttling rules multiple times a year. A common, budget-conscious pairing among full-timers is T-Mobile as the primary line (generally the best rural coverage-per-dollar) plus a cheap MVNO line on Verizon's network as backup — Visible, for instance, runs around $25/month for unlimited hotspot capped at 5 Mbps, which is slow but enough to keep a video call alive if the primary connection drops. Two networks running for roughly $125/month total is often cheaper than a single "premium" unlimited plan, and it buys you actual carrier diversity — the point of the whole exercise.

**Routers: why a Peplink (or similar) matters.** A phone hotspot works for casual use, but it's a single point of failure and a hassle to manage from a desk. MIRC's [Peplink + Starlink guide](https://www.rvmobileinternet.com/guides/peplink-starlink/) explains the alternative: a dedicated mobile router — the [Peplink MAX Transit](https://www.rvmobileinternet.com/gear/pepwave-max-transit/) line is the community's long-standing default — that takes in Starlink over Ethernet, one or two cellular SIMs, and campground WiFi, then automatically fails over between them or (on higher-tier models) bonds them together via Peplink's SpeedFusion technology so an active video call doesn't drop when one connection blips. Pricing runs roughly $500–700 for a capable single/dual-modem unit, up into the thousands for higher-throughput bonding models — a real expense, but one that buys you the thing a remote-work rig actually needs: a network that fails over in seconds instead of a scramble to find and re-tether a phone mid-meeting. If a full Peplink setup feels like overkill to start, a simpler cellular router with dual SIM slots and a basic failover rule is a reasonable starting point, upgradeable later.

**Signal boosters (a different tool, not a replacement).** A [weBoost](https://www.weboost.com/boosters/vehicle-rv) cellular booster amplifies whatever signal is already present — it can't create signal where a tower doesn't reach at all — but in marginal-signal areas it can turn a barely-usable connection into a good one. The Drive Reach RV model (roof-mounted omnidirectional antenna, works parked or driving) is the common choice; the stationary Destination RV model with its 24-ft telescoping pole suits basecamp situations better. Boosters and routers solve different problems — a booster helps a weak-but-present signal, a multi-WAN router helps you survive when one *provider* fails entirely. Most experienced full-timers end up with both, but the router/failover setup is the higher priority.

## The workspace: building a desk that survives the highway

**Where the desk goes.** In a 30-35 ft gas Class A, three spots come up again and again in real builds documented by [RV Inspiration's dinette/desk roundup](https://rvinspiration.com/makeovers/office/6-rv-dinette-desk-combinations/) and [RV Inspiration's broader desk ideas piece](https://rvinspiration.com/renovate/desk-rv-office-work-space/):

1. **Dinette conversion.** The booth dinette common to Class A floorplans is the easiest starting point — it's already wired for power nearby, already has seating, and is sized about right for a desk. The simplest version just swaps the removable tabletop insert for a fixed desk surface and treats mealtimes as "move the laptop." A step up is a slide-out or fold-down desk extension that gives you more surface when working and folds away for dinner and the kids' art projects.
2. **Wall-mounted fold-down desk.** Common in slide-outs or unused wall space — folds flat against the wall when not in use, which matters in a family rig where floor space competes with kids' gear.
3. **Custom-built dedicated desk.** Full-timers who prioritize the office often sacrifice a piece of dinette or a closet entirely for a built desk with real storage. That's a bigger renovation but the most stable, ergonomic result — realistic for Doug given he's handy and plans his own upgrades, and worth considering once you own the rig and know your actual floorplan.

Given your family's plan (Doug remote-working daily, two young kids also needing table space for meals and activities), a **hybrid** — a dinette that converts cleanly between "kids' lunch table" and "dad's desk," possibly with an add-on slide-out shelf just for the monitors and keyboard — tends to work better in practice than a single fixed desk that permanently eats the only table in the rig.

**Mounting dual monitors so they survive the road.** This is the detail people get wrong: a monitor arm rated for a home office is not rated for highway vibration, and a standard swing arm will slowly walk itself loose over a season of driving. What actually holds up, per current RV-specific mount listings, is hardware built for exactly this problem:

- **Locking/toothed-gear arms** — the [Mount-It! MI-429](https://www.mount-it.com/products/mount-it-full-motion-single-arm-rv-tv-mount-mi-429) uses a geared, knob-tightened joint specifically designed to resist vibration-induced drift, rather than a friction joint that loosens over time.
- **Dual-plate quick-release systems** — mounts like the [Kanto RV250G](https://kantomounts.com/product/rv250g/) or [USX Mount lockable RV mount](https://www.amazon.com/USX-MOUNT-Lockable-Motorhomes-Vesa100x100mm/dp/B093SX1M8T) use a fixed wall plate plus a separate mounting plate on the monitor itself, so the monitor locks/unlocks from the arm in one motion — meaning you can pull both monitors off the wall entirely and stow them in a cabinet or under the bed for highway driving, which is the safest way to protect them from vibration rather than trusting any arm to hold rock-solid at 65 mph.
- **VESA compatibility** — check your monitors are 75mm or 100mm VESA before buying (most 22-27" office monitors are), and note that RV-rated arms typically top out around 32-33 lbs capacity, which comfortably covers two lightweight 24" monitors.

The practical pattern that shows up across full-time-remote-worker RV setups: mount on locking arms while parked and working, unmount and stow in a padded slot (a repurposed drawer, a soft case wedged in a cabinet) for any drive over a few miles. It's an extra 60 seconds of routine, but it's cheaper than replacing a cracked monitor.

**Video-call acoustics: the AC problem, not the generator.** The noise that actually wrecks a video call in a parked Class A on a July afternoon is the **roof air conditioner**, not the generator — most people assume the reverse. A rooftop AC's compressor cycling on and off, plus the ducted fan, is loud enough at close range that in enclosed RVs, some owners report not being able to hear a conversation partner 15 feet away while it's running ([RV Travel forum discussion](https://www.rvtravel.com/my-rvs-roof-air-is-so-noisy-i-cant-hear-my-husband-15-feet-away-rvdt-2094/)). For **ducted** AC systems (common in Class A coaches, versus the open ceiling-vent style in smaller rigs), an AC silencer — a cotton-lined duct insert that muffles airflow noise by roughly 8-10 dB — is a real, documented fix ([The Fit RV's AC silencer install and test](https://www.thefitrv.com/rv-tech/installing-and-testing-the-rv-ac-silencer/)). It won't touch the low compressor hum, but it meaningfully cuts the rushing-air noise that a microphone picks up. Practically: put the desk as far from the AC supply vent as the floorplan allows, use a headset with a noise-canceling mic instead of relying on a laptop's built-in mic, and if a call really matters, it's fine to just cycle the AC off for 30 minutes — a Class A's thermal mass holds temperature for a while, especially with the shades down.

**Generator noise matters for a different reason** — it's what powers the AC (and everything else) when you're boondocking, not connected to shore power. If a call happens to run during a boondocking stretch and the generator needs to run, an inverter generator like the Honda EU2200i runs around 48-58 dB at 25 feet under light load — described as roughly normal-conversation volume — versus 70+ dB for an open-frame contractor-style generator ([source comparison](https://erayakpower.com/blogs/rv-generator-guide/rv-generator-noise-levels)). Most Class A gas coaches ship with a built-in enclosed generator (often a Onan) that's reasonably quiet by design; it's worth confirming the specific generator's noise rating when you tour a used rig, since older or poorly maintained units run louder.

## The power budget: running the desk off-grid

This is where "genuine boondocking capability" and "full-time remote work" intersect, and it's worth doing the arithmetic rather than guessing.

**Daily draw for the desk alone**, using typical figures gathered above:

| Item | Typical draw |
|---|---|
| Laptop | 45–100W |
| Two external monitors | 40–100W combined (efficient models run 12-16W each) |
| Starlink Standard | 25–35W (Mini: 18-20W) |
| Peplink-class router | ~10-15W |
| Desk lighting | 10–20W |

Call it roughly 150-250W continuous while actively working — a figure built from the component draws above rather than pulled from a single source, so verify current specs on your actual gear before relying on it. Over an 8-hour workday that's **1.2–2.0 kWh (1,200-2,000 Wh) just for the desk** — before the fridge, water pump, lighting elsewhere in the coach, or the kids' devices. [Battle Born's boondocking sizing guide](https://battlebornbatteries.com/blogs/articles/rv-boondocking-101-sizing-an-off-grid-power-system) recommends a personalized electrical audit rather than a fixed number, and doesn't itself publish a household total; a commonly cited full-timer figure of roughly 2,000–3,500 Wh/day (DC fridge, Starlink, laptop-based work) is reported elsewhere but not confirmed in that guide's text, so treat it as a rough planning range rather than a sourced benchmark — verify current figures against your own audit before sizing a system. Directionally, the desk still reads as a meaningful chunk of a full boondocker's daily budget, not an afterthought.

**What that means for the battery/solar system**, per the same sources: 200Ah of lithium (LiFePO4) battery paired with 400W of rooftop solar is commonly cited as enough for 2-3 days of laptop-and-internet work without sun, and is a reasonable *starting* target for a family that boondocks occasionally rather than full-time. If you add the monitors and general household draw on top, bumping to 300-400Ah of battery is the more comfortable number, especially in the more overcast stretches of the Northeast/Mid-Atlantic where solar recovery is slower than in the Southwest. Run any monitor or laptop charger through a **pure sine wave inverter** (1500W+ is a common recommendation) rather than a modified-sine unit — sensitive electronics like laptop power supplies and some monitors can run hot, buzz, or degrade faster on modified sine wave power, and add roughly 10-15% for inverter conversion losses when budgeting Wh.

None of this needs to be solved on day one of ownership — solar and lithium upgrades are exactly the kind of project a handy owner (that's Doug) typically adds to a used gas Class A after purchase, and most used rigs in this size/price range don't come with boondocking-grade power systems already installed. Budget for it as a first-year project rather than expecting it in the purchase price.

## Bottom line for this family

- **Buy both Starlink and a cellular backup — don't pick one.** MIRC's redundancy doctrine is the right model for a paycheck-dependent setup: Starlink covers open sky and remote spots, cellular covers what Starlink can't (tree cover, brief outages), and a router that fails over between them automatically is worth the money.
- **Starlink Standard dish + Roam Unlimited (~$175/mo) is the realistic default**, not the Mini or the capped 100GB plan — a full month of video calls alone can approach or exceed 100GB, and the dish itself is a one-time ~$349 plus mount versus the $1,999 Performance dish, which isn't necessary for this use case.
- **Add one cellular line as backup, ideally on a different network than your everyday phones** — T-Mobile primary plus a cheap Verizon-network MVNO backup (~$125/month combined) is a proven, budget-friendly pattern.
- **A Peplink-class router (~$500-700+) is the piece that actually delivers "redundancy"** — without it, "backup internet" means physically swapping cables mid-meeting, which defeats the purpose.
- **Plan the desk as a convertible dinette or fold-down wall unit**, not a fixed installation, so the space still works as a family table — and use RV-rated locking/quick-release monitor mounts, unmounting and stowing the monitors for any real drive.
- **The AC, not the generator, is the video-call noise problem** — position the desk away from the supply vent, consider a duct silencer if the coach has a ducted system, and use a headset mic.
- **Budget for a battery/solar upgrade as a first-year project, not a purchase requirement** — 200-400Ah of lithium plus 400W of solar is the realistic target for a desk that includes dual monitors, and most used rigs in your price range won't arrive with that already installed.

## Read more

- **[MIRC — Starlink Satellite Internet for Mobile RV and Boat Use](https://www.rvmobileinternet.com/guides/starlink-rv-boat/)** — the canonical, continuously updated Starlink-for-RV reference; start here before any purchase.
- **[MIRC — Peplink and Starlink for RV & Boat Mobile Internet](https://www.rvmobileinternet.com/guides/peplink-starlink/)** — the specific guide on building a bonded/failover network, written by the people who literally wrote the book on mobile internet.
- **[MIRC — Top Pick Cellular Data Plans for RVers](https://www.rvmobileinternet.com/planpicks/)** — kept current as carriers change hotspot terms; check this before locking in a cellular plan.
- **[MIRC — Alternatives to Starlink Mobile Internet](https://www.rvmobileinternet.com/guides/alternatives-to-starlink/)** — useful if Starlink's fair-use policy or pricing changes again before you buy.
- **[Technomadia — Tour of Our RV Office](https://www.technomadia.com/2017/02/tour-of-our-rv-office-computer-monitors-and-rolling-chairs-in-motion/)** — a real dual-monitor, full-time-remote-work RV office from the founders of MIRC; dated but the physical-setup thinking still holds up.
- **[RV Inspiration — 6 RV Dinette/Desk Combinations for Working](https://rvinspiration.com/makeovers/office/6-rv-dinette-desk-combinations/)** — photo-based roundup of real dinette-to-desk conversions at different budget/complexity levels.
- **[The Fit RV — Installing and Testing the RV AC Silencer](https://www.thefitrv.com/rv-tech/installing-and-testing-the-rv-ac-silencer/)** — a hands-on test of the actual fix for ducted-AC airflow noise, with before/after decibel numbers.
- **[Battle Born Batteries — RV Boondocking 101: Sizing an Off-Grid Power System](https://battlebornbatteries.com/blogs/articles/rv-boondocking-101-sizing-an-off-grid-power-system)** — the clearest walkthrough of matching battery/solar size to actual daily watt-hour needs.
- **[US Mobile — Best Cell Phone Plans 2026: AT&T vs Verizon vs T-Mobile](https://www.usmobile.com/blog/best-cell-phone-plans-february-2026-att-vs-verizon-vs-t-mobile-vs-us-mobile/)** — a current, non-carrier-affiliated plan comparison, useful for the cellular-backup decision.
- **[weBoost — RV Cell Signal Boosters](https://www.weboost.com/boosters/vehicle-rv)** — manufacturer page, useful for understanding what a booster does (and doesn't) fix versus a router/failover setup.
