---
layout: default
title: "Power & Boondocking: Making a Used Class C Genuinely Park-Ready"
nav_order: 2
parent: "Living With It"
---

# Power & Boondocking: Making a Used Class C Genuinely Park-Ready

## Why this matters for your family

The Class A chapter of this search is closed — the mission that's left standing is national and state park camping, including cross-country reach to places like Sequoia and Canyonlands, and most parks simply punish a big rig on length. That pivot changes this chapter's whole premise. It's not "how do we make a big coach comfortable for a weekend off-grid" anymore; it's **"most of the campgrounds we actually want to reach have no hookups at all, so can this smaller rig genuinely live off-grid for days at a time, with two kids and a full WFH workload aboard?"**

That's a materially harder question for a Class C than it was for a Class A, for two blunt reasons: less roof for solar, and a smaller stock generator and battery bank to begin with. This doc does the math for the $60-90k used Class C band — Jayco Greyhawk, Coachmen Leprechaun, Forest River Forester (see the [Class C landscape doc](18-class-c-landscape.html) for the model-by-model rundown) — and lays out a lithium upgrade path sized to that budget, not to the $14k-and-up shop quotes that made sense for a bigger coach.

## The park reality that drives this whole doc

Before the electrical math: know what you're actually plugging into (or not) once you're inside a national park.

