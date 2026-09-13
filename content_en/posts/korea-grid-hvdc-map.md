---
title: "Korea's power grid explained: where the electricity is, where the demand is, and the HVDC lines meant to connect them"
date: 2026-09-13T13:56:00+09:00
dataAsOf: "2026-09-13"
categories: ["Nuclear & Energy"]
tags: ["Korea power grid", "HVDC", "KEPCO", "transmission", "curtailment"]
description: "Korea makes electricity on the coasts and uses it around Seoul. The 765 kV backbone, every HVDC line built or planned, and why the wires are the bottleneck."
---

Anyone sizing up South Korea for a data center or a factory ends up with two maps, and the first shows where electricity is made: nuclear and coal on both coasts, solar across the southwest, all far from Seoul. The second shows where it is used. It is mostly the capital region.

Between the two maps sit one company's wires. This guide is about those wires: how the grid is laid out, which high-voltage direct current (HVDC) lines are supposed to close the gap, and why the lines, not the plants, decide what gets built next.

> **Key takeaways**
> - One state utility, KEPCO, owns every transmission line: 35,364 circuit-km of AC and 492 circuit-km of HVDC at the end of 2024. Gyeongbuk province generates 263 percent of what it uses; Seoul generates 7.5 percent.
> - Three HVDC corridors carry the plan: East Coast–capital region (8 GW; stage 1 due December 2027, stage 2 no earlier than 2029), Bukdangjin–Godeok (3 GW, in service) and the West Coast "energy highway" (four lines of 2 GW, 2030 to 2038).
> - The jam is permits, transformers and the queue: a Hanam converter station has waited two years for a building permit, 189 substations are closed to new renewables, and 9.6 GW of data center applications were waiting in March 2026.

## 1. The shape of the grid: one company, one system

Korea has one synchronous grid on the mainland, with Jeju island attached by undersea HVDC cable. The grid has one owner. **KEPCO** (Korea Electric Power Corporation, majority state-owned) owns every transmission and distribution line and generates through six subsidiaries, including KHNP (Korea Hydro & Nuclear Power) for the reactors, while the **Korea Power Exchange** (KPX) runs the wholesale market and dispatches the plants.

The backbone is 765 kV and 345 kV AC. KEPCO's own figures for the end of 2024:

| Level | Circuit-km | Role |
|---|---|---|
| 765 kV | 1,024 | Trunk lines from coastal plants toward the capital region |
| 345 kV | 10,070 | Regional backbone and inter-regional transfers |
| 154 kV and below | 24,270 | Local supply to substations and large customers |
| HVDC | 492 | Jeju links and Bukdangjin–Godeok |

### Where the power is, and where it is not

Plants cluster on the coasts because reactors and coal units need cooling water and ports. Demand clusters around Seoul. The gap shows in each province's electricity self-sufficiency, generation divided by consumption, for January to July 2025 (KEPCO data released by National Assembly member Park Jeong, September 2025):

| Region | Self-sufficiency | What is there |
|---|---|---|
| Gyeongbuk | 262.6% | Hanul and Wolsong reactors, east-coast coal |
| Jeonnam | 208.2% | Hanbit reactors, the densest solar fleet |
| Incheon | 180.6% | LNG plants beside Seoul |
| Chungnam | 180.5% | West-coast coal fleet |
| Chungbuk | 25.6% | Inland industry, little generation |
| Gwangju | 11.9% | A city inside the solar belt |
| Seoul | 7.5% | Down from 11.6% in 2024 |
| Daejeon | 3.3% | Lowest in the country |

