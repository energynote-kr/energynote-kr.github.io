---
title: "The banana equivalent dose is a meme, not a measurement — here's why it still works"
date: 2026-09-03T12:30:00+09:00
dataAsOf: "2026-09-03"
categories: ["Radiation in Daily Life"]
tags: ["banana equivalent dose", "potassium-40", "natural radioactivity", "radioactive food"]
description: "One banana is 0.1 μSv, so a CT scan is 70,000 bananas. Where the meme came from, why the physics is subtly wrong, and why the ruler still works."
---

Scroll through the comments under any radiation story and someone will post it: "One CT scan = 70,000 bananas." The line usually traces back to xkcd's radiation dose chart (2011) or the English Wikipedia entry on the "banana equivalent dose," BED for short. The ruler is one banana at 0.1 microsieverts, and X-rays, CT scans and nuclear accidents are lined up against it.

To someone who works with radiation for a living, the comparison is half right and half wrong. This post sorts out which half is which, in question-and-answer form.

> **Key takeaways**
> - One banana holds about 15 Bq of potassium-40, which the standard dose coefficients turn into roughly 0.1 μSv. The unit was proposed on the RadSafe mailing list in 1995 as a teaching aid, not a measurement.
> - Your body holds its potassium constant — an adult carries 4,000–5,000 Bq of potassium-40 — so a banana's potassium is excreted within hours to a day and the real added dose is close to zero.
> - The banana ruler is fine for comparing the size of doses in sieverts. It breaks when used to compare nuclides the body retains — cesium, radium, polonium — with one that it does not.

## 1. Who invented the banana equivalent dose?

In March 1995, Gary Mansfield of Lawrence Livermore National Laboratory posted the idea to RadSafe, a mailing list for radiation-safety professionals. His point was practical: very small doses and risks are hard to explain to the public, and a banana is something everyone has held.

The arithmetic is short. A banana weighs about 150 g and contains roughly 0.5 g of potassium. Natural potassium carries about 31 Bq of potassium-40 per gram, so **one banana is about 15 Bq** — 15 decays per second.

Multiply that by the ingestion dose coefficient for potassium-40 in ICRP Publication 72 and you get about 0.08–0.1 μSv. Rounded, **1 BED = 0.1 μSv**.

Two units for readers who do not use them daily. The becquerel (Bq) counts decays per second and says nothing about harm.

The sievert (Sv) is effective dose, which weights the energy absorbed by how much it matters to tissue; a microsievert is one-millionth of a sievert and a millisievert one-thousandth. None of Mansfield's arithmetic is wrong.

## 2. Then why call it "strictly wrong"?

The problem is not the calculation but the **premise underneath it**. A dose coefficient assumes that a radionuclide the body did not have before enters, stays for a while, and delivers its dose as it decays.

That holds for cesium or radium. It does not hold for potassium.

The body regulates its potassium concentration tightly, a process called homeostasis. When a banana's potassium arrives, the kidneys excrete the same amount within a few hours to a day. Potassium-40 is chemically identical to ordinary potassium, so it leaves with the rest.

The result is that the potassium-40 already inside you — about **55 Bq per kilogram of body weight, or 4,000–5,000 Bq in an adult** — stays the same whether you eat bananas or not. That standing inventory delivers roughly **0.17 mSv per year** of internal dose, and it is a dose you receive for as long as you are alive.

The **actual added dose from one banana is very close to zero**. We covered the body's own radioactivity in [our Korean explainer on the human body as a radiation source](/posts/body-radioactivity/) (in Korean).

| Question | Dose coefficient assumes | Potassium actually does |
|---|---|---|
| Does the nuclide stay? | Yes, for its biological half-life | No, excess is excreted in hours to a day |
| Does body inventory rise? | Yes, by the amount ingested | No, homeostasis holds it constant |
| Is the extra dose real? | Yes, ~0.1 μSv per banana | Close to zero |

## 3. So why does everyone keep using it?

**Because it is still an excellent ruler for orders of magnitude**. A figure like 0.1 μSv means nothing to most people; "one banana" is graspable. Put common exposures on that ruler and the spread becomes visible at a glance:

| Exposure | Approximate dose | Bananas (calculated) |
|---|---|---|
| One banana | 0.1 μSv | 1 |
| Chest X-ray | 0.1 mSv | 1,000 |
| World background, 2008 est. | 2.4 mSv | 24,000 |
| World background, 2026 est. | ~3.0 mSv | 30,000 |
| Korea background, 1 yr | ~3 mSv | 30,000 |
| Chest CT | 7 mSv | 70,000 |

One, a thousand, thirty thousand, seventy thousand. The X-ray, CT and background values are typical round figures rather than measurements of any particular patient or place.

The 2.4 mSv world average is the long-cited UNSCEAR 2008 figure. In February 2026 UNSCEAR published a new evaluation of public exposure (UNSCEAR 2024 Report, Annex B) that puts the worldwide average from natural sources at about 3.0 mSv, of which radon inhalation is 1.8 mSv; the committee attributes the rise to better data coverage and refined methods, not to any actual increase in radiation levels (as of September 2026).

