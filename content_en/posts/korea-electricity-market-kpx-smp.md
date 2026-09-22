---
title: "How Korea's electricity market actually works: KPX, the system marginal price, and why KEPCO lost money"
date: 2026-09-22T21:40:00+09:00
dataAsOf: "2026-09-22"
categories: ["Nuclear & Energy"]
tags: ["KPX", "system marginal price", "KEPCO", "electricity market reform"]
description: "Korea's electricity is bought and sold through one exchange and one retailer. A plain-language guide to the SMP, the settlement adjustment coefficient, and KEPCO's 2021-2023 losses."
---

In December 2022, the hourly price at which Korea's power generators were paid averaged **KRW 267.63 per kilowatt-hour** (about 19.8 cents) for the month. The state utility that had to buy all of it, KEPCO, was selling electricity to households and factories at a small fraction of that. The gap between those two numbers is the plainest way to understand why Korea's national utility lost roughly KRW 43 trillion (about $32 billion) in three years.

This post is a guide to the machine behind that gap: the **Korea Power Exchange** (KPX), which runs the wholesale market; **KEPCO** (Korea Electric Power Corporation), the only company allowed to sell electricity to most customers; and the pricing rules between them that decide who gets paid what.

> **Key takeaways**
> - Korea runs a single-buyer market: KPX sets the hourly wholesale price, and KEPCO alone resells to nearly every customer at tariffs the government sets separately.
> - The price is usually set by the last LNG plant called on to meet demand, but nuclear and coal do not simply collect that price, a **settlement adjustment coefficient** claws back most of their margin above cost before KEPCO pays them.
> - KEPCO lost about KRW 43 trillion from 2021 to 2023 because a fuel-cost spike raised its purchase price faster than tariffs, set by policy, could follow; it returned to a record KRW 13.52 trillion operating profit in 2025, but KRW 36.1 trillion of the old losses is still unresolved as of late 2025.

## 1. One exchange, one buyer

Korea's electricity sector was split apart in 2001, but only partway: generation was separated from the wire and retail business, and six state generation companies were created. Retail never opened up. The result today:

- **KPX** (Korea Power Exchange) dispatches power plants hour by hour and clears the wholesale market. It never buys or sells electricity itself; it only sets the price.
- **KEPCO** (Korea Electric Power Corporation), majority state-owned, is the only company that buys wholesale electricity and resells it to almost every household and business. It also owns the transmission and distribution grid.
- **Six generation subsidiaries** sell into the market: KHNP (Korea Hydro & Nuclear Power, which runs every reactor) and five coal-and-gas gencos, Korea South-East Power, Korea Midland Power, Korea Western Power, Korea Southern Power and Korea East-West Power. All six are KEPCO subsidiaries.
- **Private and independent power producers** (IPPs), mostly LNG and some coal plants owned by conglomerates such as SK and GS, sell into the same market outside the KEPCO group. Private generators say they now produce more electricity than the five state gencos combined, per a private-generator association cited by UPI in August 2026.

## 2. How the hourly price is set

KPX runs a day-ahead market. Generators submit capacity and cost data; KPX ranks them cheapest to most expensive and dispatches enough to cover the hour's forecast demand. The price paid for that hour, the **system marginal price**, or SMP, is set by the costliest plant KPX had to call on, not by an average of all plants running.

Nuclear and coal are cheap to run and dispatched first, so the plant that ends up setting the price is almost always an LNG unit, called on last to cover the final slice of demand. LNG's fuel price tracks the international gas market directly, so when gas spikes, so does the SMP, for every generator running that hour, not just the LNG one.

That single fact is the seed of Korea's problem: a cheap generation fleet sits inside a price that one expensive fuel controls.

## 3. What nuclear and coal actually get paid

Paid the SMP outright, nuclear and coal would collect a large margin above real cost whenever gas prices rose, a windfall paid for by KEPCO. Two mechanisms change that.

- **Capacity payment**, or CP: paid per kilowatt of available capacity, dispatched or not, to keep plants financially viable. It came to about KRW 7.5 trillion of the roughly KRW 78 trillion KPX settled with generators in 2023, about 9.5% of the total.
- **Settlement adjustment coefficient**, 정산조정계수 in Korean: a factor between 0 and 1, applied to the SMP before KEPCO pays its own gencos, that shaves off margin above their actual cost. KPX's Cost Assessment Committee reviews it, and the ministry sets each coming year's coefficient at year-end. When SMP is low it sits near 1, letting gencos keep nearly the full price; when SMP spikes, as in 2022, it is pushed toward 0, clawing the windfall back for KEPCO.

