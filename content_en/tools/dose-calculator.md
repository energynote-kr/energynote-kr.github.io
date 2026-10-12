---
title: "Annual Radiation Dose Calculator — CT scans, X-rays and flights in one number"
date: 2026-10-12T11:00:00+09:00
dataAsOf: "2026-10-12"
description: "Enter your CT scans, X-rays, flights and smoking for the past year and get your estimated annual radiation dose in millisieverts, compared with natural background and dose limits. A free tool built from official reference values by a writer trained in nuclear engineering and radiation science."
tags: ["radiation dose", "calculator", "CT", "mSv", "cosmic radiation"]
---

Two CT scans this year and a trip to the United States: how much radiation is that? Enter the number of exams and flights below and the estimate updates instantly. The result is shown next to the natural background dose everyone receives, the public dose limit and the occupational limit, so the number has something to stand against.

{{< dosecalc >}}

## Values used in the calculation

Every figure is a **typical effective dose** for one exam or one trip. Your actual dose can be half or double these values depending on the machine, the protocol and your body size (values as of October 2026).

| Item | Dose per exam | Source |
|---|---|---|
| Chest X-ray | ~0.1 mSv | Korea Disease Control and Prevention Agency (KDCA) |
| Dental panoramic | ~0.01 mSv | RadiologyInfo (ACR/RSNA) |
| Mammography | ~0.4 mSv | RadiologyInfo (ACR/RSNA) |
| Bone density (DXA) | ~0.001 mSv | ARPANSA |
| Head CT | ~2 mSv | RadiologyInfo (ACR/RSNA) |
| Low-dose lung CT | ~1–2 mSv | KDCA, national lung screening programme |
| Chest CT | ~7 mSv | KDCA |
| Abdomen/pelvis CT | ~8–10 mSv | KDCA |
| PET-CT | ~10–25 mSv | Korean Society of Nuclear Medicine screening guidance |

Flight doses depend on altitude and latitude. A Seoul–New York round trip is roughly 0.1–0.2 mSv and Seoul–Nagoya about 0.01 mSv, because the atmosphere thins at cruising altitude and polar routes receive more cosmic rays. Southeast Asian round trips use an intermediate value of about 0.03 mSv.

Smoking is included because tobacco leaves accumulate polonium-210. The value of about 0.36 mSv per year for a pack-a-day smoker comes from NCRP Report 160 (2009); estimates vary widely between studies. Brazil nuts, which concentrate radium from the soil, add about 0.16 mSv per year at two nuts a day according to Germany's Federal Office for Radiation Protection (BfS). The [banana equivalent dose article](/en/posts/banana-equivalent-dose/) covers both.

## How to read the result

- **Natural background, about 3 mSv** in Korea, is what you receive without ever visiting a hospital: granite bedrock, indoor radon, potassium-40 in food and cosmic rays. It is slightly above the world average of about 2.4 mSv.
- **The public dose limit of 1 mSv per year** applies only to man-made sources such as nuclear or industrial facilities. Medical exposure and natural background are excluded by design, so a CT scan does not put you "over the limit".
- **100 mSv** is the level at which the International Commission on Radiological Protection (ICRP) considers effects clearly observed for a single exposure. Below that, risk is not proven absent; it is too small to confirm in individual studies.

If the calculator returns a large number, CT scans are almost certainly the reason. One CT equals two to three years of natural background. That is not a reason for alarm, but it is a reason to tell your doctor about previous scans when repeat imaging is planned. That one habit is the most reliable way to avoid duplicate exams.

## What this calculator does not cover

- Nuclear medicine exams that inject radiopharmaceuticals (thyroid scans, bone scans) come in too many varieties; only PET-CT is included as a representative case.
- Radiotherapy doses are not converted to whole-body effective dose, so they are out of scope.
- Occupational exposure (medical staff, nuclear and industrial radiography workers, aircrew) is measured by personal dosimeters, which are far more accurate than any estimate here.
- Inputs are processed in your browser only. Nothing is sent to a server.

> **Health note** — This tool provides general information from a radiation-protection perspective and does not replace medical diagnosis or treatment. Decisions about exams and treatment should be made with your clinician.

---

*Sources: KDCA medical radiation safety guidance; RadiologyInfo 'Radiation Dose' (ACR/RSNA, 2024); ARPANSA 'Ionising radiation and health'; UNSCEAR 2008 Report (world average 2.4 mSv); ICRP Publication 103; NCRP Report 160 (2009); BfS data on natural radionuclides in food; Korean Act on Safety Management of Radiation Around Living Environments (aircrew 6 mSv/yr)*
