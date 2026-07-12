---
layout: default
title: "Power & Boondocking: Making a Gas Class A Genuinely Off-Grid Capable"
nav_order: 8
---

# Power & Boondocking: Making a Gas Class A Genuinely Off-Grid Capable

## Why this matters for your family

You've told us the plan: mostly campgrounds with electric and water hookups, but you want **real** boondocking capability in reserve — the freedom to pull into a national forest dispersed site or a Harvest Host without worrying about the power going dead by dinner. Layer onto that a constraint most RV shoppers don't have: **Doug works full-time remote from the rig**, with two monitors that need to stay lit for 8-10 hours a day, every workday, regardless of where you're parked. That's not a "nice to have" — it's a hard daily load that stock RV electrical systems were never designed around, because they were designed for weekend warriors running a few lights and a furnace fan, not a home office.

The good news: every gas Class A you're considering (Sunstar, Vista, Adventurer) ships with a lead-acid-and-generator system that's fine for weekends but genuinely inadequate for your use case. The *also*-good news: this is one of the most well-trodden DIY upgrade paths in the RV world, with mature parts, established installers if you want help, and real cost numbers below $10K for a system that changes what the rig can actually do. This document lays out what you get stock, what it actually supports, and the upgrade path that gets you to comfortable, repeatable off-grid stays — including the WFH load.

A note on scope: this doc is written around a **gas Class A**, but the electrical logic here is chassis-agnostic — the same lithium/inverter/solar/DC-DC path applies just as well to a diesel pusher (see the [diesel primer](17-diesel-primer.html)) or a 30-ft-plus Class C (see the [Class C landscape](18-class-c-landscape.html)), both of which are now on your list. Diesel coaches often ship with larger house-battery and inverter provisions to begin with, but the boondocking math below doesn't change. If you end up towing a car for around-town errands (the [towing-a-car doc](19-towing-a-car.html) covers the RAV4 and Tucson), that's a mobility question, not a power one — it doesn't touch anything here.

## What Ships Stock: Lead-Acid + a Big Gas Generator

All three Winnebago gas Class A lines you liked use the same basic recipe, just scaled differently:

