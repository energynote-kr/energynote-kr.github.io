---
title: "How much radiation did the Artemis II crew get in ten days? The math from the Artemis I mannequins"
date: 2026-09-03T12:30:00+09:00
dataAsOf: "2026-09-03"
categories: ["Radiation in Daily Life"]
tags: ["space radiation", "Artemis", "Van Allen belts", "Mars", "NASA"]
description: "Nine days beyond Earth's magnetic field in April 2026: Artemis I mannequin data puts the Artemis II crew's dose near 10–15 mSv, on a ladder from ground to Mars."
---

On April 6, 2026 (US Eastern time), the Orion spacecraft passed a point 406,771 km (about 252,750 miles) from Earth — farther from Earth than any crew in history, beating a record Apollo 13 had held since 1970, 56 years earlier. Aboard were commander Reid Wiseman, pilot Victor Glover, mission specialists Christina Koch and Jeremy Hansen of the Canadian Space Agency. From launch on April 1 to splashdown off San Diego on April 10, the flight lasted **9 days, 1 hour and 32 minutes** — the time the four spent outside the umbrella of Earth's magnetic field.

The crews that follow will be out there longer. In late February NASA reshuffled the plan: Artemis III in 2027 will first rehearse docking with the SpaceX Starship and Blue Origin Blue Moon landers in low Earth orbit, and the actual Moon landing moves to Artemis IV in 2028.

So the question is worth asking in numbers: how much radiation does ten days in deep space give you? What follows is the arithmetic, from someone who does radiation work for a living.

> **Key takeaways**
> - Scaled from the Artemis I mannequin measurements, the Artemis II crew's ten-day dose comes out at roughly 10–15 mSv, generously up to about 20 mSv — one to three chest CT scans, or 10–20% of the five-year occupational limit. NASA had not published the crew's measured dose as of September 2026.
> - Six months on the ISS is 80–160 mSv; the transit legs of a Mars round trip alone are about 660 mSv. Only Mars breaks NASA's 600 mSv career limit.
> - Shielding in space means light, hydrogen-rich material — water, polyethylene, cargo — plus spacecraft attitude, not lead; a solar storm is handled by building a shelter out of stowage bags.

## 1. Why space is different: one umbrella and a belt

On the ground we live under two shields, the atmosphere and Earth's magnetic field. At airliner altitude the atmospheric shield thins and the dose rate rises to tens of times the ground level — see [our explainer on cosmic radiation in flight](/posts/cosmic-radiation-flight/) (in Korean). Orion flies above that and then leaves the magnetic shield as well. What it meets out there comes in three kinds.

- **The Van Allen belts.** Bands of high-energy protons and electrons that Earth's magnetic field has trapped. A lunar mission crosses them once on the way out and once on the way back, and for a few hours each time the dose rate jumps sharply.
- **Galactic cosmic rays (GCR).** Very high-energy particles arriving from across the galaxy. The flux is low, but it never stops, and the particles are heavy and fast — the hardest kind to shield. GCR is the main source of dose for any long deep-space stay.
- **Solar particle events (SPE).** A solar eruption that throws out protons in a burst. On most days there is none, but a single large event can exceed months' worth of dose, which makes it the only space radiation that calls for the crew to take shelter.

## 2. Measurement 1: two mannequins went first

Before anyone flew, the Artemis I Orion of November 2022 carried two female-form mannequins, Helga and Zohar, in an experiment led by the German Aerospace Center (DLR). More than 5,600 detectors, spaced 3 cm apart through their bodies, recorded a 25.5-day lunar flight, and the results appeared in *Nature* in September 2024.

- Over 25.5 days the **total dose inside Orion was 26.7–35.4 mSv**, depending on position. Most of it was galactic cosmic rays; the Van Allen belt crossings contributed only 1.8–3.9 mSv (roughly a tenth to a fifth of the total).
- During deep-space cruise the dose rate was **0.96–1.24 mSv per day**. That is about 30% below what Curiosity measured on its Mars cruise (1.58 mSv/day) and what the Lunar Reconnaissance Orbiter (LRO) measured in lunar orbit (1.55 mSv/day), so Orion's thicker hull does take that much off the GCR. But note the ratio: 80% more shielding mass bought a 30% reduction. That is what "GCR is hard to shield" means in practice.
- During the belt crossings, the best-shielded location (69 μGy per minute) and the most exposed (240–287 μGy per minute) differed by a factor of **four**, and when the spacecraft rolled 90 degrees during an engine burn, putting its thick side toward the particles, the dose rate halved. The protective vest Zohar wore was evaluated separately in *Science Advances* in August 2026: modeling 1972- and 1989-class solar storms on the belt-transit measurements, the vest was estimated to cut dose by 40–60%. No actual solar storm occurred during Artemis I.

## 3. From measurement to arithmetic: the crew's ten days

The Artemis II crew's dose was recorded by six cabin sensors (HERA) and by active dosimeters worn on the body, but as of this writing in September 2026 no official NASA dose release or paper has appeared. So here is the arithmetic using the Artemis I values.

GCR at 1.0–1.2 mSv per day for nine days, plus 2–4 mSv for the two belt crossings, gives **roughly 10–15 mSv**, or about 20 mSv with a generous margin. That sits a little under NASA's pre-flight estimate — "comparable to a 1-month stay on the International Space Station, or about 5% of an astronaut's career limit", i.e. the 20–30 mSv range, with any solar event on top — but in the same order of magnitude. And there was no solar event during the mission that required shelter, according to NOAA.