- The National Park Service runs camping at **130+ park units**, and only **about a dozen — roughly 13 — have any full or partial RV hookups at all.** Everywhere else is dry camping by default. ([RVezy, USA National Parks Camping Guide](https://www.rvezy.com/blog/usa-national-parks-camping-guide); [Roadtrippers, National Park Campgrounds with RV Hookups](https://roadtrippers.com/magazine/national-park-campgrounds-with-rv-hookups/))
- Where hookup sites do exist, they're the exception inside the exception — places like Fishing Bridge RV Park (Yellowstone) and Colter Bay RV Park (Grand Teton) are full-hookup, but most of each park's other campgrounds remain hookup-free. ([Roadtrippers, National Park Campgrounds with RV Hookups](https://roadtrippers.com/magazine/national-park-campgrounds-with-rv-hookups/))
- Some parks go further and restrict or ban generators outright inside developed campgrounds, or limit them to narrow daytime windows — **Zion is a commonly cited example of a no-generator campground**, and posted generator-hour windows (commonly cited in the roughly 8-10am / 4-7pm range) are set and enforced **per park, not by a single nationwide rule.** Always check the specific park's current campground page before you go — this is guidance that changes park-by-park and season-by-season, not a fixed federal schedule. ([BlackSeries, National Park Camping 2026 Reservation Tips](https://blackseries.net/blogs/news/national-park-camping-2026-reservation-tips-blackseries))
- **What's actual law vs. what's local policy:** there's no single federal statute setting generator hours across all NPS land. The closest thing to a universal legal backstop is the general nuisance-noise prohibition at [36 CFR 261.10(i)](https://www.law.cornell.edu/cfr/text/36/261.10) (written for National Forest land, not NPS parks specifically, but illustrative of the "unreasonably disturb" standard land managers lean on). Individual park superintendents set the actual generator-hour and hookup policy for their own campgrounds, posted per-campground — that's policy/guidance, confirmed at booking or check-in, not something you can look up once for the whole system.

**The upshot:** for this family's actual mission — parks, not truck-stop overnights — boondocking capability isn't a bonus feature bolted onto a hookup-focused rig. It's core, because most of the nights that matter will be dry-camped, generator-restricted, or both.

## What Ships Stock on a Used $60-90k Class C

Unlike the Class A market, where Onan 4,000-5,500W generators and beefy 4-battery banks are common even at entry trims, a used Class C in this budget band typically ships leaner:

- **Generator:** an **Onan 4,000-watt (gasoline)** unit with auto-gen-start is the standard fit across this segment — the 2026 Jayco Greyhawk, for example, ships a 4,000W generator paired with only a **1,000W inverter** as standard equipment. ([Jayco, 2026 Greyhawk 27U](https://www.jayco.com/rvs/class-c-motorhomes/2026-greyhawk/27u/)) A 1,000W inverter is enough to run a laptop, phones, and small electronics — it is **not** enough to run a microwave or coffee maker off battery power without the generator running.
- **House battery:** stock setups on this tier commonly run **dual Group 24 AGM (lead-acid) batteries** — Coachmen's Leprechaun spec sheet lists dual Group 24 AGM as available equipment. ([search-aggregated Coachmen Leprechaun spec summary](https://coachmenrv.com/leprechaun)) Group 24 batteries are smaller than the Group 31s common on Class A coaches — typically **70-85Ah rated** per battery, so a dual-Group-24 bank is roughly **140-170Ah rated → ~70-85Ah usable** at the lead-acid 50%-discharge rule. That's meaningfully less than even the Class A Vista/Sunstar's stock bank was.
- **Solar prep:** many Class C floorplans ship "solar-ready" (a roof port and wiring stub) rather than an actual panel — Coachmen lists a 200W roof-mounted panel with 30A controller as an *optional*, not standard, add. ([search-aggregated Coachmen Leprechaun spec summary](https://coachmenrv.com/leprechaun)) Forest River's Forester line has offered a factory 190W roof solar option on some trims. ([search-sourced Forester spec reference](https://forestriverinc.com/rvs/forester/2401BDS/11999)) Don't assume a used unit has solar installed — check for an actual panel, not just a roof cap.

**The honest comparison to the old Class A math:** the Class A Vista/Sunstar's stock 2x Group 31 lead-acid bank gave roughly 100-125Ah usable. A Class C's stock 2x Group 24 bank gives roughly **70-85Ah usable — meaningfully less**, on a rig that's now doing more dry-camping, not less. Stock is even further from adequate here than it was for the coach type this family has moved away from.

## Fuel Burn on the Smaller Generator

**Onan 4000 (gasoline), the standard fit at this budget:** roughly **0.29 gal/hr at no load, 0.48 gal/hr at half load, 0.71 gal/hr at full load**, per manufacturer-cited figures — real-world moderate-load use commonly lands around 0.5 gal/hr. ([JustAnswer, Onan 4000 fuel consumption](https://www.justanswer.com/small-engine/boldt-onan-4000-microquiet-runs-uses-gallon.html); [RVForum.net, gas consumption for 4KW Onan](https://www.rvforum.net/threads/gas-consumption-for-4kw-onan-generator.812442/)) A Class C's smaller onboard fuel tank (commonly in the 55-gallon range for chassis fuel, with the generator typically drawing off the same tank on gas Class C units — confirm this per specific unit, since some builders use a separate small generator tank) still gives you a healthy multi-day runtime budget, but you're burning chassis gasoline to do it, which matters more on a rig that will already be visiting fewer fuel stops on remote park roads.

The same etiquette-vs-law distinction from the general RV-101 material applies here: **generator-hour "rules" at national and state parks are campground policy, not one nationwide statute** — confirm the specific park's posted policy before you go, and plan around the tighter of "what the park allows" and "what's decent to your camping neighbors," since national park campgrounds run denser than dispersed National Forest boondocking sites.

## The Upgrade Path, Right-Sized for a Class C at This Budget

The Class A version of this doc sized a 300-400Ah lithium bank against a big-roof solar budget. That doesn't transfer directly — a Class C at $60-90k has less roof, a smaller generator, and (per the [budget pivot](18-class-c-landscape.html)) a tighter overall spend. Here's the right-sized version.

### 1. LiFePO4 battery bank — target 200-300Ah, not 300-400Ah

A Class C house-battery compartment and the electrical bay sized around it are generally built for the stock 2x Group 24 footprint, not a big Class A battery bay — so the realistic swap target is a **200-300Ah lithium bank**, either as 12V drop-in replacements or a built-up 2-battery lithium pair. At 80-100% usable depth of discharge, that's **1,600-2,880Wh usable** — roughly double to triple the stock Group-24 lead-acid bank's ~70-85Ah (840-1,020Wh) usable capacity, without requiring a bigger battery bay than the coach already has.

**Cost, DIY parts-only (the realistic path at this budget):** a single 100Ah LiFePO4 battery from a reputable brand (Battle Born, Renogy, Epoch, Redodo) runs roughly **$650-$950**; a 200-300Ah bank (2-3 batteries) lands around **$1,500-$2,800** in battery cost alone. Add a lithium-compatible converter/charger upgrade (**$150-$400**) and, if needed, a lithium-compatible solar charge controller (**$100-$300**). All-in DIY parts for a 200-300Ah system with basic solar and charging upgrades: roughly **$2,500-$4,500** — meaningfully below the $4,000-$7,000 DIY figure the Class-A-era version of this doc cited for a bigger 300-400Ah bank, and far below shop-installed quotes that start around $14,500 for a larger system. ([Mach 1 Lithium, Lithium Battery Cost Guide 2026](https://mach1lithium.com/blogs/power-tools/lithium-battery-cost); [BatteryTrail, Battle Born vs Renogy](https://www.batterytrail.com/posts/battleborn-vs-renogy/)) Professional installation, if you'd rather not DIY it, commonly adds **$500-$1,500**. ([backuppowerhub.com, RV Lithium Battery Upgrade Guide 2026](https://backuppowerhub.com/rv-lithium-battery-upgrade/))

This is a budget that actually fits inside the $60-90k purchase-plus-upgrade math, rather than assuming a Class-A-scale accessory spend on top of a smaller rig.

### 2. Inverter/charger — upsize from the stock 1,000W

Stock inverters on this tier (1,000W per the Greyhawk spec above) can't run a microwave, coffee maker, or the workstation's charging bricks simultaneously without tripping. A **2,000-3,000W inverter/charger** (Victron MultiPlus-class, or a comparable Renogy/Xantrex unit) is the practical upgrade target — enough headroom for household loads plus the WFH desk, without trying to run the roof A/C off the inverter (that stays generator- or shore-fed, same as on a Class A). This is a smaller unit than the 3,000W commonly sized for a Class A, and correspondingly cheaper.

### 3. Rooftop solar — this is where the Class C pivot bites hardest

**Be blunt with yourselves here: a Class C roof is genuinely tighter than a Class A's**, and that's before subtracting the cab-over bunk structure, roof A/C unit(s), vents, and antenna that all compete for the same limited flat area. Realistic panel counts on a 30-32' Class C commonly land in the **150-400W range total** — forum-reported builds commonly land around 2x150W or up to roughly 300-400W with careful layout, well below the 600-1,200W a big Class A roof can carry. ([The Fit RV, How Much Solar Do I Need On My RV](https://www.thefitrv.com/rv-tech/how-much-solar-do-i-need-on-my-rv/); [DIY Solar Power Forum, Upgrading to lithium/solar on a Class C motorhome](https://diysolarforum.com/threads/upgrading-to-lithium-solar-on-a-class-c-motorhome.69198/))

Applying the same 25-40% real-world derating this doc used for the Class A case: **300W of rated Class C roof solar** might realistically deliver **180-270Wh per peak sun-hour**, or roughly **700-1,200Wh across a 4-5 hour sun window** on a good day. That's meaningfully less daily solar recharge than the Class A case — solar on a Class C should be planned as a **partial offset that stretches your battery runway and reduces (not eliminates) generator dependence**, not as a source that can fully recharge a 200-300Ah bank in a single day. Portable/ground-deployable panels are worth considering as a supplement precisely because roof space is the real constraint here, not budget.

### 4. DC-DC / alternator charging

Unchanged in principle from the Class A case: a DC-DC charger (typically 20-60A) takes power from the chassis alternator while driving and multi-stage-charges the lithium bank, isolating the starter battery. This matters even more on a park-touring itinerary — driving between campgrounds (which this family will do often, moving toward more, smaller destinations rather than settling in for a week) tops the battery bank for free on every travel day, which does real work toward the daily energy budget below.

## Tank Sizes for a Family of Four on a Class C

Class C tanks run smaller than the Class A figures this doc previously cited — expect to plan around the lower end of what a full-size coach offers:

- **Fresh water:** typically **35-50 gallons** on a 27-32' Class C, versus 55-100 gallons on a Class A. Coachmen's Leprechaun advertises roughly 40-50 gallons fresh as an above-average figure for the segment; the 2026 Greyhawk 27U spec sheet lists **42 gallons fresh**. ([Jayco, 2026 Greyhawk 27U](https://www.jayco.com/rvs/class-c-motorhomes/2026-greyhawk/27u/); [search-aggregated Coachmen Leprechaun spec summary](https://coachmenrv.com/leprechaun))
- **Grey water:** the same Greyhawk 27U lists **41 gallons** grey — close to fresh capacity, consistent with grey filling roughly as fast as fresh empties.
- **Black water:** **31 gallons** on the Greyhawk 27U — smaller than typical Class A black tanks, which matters on longer dry-camped stretches.
- General Class C ranges reported across the segment: fresh 35-60 gal, grey 31-91 gal, black 27-63 gal, with the 27-32' models this family is shopping trending toward the lower-middle of those ranges. ([RVing Know How, Typical RV Holding Tank Size](https://www.rvingknowhow.com/typical-rv-holding-tank-size/); [GoDownsize, What Size RV Holding Tank Do I Need](https://www.godownsize.com/what-size-rv-holding-tank-to-need/))

**Redoing the family-of-4 water math for these smaller tanks:** at the same conservation habits this doc assumed for the Class A case (navy showers, pump-on-demand, no running taps for dishes), a **40-42 gallon fresh tank realistically lasts 1.5-2.5 days** for two adults and two young kids — noticeably shorter than the 2-3 days estimated for a 55-60 gallon Class A tank, roughly in proportion to the smaller tank size. **Grey water remains the practical limiter, and it gets tighter faster on a Class C** — a 41-gallon grey tank against the same household usage pattern will often fill before the fresh tank runs dry, especially with two kids generating extra dish and bath water. For multi-day park stays without hookups, plan on **needing a water/dump run every 1.5-2 days**, not the 2-3 days that was realistic for the bigger coach — check whether the specific park has a potable-water fill and dump station on-site (many NPS campgrounds do, even the hookup-free ones) before assuming you'll need to leave the park entirely.

## Propane: Still Not the Constraint

This holds from the Class A version of this doc, just at smaller scale. Class C coaches typically carry a smaller built-in ASME propane tank than a Class A (commonly in the **40-60 lb range**, versus 80-100 lb on a big Class A) — the Greyhawk 27U spec sheet lists a **56 lb propane tank**. ([Jayco, 2026 Greyhawk 27U](https://www.jayco.com/rvs/class-c-motorhomes/2026-greyhawk/27u/)) At the same rule-of-thumb burn (a 30,000 BTU furnace uses about a gallon of propane per 3 hours of runtime), a 56 lb (roughly 13-gallon-equivalent) tank still comfortably covers **several days to a week-plus** of typical boondocking use — shorter than the Class A's multi-week margin, but still longer than your water or battery runway in every realistic scenario, except a long, cold winter stretch running the furnace overnight for many consecutive nights.

## The WFH Reality Check, Redone for a Class C

**Workstation load is unchanged by chassis type:** laptop (~30-70W) plus two external monitors (~15-40W combined) runs roughly **100W** for 8-10 working hours — call it **~900Wh/day** for the desk alone, same as the Class A case. ([Habitatista, low-power monitors for RV remote work](https://www.habitatista.com/468841/low-power-monitors-for-remote-work-in-an-rv/))

**Household load** — water pump, LED lighting, device charging, furnace fan, occasional TV — for a family of four commonly runs **1,000-2,000Wh/day**, the same range cited previously; nothing about a smaller coach meaningfully reduces this line item. ([SunGold Solar, RV Solar System Cost Breakdown 2026](https://www.sungoldsolar.com/blogs/rv-solar-system-cost-breakdown-2026/))

**Combined realistic daily draw: roughly 1,900-2,900Wh/day**, before A/C — essentially the same total as the Class A case, because the WFH and household loads don't scale down with the coach.

Compare that to what a Class C actually offers:

- **Stock 2x Group 24 AGM (~840-1,020Wh usable):** gone in well under half a day with the workstation running. On a Class C, stock lead-acid isn't a "weekend system" the way it arguably still was on a 4-battery Class A Adventurer — it's closer to a single-shift system. You will be running the generator daily, full stop, if you're dry-camping and working.
- **Upgraded 200-300Ah lithium (1,600-2,880Wh usable) + 300W solar:** solar realistically contributes 700-1,200Wh/day toward the 1,900-2,900Wh draw — a meaningful dent, not a full offset. Expect the battery bank to **drain gradually even with solar running**, landing you at roughly **1-2 days of genuinely generator-free work**, and needing the generator (or a drive day, via the DC-DC charger) every couple of days to top back up. That's a real improvement over stock, but it's a shorter off-grid runway than the Class A case's "mostly holds steady" result — **the smaller roof is the binding constraint, not the battery bank.**

**The A/C caveat carries over unchanged, and is if anything tighter:** a single RV A/C draws roughly 1,200-1,800W continuously — running it overnight will exhaust a 200-300Ah lithium bank in a couple of hours and isn't realistically solar-supportable at this scale. Plan generator use (where the park allows it, within posted hours) for hot-night A/C, or accept warmer nights when a park restricts or bans generator use — Zion-style no-generator campgrounds mean this is a real trade-off on parts of this itinerary, not a hypothetical.

## Bottom line for this family

1. **A used Class C ships leaner than the Class A coaches this family previously considered** — a 4,000W Onan generator with just a 1,000W stock inverter, and a smaller dual-Group-24 lead-acid bank (~70-85Ah usable) than the Class A's Group-31 setup. Don't assume "boondocking ready" on a spec sheet; check the actual installed battery count and inverter size on any used unit you tour.
2. **Boondocking capability is now core to the mission, not a reserve feature** — roughly 117 of the 130+ NPS units with camping have no hookups at all, and some parks restrict or ban generators outright. Budget the lithium upgrade as part of the purchase, the same way you'd budget an inspection.
3. **Right-size the lithium bank to 200-300Ah, not 300-400Ah** — the Class C's smaller battery bay doesn't support the bigger Class A-style bank without custom fabrication, and a smaller bank fits the $60-90k budget: roughly **$2,500-$4,500 in DIY parts**, well under both the old Class A DIY figure and any shop-installed quote.
4. **Solar is the tightest link in this system, not the battery.** A 30-32' Class C roof realistically carries 150-400W of panel versus 600-1,200W on a Class A — plan on solar meaningfully stretching your runway (roughly 700-1,200Wh/day on a good day) rather than fully recharging the bank. Portable/ground panels are worth a look precisely because roof space, not money, is the constraint.
5. **Water is a shorter runway than it was on the Class A shortlist** — a 40-42 gallon fresh tank lasts roughly 1.5-2.5 days for this family with conservation habits, versus 2-3 days on a bigger coach's 55-60 gallon tank. Plan dump/fill stops more frequently; check each park's on-site water/dump station before assuming a trip outside the park is needed.
6. **Propane still isn't your limiting factor** — a smaller 40-60 lb Class C tank still comfortably outlasts your water and battery runway in nearly every realistic scenario.
7. **Set the A/C expectation early and honestly:** the right-sized system supports genuinely sustainable off-grid workdays and evenings without A/C; overnight air conditioning while boondocking still means the generator, subject to whatever that specific park allows.

## Sources

Primary sources (manufacturer/dealer spec sheets, federal regulation text, NPS-adjacent statistics) are marked **[primary]**; forum, retailer-blog, and travel-guide write-ups are marked **[community]** and should be read as real-owner or industry-aggregated experience, not verified engineering data.

**National park hookup and generator reality**

- [RVezy: USA National Parks Camping Guide](https://www.rvezy.com/blog/usa-national-parks-camping-guide) **[community]** — the "13 of 130+ NPS camping units have hookups" figure.
- [Roadtrippers: Where to Find National Park Campgrounds with RV Hookups](https://roadtrippers.com/magazine/national-park-campgrounds-with-rv-hookups/) **[community]** — confirms full-hookup sites (Fishing Bridge, Colter Bay) are the rare exception, not the norm.
- [BlackSeries: National Park Camping 2026 Reservation Tips](https://blackseries.net/blogs/news/national-park-camping-2026-reservation-tips-blackseries) **[community]** — generator-hour windows and no-generator parks (e.g., Zion), framed as per-park policy.
- [36 CFR 261.10(i), Cornell LII](https://www.law.cornell.edu/cfr/text/36/261.10) **[primary]** — federal nuisance-noise standard (National Forest land; cited here as the general legal backstop, not an NPS-specific rule).

**Stock Class C specs**

- [Jayco: 2026 Greyhawk 27U](https://www.jayco.com/rvs/class-c-motorhomes/2026-greyhawk/27u/) **[primary — manufacturer]** — stock 4,000W generator, 1,000W inverter, 42 gal fresh / 41 gal grey / 31 gal black, 56 lb propane.
- [Coachmen RV: Leprechaun](https://coachmenrv.com/leprechaun) **[primary — manufacturer, search-aggregated]** — dual Group 24 AGM battery option, optional 200W roof solar, 40-50 gal fresh water range.
- [Forest River: 2026 Forester 2401BDS](https://forestriverinc.com/rvs/forester/2401BDS/11999) **[primary — manufacturer, search-sourced]** — reference for factory solar-prep option on the Forester line.

**Generator fuel burn**

- [JustAnswer: How Many Hours Will an Onan 4000 Watt Generator Last?](https://www.justanswer.com/small-engine/boldt-onan-4000-microquiet-runs-uses-gallon.html) **[community]** — 0.29/0.48/0.71 gal/hr no-/half-/full-load figures.
- [RVForum.net: Gas Consumption For 4KW Onan Generator](https://www.rvforum.net/threads/gas-consumption-for-4kw-onan-generator.812442/) **[community]** — real-world moderate-load consumption around 0.5 gal/hr.

**Lithium battery cost**

- [Mach 1 Lithium: Lithium Battery Cost Guide 2026](https://mach1lithium.com/blogs/power-tools/lithium-battery-cost) **[community — retailer]** — per-Ah and per-battery pricing used for the 200-300Ah bank estimate.
- [BatteryTrail: Battle Born vs Renogy](https://www.batterytrail.com/posts/battleborn-vs-renogy/) **[community]** — brand-specific pricing (Battle Born ~$799-$949/100Ah; Renogy ~$630-$800/100-200Ah).
- [backuppowerhub.com: RV Lithium Battery Upgrade Guide 2026](https://backuppowerhub.com/rv-lithium-battery-upgrade/) **[community]** — professional installation cost range ($500-$1,500) and converter/charger upgrade costs.

**Solar sizing on a Class C roof**

- [The Fit RV: How Much Solar Do I Need On My RV?](https://www.thefitrv.com/rv-tech/how-much-solar-do-i-need-on-my-rv/) **[community]** — typical Class C solar wattage ranges (150-400W).
- [DIY Solar Power Forum: Upgrading to lithium/solar on a Class C motorhome](https://diysolarforum.com/threads/upgrading-to-lithium-solar-on-a-class-c-motorhome.69198/) **[community]** — real owner Class C solar build reports informing the roof-space constraint.

**Tank sizes**

- [RVing Know How: Typical RV Holding Tank Size](https://www.rvingknowhow.com/typical-rv-holding-tank-size/) **[community]** and [GoDownsize: What Size RV Holding Tank Do I Need](https://www.godownsize.com/what-size-rv-holding-tank-to-need/) **[community]** — general Class C fresh/grey/black tank ranges.

**WFH load (carried forward, unchanged by chassis type)**

- [Habitatista: low-power monitors for RV remote work](https://www.habitatista.com/468841/low-power-monitors-for-remote-work-in-an-rv/) **[community]** — laptop/monitor wattage for the workstation estimate.
- [SunGold Solar: RV Solar System Cost Breakdown (2026)](https://www.sungoldsolar.com/blogs/rv-solar-system-cost-breakdown-2026/) **[community — manufacturer blog]** — household daily-load estimates.

**Cross-references**

- See the [Class C landscape doc](18-class-c-landscape.html) for the model shortlist (Jayco Greyhawk, Coachmen Leprechaun, Forest River Forester) and the frozen $60-90k budget band this doc's upgrade costs are sized against.
