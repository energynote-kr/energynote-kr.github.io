---
title: "The real bottleneck for AI data centers is the wire, not the power plant — Korea's 1.9% approval rate and the US interconnection queue"
date: 2026-09-03T12:30:00+09:00
dataAsOf: "2026-09-03"
categories: ["Nuclear & Energy"]
tags: ["data centers", "transmission", "HVDC", "transformers", "interconnection queue"]
description: "Only 1.9% of Seoul-area data center power applications are approved. Korea's HVDC delays, 2–3-year transformer lead times and PJM's 40-month queue explained."
---

1.9 percent. Through March 2026, developers had filed 522 grid impact assessments for data centers in the Seoul metropolitan area, asking for a combined 33,592 MW. Ten of them had received a final "supply available" decision, according to a July 2026 tally by CBRE Korea, the real estate services firm.

The reason is not a shortage of power plants. In the first seven months of 2025, the provinces of Gyeongbuk and Jeonnam generated more than 200 percent of the electricity they consumed, while Seoul generated 7.5 percent of its own (data submitted to the National Assembly's Environment and Labor Committee).

Korea has electricity to spare in the east and south. **What it does not have is a way to bring it to where the data centers want to be**. That is the story of this post, and, as the second half shows, it is the same story the United States tells in the language of the "interconnection queue."

> **Key takeaways**
> - Seoul-area data center power applications have a 1.9 percent approval rate (as of March 2026). The constraint is transmission lines, substations and transformers, not generation.
> - Korea's flagship East Coast–capital region HVDC line missed its June 2026 target and now runs to December 2027; transformer lead times worldwide are two to three years.
> - The US PJM grid's average interconnection wait is 40 months. Oklo's 750 MW Virginia project was withdrawn from PJM's study cycle on August 3, 2026 over paperwork, not reactor technology.

## 1. Korea's map problem: power in the east and south, demand in Seoul

IDC Korea, the market research firm, forecast in June 2025 that power demand from Korean data centers would grow from **4,461 MW in 2025 to 6,175 MW in 2028**, about 11 percent a year. The location of that demand is the problem.

Of 290 data center electricity-supply applications received between August 2024 and June 2025, **195 (67 percent) were for the capital region** around Seoul, and together they asked for roughly 20 GW, the output of twenty 1 GW reactors (ministry and utility data disclosed to the National Assembly in July 2025). Of the 19 Seoul-area projects that had completed review by then, four passed.

Three institutions run this process, and international readers will meet them again below.

- **KEPCO** (Korea Electric Power Corporation) is the state-controlled utility that owns the entire transmission and distribution grid and sells nearly all of Korea's electricity. Every data center's power application lands on its desk.
- **MOTIE**, the Ministry of Trade, Industry and Energy, held the energy portfolio until October 1, 2025, when electricity, grid and energy-transition policy (and KEPCO, among 21 agencies) moved to the new **Ministry of Climate, Energy and Environment**; MOTIE, since renamed the Ministry of Trade, Industry and Resources, kept resources and overseas nuclear projects. The 2025 figures above came through MOTIE; the 2026 HVDC notice below came from the new ministry.
- The **grid impact assessment** is a review, in force since June 14, 2024 under the Distributed Energy Act, that any new load of 10 MW or more anywhere in the country must pass before KEPCO will sign a supply contract. Its scoring favors sites outside the capital region, which is where it bites hardest. It is the gate that produces the 1.9 percent.

The policy intent is to push data centers out of Seoul: distributed-energy special zones and tax incentives are on offer for projects that move to the provinces. But relocated projects join a queue of their own.

As of the end of March 2026, about **9.6 GW of data center applications nationwide were still waiting for approval** (Seoul Economic Daily, citing KEPCO data, August 2026). Wherever a developer builds, it runs into the same wall.

Korean data center power applications, as of the dates shown:

| Measure | Figure | Source |
|---|---|---|
| Seoul-area filings | 522 projects, 33,592 MW (cumulative to Mar 2026) | CBRE Korea, July 2026 |
| Approved | 10 projects ("supply available"), 1.9% | CBRE Korea, July 2026 |
| Filings, Aug 2024–Jun 2025 | 290 nationwide; 195 (67%) Seoul area, about 20 GW | MOTIE/KEPCO data to the National Assembly, July 2025 |
| Backlog | About 9.6 GW nationwide, end of March 2026 | Seoul Economic Daily / KEPCO, August 2026 |

## 2. What takes longer than a power plant: the line and the transformer

### The East Coast–capital region HVDC line

The case that explains Korea's numbers is the **East Coast–capital region HVDC** (high-voltage direct current) transmission line: 280 km built to carry 8 GW from the Shin-Hanul reactors at Uljin and the east coast coal plants to the Seoul area. It was first planned in 2009.

Local opposition changed the route and the technology, and both the stage 1 target (June 2025) and the stage 2 target (June 2026) came and went. In July 2026 the Ministry of Climate, Energy and Environment issued a notice extending the stage 1 (East Coast–Shin-Gapyeong) project period to **December 2027**.

The gateway on the Seoul end is the **Dongseoul converter station** in Hanam, just east of the city. KEPCO won an administrative appeal in December 2024 against the local government's refusal to permit it, but the last local permit was still outstanding and, as of late July 2026, construction had not begun (Korean daily Hankook Ilbo, July 29, 2026).

KEPCO estimates the delay costs it about **KRW 300 billion (about $220 million) a year**, and some east coast plants have been held below 20 percent utilization for lack of transmission capacity (Hankook Ilbo, July 2026). The country's cheapest electricity is sitting at the far end of a line that does not exist yet.

### Transformers: a global two-to-three-year wait

The second bottleneck is the **transformer**. According to Wood Mackenzie, the average lead time for a power transformer in the United States rose from about 50 weeks in 2021 to **128 weeks in the second quarter of 2025**, and substation-class units passed 160 weeks in 2026. Prices are up 77 percent on 2019.

The shortage runs through the whole supply chain: electrical steel, copper, and the skilled workers who wind the coils. It is not a US problem or a Korean problem; it is the same queue everywhere. A permitted power plant whose transformer arrives in two or three years delivers nothing in the meantime.

![Diagram of the power flow from power plants through the transmission grid to data centers, with the grid marked as the bottleneck, alongside IDC Korea's forecast of Korean data center power demand rising from 4,461 MW in 2025 to 6,175 MW in 2028](/images/datacenter-grid-bottleneck-en.svg)

## 3. The US version: the interconnection queue

In the United States this problem has a name: the **interconnection queue**, the line a generator (or a large load) waits in while the grid operator studies whether it can be connected. At the end of 2025 the projects waiting in US queues totaled about **2,060 GW**, more than the country's entire installed generating capacity (Lawrence Berkeley National Laboratory, "Queued Up 2026").

In PJM, the grid operator for the mid-Atlantic region that includes northern Virginia's data center corridor, the average wait is **40 months** (Carbon Direct analysis, May 2026). The time from application to operation across the region has stretched from under two years in 2008 to more than eight years in 2025 (RMI).

### Oklo's 750 MW Virginia project

Oklo, the small modular reactor developer covered in [our 2026 SMR licensing map](/en/posts/smr-global-status-2026/), ran into this wall in August 2026. In April it applied to PJM for a **750 MW project in Virginia** (in Dominion Energy's zone) combining 150 MW of nuclear, 300 MW of fuel cells and 300 MW of gas.

PJM issued a deficiency notice on May 15 listing six categories. Oklo says it cured them; PJM then posted further comments on its portal on June 24 without notifying the company, among them a request for data on **ride-through**, the ability to keep running through a sudden voltage dip, and on **August 3 withdrew the project from its Cycle 1 study process**, the first full interconnection cycle under PJM's reformed rules.

On August 28 Oklo filed an emergency complaint with the Federal Energy Regulatory Commission (FERC), arguing the withdrawal means a delay of at least 14 months; FERC had not ruled as of early September 2026.

Nothing in the dispute is about the reactor. **More than a year of schedule is riding on connection paperwork**. That is what a queue weighs.

## 4. So should we build plants closer to the demand?

Here the argument splits, in Korea as in the US. One side says: put generation (gas plants, and eventually SMRs) close to Seoul and bypass the long lines. The other says: the country already has surplus generation, so grid investment and moving demand out of the capital should come first.

Each side has a fair point against the other. The "build near demand" camp points to the reality that a single transmission line can take more than a decade. The "grid first" camp answers that a plant built next to Seoul still needs the same substations and transformers, so it changes the length of the wire but not the queue for the equipment.

Environmental groups take a third position. Green Korea and the Green Transition Institute argued in August 2026 that the AI data center demand in the draft 12th Basic Plan rests on uncertain corporate investment plans and should be re-examined before it justifies new plants (Kyunghyang Shinmun, August 20, 2026).

With Korea's 12th Basic Plan for Electricity Supply and Demand, the government's rolling 15-year power plan, being drafted and a public deliberation on new reactors under way (see [our post on the new-reactor debate](/en/posts/new-reactor-public-debate/)), the two camps agree on one thing: **the cost of the grid ends up in the electricity bill**, whichever way it is built. Where SMRs fit in Korea's own plans is covered in [our i-SMR status report](/en/posts/korean-smr-ismr-status/). Speaking from inside the nuclear field, one cautious observation: the hotter the argument over which kind of power plant to build, the further the slowest item on the list, the wire, slips down the agenda.

## Where this goes next

Three dates will show whether the wall is moving. In Korea, whether the Dongseoul converter station finally breaks ground in the second half of 2026, and whether the December 2027 date for stage 1 of the East Coast line holds. In the US, FERC's ruling on Oklo's complaint, which will signal how much slack PJM has to give data center-linked projects, and Wood Mackenzie's next transformer lead-time survey, which will say whether the two-to-three-year wait has started to shorten.

## Industry note

The value chain here sits one step downstream of the power plant: transformers, switchgear, cables and transmission construction. In Korea, HD Hyundai Electric (KRX: 267260) and Hyosung Heavy Industries (KRX: 298040) make ultra-high-voltage transformers with large North American export shares, LS ELECTRIC (KRX: 010120) and Jeryong Electric (KOSDAQ: 033100) cover substation and distribution equipment, and LS Corp (KRX: 006260, parent of unlisted LS Cable & System) and Taihan Cable & Solution (KRX: 001440) supply HVDC cable. In the US, GE Vernova (NYSE: GEV), Quanta Services (NYSE: PWR) and Eaton (NYSE: ETN) cover grid equipment, transmission construction and data center power distribution. A two-to-three-year lead time means a full order book, but capacity additions and permitting delays change when that revenue arrives; our [Korean guide to nuclear-sector stocks](/posts/nuclear-stocks-guide/) (in Korean) covers the reactor side.

> This section is provided to help understand the industry and is not a recommendation to buy or sell any security. Investment decisions and their consequences are the reader's own.

---

*Sources: IDC Korea, Korean data center power demand forecast (June 2025); MOTIE and KEPCO, data center electricity-supply application status submitted to the National Assembly (July 2025); CBRE Korea, data center grid impact assessment status (July 2026); Ministry of Climate, Energy and Environment Notice No. 2026-168 on the East Coast–Shin-Gapyeong HVDC project period (July 2026); Hankook Ilbo and Kyeongin Ilbo reports on the Dongseoul converter station (2026); Seoul Economic Daily, KEPCO nationwide data center grid impact assessment status (August 2026); Kyunghyang Shinmun report on civic groups' response to the 12th Basic Plan demand forecast (August 2026); Wood Mackenzie transformer lead-time surveys (2025–2026, as reported by POWER and Data Center Knowledge); PJM interconnection reform materials (2026); Carbon Direct, PJM and ERCOT queue analysis (May 2026); RMI, "PJM's Speed to Power Problem" (2025); Lawrence Berkeley National Laboratory, "Queued Up 2026"; Utility Dive reporting on Oklo's FERC complaint EL26-101 (2026); Shin & Kim client note on the Ministry of Climate, Energy and Environment (September 2025); Kim & Chang note on the Distributed Energy Act enforcement decree (2024); company investor relations materials*