For US readers, NCRP Report 160 (2009, data for 2006) puts "ubiquitous background" at about 3.1 mSv per year, so the Korean figure is not unusual.

![Comparison ladder: one banana at 0.1 μSv, a chest X-ray at 0.1 mSv (1,000 bananas), annual natural background of about 3 mSv (30,000 bananas) and a chest CT at 7 mSv (70,000 bananas), drawn as rows of banana icons, with a note that the body keeps its total potassium constant](/images/banana-dose-scale-en.svg)

One caveat belongs next to every banana chart. The scale is not "the dose you receive from eating a banana."

It is **15 Bq of potassium-40 converted into a calculated dose** so that other exposures can be measured against it. The tick marks on the ruler are valid; the name written on the ruler does not describe a real event.

## 4. What foods really are radioactive, then?

The ones carrying nuclides that the body does not regulate away. Two are worth knowing.

- **Brazil nuts**: the tree's wide root system draws radium out of the soil. Germany's Federal Office for Radiation Protection (BfS) puts the nuts at about **41 Bq/kg of radium-226 and 46 Bq/kg of radium-228** — roughly a thousand times the radium in a kilogram of an ordinary diet, by BfS's German comparison. Radium behaves chemically like calcium, so a fraction lodges in bone. Two nuts (about 8 g) every day works out to **roughly 0.16 mSv per year** for an adult, about the same size as the dose from your own potassium-40.
- **Tobacco**: **polonium-210 and lead-210** accumulate on the leaves and, when smoked, deposit at the branch points of the bronchial airways. The US National Council on Radiation Protection and Measurements, in NCRP Report 160 (2009), estimates the effective dose to a pack-a-day smoker at **about 0.36 mSv per year** (0.2–0.4 mSv depending on the study); the local dose at the deposition sites is far higher.

Polonium-210 is almost a pure alpha emitter, which makes it hard to detect from outside the body; the lead-210 alongside it emits a weak gamma ray and is what instruments usually catch. The hazard comes from the pathway into the body — inhaled or swallowed, the alpha particles do their damage inside. We explain alpha radiation in [our Korean post on alpha risk](/posts/alpha-radiation-risk/) (in Korean).

Unlike bananas, both of these add real dose in proportion to how much you consume.

Two qualifications. On radiation alone, these are low-dose exposures whose risk is too small to detect in individual studies. And tobacco's cancer risk is driven by the thousands of chemicals in smoke, not by its polonium; the radiation is a footnote to a much larger problem.

## 5. Where is the trap in the meme?

The banana ruler can compare the **size of a dose in sieverts**. It cannot compare **nuclides and pathways**. When a news item reports "cesium at 10 Bq/kg detected in seafood" and a reply says "bananas are 100 Bq/kg, so what," the reply is putting potassium that the body excretes on the same scale as cesium that the body retains in muscle.

A becquerel is just a count of decays. What that decay does to a body is decided by the nuclide, the route it takes in and how long it stays.

This is the point where the meme is most often deployed and least often examined. Seafood monitoring numbers are a case in point: what matters in a cesium reading is the nuclide and where it goes in the body, and no banana count answers that.

Our post on [three years of the Fukushima discharge](/en/posts/fukushima-discharge-3years/) looks at what the monitoring data actually shows. In [our Korean post on what "not detected" means](/posts/nd-meaning-mda/) (in Korean), we set the body's potassium-40 next to detection limits to convey how low modern instruments can measure, not to argue that cesium at 55 Bq/kg would be fine.

The banana equivalent dose is a meme that was born in science. Used as a meme, it is useful. Used as science, it makes you forget its premise.

## Where this goes next

The same confusion between "how many decays" and "how much harm" runs through most public arguments about radiation, from radon in hot springs to the doses astronauts will receive on the Moon. Two companion posts continue the thread: [radon hot springs and the hormesis claim](/en/posts/radon-hot-spring-hormesis/) and [what Artemis crews face in space radiation](/en/posts/artemis-space-radiation/). If you want the units themselves, [our Korean primer on Bq, Gy and Sv](/posts/radiation-units-explained/) (in Korean) is the place to start.

> **Health note** — This article is general information from a radiation-protection perspective and does not replace medical advice.

---

*Sources: RadSafe mailing list archive, G. Mansfield post (March 7, 1995); ICRP Publication 72 (ingestion dose coefficient for potassium-40); UNSCEAR 2000 Report (annual effective dose from potassium-40, 0.165 mSv) and UNSCEAR 2008 Report (worldwide average natural background 2.4 mSv); UNSCEAR 2024 Report, Annex B, "Evaluation of public exposure to ionizing radiation" (published February 2026; UN Information Service release UNIS/OUS/453, 12 February 2026, worldwide average about 3.0 mSv); German Federal Office for Radiation Protection (BfS), natural radionuclides in Brazil nuts; Health Physics Society, Ask the Experts; NCRP Report 160 (2009), Ionizing Radiation Exposure of the Population of the United States (smoking dose, US background); ORAU Museum of Radiation and Radioactivity, Brazil nuts entry; Wikipedia, "Banana equivalent dose"; xkcd Radiation Dose Chart (2011)*
