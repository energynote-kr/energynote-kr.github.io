---
title: "What does it mean when a reactor goes critical? Reactor criticality and first criticality explained"
date: 2026-11-01T09:00:00+09:00
dataAsOf: "2026-10-31"
categories: ["Nuclear & Energy"]
tags: ["reactor criticality", "first criticality", "delayed neutrons", "supercritical vs critical", "Rooppur"]
description: "A reactor going critical is running steadily, not out of control. How k, delayed neutrons and control rods work, and why first criticality is a commissioning milestone."
---

At 15:34 local time on Sunday, October 11, 2026, Bangladesh's first nuclear power reactor went critical. World Nuclear News reported it the next day, and Rosatom, the Russian state nuclear company supplying Rooppur unit 1, presented it as a major step for the project.

To many readers, "critical" sounds like an alarm. In everyday English a critical patient is close to death and a critical failure is the worst kind. In reactor physics the word means something almost boring: the chain reaction is exactly in balance.

This piece explains what criticality is, why a reactor can sit there safely for months, why first criticality is the moment a new plant comes alive, and how all of this differs from a bomb's supercritical mass and from a criticality accident.

## 1. Reactor criticality in one idea: each generation replaces itself

When a uranium-235 nucleus absorbs a neutron and splits, it releases two or three new neutrons. Some are absorbed in water or structures, some leak out of the core, and the rest go on to cause the next round of fissions. The average number of next-generation fissions per fission is the effective multiplication factor, k.

The glossary used by the US Nuclear Regulatory Commission's Technical Training Center sorts the three cases cleanly:

- **Subcritical (k below 1)**: the chain reaction converges and dies away. A shut-down reactor sits here.
- **Critical (k equal to 1)**: the chain reaction is self-sustaining. Power stays constant.
- **Supercritical (k above 1)**: the chain reaction diverges. Operators use this briefly to raise power.

Think of a family tree. If each generation leaves exactly one generation's worth of descendants, the family stays the same size. Criticality is that steady state, nothing more. It says nothing about how big the family is: a reactor at near-zero power on the day of first criticality and one running at 100% rated power both have k equal to 1.

![Diagram showing neutron numbers falling, staying constant or rising over four generations in subcritical, critical and supercritical reactors, with the commissioning sequence from fuel loading to first criticality, low-power tests, power ascension and commercial operation](/images/reactor-criticality-en.svg)

## 2. The 0.65% that makes reactors controllable

The real key is time. Most fission neutrons are prompt, emitted at the instant of fission, and a chain carried only by prompt neutrons turns over generations far faster than a blink. If that were the whole story, a k just slightly above 1 would make power climb almost instantly.

A small minority changes everything. Delayed neutrons come from fission products that undergo beta decay first, so they appear seconds to minutes after the fission, according to the NRC glossary. For uranium-235 they are only about 0.65% of all fission neutrons (data sets give 0.64% to 0.66%), and the World Nuclear Association calls their delayed release the crucial factor that lets a chain-reacting system be controlled.

Here is a savings-account way to see it. Suppose almost all your interest is paid instantly, but 0.65% of it arrives a little later. If you raise the interest rate by less than that 0.65%, the balance can only grow by waiting for the late payments. That wait is what gives operators and control systems time to act.

Raise it by more than 0.65% and the account grows on instant payments alone. In reactor terms that is **prompt criticality**: the prompt neutrons by themselves make k equal 1. In a real core the line sits lower than 0.65%, because plutonium-239, whose delayed fraction the World Nuclear Association gives as 0.23%, builds up as the fuel burns. Reactor design and operating limits keep normal power changes far below that line.

## 3. Reactivity, control rods and boron

Reactivity measures how far a reactor is from critical. The NRC training glossary defines it as (k − 1)/k: zero when critical, positive when supercritical, negative when subcritical.

A pressurized water reactor has two main dials:

- **Control rods**: rods containing strong neutron absorbers such as boron or cadmium. Pull them out and reactivity rises; push them in and it falls.
- **Boron in the coolant**: dissolved boron whose concentration, the World Nuclear Association notes, is reduced progressively as other neutron absorbers build up in the fuel.

To raise power, operators withdraw rods a little, let the reactor run slightly supercritical, then settle back to k = 1 at the new level. Light-water reactors are also designed so that hotter fuel and coolant push reactivity down on their own, which helps hold the balance.

## 4. Why first criticality is a commissioning milestone

A new reactor usually goes through these steps:

1. **Fuel loading**: after the operating licence, fuel goes into the core. The reactor is still deeply subcritical.
2. **First criticality**: rods are withdrawn and boron diluted step by step until k reaches 1 for the first time.
3. **Low-power tests**: at very low power, engineers check that the core behaves as the design calculations predicted.
4. **Power ascension**: output is raised in stages, the generator is synchronised with the grid, and equipment and safety systems are tested.
5. **Commercial operation**: with all tests and inspections complete, the plant enters formal commercial service.

First criticality is the first proof that a core which existed only in calculations can sustain its own chain reaction. That is why utilities announce it.

