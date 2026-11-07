---
title: "Big tech nuclear deals: why tech companies buy power from existing plants, from Amazon to the Three Mile Island restart"
date: 2026-11-08T09:00:00+09:00
dataAsOf: "2026-11-07"
categories: ["Nuclear & Energy"]
tags: ["big tech nuclear deals", "Amazon nuclear deal", "Three Mile Island restart", "power uprates", "additionality"]
description: "Near-term hyperscaler contracts favor running reactors, restarts and uprates over new SMRs. The physics, the FERC fight, and why Korea does not yet allow a direct nuclear PPA."
---

In August a transformer shipped from South Korea rolled onto Three Mile Island, the first of three, according to The National. It was headed for the unit that Microsoft has agreed to buy power from for 20 years. That reactor closed in 2019 and is not new.

That is the pattern. Small modular reactors get the headlines, but the contracts with near-term delivery dates went to machines already standing. On October 6, 2026, Google signed for 890 MW from Constellation, all of it from upgrades to 11 operating units, and a week earlier Amazon's Calvert Cliffs deal added 190 MW the same way. The Google announcement also included a separate 15-year supply agreement for 2,700 MW from Constellation's existing PJM fleet, which adds no new capacity.

I studied nuclear engineering and radiation science and live in South Korea, where a direct power purchase agreement for nuclear is not allowed. This post explains why the deals make engineering sense, what they change inside a plant, and why the argument over them is not settled.

> **Key takeaways**
> - Carnegie counted up to 13 GW of hyperscaler nuclear commitments through March 2026. The roughly 6.9 GW in power purchase agreements arrives by the early 2030s and mostly involves existing reactors; the 6.1 GW in direct partnerships depends on SMR developers delivering by the mid-2030s.
> - Restarts and uprates add power to the grid. Contracts for output from reactors that were already running are where the additionality criticism bites hardest, and where the two sides still disagree.
> - Korea runs on a different structure. Direct PPAs are limited to renewables, so nuclear output reaches companies through KEPCO's system, and bills to change that met ministry opposition and presidential skepticism in 2026.

## 1. Where the money has gone

Carnegie's June 2026 report, "Beyond the Hype," was tallied in March, so it misses the autumn deals. The table adds those. All dates are company or agency targets as of November 7, 2026.

| Route | Deal | Capacity | Stated timing |
|---|---|---|---|
| Existing PPA | Meta–Vistra (Perry, Davis-Besse) | 2,176 MW | Purchases begin late 2026 |
| Existing PPA | Meta–Constellation (Clinton) | 1,121 MW | From June 2027 |
| Existing PPA | Amazon–Talen (Susquehanna) | 1,920 MW | Ramping, full volume by 2032, runs through 2042 |
| Restart | Microsoft–Constellation (Crane, formerly TMI-1) | 835 MW | 2027 |
| Restart | Google–NextEra (Duane Arnold) | 615 MW plant, most of it to Google | No later than Q1 2029 |
| Uprate | Google–Constellation | 890 MW | First in 2028, all by 2032 |
| Uprate | Amazon–Constellation (Calvert Cliffs) | 190 MW of a 690 MW PPA | 2030 to 2032 |
| Uprate | Meta–Vistra | 433 MW | Through 2034 |
| Uprate | Google–Georgia Power (Vogtle, Hatch) | About 96 MW | Subject to state regulator approval |

Compare the new-build side. Carnegie lists Meta's TerraPower deal (up to 2.8 GW, first two units as early as 2032), Meta's Oklo campus (up to 1.2 GW) and Google's Elementl sites (1.8 GW, 2035, reactor not yet chosen). It describes these as modest capital, site commitments or advance offtake, and says hyperscaler interest has not produced the financing an order book for new reactors would require.

![Timeline from 2026 to 2036 comparing target power delivery dates for twelve US nuclear projects, most tied to big tech deals, across existing plant contracts, restarts, uprates and new small modular reactors](/images/big-tech-existing-nuclear-en.svg)

