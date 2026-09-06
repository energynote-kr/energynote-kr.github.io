---
title: "Why is a nuclear reactor blue? Cherenkov radiation, explained"
date: 2026-09-12T18:00:00+09:00
dataAsOf: "2026-09-06"
categories: ["Radiation in Daily Life"]
tags: ["Cherenkov radiation", "spent fuel pool", "research reactor", "IAEA safeguards", "neutrinos"]
description: "Spent fuel pools glow blue because electrons outrun light in water. What Cherenkov radiation is, why workers can stand above the pool, and who uses the glow."
---

A deep pool lit from below, as if someone had switched on a blue fluorescent lamp under the water: it is the stock photograph of the nuclear industry. Reactors in films glow the same blue, and in *Watchmen* Doctor Manhattan's whole body is that color (we graded him in [our superhero radiation scorecard](/en/posts/superhero-radiation-scorecard/)).

Two items from this summer are the same story. The IAEA published a "What is Cherenkov radiation?" explainer on July 28, 2026, the anniversary of Pavel Cherenkov's birth, and IceCube, the neutrino telescope buried in Antarctic ice, finished an expansion in February and reported in *Physical Review Letters* in March that the cosmic-neutrino spectrum is not a simple straight line (a single power law). Both run on this blue light, so here it is in question-and-answer form.

> **Key takeaways**
> - Cherenkov light is a "sonic boom" of light: an electron moving faster than light does in water (about 75% of its vacuum speed) leaves a cone-shaped wavefront, and short wavelengths dominate, so it looks blue.
> - The light itself is ordinary visible light, and looking at it does not expose you to radiation. The hazard is what makes the light, the gamma rays and electrons, and 6 m or more of water above the fuel is what lets people work at the pool's edge.
> - IAEA inspectors use the glow to verify spent fuel without touching it, IceCube and Super-Kamiokande use it to catch neutrinos, and radiotherapy clinics have started using it to check where the beam lands.

## Q1. Is anything really faster than light?

Not in a vacuum. But light slows down in water: with a refractive index of 1.33, light in water travels at **about 75% of its vacuum speed**. An electron thrown out of a radioactive material (beta radiation) can beat that if it carries enough energy, and in water the threshold is **around 0.26 MeV** of electron energy.

When the electron outruns the light, the light given off by the water molecules it disturbs cannot get ahead of it. The emissions pile up behind it into a **cone-shaped wavefront**, the same geometry as the shock wave of an aircraft flying faster than sound, and in water the cone angle is at most about 41 degrees.

Pavel Cherenkov found the effect experimentally in 1934, Ilya Frank and Igor Tamm worked out the theory in 1937, and the three shared the 1958 Nobel Prize in Physics.

## Q2. Why blue, of all colors?

The intensity of Cherenkov light rises as the wavelength shortens (it goes as the inverse square of the wavelength). The strongest part is in the ultraviolet, which the eye cannot see; what reaches us is the tail of blue and violet, so the glow looks **blue**.

It is not the color of any particular material. Water, glass and ice all give the same blue.

## Q3. Where can you see it?

- **Spent fuel pools**: the water-filled basins where fuel taken out of a reactor cools down. Gamma rays leaving the fuel rods knock electrons loose from water molecules (Compton scattering), and those electrons make the light. Most "glowing reactor" photographs are of a pool.
- **Research reactors**: HANARO, the 30 MW (thermal) research reactor that the Korea Atomic Energy Research Institute (KAERI) has run in Daejeon since 1995, is an open-pool design. The core sits about 12 m down in a tank holding 318 t of water, so the blue glow of the core is visible from the surface while it operates.
- **Power reactors**: the core is sealed inside a steel pressure vessel, so there is nothing to see in normal operation. The glow appears during refueling, when the vessel head is removed and the cavity above it is flooded.

![Two-panel diagram: on the left, an electron outrunning light in water leaves a cone-shaped Cherenkov wavefront; on the right, a spent fuel pool in cross-section, with 6 m or more of water above the fuel shielding a worker standing at the surface](/images/cherenkov-blue-glow-en.svg)

## Q4. Is the light dangerous?

Separate **the light you see from what causes it**.

- **The light itself**: ordinary visible light, the same kind a fluorescent tube makes. Looking at it does not expose you to radiation.
- **The cause**: the gamma rays and electrons that produce the light are intense radiation. The space right next to freshly discharged spent fuel, with no shielding, is not somewhere a person can go. But that radiation starts in the water and stops in the water.