Rooppur 1 shows the sequence in real time. It finished loading 163 fuel assemblies in May 2026, received regulatory approval for start-up three days before criticality, and went critical on October 11, according to World Nuclear News. Rosatom described the result as reaching the minimum controlled power level. Bangladesh's regulator, BAERA, then approved the power start-up stage on October 29, and power start-up began on October 30 (The Daily Star and Bangladesh Post, October 30). Grid supply still needs further tests and approvals, and local reports put it between late November and December (status as of October 31, 2026).

## 5. The view from Korea

Korea has walked through the same steps this year with Saeul 3, an [APR1400](/en/posts/apr1400-explained/) unit near Ulsan.

- **Licence and inspections**: the Nuclear Safety and Security Commission (NSSC, Korea's nuclear regulator) issued the operating licence on December 30, 2025. On April 10, 2026, it said all nine inspections required before first criticality, including fuel-loading checks and hot functional testing, were complete, according to Korean trade daily Energy Daily.
- **First criticality**: Korea Hydro & Nuclear Power (KHNP, the state utility that operates all of Korea's nuclear power reactors) reported first criticality on April 12, 2026, and said output would be raised step by step over about six months.
- **Power ascension**: the NSSC listed 31 follow-up inspections, including power ascension testing. The unit tripped automatically on August 11 at 33.9% power during testing; the NSSC attributed it to an operator entering a wrong setpoint and approved a restart on September 4, according to Korean media reports. Two days later, on September 6, KHNP shut the reactor down manually during power ascension after a leak was found in a pipe draining steam condensate on the turbine side, and the NSSC opened an investigation. As of October 31, 2026, Saeul 3 has not yet entered commercial operation.

Restarts after refueling go through the same gate. On April 28, 2026, the NSSC issued a release titled "Hanul 3, criticality permitted during periodic inspection." Our explainer on [Korea's licensing ladder](/en/posts/korea-nuclear-licensing-process/) shows where each of these approvals sits.

Having studied nuclear engineering, I read Korean headlines about "임계" (criticality) the same way I read them in English. The word only tells you a reactor has started. What follows, months of power ascension testing, tells you how good the plant is.

## 6. Supercritical vs critical: reactors, bombs and criticality accidents

The fear around "supercritical" comes from weapons. A bomb brings highly enriched material together very fast so that k on prompt neutrons alone is well above 1, and releases its energy in the tiny interval before the material blows itself apart. The World Nuclear Association notes that weapons material must be enriched to at least 90% uranium-235, while light-water reactor fuel is 3% to 5%.

A reactor's supercritical state, by contrast, is a sliver above 1 while power is being raised, paced by delayed neutrons. That does not make reactor accidents impossible. At Chernobyl in 1986, a quirk of the control rod design and a large positive void coefficient produced a dramatic power surge, and the World Nuclear Association describes the explosions that followed as a steam explosion and a likely hydrogen explosion.

A **criticality accident** is a different thing again. The NRC training glossary defines it as the release of energy from accidentally producing a self-sustaining or divergent chain reaction. It happens where criticality was never supposed to occur, not in a reactor designed for it.

Japan's 1999 accident at the JCO fuel conversion plant in Tokaimura is the textbook case. On September 30, workers poured uranium solution enriched to 18.8% into a precipitation tank whose shape made criticality more likely. With about 16 kg of uranium in the tank, the chain reaction ran intermittently for about 20 hours until cooling water around the tank, which acted as a neutron reflector, was drained and boric acid added. Two of the three workers died, and the event was rated level 4 on the International Nuclear Event Scale (World Nuclear Association).

## Where this goes next

Two milestones are worth watching. Rooppur 1, now in power start-up, still has to connect to Bangladesh's grid, which would deliver the country's first nuclear electricity. Saeul 3, stopped twice during testing, still has to finish power ascension testing ahead of commercial operation.

Both units will go critical again every time they restart, but first criticality happens only once. That is the day a reactor first comes alive. Everything after it is about how well the plant runs.

---
*Sources: US NRC Technical Training Center, "Nuclear Criticality Safety Trainee Guide: Abbreviations, Acronyms, and Glossary" (0905 Rev 3), and NRC online glossary entries "Criticality" and "Reactivity"; World Nuclear Association, "Physics of Nuclear Energy," "Uranium Enrichment," "Tokaimura Criticality Accident 1999" and "Chernobyl Accident 1986"; World Nuclear News, "Bangladesh's Rooppur 1 achieves criticality" (Oct. 12, 2026) and "Third unit at Korea's Saeul plant starts up" (Apr. 13, 2026); The Daily Star, "Rooppur gets clearance for power generation" (Oct. 30, 2026); Bangladesh Post on Rooppur 1 power start-up (Oct. 30, 2026); Prothom Alo and bdnews24 on Rooppur 1 criticality (Oct. 11, 2026); Korea NSSC press releases on the Saeul 3 operating licence (Dec. 30, 2025) and on Hanul 3 criticality during periodic inspection (Apr. 28, 2026); Energy Daily on Saeul 3 pre-criticality inspections (Apr. 10, 2026); Energy News on Saeul 3 first start (Apr. 12, 2026); Energy Daily and E2News on the Saeul 3 restart approval (Sept. 4, 2026); Asia Economy on the Saeul 3 manual shutdown (Sept. 6, 2026).*