## 2. Why a running reactor suits a 24-hour buyer

A data center needs power at 3 a.m. as much as at 3 p.m. That makes capacity factor, the share of maximum possible output a plant actually produces, the first number to check. US nuclear ran at 91.1 percent in 2025, against 33.8 percent for wind and 24.0 percent for solar photovoltaics (EIA, Electric Power Monthly, October 2026 release).

In energy terms, 1 GW of nuclear at that rate yields about 8.0 TWh a year. The same nameplate of solar yields about 2.1 TWh.

Baseload operation follows from reactor economics: fuel is a small share of cost, so operators want to run flat out. Two caveats matter.

- **91 percent is not every hour.** US reactors typically stop every 18 to 24 months to refuel, mostly in spring and fall (EIA). A buyer that promises round-the-clock clean power still needs the grid during those weeks.
- **The electrons mostly do not change direction.** Constellation says Calvert Cliffs' output will keep flowing to the PJM grid, and Vistra says the same of its plants. PJM is the grid operator for 13 mid-Atlantic and Midwestern states. These are financial contracts more than wires.

## 3. What a restart actually takes

The name causes confusion, so the facts first. The 1979 accident was at Three Mile Island Unit 2. The unit returning is Unit 1, which closed in 2019 for economic reasons, four decades after the accident.

Constellation describes Unit 1 as a fully independent facility unaffected by the accident. Unit 2 is being decommissioned by a different owner, EnergySolutions.

Closing a US reactor is a legal act as well as a physical one. Once the operator certified permanent shutdown and fuel removal in 2019, the license no longer allowed it to operate or to hold fuel in the vessel, according to the NRC's Federal Register notice. So the return runs through several tracks:

- **License restoration.** One exemption and three license amendments, restoring operation through the license's April 19, 2034 expiry. Constellation plans to seek an extension to 2054.
- **Environmental review.** The NRC issued its final assessment and a finding of no significant impact in September 2026. That is a step, not the restart approval.
- **Hardware.** Constellation lists the turbine, generator, main power transformer, and cooling and control systems.
- **People and fuel.** Operators have to be trained and licensed, and new fuel bought.
- **The wire.** PJM approved reconnection from 2027, but full delivery may wait until after 2030 for transmission upgrades, World Nuclear News reports. FERC agreed in June 2026 to let Constellation move 760 MW of interconnection rights from its Eddystone units to help close that gap.

Our [post on the data center grid bottleneck](/en/posts/datacenter-grid-bottleneck/) covered why that last item matters. Even a reactor that used to feed this grid has to wait for it.

Not everyone is on board. TMI Alert, a local group, says it is litigating aspects of the restart in federal court and challenging a state decision (The National, August 2026).

Palisades in Michigan shows how a restart can stall late. Fuel loading began August 30, then one assembly tilted about 30 degrees and could not be lifted with standard equipment. Holtec built a custom device, the NRC approved a one-time license amendment, and the assembly went to the spent fuel pool.

The NRC reported no release or injury, and refueling was resuming as of late October (Nuclear Engineering International). Energy Secretary Chris Wright said on October 29 that a restart could come as soon as late November, but I found no date from the company (Michigan Public). The contractual target is selling power by March 2027. Palisades is not a big tech deal; its buyers are the Wolverine and Hoosier cooperatives.

## 4. What an uprate changes inside the plant

An uprate raises the power a reactor is licensed to produce. The licensed thermal power goes up, and utilities usually refuel with slightly more enriched uranium or a higher share of new fuel so the core can sustain that power through the operating cycle. More heat means more steam, and the turbine makes more electricity (NRC). The NRC sorts them into three kinds:

- **Measurement uncertainty recapture, under 2 percent.** Better feedwater flow measurement reduces the margin held back for uncertainty in the power calculation.
- **Stretch, typically up to 7 percent.** Usually instrument setpoint changes without major modifications.
- **Extended, approved up to 20 percent.** Significant work on high-pressure turbines, condensate pumps and motors, generators and transformers. Calvert Cliffs' roughly 10 percent falls here, according to the American Nuclear Society.