The coefficient applies only to KEPCO's own six gencos; private and IPP generators are paid the SMP directly, without it.

![Flow diagram of Korea's electricity market: state gencos and private generators sell into KPX, which sets the SMP, capacity payment and settlement adjustment coefficient; KEPCO buys everything and resells to residential, industrial and other customers at government-set tariffs](/images/korea-electricity-market-en.svg)

## 4. When the price cap kicked in

By late 2022, Russia's war in Ukraine had pushed global LNG prices to extremes, and Korea's SMP rose with them, from a 2021 average of about KRW 94.34 per kWh to a December 2022 monthly average of KRW 267.63. The ministry responded with an emergency **SMP price cap** (SMP 상한제), announced May 24, 2022 and first triggered that December.

- **December 2022 to February 2023**: the cap took effect December 1, 2022 at KRW 158.96 per kWh on the mainland (KRW 226.56 on Jeju), about 150% (1.5 times) of the ten-year average SMP. In December alone it cut settlement payments by about KRW 684 billion, split between LNG plants (KRW 346.1 billion) and smaller renewable and non-central generators (KRW 326.2 billion). A three-month limit forced it to lapse in March 2023.
- **April 2023**: SMP climbed back into cap territory, and the ministry reactivated it for one month.
- **After that**: a sunset clause let the enabling rule expire automatically on November 30, 2023. It has not returned since.

Solar, wind and private generators opposed the cap loudly, arguing it cut rooftop solar returns so much that some projects would need 15 years to recover capital; some prepared lawsuits claiming it violated their property rights. Their case: suppressing payments after contracts were signed changes the economics generators had agreed to.

## 5. Why this bankrupted KEPCO, a worked example

KEPCO's retail tariffs are not set by its purchase costs. They are policy prices, reviewed quarterly, and through the 2021-2023 fuel shock the government held them down far more than KEPCO's wholesale bill rose.

The arithmetic, in miniature: in 2024, KEPCO's average electricity-sales revenue was about KRW 162.9 per kWh sold, rising to KRW 170.4 in 2025 after repeated hikes. But at the worst of the crisis, the monthly average SMP it had to pay generators hit KRW 267.63 per kWh, far above where either figure stood at the time. Multiply a gap that size across tens of terawatt-hours a month, and the shortfall runs into trillions of won.

That is close to what happened: consolidated operating losses of about KRW 5.8 trillion in 2021, a record KRW 32.7 trillion in 2022, and KRW 4.5 trillion in 2023, a cumulative **KRW 43 trillion** (about $32 billion), per KEPCO's filings and Korean press tallies. KEPCO's own explanation, per the Seoul Economic Daily in February 2026, was that it "absorbed fuel costs as debt rather than passing them on to electricity rates" as LNG prices surged. Debt grew from KRW 145.8 trillion at end-2021 to KRW 205.7 trillion at end-2025.

## 6. From losses to record profit, and 2026's freeze

Industrial tariffs rose seven times between July 2022 and October 2024, a cumulative increase of roughly 70%, while household tariffs stayed mostly frozen. That, plus calmer fuel prices, turned KEPCO around: its first profit in four years came in 2024 (about KRW 8.3 trillion), then a record consolidated operating profit of KRW 13.52 trillion in 2025 on revenue of KRW 97.43 trillion, a sixth straight annual record.

The turnaround has not closed the hole. Of the roughly KRW 47.8 trillion in operating losses accumulated from 2021 to 2023 on a broader accounting basis, about **KRW 36.1 trillion remained unresolved at end-2025**; KEPCO said normalizing its finances would take three to four more years like 2025. Rates stayed frozen again for Q4 2026, KED Global reported on September 21, even as rising fuel costs argued the other way, a decision the government framed as protecting households and businesses over the balance sheet. Industrial customers pushed back on their own front: Samsung Electronics and SK Hynix rejected a KEPCO proposal that they prepay about KRW 25 trillion (about $17 billion) of future bills to help fund grid expansion for their own chip plants, Korean press reported in September 2026.

## 7. What is being reformed

Three changes are moving as of September 2026, alongside the wider **12th Basic Plan for Electricity Supply and Demand**, originally due as a government draft in October, now pushed back after the ministry launched a public deliberation on nuclear power's role that runs through December, which leaves the final plan's year-end timeline uncertain.

- **Regional (locational) pricing**: under the Special Act on the Promotion of Distributed Energy (in force since June 2024), the government and KEPCO published a design in August 2026 dividing the country into zones, cutting industrial rates by up to about KRW 18 per kWh in the south while leaving the southern Seoul metro area nearly unchanged, an estimated KRW 2.8 trillion a year in combined industrial savings meant to pull factories and data centers toward surplus provinces. Launch is targeted within 2026.
- **A two-track pilot for renewables on Jeju**: since June 1, 2024, Jeju has run a 15-minute real-time market, a reserve-capacity market and a bidding system letting solar and wind compete on price and forecast output, outside the conventional day-ahead process. KPX is now extending it to virtual power plants and two-way bidding and calls Jeju the test bed for a nationwide rollout, though industry participants say compensation rules for batteries, EV chargers and heat pumps remain unsettled (Sept. 2026).
- **A possible generation-subsidiary merger**: the government is weighing merging KEPCO's five thermal gencos into one company of about 53 GW. Private generators oppose it, telling their association, per UPI in August 2026, that a larger state genco would gain more influence over the settlement rules, including the coefficient, that decide what private plants get paid.

## 8. The critics' case

No group here is satisfied. Industrial users say seven hikes in two years, even as KEPCO now books record profit, is too much; Samsung and SK Hynix rejected its own bill-prepayment request. Renewable developers and small private generators say the SMP cap hit their contracts after the fact and nearly wiped out rooftop solar returns, with compensation some still call inadequate. Private thermal generators argue the coefficient and a possible genco merger both concentrate pricing power in KEPCO's hands, even though private plants now generate more than the five state gencos combined. None of this is groundless; the government has mostly deferred these fights into the reforms above rather than resolved them.

## Where this goes next

Two things converge this fall. The 12th Basic Plan will set the mix that decides how much of Korea's electricity stays cheap (nuclear, coal) versus price-setting (LNG), and the locational-pricing rollout will decide whether provincial industrial users see the savings promised for 2026. The real test is whether KEPCO's balance sheet normalizes on the "three to four years" timeline it has set itself, the 2021-2023 losses are still on the books, and another fuel-price shock before they clear would leave far less room to absorb it than four years ago.

The settlement adjustment coefficient is, in my experience, the hardest piece of this system for outsiders to picture, mostly because Korean coverage rarely explains why it exists: it is not a subsidy, but a brake on the windfall that uniform pricing would otherwise hand to the cheapest generators in the room.

## Industry note

KEPCO (KRX: 015760) is the listed company whose earnings move with every piece of this system: a tariff freeze, a rate hike or a coefficient change all land on its income statement first. None of its six generation subsidiaries, including KHNP, trades separately, they are wholly owned. Korea's largest private generators sit inside conglomerates such as SK and GS rather than as standalone power-generation tickers.

> This section is provided to help understand the industry and is not a recommendation to buy or sell any security. Investment decisions and their consequences are the reader's own.

---

*Sources: Korea Power Exchange (KPX), Electric Power Statistics Information System and market operation rules; KEPCO, FY2025 consolidated financial results; Ministry of Trade, Industry and Energy, SMP price cap notice (May 24, 2022) and related market-rule amendments; Shin & Kim, newsletters on the SMP price cap; Korea Times and KED Global on KEPCO's 2021-2023 losses and 2024-2025 results; Seoul Economic Daily on KEPCO's FY2025 results and debt (Feb. 27, 2026) and on the KEPCO genco-merger debate (Aug. 13, 2026, via UPI); Korea Herald on the regional/locational electricity-pricing plan (Aug. 2026); KED Global on the Q4 2026 tariff freeze (Sept. 21, 2026); Ministry of Climate, Energy and Environment on the 12th Basic Plan process (Aug.-Sept. 2026); Solutions for Our Climate (SFOC) and Korean trade press on renewable-industry opposition to the SMP cap; Korean energy trade press (Electric Times, Energy News, EPJ, Financial News) on the settlement adjustment coefficient and the Jeju real-time market pilot*