That is why a person can stand on the platform above the pool. Electrons (beta radiation) stop within about a centimeter of water, and gamma rays weaken by roughly an order of magnitude for every meter of water they cross. The US Nuclear Regulatory Commission (NRC), the American regulator, requires spent fuel to sit under **at least 20 feet (about 6 m) of water** and explains that this water is the shield for anyone near the pool; the pools themselves are typically 12 m or more deep.

Hold a radiation meter over a glowing pool and it picks up almost nothing from the fuel below. This is also why fuel goes straight into water the moment it leaves the reactor: the water carries away the decay heat and blocks the radiation at the same time.

## Q5. What is the glow used for?

**Safeguards inspections**. Inspectors from the IAEA, the UN nuclear watchdog, visit spent fuel pools to confirm that the fuel a country has declared is actually there and has not been diverted. Standing at the pool's edge, they look down through a Cherenkov viewing device (the DCVD, and its successor the XCVD): real spent fuel glows, dummies and fresh fuel do not, and the brightness has to match the fuel's declared burnup and cooling time.

Nothing is lifted out of the pool; the question "is everything still here as declared?" is answered from above. The IAEA said the XCVD was used in 2023 for its largest spent fuel verification ever, at eight times the previous efficiency.

**Neutrino telescopes**. IceCube has 5,160 light sensors frozen into a cubic kilometer of Antarctic ice, watching for the Cherenkov light of charged particles created when a neutrino collides with the ice (in February 2026, per IceCube's announcement, five more cables carrying more than 600 sensors were added). Japan's Super-Kamiokande does the same in a 50,000 t tank of ultrapure water: about 11,000 light sensors on the inner walls record the cone, and running the geometry backwards gives the direction the neutrino came from.

**Medicine**. During radiotherapy, the patient's skin gives off a faint Cherenkov glow where the beam passes. Cameras that capture it, so that staff can see in real time whether the beam is landing where the plan says, have started to be used clinically; a 2025 review counted two approved systems. There are published cases where this imaging revealed dose reaching areas outside the plan.

## Q6. Are the "flashes" astronauts see Cherenkov light too?

Apollo crews reported flashes of light every few minutes, even with their eyes closed, and the same thing is logged on the International Space Station. The cause is the cosmic radiation covered in [our Artemis space-radiation post](/en/posts/artemis-space-radiation/); **what the flash actually is** has not been settled.

- **Cherenkov hypothesis**: a fast particle crossing the vitreous body of the eye generates light inside the eyeball. A 2019 study that used a camera to record Cherenkov light coming from the eyes of radiotherapy patients supports this idea.
- **Direct-stimulation hypothesis**: ground experiments in the 1970s produced flashes with particles below the Cherenkov threshold, and observations on the ISS and Mir concluded that heavy nuclei striking the retina or optic nerve directly is the more likely mechanism.

"Cherenkov may contribute, but it does not seem to be the only cause" is the most honest summary for now.

## Where this goes next

The pool in the photograph is a waypoint, not a destination. Fuel cools there for years, then moves to dry casks and, eventually, to a deep repository; how that plays out at a reactor being dismantled is in [our Kori-1 decommissioning tracker](/en/posts/kori1-decommissioning/), and where the world stands on final disposal is in [our survey of deep repositories](/en/posts/world-repositories/). The blue glow itself will keep turning up in the news: IceCube's expanded array and the IAEA's next rounds of spent fuel verification both depend on it.

> **Health note** — This article is general information from a radiation-protection perspective and does not replace medical advice.

---

*Sources: IAEA, "What is Cherenkov Radiation?" (July 28, 2026); IAEA Bulletin, "What the Nuclear Declaration at COP28 Means for IAEA Verification" (XCVD verification, 2023); US NRC, "Spent Fuel Pools"; KAERI, HANARO research reactor safety information; IceCube press release (February 12, 2026); IceCube Collaboration, Phys. Rev. Lett. 136, 121002 (published March 26, 2026) and Phys.org (May 29, 2026); Practical Radiation Oncology, "A Review of Cherenkov Imaging for Real-Time Verification in Radiation Therapy" (2025); Physics World, "Cherenkov imaging for visualizing radiotherapy: one year of clinical use"; Int. J. Radiat. Oncol. Biol. Phys., "Experimentally Observed Cherenkov Light Generation in the Eye During Radiation Therapy" (2019); Wikipedia, "Cherenkov radiation" and "Cosmic ray visual phenomena" and "Spent fuel pool"*