The electrical side gets the attention, but what caught my eye when I studied this is the core. More thermal power means more decay heat to remove after shutdown and more neutrons reaching the pressure vessel over its life. That is why the safety analysis is redone and reviewed, and why this is not simply a turbine purchase.

The scale is real. The NRC had approved 171 uprates worth about 8,030 MWe by January 2022. Constellation compares the Google package to one large new reactor, at more than $4.3 billion of its own investment; it has not published the split by unit or the share from turbine efficiency. On October 27, it received a conditional DOE loan commitment of up to $5 billion for uprates, which is not yet a final decision on any plant.

## 5. Who pays: additionality and the FERC fight

Additionality asks a blunt question: would this clean power exist without the contract?

**The critics.** Princeton's Jesse Jenkins argued after Meta's January 2026 announcement that buying from two operating Ohio plants adds no clean supply for new demand and could raise both emissions and rates (Heatmap). PJM's market monitor attributed $6.5 billion, or 40 percent, of the $16.4 billion cost of the auction for 2027/28 to data center load.

**The defenders.** Jeff Dennis of the Electricity Customer Alliance, whose members include Meta, told Heatmap that the plants keep selling into energy and capacity markets, so nothing is being removed. He also argues that uprates rely on the revenue certainty of the wider contract. Ethan Paterno of PA Consulting accepted the critique at first principles but said such contracts may keep plants open that would otherwise retire.

The retirement argument has a real case behind it. Clinton was slated for early closure in 2017, and its Illinois credit support ends in mid-2027, when Meta's contract begins. Vistra says its three plants were on a path to retirement as recently as 2020, though that is the seller's account.

My own view is that these deals should not be judged as one lump. Restarts and uprates add megawatts, while rescues turn on a counterfactual nobody can test. Contracts for output from plants that had no plan to close look the weakest as climate claims.

In the Meta–Vistra deal, 433 of 2,609 MW, about 17 percent, is new capacity.

**The behind-the-meter fight is separate.** In November 2024, FERC rejected a plan to raise the Amazon campus load connected directly to Susquehanna from 300 MW to 480 MW. Exelon and AEP had argued that up to $140 million a year in transmission costs could shift to other customers. Talen then agreed a new front-of-the-meter structure, with power going through the grid and PPL handling delivery, and a reconfiguration planned for 2026.

FERC has since found PJM's tariff unjust and unreasonable on co-located load, in December 2025 and again in its June 18, 2026 order. It told PJM to offer three transmission services matched to how a customer actually uses the grid, set a 50 MW threshold for the netting rules, and accepted penalties for breaches. Developers get a clearer route, and other customers get protection against a large load treating the grid as free backup.

PJM proposed starting June 1, 2029, and FERC asked for more support. PJM made a partial compliance filing on August 17. The remaining PJM compliance items, the transmission owners' compliance and the related large-load filings are due November 16.

## 6. The view from Korea

A direct nuclear PPA is not allowed in Korea today, and the reason is structural. KEPCO, the state utility, [buys nearly all the electricity on the wholesale market](/en/posts/korea-electricity-market-kpx-smp/) and resells it. KHNP (Korea Hydro & Nuclear Power), which operates all the country's reactors, sells into that market. Direct power purchase agreements are allowed only for renewables (Korean trade press Energy Daily, July 2026).

Rep. Ko Dong-jin of the opposition People Power Party introduced a bill on July 27, 2026 to add nuclear, with a legal basis for state support. Two earlier bills drew ministry opposition in March. Korean chipmakers and steelmakers want it. POSCO's energy executive reportedly asked at a September National Assembly forum to pay for refurbishing the shut Wolsong 1 in return for its power, and President Lee Jae-myung raised concern on social media on October 11 about favoring large companies (NewDaily, October 13). I could not confirm any committee progress as of November 7.

