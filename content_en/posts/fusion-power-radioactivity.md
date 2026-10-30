---
title: "Is fusion energy radioactive? Tritium, neutrons and the waste question, with a view from KSTAR"
date: 2026-10-31T09:00:00+09:00
dataAsOf: "2026-10-30"
categories: ["Nuclear & Energy"]
tags: ["fusion energy", "fusion tritium", "fusion radioactive waste", "KSTAR", "ITER"]
description: "Is fusion energy radioactive? Yes, but not like fission: tritium fuel, activated steel, mostly short-lived waste. Plus regulators' choices and KSTAR's record."
---

On August 12, 2026, the Korea Institute of Fusion Energy (KFE) signed a contract with a domestic consortium to design and build storage vessels for ITER's fuel. The vessels will hold deuterium and tritium by binding the gas to depleted uranium as a solid, then releasing it again when heated. Korea is responsible for ITER's tritium Storage and Delivery System and aims to finish delivering it by 2030.

That is an odd job for a machine often sold as a clean "artificial sun." A clean energy source that needs a radioactive fuel store raises the obvious question. Is fusion power radioactive or not?

The short version is that fusion has a radiation problem, just not the one fission has. This piece walks through where the radioactivity comes from, how the waste compares with spent fuel, what the American and British regulators decided, and where Korea's own program stands as of October 30, 2026.

## 1. The fuel is already radioactive

ITER describes the deuterium-tritium (D-T) reaction as the most efficient for fusion devices. The two nuclei fuse into helium-4 and a free neutron. Of the 17.6 MeV released per reaction, the helium carries about a fifth (3.5 MeV) and the much lighter neutron about four-fifths (14.1 MeV).

The helium is stable. The neutron is itself penetrating radiation, and the fuel is radioactive too.

Tritium is radioactive hydrogen with a half-life of about 12.3 years. France's atomic energy commission (CEA) notes that it decays by emitting a low-energy electron that a sheet of paper stops and that cannot pass through skin. The concern is intake: tritiated water can be drunk or breathed in, and some of the tritium that enters the body becomes organically bound tritium (OBT), which stays longer than the water form.

The quantities are not trivial. The US Nuclear Regulatory Commission's February 2026 proposed rule says that tritium used and produced at near-term commercial fusion machines "could exceed 100 grams," which the agency puts at roughly 1 million curies. A gram of tritium holds about 3.6 × 10^14 becquerels, so 100 grams is about 3.6 × 10^16 Bq, a little over 1,600 times the 22 trillion becquerel annual cap on Japan's [Fukushima treated-water discharge](/en/posts/fukushima-discharge-3years/).

The comparison needs a caveat. One figure is an inventory to be kept inside a plant; the other is a release to the sea.

![Diagram of the deuterium-tritium reaction producing helium-4 at 3.5 MeV and a neutron at 14.1 MeV, the three places where radiation problems arise (tritium fuel, neutron activation, waste), and a strip summarizing differences from fission](/images/fusion-radioactivity-en.svg)

## 2. The neutron turns the machine radioactive

The bigger source of radioactivity is the neutron. It has no charge, so the magnetic field that holds the plasma cannot hold it.

It flies into the walls and is absorbed by nuclei in the steel, turning stable atoms into radioactive ones. This is activation.

The NRC's proposal says plainly that "neutron bombardment will activate components, with quantities of activation products increasing over time." A 2014 paper by Neill Taylor of the UK's Culham Centre and Pierre Cortes of the ITER Organization, drawing on ITER's licensing in France, gives concrete examples:

- **Nitrogen-16 in cooling water**: oxygen in water hit by neutrons above roughly 10 MeV becomes N-16. Its half-life is 7.1 seconds, but its gamma rays are intense enough that ITER bars access during plasma operation to every room holding part of the primary cooling circuit. The authors note that the energy threshold makes this far more important in D-T machines, whose neutrons start at 14.1 MeV, though N-16 is also a familiar operating dose source in light-water fission reactors.
- **Dust**: the plasma erodes the inner wall into dust that carries tritium. ITER's safety case assumed up to 1 kg of tritium and 1,000 kg of activated dust inside the vacuum vessel.
- **Tritium soaked into metal**: hydrogen isotopes diffuse into steel. When the paper was written, waste that is both activated and tritium-contaminated had no disposal route in France's repositories, so ITER planned an interim store to let the tritium decay through several half-lives first.

## 3. How it compares with fission

The basic differences, from the public sources cited here (as of October 2026):

| Item | Fission reactor | D-T fusion plant |
|---|---|---|
| Fuel | Uranium and other fissile material | Deuterium and tritium (only tritium is radioactive) |
| Neutrons | Sustain the chain reaction | Carry 80% of the energy at 14.1 MeV and activate structures |
| Waste | High-level spent fuel containing transuranics | Activated steel and tritiated parts; larger volume, mostly short-lived |
| After shutdown | Decay heat needs continued cooling | No chain reaction; ITER decay heat about 10 MW at shutdown, under 1 MW within a day |

The NRC's own summary of the hazard is that no fissile material is present, so criticality "is not possible," and that active post-shutdown cooling of structures containing radioactive material "is not necessary." It expects low offsite doses in credible accidents, giving less than 1 rem (10 mSv) as an example.

### Waste: more of it, shorter-lived