- **Winnebago Vista/Sunstar (base):** 2x deep-cycle Group 31 marine/RV batteries (lead-acid), a 2,000-watt inverter/charger, and a 4,000-watt gas generator standard (a 5,500-watt generator plus 50-amp shore cord is available as part of a "Cooling Upgrade Package" with dual A/C). ([RVUSA spec sheet, 2026 Sunstar 31B](https://www.rvusa.com/rv-guide/2026-winnebago-sunstar-31b-class-a-specs-fp20536); [Lichtsinn RV blog](https://www.lichtsinn.com/blog/winnebago-vista-and-sunstar-29v-feature-overview/))
- **Winnebago Adventurer:** 4x deep-cycle Group 31 batteries and a 2,000-watt inverter/charger — double the stock lead-acid of the Vista/Sunstar. ([Lichtsinn RV: Adventurer vs Vista](https://www.lichtsinn.com/blog/the-winnebago-adventurer-vs-the-winnebago-vista/))
- Special editions (e.g., the Vista National Park Foundation trim) have shipped with a 320Ah Lithionics lithium house battery and a 4,000W Onan MicroQuiet generator as standard — a preview of where the factory is headed, and worth checking for on used listings since it saves you the upgrade cost outright. ([Lichtsinn RV: Winnebago + Lithionics](https://www.lichtsinn.com/blog/winnebago-motorhomes-with-lithionics-battery/))

**What that lead-acid actually gets you.** A Group 31 battery is rated roughly 100-125Ah, but the critical number is *usable* capacity: lead-acid batteries should not be discharged below 50% without shortening their life dramatically, so a Group 31 gives you about 50-60Ah usable — not the rated number. ([Power Queen deep-cycle sizing guide](https://ipowerqueen.com/blogs/knowledge/deep-cycle-battery-sizes-guide); [RV Life amp-hour guide](https://rvlife.com/batteries-amp-hours/))

- **Vista/Sunstar stock (2x Group 31):** ~200-250Ah rated → **~100-125Ah usable**, roughly 1,200-1,500 watt-hours.
- **Adventurer stock (4x Group 31):** ~400-500Ah rated → **~200-250Ah usable**, roughly 2,400-3,000 watt-hours.

For scale, a family of four running lights, a furnace fan, water pump, phone charging, and a bit of TV burns somewhere in the 1,000-2,000Wh range per day *before* any workstation load. That means stock Vista/Sunstar batteries alone are good for **about a day, maybe less**, before you're relying entirely on the generator or driving to recharge. The Adventurer's doubled bank buys you closer to two days. Neither is remotely enough once you add 8-10 hours of laptop-plus-two-monitors on top — more on that below.

## Generator: The Real Workhorse, With Real Limits

The Onan generator is the piece doing the actual boondocking work in a stock rig — it's what recharges the batteries and runs the air conditioner, microwave, and other high-draw loads when you're off shore power. Onan is the standard in this segment and has been for decades; it's a known-reliable, well-supported unit with parts and service everywhere. ([iRV2: What does the Onan Generator do?](https://www.irv2.com/threads/what-does-the-onan-generator-do.1976240/))

**Fuel burn (gasoline Onan 5500):** roughly 0.3 gal/hr at no load, 0.6 gal/hr at half load, 0.9 gal/hr at full load — real-world camping use tends to land around 0.6 gal/hr. On a typical 10-gallon onboard generator tank that's about 16-18 hours of runtime. ([Justanswer / forum-sourced Onan fuel data](https://www.justanswer.com/rv-motorhome/6izyg-5500-watt-onan-generator-know.html); [Forest River Forums fuel consumption thread](https://www.forestriverforums.com/threads/fuel-consumption-onan5500-generator.124328/)) Note the 5500 is a conventional (non-inverter) generator — it runs at a fixed high output whenever it's on, unlike a small portable inverter generator that throttles down at light load, so fuel burn doesn't drop much just because your load is light.

**Etiquette and quiet hours — what's rule vs. what's courtesy.** There is no single nationwide generator-hours *law*; the binding rules are set locally and vary by land manager, so this is one place to separate the two:

- **What the rules require (varies by where you are):** On National Forest land, dispersed camping is governed by each forest's own rules and by the federal prohibition, in or near a campsite, on "operating or using... any device which produces noise, such as a radio, television, musical instrument, motor or engine... so as to unreasonably disturb any person" — the standard set in the Code of Federal Regulations at [36 CFR 261.10(i)](https://www.law.cornell.edu/cfr/text/36/261.10), which a generator falls under and which is enforced at a ranger's discretion rather than as a fixed decibel-and-clock rule. Developed and private campgrounds each set and post their own generator hours and enforce them as a condition of your stay — **always check the specific campground's posted policy at check-in.**
- **What's courtesy (not law, but expected):** the informal boondocking norm is generator hours of roughly **8am-8pm, quiet by 10pm**, parking away from other campers, angling your exhaust away from neighbors, and keeping runtime reasonable. Community write-ups commonly cite a target of around 60 dB at 50 feet as "polite," but treat that as etiquette guidance, not a citable legal limit. ([iRV2: generator etiquette while boondocking](https://www.irv2.com/threads/what-is-generator-etiquette-while-boondocking.1824436/); [Boondocker's Bible: generator at night](https://www.boondockersbible.com/learn/do-i-have-to-shut-off-my-generator-at-night/) — both community-experience sources.)

**The practical takeaway:** the generator alone can run your A/C and recharge the batteries on demand, but running it for hours every evening to power a home office is neither quiet-hours-compliant nor pleasant for a family trying to unwind at a campsite. It's the reliable fallback, not the daily driver, for WFH boondocking.

## The Upgrade Path: LiFePO4, Inverter/Charger, Solar, DC-DC

This is the well-worn path handy owners take, and it directly solves your two constraints (genuine off-grid days + a working home office).

### 1. LiFePO4 battery bank

Lithium (LiFePO4) batteries typically allow ~80-100% usable depth of discharge versus lead-acid's 50%, meaning a 300Ah lithium bank gives you roughly double the usable energy of a 300Ah-*rated* lead-acid bank, plus far more charge cycles and no maintenance. Reputable DIY-friendly brands mentioned repeatedly on RV and solar forums include **Battle Born, Epoch, Renogy, and Redodo**; for drop-in 12V packs designed to be a plug-compatible replacement for lead-acid, these are the names to shortlist.

**Cost — be careful here, because quotes vary wildly by whether labor is included:**
- **Fully installed, professional shop system** (300-460Ah lithium + Victron MultiPlus inverter/charger + solar + monitoring, done for you): an installer's public pricing lists a turnkey RV Victron-lithium-plus-solar upgrade **starting from $14,500 installed**, with larger banks priced higher (as of July 2026). Treat that as the entry point of the installed-system range, not a ceiling — bigger battery banks and more solar push it well above that. ([RevampCustomVans installed pricing](https://revampcustomvans.com/); the individual-battery cost of a heated, Victron-comms 460Ah lithium module is shown for reference at [Epoch Batteries](https://www.epochbatteries.com/products/12v-460ah-lifepo4-battery-ip67-heated-bluetooth-victron-comms).)
- **DIY, parts only** (the path that fits Doug's profile): a single 300Ah drop-in lithium battery runs roughly **$450-$800** depending on brand and features (Bluetooth monitoring, built-in heating pad for cold-weather charging, etc.); a full DIY system — 300-400Ah lithium + Victron-class inverter/charger + basic solar + wiring/breakers/cabling — is reported as landing in the **$3,000-$7,000** range depending on inverter size and how much solar you add, versus the $14,500-and-up number for the same specs done by a shop. Verify current pricing before relying on this: the specific DIY Solar Power Forum thread originally cited for this range could not be independently re-verified (link now returns an error), though broader DIY Solar Forum discussion documents budget lithium builds from under $1,000 up to several thousand dollars depending on capacity, which is directionally consistent. ([DIY Solar Power Forum: RV Solar/LiFePo4 on a budget](https://diysolarforum.com/threads/rv-solar-lifepo4-on-budget.104148/))

For your family's load (WFH + household), **300-400Ah of lithium (12V)** is a reasonable target — enough for 1.5-2 days of real off-grid use without the generator, assuming moderate solar input helps refill it during the day.

### 2. Inverter/charger — Victron MultiPlus (or equivalent)

The MultiPlus (and MultiPlus-II) is the de facto standard reference point in the DIY RV solar world: it's a combined inverter (turns battery DC into household AC) and smart charger (recharges the battery from shore power or generator with a proper multi-stage lithium charge profile), and it's explicitly designed to work well with LiFePO4 when configured with the correct lithium charge profile. ([Victron Community: MultiPlus and LiFePO4](https://communityarchive.victronenergy.com/questions/309368/multiplus-and-lifepo4.html); [BlueMarine MultiPlus-II sizing guide](https://bluemarine.com/blogs/news/victron-multiplus-ii-sizing-guide)) A 3,000W unit is a common sizing choice for a Class A running a microwave, coffee maker, and the workstation without also trying to run A/C off the inverter (A/C stays generator- or shore-fed). Other reputable brands in this space include Renogy and Xantrex, but Victron's ecosystem (Cerbo GX monitoring, app control, wide installer familiarity) is why it shows up as the default recommendation across nearly every RV solar build thread.

### 3. Rooftop solar — set expectations correctly

Class A roofs are large but crowded — A/C units, vents, antennas, and roof racks all compete for space, so the real limit is often roof real estate, not budget. A practical target for a 30-35' Class A supporting a 300-400Ah battery bank is **roughly 600-1,200 watts** of panel, depending on what fits around your roof obstacles. ([US Solar Supplier RV solar sizing guide](https://ussolarsupplier.com/blogs/news/rv-solar-panels-guide-to-sizing-installing-and-getting-it-right); [Oukitel 2026 RV solar sizing guide](https://oukitelpower.com/blogs/blog/how-much-solar-do-you-need-for-your-rv))

Be realistic about output: real-world panel production runs well below the sticker rating once you factor in angle, shading, dust, and heat — plan on a 25-40% haircut off the rated wattage for a realistic daily-average number. In central NJ / East Coast summer sun, 800W of rated panel might realistically deliver **300-450Wh per peak sun-hour equivalent**, or roughly **1,500-2,500Wh on a good day** across 4-5 usable sun-hours — enough to meaningfully offset (not fully replace) daily household + WFH use, and to fully recharge the bank over a day or two of light use.

### 4. DC-DC / alternator charging

A DC-to-DC charger takes power from the chassis alternator (while driving) and delivers a proper multi-stage charge to the lithium house bank, isolating the starter battery so you can never accidentally strand yourself. This matters especially for modern "smart" alternators that vary voltage — a simple isolator relay can't handle that, but a DC-DC charger can. A common sizing rule is reported as drawing no more than 25-40% of the alternator's rated output, and typical DC-DC charger sizes run 20-60A; verify current guidance before relying on this, since the underlying forum thread could not be independently re-verified and other sources frame the ceiling more loosely as "up to 50% of rated output" without the extra vehicle-load deduction. ([iRV2: DC-DC size calculations](https://www.irv2.com/threads/dcdc-size-calculations.2020306/)) Practically: every driving day (and you'll have plenty, moving between campgrounds) tops the battery bank back up for free, which is a genuinely underrated part of this whole system for a family that's touring, not parking in one place for a week.

## Propane: The Constraint People Forget

Everyone fixates on amp-hours and forgets that the **furnace, water heater (unless electric-hybrid), stovetop, and often the fridge** run on propane, not battery power — though the furnace's blower fan does draw DC, which is a real (if small) battery load on cold nights. Large Class A coaches typically carry an 80-100 lb (roughly 18-35 gallon-equivalent) built-in ASME propane tank; for example, a Winnebago Vista has been documented with an 18-gallon tank. ([The RV Geeks: propane tank sizing](https://www.thervgeeks.com/propane-tank-sizes/); [Outdoorsy: RV propane tank guide](https://www.outdoorsy.com/blog/rv-propane-tanks-guide))

Rule-of-thumb consumption: a 30,000 BTU furnace burns about one gallon of propane per 3 hours of runtime. A standard 20-lb (4.6-gallon) portable tank lasts roughly **3-7 days** of typical boondocking use (furnace overnight + water heater + cooking), or **7-10 days** if you're conservative with the furnace and water heater. Scale that up to your rig's 18-35 gallon built-in tank and propane will comfortably outlast your battery bank in every scenario — **it will not be your limiting factor**, except potentially on a multi-week winter trip. ([Boondocker's Bible: propane duration](https://www.boondockersbible.com/learn/how-long-will-a-propane-tank-last-while-boondocking/); [NW Adventure Rentals propane calculator](https://nwadventurerentals.com/calculating-rv-propane-usage/))

## Tank Sizes and Water Conservation for a Family of Four

Typical holding tank sizes for 30-35' Class A coaches: **fresh water 55-100 gallons**, **grey water 40-65 gallons**, **black water 31-51 gallons** — smaller floorplans (around 30') often run on the lower end (e.g., 55-60 gal fresh, 35 gal grey, 35 gal black); larger 35' coaches trend toward the upper end. ([RVing Know How: typical tank sizes](https://www.rvingknowhow.com/typical-rv-holding-tank-size/); [Camp Addict: RV holding tank sizes guide](https://campaddict.com/rv-holding-tanks/size/))

For a family of four (two adults, two young kids) practicing reasonable water conservation — navy showers, running the water pump only when needed, not letting the tap run for dishwashing — 55-60 gallons of fresh water typically lasts **2-3 days** of boondocking, and grey water (which fills faster than fresh empties, since it includes dish and shower water) is usually the practical limiter, not fresh or black. This is consistent with what most family boondocking guides report as a realistic multi-day stint without water hookups. ([Winnebago: Boondocking in a Class A Motorhome](https://winnebago.com/lifestyle/winnebagolife/education/boondocking-in-a-class-a-motorhome))

## 30A vs 50A Shore Power, and Get an EMS

Base Vista/Sunstar trims may ship 30A; the Cooling Upgrade Package (dual A/C, 5,500W generator) bumps you to a 50A cord. **50A is what you want** if you're running two A/C units in NJ/mid-Atlantic summer heat with two kids in the rig — 30A service simply can't support two A/C units plus a water heater and microwave without tripping. When shopping used, confirm which cord/amperage the actual coach has; it's a meaningfully different camping experience.

(To be clear, none of this is a legal requirement — no law dictates 30A vs 50A or mandates a surge protector. It's all comfort-and-equipment guidance: what experienced owners recommend to avoid a miserable summer or a fried A/C compressor.)

Regardless of amperage, buy a **surge protector / EMS (Energy Management System)** — this is cheap insurance against bad campground pedestals, which are more common than you'd think, especially at older public campgrounds. An EMS (as opposed to a basic surge protector) actively monitors for high/low voltage, incorrect wiring, and open ground/neutral faults, and cuts power before it fries your electronics or A/C compressor. **Progressive Industries** and **Hughes Autoformer/Power Watchdog** are the two names that come up repeatedly as the reputable choices; Hughes adds Bluetooth app monitoring, Progressive has a long track record as the full-timer default. Buy the model matched to your cord amperage (30A or 50A). ([RV Travel: EMS brand comparison](https://www.rvtravel.com/rv-electricity-pros-cons-big-three-ems-surge-protectors-rvt-1003/); [Forest River Forums: 30A EMS comparison](https://www.forestriverforums.com/threads/best-30a-surge-protectors-progressive-vs-hughes-power-watchdog.1113909/))

## The WFH Reality Check: Can the Workstation Actually Run Off-Grid?

This is the number that should drive your upgrade decision, so let's build it explicitly.

**Workstation load:** a typical work laptop draws roughly 30-70W; two external monitors add roughly 15-40W combined depending on size (dual smaller/efficient monitors land toward the low end). Call it **~100W combined**, running 8-10 hours a workday: **100W × 9h ≈ 900Wh/day**, just for the desk. ([Habitatista: low-power monitors for RV remote work](https://www.habitatista.com/468841/low-power-monitors-for-remote-work-in-an-rv/); general laptop wattage references)

**Household load on top:** water pump, LED lighting, phone/device charging, furnace fan (cool nights), fridge if it's residential-style rather than propane-absorption, occasional TV — commonly estimated at **1,000-2,000Wh/day** for a family of four in a Class A. ([SunGold Solar 2026 cost/sizing breakdown](https://www.sungoldsolar.com/blogs/rv-solar-system-cost-breakdown-2026/))

**Combined realistic daily draw: reported as roughly 2,000-2,900Wh/day** — before air conditioning. Verify this against your family's actual habits before relying on it: the household-load component is a commonly cited estimate rather than a figure specific to your appliance mix, and it lands close enough to the Adventurer's usable capacity (below) that the margin matters.

Compare that to what you have:
- **Stock Vista/Sunstar lead-acid (~1,200-1,500Wh usable):** gone in well under a day. You are running the generator daily, full stop, if you're off-grid and working.
- **Stock Adventurer lead-acid (~2,400-3,000Wh usable):** roughly one day, maybe stretching into a second with a light-use day — note this usable-capacity range actually overlaps the 2,000-2,900Wh/day draw estimate above rather than being reliably exceeded within a day, so don't assume the Adventurer is clearly worse off than the math above implies; it's closer to a wash.
- **Upgraded 300-400Ah lithium (2,400-3,800Wh usable, ~80-100% DoD) + 800W solar:** with even modest sun, solar can offset 1,500-2,500Wh/day, meaning the battery bank mostly *holds steady* day to day rather than draining — genuinely sustainable multi-day off-grid work, generator as backup rather than daily necessity.

**The one honest caveat: air conditioning changes everything.** A single RV A/C unit draws roughly 1,200-1,800W continuously while cycling — running it overnight in NJ summer humidity would exhaust the 300-400Ah lithium bank sized above in a few hours and is not realistically solar-supportable at that capacity. Correction: overnight off-grid A/C isn't strictly impossible at any price — it's achievable with a substantially larger bank, roughly 400-800Ah of lithium (nearer the $10,000-$18,000 "AC-ready" system tier, not the $4,000-$7,000 DIY budget used elsewhere in this doc) — but a generator remains the more cost-effective and reliable choice for extended hot-weather stretches, and the budget system sized for WFH + household loads above will not cover it. Plan generator use for overnight A/C, or accept warmer nights when boondocking in summer, unless you're willing to size and spend well beyond the WFH-driven recommendation. ([SunGold Solar: RV Solar System Cost Breakdown](https://www.sungoldsolar.com/blogs/rv-solar-system-cost-breakdown-2026/); [Micro-Air: How many batteries do you need to run an RV A/C overnight](https://www.microair.net/blogs/news/how-many-batteries-do-you-need-to-run-an-rv-ac-overnight))

## Bottom line for this family

1. **Stock lead-acid is a weekend system, not a WFH system.** The Vista/Sunstar's 2x Group 31 batteries give you ~1,200-1,500Wh usable — gone in under a day with the workstation running. The Adventurer's 4-battery setup roughly doubles that but still isn't enough for repeated off-grid workdays. Don't let a stock spec sheet's "boondocking capable" claim substitute for doing this math yourselves when you're looking at a specific used rig.
2. **Budget for the upgrade as part of the purchase price, not an afterthought.** A DIY 300-400Ah LiFePO4 + Victron-class inverter/charger + 600-800W solar + DC-DC charging is realistically **$4,000-$7,000 in parts** for a handy owner doing the install — a different universe from the "$14,500-and-up, fully installed by a shop" quotes you'll see, and well within reach for someone who does his own upgrades. If you'd rather not install it yourself, budget the higher number and get quotes locally.
3. **Watch for the Lithionics/lithium special editions on the used market** — some factory trims already ship with a 320Ah lithium house battery, which could save you the whole upgrade if you find the right used unit.
4. **Propane and water will outlast your battery bank in every realistic scenario** — an 80-100 lb tank and 55-100 gallon fresh tank both comfortably cover multi-day stints; grey water is usually the actual limiter on trip length, not fresh water or propane.
5. **Get a 50A coach if you can, and buy an EMS on day one** regardless of amperage — this is cheap, unglamorous insurance against a bad campground pedestal frying your new electrical investment.
6. **Set the right mental model for A/C:** boondocking with the upgraded system means comfortable, connected workdays and evenings; it does not mean silent, generator-free overnight air conditioning in a New Jersey summer. Plan generator use for that specific case and it'll feel like the exception, not the daily grind.

## Sources

Every non-obvious claim above links to one of these. Primary sources (statute, manufacturer/dealer specs) are marked **[primary]**; forum and community write-ups are marked **[community]** and should be read as real-owner experience, not verified engineering data.

**Law and rules**

- [36 CFR 261.10(i) — Occupancy and use (Cornell LII)](https://www.law.cornell.edu/cfr/text/36/261.10) **[primary]** — the federal noise prohibition that governs generator use in and near National Forest campsites; the "unreasonably disturb any person" standard.

**Winnebago stock specs**

- [RVUSA: 2026 Winnebago Sunstar 31B specs](https://www.rvusa.com/rv-guide/2026-winnebago-sunstar-31b-class-a-specs-fp20536) **[primary]** — factory spec sheet confirming the stock 2x Group 31 batteries, 2,000W inverter, 4,000W generator, and the optional 5,500W Cooling Upgrade Package.
- [Lichtsinn RV: Vista and Sunstar 29V feature overview](https://www.lichtsinn.com/blog/winnebago-vista-and-sunstar-29v-feature-overview/) **[primary — dealer]** — Winnebago-specialist dealer detail on the Vista/Sunstar stock electrical package.
- [Lichtsinn RV: The Winnebago Adventurer vs. The Winnebago Vista](https://www.lichtsinn.com/blog/the-winnebago-adventurer-vs-the-winnebago-vista/) **[primary — dealer]** — side-by-side confirming the Adventurer's 4-battery bank vs. the Vista/Sunstar's 2.
- [Lichtsinn RV: Winnebago motorhomes with Lithionics batteries](https://www.lichtsinn.com/blog/winnebago-motorhomes-with-lithionics-battery/) **[primary — dealer]** — the factory 320Ah Lithionics lithium special-edition trims worth hunting for on the used market.
- [Winnebago: Boondocking in a Class A Motorhome](https://winnebago.com/lifestyle/winnebagolife/education/boondocking-in-a-class-a-motorhome) **[primary]** — manufacturer's own framing of realistic Class A boondocking and family water endurance.

**Batteries, usable capacity, and lithium upgrade**

- [RV Life: Amp Hours — How Long Will My RV Batteries Last Off the Grid?](https://rvlife.com/batteries-amp-hours/) **[community]** — the usable-vs-rated capacity and lead-acid 50% rule.
- [Power Queen: deep-cycle battery sizes guide](https://ipowerqueen.com/blogs/knowledge/deep-cycle-battery-sizes-guide) **[community — manufacturer blog]** — Group 31 amp-hour ratings.
- [Epoch Batteries: 12V 460Ah LiFePO4 (Victron comms) product page](https://www.epochbatteries.com/products/12v-460ah-lifepo4-battery-ip67-heated-bluetooth-victron-comms) **[primary — manufacturer]** — reference cost of a single heated, Victron-comms 460Ah lithium module (the battery line item inside an installed system).
- [RevampCustomVans: installed system pricing](https://revampcustomvans.com/) **[community — installer]** — installer's public "starting from $14,500 installed" figure for a turnkey RV Victron-lithium-plus-solar upgrade; the counterweight to the DIY numbers. (As of July 2026 the page lists the $14,500 entry point but not the more granular per-module figures, so those were removed.)
- [DIY Solar Power Forum: RV Solar/LiFePo4 on a budget](https://diysolarforum.com/threads/rv-solar-lifepo4-on-budget.104148/) **[community]** — DIYer cost breakdowns; note the original specific thread for the $3,000-$7,000 range could not be re-verified, so that figure is flagged in-text as directional.

**Inverter/charger and solar**

- [Victron Community: MultiPlus and LiFePO4](https://communityarchive.victronenergy.com/questions/309368/multiplus-and-lifepo4.html) **[primary — manufacturer community]** — configuring a MultiPlus for lithium charge profiles.
- [BlueMarine: Victron MultiPlus-II sizing guide](https://bluemarine.com/blogs/news/victron-multiplus-ii-sizing-guide) **[community]** — inverter sizing rationale.
- [US Solar Supplier: RV solar sizing guide](https://ussolarsupplier.com/blogs/news/rv-solar-panels-guide-to-sizing-installing-and-getting-it-right) **[community]** — rooftop panel wattage targets and roof-space constraints.
- [Oukitel: how much solar do you need for your RV (2026)](https://oukitelpower.com/blogs/blog/how-much-solar-do-you-need-for-your-rv) **[community — manufacturer blog]** — solar sizing and real-world output derating.
- [iRV2: DCDC size calculations](https://www.irv2.com/threads/dcdc-size-calculations.2020306/) **[community]** — DC-DC charger sizing to alternator output; flagged in-text as not independently re-verified.

**Generator**

- [iRV2: What does the Onan Generator do?](https://www.irv2.com/threads/what-does-the-onan-generator-do.1976240/) **[community]** — how the stock generator/battery/converter relationship works day to day.
- [JustAnswer: Onan 5500 fuel consumption](https://www.justanswer.com/rv-motorhome/6izyg-5500-watt-onan-generator-know.html) **[community]** and [Forest River Forums: Onan 5500 fuel consumption](https://www.forestriverforums.com/threads/fuel-consumption-onan5500-generator.124328/) **[community]** — the 0.3 / 0.6 / 0.9 gal/hr no-/half-/full-load burn figures (consistent with the Onan spec sheet).
- [iRV2: generator etiquette while boondocking](https://www.irv2.com/threads/what-is-generator-etiquette-while-boondocking.1824436/) **[community]** and [Boondocker's Bible: generator at night](https://www.boondockersbible.com/learn/do-i-have-to-shut-off-my-generator-at-night/) **[community]** — the informal quiet-hours and exhaust-etiquette norms (courtesy, not law).

**Propane**

- [The RV Geeks: propane tank sizing](https://www.thervgeeks.com/propane-tank-sizes/) **[community]** and [Outdoorsy: RV propane tank guide](https://www.outdoorsy.com/blog/rv-propane-tanks-guide) **[community]** — built-in ASME tank sizes for large Class A coaches.
- [Boondocker's Bible: how long will a propane tank last](https://www.boondockersbible.com/learn/how-long-will-a-propane-tank-last-while-boondocking/) **[community]** and [NW Adventure Rentals: RV propane usage calculator](https://nwadventurerentals.com/calculating-rv-propane-usage/) **[community]** — furnace/water-heater propane duration numbers.

**Tanks and water**

- [RVing Know How: typical RV holding tank sizes](https://www.rvingknowhow.com/typical-rv-holding-tank-size/) **[community]** and [Camp Addict: RV holding tank sizes guide](https://campaddict.com/rv-holding-tanks/size/) **[community]** — fresh/grey/black tank ranges for 30-35' Class A coaches.

**Shore power and EMS**

- [RV Travel: pros and cons of the big three EMS surge protectors](https://www.rvtravel.com/rv-electricity-pros-cons-big-three-ems-surge-protectors-rvt-1003/) **[community — expert column]** — Progressive Industries vs. Hughes comparison.
- [Forest River Forums: 30A EMS comparison](https://www.forestriverforums.com/threads/best-30a-surge-protectors-progressive-vs-hughes-power-watchdog.1113909/) **[community]** — owner comparison of 30A surge/EMS units.

**WFH load and A/C**

- [Habitatista: low-power monitors for RV remote work](https://www.habitatista.com/468841/low-power-monitors-for-remote-work-in-an-rv/) **[community]** — laptop/monitor wattage for the workstation estimate.
- [SunGold Solar: RV solar system cost breakdown (2026)](https://www.sungoldsolar.com/blogs/rv-solar-system-cost-breakdown-2026/) **[community — manufacturer blog]** — household daily-load estimates and system cost tiers.
- [Micro-Air: how many batteries to run an RV A/C overnight](https://www.microair.net/blogs/news/how-many-batteries-do-you-need-to-run-an-rv-ac-overnight) **[community — manufacturer blog]** — the 400-800Ah+ battery bank needed for overnight off-grid A/C.