The additionality debate looks different here. In 2025, nuclear settled at about KRW 79 per kWh (about 6 US cents) against about KRW 158 for LNG, according to the Korea Power Exchange. If cheap nuclear output leaves the pool, the worry is that KEPCO's average purchase cost rises and falls on everyone else (Energy Economic News, July 2026).

In PJM the fight is over capacity prices and transmission charges. In Korea it is over who gets the low-cost pool.

Two more contrasts stand out. KHNP's fleet ran at 84.6 percent in 2025 against a target of 89 percent for 2026 (Herald, January 2026), and Korea's growing problem is [cutting nuclear output in low-demand seasons](/posts/nuclear-load-following-korea/) (in Korean), not selling more of it. And Korea's own SMR program, [i-SMR](/en/posts/korean-smr-ismr-status/), targets design approval in 2028 and commercial operation in 2035, with no announced power buyer.

The links are industrial for now. KHNP and Doosan Enerbility joined Amazon and X-energy in an SMR partnership in August 2025.

The [US-Korea nuclear package](/en/posts/us-korea-nuclear-package/) of up to eight large reactors had no named power buyer as of early October. If hyperscalers keep preferring running plants, someone else has to supply that demand.

## Where this goes next

Five things to watch:

- **Crane.** The NRC's final decision will test the 2027 date.
- **Palisades.** First power will show how many surprises a restart still holds.
- **Georgia.** The state regulator still has to rule on the uprate tariff, which Georgia Power says protects other customers.
- **PJM.** Final rules will decide how much co-location is worth.
- **Korea.** Does the nuclear PPA bill reach a committee vote at all?

## Industry note

Operators named here are Constellation (NASDAQ: CEG), Vistra (NYSE: VST), Talen Energy (NASDAQ: TLN), NextEra Energy (NYSE: NEE) and Southern Company (NYSE: SO, parent of Georgia Power). In Korea, Doosan Enerbility (KRX: 034020) and KEPCO (KRX: 015760) connect through the SMR partnership and the PPA debate. Contract size is not the same as earnings, and approvals and construction can move the timing.

> This section is provided to help understand the industry and is not a recommendation to buy or sell any security. Investment decisions and their consequences are the reader's own.

---

*Sources: Constellation press releases (Google, October 6, 2026; Amazon, September 30, 2026; DOE loan commitment, October 27, 2026; Meta, June 3, 2025; Microsoft, September 20, 2024) and Crane site page; Google blog (October 6, 2026); Vistra press release (January 9, 2026); NextEra releases (October 2025; September 8, 2026); Talen Energy release (June 11, 2025, via press coverage); Carnegie Endowment, "Beyond the Hype" (June 2026); EIA, Electric Power Monthly Table 6.07.B (October 2026) and Today in Energy on refueling outages; NRC power uprate fact sheet and Palisades page; Federal Register notices on Crane (June 8 and September 25, 2026); World Nuclear News (Crane, June and September 2026; Calvert Cliffs, October 2026; Georgia, September 2026; Susquehanna, November 2024); American Nuclear Society Nuclear Newswire (Calvert Cliffs, October 2026); Nuclear Engineering International (Palisades, October 26, 2026); The National (Crane transformer and TMI Alert, August 2026); Michigan Public (Palisades, October 29, 2026); Heatmap (additionality debate, January 2026); Utility Dive (PJM market monitor, January 2026; Google deal, October 2026); Willkie Farr & Gallagher client alert on FERC's June order (July 2026); Mayer Brown on FERC's December order (January 2026); FERC notice of extension in docket EL25-49-002, posted by PJM (August 2026); Energy Daily and Energy Economic News on Korea's nuclear PPA bill (July 2026); SBS Biz and The Fact on earlier bills (March 2026); NewDaily (October 13, 2026); Herald on KHNP utilization (January 2026); Korea Power Exchange 2025 settlement figures; X-energy partnership as reported by Carnegie*