Three clusters supply the surplus. The **east coast** has Hanul, [the largest of Korea's five reactor sites](/en/posts/korea-reactor-fleet-map/) at 8,700 MW, plus Wolsong, Kori–Saeul and east-coast coal. The **west coast** has the Hanbit reactors in Jeonnam and Chungnam's coal fleet, and the **southwest** has most of Korea's solar, which is why Jeonnam produces twice what it uses.

The capital region (Seoul, Gyeonggi, Incheon) bought nearly 40 percent of the electricity KEPCO sold in 2024 (KEPCO statistics via the Electric Times, May 2026). Incheon's LNG plants flatter the total.

## 2. The HVDC lines: built, building, planned

HVDC is the tool for moving several gigawatts a long way or under the sea, with lower losses and a flow the operator sets exactly. The price is a converter station at each end. That is where Korea's loudest fight is.

Korea's HVDC lines and projects, as of September 2026:

| Line | Route, length | Capacity, type | Status (Sept. 2026) |
|---|---|---|---|
| Jeju #1 | Haenam–Jeju, 101 km | 300 MW, ±180 kV, LCC | In service since March 1998 |
| Jeju #2 | Jindo–Jeju, 113 km | 400 MW, ±250 kV, LCC | In service since 2014 |
| Jeju #3 | Wando–East Jeju, 98 km | 200 MW, ±150 kV, VSC (reversible) | In service Nov. 29, 2024; KRW 470 billion (about $350 million) |
| Bukdangjin–Godeok | Dangjin–Pyeongtaek, 34.2 km | 3 GW, 500 kV, cable | In service: 1.5 GW Dec. 2020, 1.5 GW May 2024; KRW 1.15 trillion (about $850 million) |
| East Coast, stage 1 | Uljin (Shin-Hanul)–Shin-Gapyeong, 230 km overhead | 4 GW, 500 kV | Extended to Dec. 2027 (July 2026 notice) |
| East Coast, stage 2 | Yangpyeong–Dongseoul (Hanam), 50 km, 40 km underground | 4 GW, 500 kV | Cable contract June 2026; Dongseoul permit pending; 2029 at the earliest |
| West Coast "energy highway" | Four submarine lines to the capital region, 1,070 km | 4 × 2 GW, 525 kV | Stage 1 (Saemangeum–Seohwaseong, 220 km) by 2030; all by 2038; KRW 12.2 trillion (about $9 billion); later lines under review since Aug. 2026 |

**The Jeju links** are the oldest. The third, completed on November 29, 2024 (ceremony December 6), can reverse in seconds, so Jeju's wind surplus now flows to the mainland.

**Bukdangjin–Godeok** is the only mainland HVDC in service. It carries Chungnam coal and gas output 34 km to the Pyeongtaek semiconductor cluster and, KEPCO says, freed about 900 MW of west-coast generation that had been held back for lack of a line.

[**The East Coast line**](/en/posts/datacenter-grid-bottleneck/) is 280 km and 436 towers from the Shin-Hanul reactors to Hanam, planned in 2009 for completion in 2019. Stage 1 now runs to December 2027. Stage 2's cable contract went to LS Cable & System on June 15, 2026, but the construction daily Daehan Economic Daily had reported in November 2024 that the full line could not be complete before 2029, and the converter station has lost another year since.

**The West Coast line** is the newest plan. The 11th transmission plan of May 2025 set four 2 GW routes for 2031, 2036 and 2038, 2 GW being the largest voltage-source converter unit available today, by KEPCO's reckoning; in March 2026 KEPCO branded them the "West Coast energy highway" and pulled stage 1 forward to 2030. No cable has been laid. In August 2026 the government said it is reviewing the three later lines against the 12th Basic Plan; stage 1 is unaffected.

![Flow strip showing Korea's three generation clusters on the left, the capital region's demand on the right, the HVDC corridors between them with their capacities and dates, and a bottleneck callout with the 1.9 percent approval rate, 9.6 GW waiting and two-to-three-year transformer lead times](/images/korea-grid-hvdc-map-en.svg)

## 3. Where it jams: permits, transformers, the queue

### The converter station without a building permit

The Seoul end is Hanam's **Dongseoul converter station**. The city refused KEPCO's building permits on August 21, 2024 over residents' fears of electromagnetic fields and has not issued them since, even after KEPCO won an administrative appeal that December. KEPCO measured 0.02 microtesla, less than a refrigerator gives off; the dispute is about consent, not physics.

On August 20, 2026 a four-party body (the local National Assembly member, the ministry, KEPCO and residents) met for the first time, planning about 16 sessions over eight weeks. Success means groundbreaking as early as November. Failure sends the case to the fast-track procedure under the National Grid Expansion Special Act, which takes at least six months (Kyeongin Ilbo, September 3, 2026), while KEPCO puts each year of delay at about KRW 300 billion (about $220 million).

### Transformers: the same queue everywhere

A line without substations is a wire to nowhere. Wood Mackenzie put the average US lead time for a power transformer at 128 weeks in the second quarter of 2025, past 160 weeks for substation-class units in 2026.

### The queue and the closed substations

Two queues run at once. On the demand side, the grid impact assessment introduced in June 2024 had cleared 10 of 522 Seoul-area data center applications by March 2026, 1.9 percent, with about 9.6 GW waiting nationwide (CBRE Korea; KEPCO data). On the supply side, KEPCO on May 30, 2024 designated 205 **grid-managed substations** closed to new renewable connections until reinforced: 103 in Gwangju and Jeonnam, 61 in Jeonbuk, 25 on the east coast and 16 on Jeju.

In Honam every substation was on the list. A new solar or wind project there could not get a connection date before January 2032. Jeju's 16 were released on March 30, 2026; the other 189 stay closed (Solutions for Our Climate, May 2026).

### Curtailment: when the surplus has nowhere to go

When a region generates more than its lines can carry, KPX orders plants to cut output, which Korean headlines call **output control** (출력제어). On Jeju it is routine. KPX counted 56 curtailment days there in 2024, with wind cut 51 times for 9,370 MWh, down from 117 times and 26,201 MWh in 2023 after a bidding market launched June 1, 2024 let plants bid for the right to run.

The mainland followed. The first large curtailment of private solar outside Jeju came on April 7, 2024 in Haenam and Goheung, Jeonnam (Electric Times); on May 1, 2026 mainland solar hit 28.9 GW, 50.1 percent of load, and KPX curtailed three times over the holiday. Operators want the selection rules published and a compensation scheme, which the mainland lacks (Asia Today, May 13, 2026).

## 4. What the government is doing about it

Four measures are in motion as of September 2026:

| Measure | What it does | Status (Sept. 2026) |
|---|---|---|
| National Grid Expansion Special Act | Central committee can override local permit refusals; more compensation for host communities | In force since Sept. 26, 2025; Dongseoul is the first test |
| 11th transmission plan (2024–2038) | KRW 72.8 trillion (about $54 billion), KRW 18.2 trillion of it for HVDC and grid stabilization | Confirmed May 27, 2025 |
| Distributed energy special zones | Local generators may sell directly to local customers, bypassing KEPCO's tariff | Seven zones: Busan, Gyeonggi (Uiwang), Jeonnam, Jeju (Nov. 5, 2025); Pohang, Ulsan, Seosan (Dec. 2025) |
| Regional industrial tariff | Up to KRW 18 per kWh (about 1.3 cents) off in the south, 15 in the center, 10 in the northern capital region (northern Seoul, Incheon); southern Seoul and southern Gyeonggi unchanged | Design published Aug. 26, 2026; launch planned within 2026 |

The tariff matters most to anyone choosing a site. It applies only to industrial customers, who use more than half of Korea's electricity, and is meant to pull factories and data centers toward the surplus provinces. The discount is the carrot; Seoul's 1.9 percent approval rate is the stick.

## 5. What it means for data centers and new reactors

For data centers the arithmetic is unforgiving. Sixty-seven percent of the applications filed between August 2024 and June 2025 were for the capital region, which gains no new import line before December 2027, and the ministry's August 2026 work plan says Honam alone needs 7.5 GW more for four planned semiconductor fabs and AI data centers. Both are demands for lines, not plants, the heart of the argument between [building generation near Seoul and building the grid first](/en/posts/datacenter-grid-bottleneck/).

For new reactors the map cuts the other way. The 11th Basic Plan's two large units for 2037–38 were sited in June 2026 at Yeongdeok, on the east coast, the corridor the East Coast HVDC is meant to serve. A reactor there is worth what its line can carry, and [the public deliberation on new reactors](/en/posts/new-reactor-public-debate/) now under way will decide whether to add more units to a corridor whose first line is eight years late.

Critics make the grid argument from the other side. Solutions for Our Climate, a Korean climate group, says LNG plants that have not broken ground are holding connection capacity ahead of renewable projects ready to build, and wants the first-come, first-served queue replaced by a readiness test (May 2026). Whatever mix the 12th Basic Plan lands on, the lines end up in [the electricity bill](/en/posts/electricity-bill-energy-mix/).

One thing I have learned from reading these plans: a completion year in a transmission plan is a floor. It is not a forecast. The East Coast line was due in 2019, then 2025, then 2026, and now 2027.

## 6. How to read a grid headline

Four terms cover most Korean grid headlines.

- **Grid saturation** (계통 포화): a substation or line has no spare capacity for new connections; it is local, so Gyeongbuk can be saturated for exports while Seoul is short.
- **Connection wait** (접속 대기): an applicant is waiting for a study or for reinforcement; the 9.6 GW of data centers and the projects behind 189 closed substations are both "waiting."
- **Output control** (출력제어): KPX has ordered plants to cut output; counted in "times" and MWh, highest in spring.
- **Grid-managed substation** (계통관리변전소): a substation formally closed to new renewable connections until a stated date; 205 designated in 2024, 189 remain.

Ask which of the four a headline means. A saturated substation can be fixed with one transformer; a 2032 connection date cannot.

## Where this goes next

Four things to watch. Whether the Dongseoul body reaches agreement and construction starts in November, or the case becomes the Special Act's first override; whether the draft 12th Basic Plan, due this fall, keeps the West Coast schedule; whether the regional tariff launches this year; and whether the target of 12 GW of battery storage by 2030, from 0.1 GW in 2025, turns into orders. Storage is the one thing that shortens a queue without a new line.

## Industry note

The listed companies here sit on the wires. KEPCO (KRX: 015760) owns the grid; LS Corp (KRX: 006260) is the parent of unlisted LS Cable & System, and Taihan Cable & Solution (KRX: 001440) is the other HVDC cable maker. Hyosung Heavy Industries (KRX: 298040) and HD Hyundai Electric (KRX: 267260) make the ultra-high-voltage transformers; the reactor side of [Korea's nuclear supply chain](/en/posts/korea-nuclear-industry-map/) sits one step upstream.

> This section is provided to help understand the industry and is not a recommendation to buy or sell any security. Investment decisions and their consequences are the reader's own.

---

*Sources: KEPCO, transmission and distribution business page, network statistics as of 2024; KEPCO, 11th Long-term Transmission and Substation Plan release (May 27, 2025); KEPCO webzine on the Wando–East Jeju HVDC (January 2025); KEPCO release on the Bukdangjin–Godeok HVDC completion (May 2024, via ZDNet Korea and Busan Ilbo); Ministry of Climate, Energy and Environment Notice No. 2026-168 on the East Coast–Shin-Gapyeong HVDC project period (July 2026); Ministry of Climate, Energy and Environment, industrial regional tariff design via Korea Policy Briefing (Aug. 26, 2026) and 2026 work report via Newspim (Aug. 4, 2026); Ministry of Climate, Energy and Environment, distributed energy special zone designations (Nov. 5, 2025; Dec. 2025, via Busan Ilbo); National Grid Expansion Special Act and enforcement decree (in force Sept. 26, 2025); National Assembly member Park Jeong, regional self-sufficiency data via Insight Energy News (Sept. 25, 2025); Electric Times on capital region consumption (May 21, 2026), the Jeju grid-managed substation release (Mar. 30, 2026), the first mainland solar curtailment (Apr. 9, 2024), the West Coast HVDC (Mar. 19 and May 18, 2026) and the Dongseoul station (June 9, 2026); Kyeongin Ilbo on the Dongseoul four-party body (Sept. 3, 2026); Daehan Economic Daily on the East Coast HVDC schedule (Nov. 19, 2024); Electric Industry News on the stage 2 route (2024); LS Cable & System release on the stage 2 contract (June 15, 2026); Korea Power Exchange, 2024 Jeju power system operating report (Feb. 2025); Shin & Kim client note on grid-managed substations (Sept. 3, 2024); Solutions for Our Climate press release on connection queues (May 19, 2026); Asia Today on mainland curtailment (May 13, 2026); CBRE Korea and Seoul Economic Daily on data center grid applications (July–Aug. 2026); Wood Mackenzie transformer lead-time surveys (2025–2026); Hankook Ilbo on the East Coast delay cost (July 2026)*