The ladder, as of September 2026 (values are approximate and assume no solar particle event):

| Scenario | Dose | Basis |
|---|---|---|
| Ground, 1 year | 2.4 mSv world average; about 3 mSv in Korea | Natural background |
| Aircrew, 1 year | 2–5 mSv | Long-haul routes; Korea's legal limit for aircrew is 6 mSv/yr |
| Moon, 10 days | Roughly 10–15 mSv, up to about 20 | Artemis II, scaled from Artemis I measurements |
| ISS, 6 months | 80–160 mSv | Higher when the Sun is quiet |
| Mars, transit only | About 660 mSv | Curiosity cruise data applied to about a year of round-trip transit |

In everyday terms, ten days on a lunar round trip equals one to three chest CT scans, or the natural background a resident of Korea receives in three to seven years (four to eight years at the world average of 2.4 mSv). Against the occupational limit used in Korea and most countries — 100 mSv over five years — it is 10–20%: managed occupational exposure, at a size where any added cancer risk is too small to detect in individual studies. For a sense of how such everyday comparisons hold up, see [our post on the "banana equivalent dose"](/en/posts/banana-equivalent-dose/).

For a historical comparison, the Apollo crews of 1968–72 recorded skin absorbed doses of 0.16–1.14 rad (about 1.6–11.4 mGy) per mission. The highest, Apollo 14, flew a trajectory through the heart of the Van Allen belts.

![Log-scale bar chart placing a year on the ground, a year as aircrew, ten days on a lunar round trip, six months on the ISS and the transit legs of a Mars round trip on one dose ladder, with the five-year worker limit and NASA's career limit marked](/images/space-radiation-ladder-en.svg)

## 4. Up the ladder: six months on the ISS and a Mars round trip

Six months on the International Space Station brings about 80 mSv when the Sun is active and about 160 mSv when it is quiet. The solar wind pushes galactic cosmic rays out of the inner solar system, so an active Sun means less GCR. That is roughly 5–15 times the ten-day lunar trip, about 8 times at the midpoints.

Mars is a different order of magnitude. During its 253-day cruise to Mars in 2011–12, the Curiosity rover's detector inside its capsule measured **1.8 mSv per day** (the Nature team's like-for-like comparison in Section 2 quotes 1.58 for the same instrument); applied to the transit legs of a round trip, about a year in total, that is **about 0.66 Sv, or 660 mSv** (Zeitlin et al., *Science*, 2013). Time on the surface is extra.

NASA's 2022 revision of its crew health standard (NASA-STD-3001), which followed a 2021 report by the US National Academies, sets the astronaut career limit at **600 mSv** regardless of age or sex — the dose corresponding to no more than a 3-percentage-point increase in lifetime cancer mortality risk. A single Mars round trip exceeds it on transit alone. This arithmetic is why Mars is called a "radiation problem".

## 5. The science of shielding: light beats thick

Lead is not the answer. When a heavy GCR particle hits a heavy nucleus like lead, it sprays secondary particles, and the dose behind the shield can go up rather than down. Space shielding therefore favors **light, hydrogen-rich material**: water, polyethylene, food and cargo.

The solar-storm drill the Artemis II crew trained for works the same way. On an alert, within an hour they pull stowage bags out of the lockers and strap them to the cabin walls to build a makeshift shelter, and stay in it for up to 24 hours if needed. NASA's design target is to hold crew dose below 150 mSv even in a large solar event, and — as Artemis I's "roll 90 degrees, halve the dose rate" showed — turning the spacecraft so its thick side faces the particles is part of the toolkit.

## 6. Where this goes next

Two numbers to watch. The first is the Artemis II crew's actual dose from the HERA sensors and personal dosimeters, which NASA had not released as of September 2026 — it will show whether the 10–15 mSv arithmetic above holds. The second is duration: Artemis III in 2027 stays in low Earth orbit, but Artemis IV in 2028 adds a surface stay, and every mission after that gets longer.

Ten days was the easy case; the 600 mSv career limit is the hard constraint, and it is Mars, not the Moon, that runs into it.

**Industry note** — Orion is built by Lockheed Martin (NYSE: LMT), which also partnered with Israel's StemRad (privately held) on the AstroRad vest that Zohar wore on Artemis I. The landers named in NASA's revised plan come from SpaceX and Blue Origin, both privately held.

> This section is provided to help understand the industry and is not a recommendation to buy or sell any security. Investment decisions and their consequences are the reader's own.

> **Health note** — This article is general information from a radiation-protection perspective and does not replace medical advice.

---

*Sources: NASA Artemis II mission blog (April 2026); NASA Science, "To Protect Artemis II Astronauts, NASA Experts Keep Eyes on Sun" (March 2026); George et al., "Space radiation measurements during the Artemis I lunar mission", Nature (2024); DLR MARE experiment press release (2024); Houri et al., "First evaluation of wearable radiation protection…", Science Advances (August 2026); NOAA NESDIS, "Artemis II Returns" (April 2026); Zeitlin et al., "Measurements of Energetic Particle Radiation in Transit to Mars", Science (2013); NASA-STD-3001 and US National Academies, "Space Radiation and Astronaut Health" (2021); NASA SP-368, "Biomedical Results of Apollo"; Royal Observatory of Belgium SIDC space-radiation data; Lockheed Martin, AstroRad product page; UNSCEAR (world-average natural background).*