Spent fission fuel is compact but needs isolation for tens of thousands of years, which is why countries are still [searching for deep repositories](/en/posts/world-repositories/). Fusion reverses the trade. CEA estimates that a fusion reactor's waste would be about 20% very low-level, 75% short-lived low- and intermediate-level, and 5% long-lived intermediate-level, and that a century after shutdown the radiotoxicity of the structures falls close to that of natural radioactivity.

Note the 5%. "No long-lived waste" is not quite right either.

Taylor and Cortes add two caveats. Clearance and recycling criteria differ by country, and viable industrial processes to recycle activated steel still have to be developed. And a power plant's lifetime neutron exposure could reach about 50 MW·yr/m², roughly 170 times ITER's 0.3, so even with low-activation steels its waste class could end up similar to ITER's.

## 4. What regulators decided

The interesting split is between treating fusion as a nuclear reactor and treating it as a radioactive-materials facility.

- **United States**: On April 13, 2023, the NRC Commission chose the byproduct material approach under the existing 10 CFR Part 30 framework, rather than the fission-reactor (utilization facility) route. The ADVANCE Act of July 2024 then wrote a "fusion machine" definition into the Atomic Energy Act. The proposed rule was published on February 26, 2026, and comments closed on May 27. As of October 30, the NRC's rulemaking status page lists no final rule; the statutory deadline is December 31, 2027. Our [ALARA explainer](/en/posts/alara-principle-explained/) covers a separate NRC rulemaking on dose limits running in parallel.
- **United Kingdom**: Section 156 of the Energy Act 2023 states that a fusion energy facility does not need a nuclear site licence. It came into force on September 10, 2024. The government said nuclear site licensing, designed for higher-hazard fission sites, "would be disproportionate for fusion," leaving regulation with the Health and Safety Executive and environmental regulators.
- **France (ITER)**: ITER went the other way. It was assessed as a nuclear facility and received its construction decree from the French government in November 2012.

## 5. The view from Korea

Korea is closer to fusion hardware than most countries, which makes the radiation question less abstract here.

- **KSTAR's record**: KFE's official results page, checked October 30, 2026, lists 48 seconds at an ion temperature of 100 million °C and 102 seconds in high-confinement (H) mode, both from the December 2023 to February 2024 campaign. The stated goal is 300 seconds at 100 million °C, and KFE says the plasma-facing parts will be switched to tungsten in the second half of 2026.
- **ITER's timetable**: Under the July 2024 baseline, ITER plans the Start of Research Operation in 2034, deuterium-deuterium operation in 2035, full magnetic energy in 2036 and deuterium-tritium operation in 2039. ITER is an experiment and will not sell electricity.
- **Korea's own plant**: On December 19, 2025, the 22nd National Fusion Committee, as announced by the Ministry of Science and ICT, pulled the target for demonstrating fusion electricity from the 2050s into the 2030s. Conceptual design of a "Korean innovative fusion reactor," a compact demonstration plant, was set to start in 2026, alongside a planned KRW 1.5 trillion (about $1.1 billion) program for core technology and demonstration research infrastructure. Two of the roadmap's eight core technologies are the fuel cycle and safety and licensing.
- **The regulator**: Korea's Nuclear Safety and Security Commission (NSSC, the country's nuclear regulator) visited KFE in July 2026 to hear researchers' concerns and discuss improving its regulatory standards, according to Korean wire service News1. I could not find a published Korean decision comparable to the American or British ones.

Having studied radiation science, I find the Korean contrast instructive. Korea's fission waste problem is about [spent fuel with no repository site](/en/posts/korea-spent-fuel-dry-storage/). Fusion would swap that for a different burden: large volumes of activated steel and a tritium inventory that has to stay inside the building. Neither is zero. The honest selling point of fusion is narrower: no chain reaction to run away, decay heat that does not depend on active cooling, and waste that is mostly short-lived.

## Where this goes next

Three things are worth watching. Whether the NRC finalizes its Part 30 fusion rule before the end-of-2027 deadline, and how much tritium it lets a licensee hold. Whether Korea's NSSC decides to treat fusion as a nuclear facility, as France did with ITER, or as a radioactive-materials facility. And, much later, ITER's first D-T plasma in 2039, which will be the first time a machine of this size actually runs on radioactive fuel and starts making its own activated waste.

---
*Sources: Korea Institute of Fusion Energy press releases on ITER fuel storage vessels (Aug. 12, 2026), KSTAR long-pulse results (Mar. 20, 2024) and KSTAR–EU tungsten collaboration (Aug. 27, 2026), and KSTAR annual operating results page; Ministry of Science and ICT, 22nd National Fusion Committee (Korea.kr policy briefing, Dec. 19, 2025); News1 (July 10, 2026); ITER Organization, Baseline 2024 press conference summary (July 3, 2024) and Fusion Fuels page; CEA IRFM, "Implementing the intrinsic safety of the fusion reactor"; N. Taylor and P. Cortes, "Lessons learnt from ITER safety & licensing for DEMO and future nuclear fusion facilities," Fusion Engineering and Design 89 (2014); US NRC, "Regulatory Framework for Fusion Machines" proposed rule, 91 FR 9476 (Feb. 26, 2026), and Fusion Machine Rulemaking Status page; UK Energy Act 2023, section 156, and the Energy Security Bill factsheet on fusion regulation (gov.uk).*
