# Awesome Cycling Power Training [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of evidence-based resources on power-based training for cyclists — covering FTP, the 7-zone Coggan model, critical power theory, power meter selection, structured training design, W' (anaerobic work capacity), VLamax, and practical protocols for every rider category from recreational to elite.

Power meters have democratised physiological training precision that was once available only in sports science laboratories. This list covers the science, tools, and structured training resources to use that data effectively.

---

## Contents

- [Why Power Over Heart Rate](#why-power-over-heart-rate)
- [FTP — What It Is and Isn't](#ftp--what-it-is-and-isnt)
- [The 7-Zone Power Model (Coggan)](#the-7-zone-power-model-coggan)
- [Critical Power Theory — A More Complete Model](#critical-power-theory--a-more-complete-model)
- [W' — Anaerobic Work Capacity](#w--anaerobic-work-capacity)
- [VLamax — The Glycolytic Rate Variable](#vlamax--the-glycolytic-rate-variable)
- [FTP Testing Protocols](#ftp-testing-protocols)
- [Power Meters — Selection Guide](#power-meters--selection-guide)
- [Power-Based Training Concepts](#power-based-training-concepts)
- [Structured Workout Library by Zone](#structured-workout-library-by-zone)
- [Training Peaks and PMC Metrics](#training-peaks-and-pmc-metrics)
- [Nutrition for Power-Based Training](#nutrition-for-power-based-training)
- [Calculators & Tools](#calculators--tools)
- [Landmark Research Papers](#landmark-research-papers)
- [Books & Courses](#books--courses)
- [Software & Analysis Tools](#software--analysis-tools)
- [Communities](#communities)

---

## Why Power Over Heart Rate

Heart rate is a *response* to exercise; power is the *stimulus*. This distinction has fundamental training implications.

### Heart Rate Limitations

- **Cardiac drift:** HR rises over a long ride even at constant power — due to dehydration, heat, fatigue. The same power output corresponds to different HR at minute 30 vs. minute 180.
- **Day-to-day variation:** Stress, sleep quality, caffeine, ambient temperature, and illness all affect resting and exercise HR by 5–15 bpm.
- **Lag time:** HR takes 2–3 minutes to fully respond to a change in effort. Interval training with HR targets is imprecise during the critical early seconds of each interval.
- **Altitude:** HR at the same absolute power is higher at altitude, masking actual training intensity.

### Power Advantages

- Instantaneous: Power meters respond in milliseconds.
- Objective: 250W is 250W regardless of temperature, fatigue, or altitude.
- Quantifiable training stress: TSS (Training Stress Score) calculated from power allows precise training load quantification.
- Pacing tool: Power allows accurate race and interval pacing without the delayed HR response.

---

## FTP — What It Is and Isn't

### Definition

Functional Threshold Power (FTP) is the highest average power output an athlete can sustain for approximately 60 minutes in a maximal effort. It is the cycling equivalent of lactate threshold 2 (LT2) — the highest sustainable steady-state intensity.

**Formula (Coggan):** FTP ≈ Best 60-minute average power.

In practice, 60-minute all-out efforts are exhausting and rarely performed. Most protocols estimate FTP from shorter efforts (see Testing Protocols).

### Typical FTP Values (W/kg)

| Level | FTP (W/kg) |
|-------|-----------|
| Untrained | <2.0 |
| Recreational | 2.0–3.0 |
| Fit amateur | 3.0–3.5 |
| Competitive amateur | 3.5–4.0 |
| Cat 3–4 racer | 4.0–4.5 |
| Cat 1–2 / elite amateur | 4.5–5.0 |
| Professional | 5.0–6.5+ |
| Grand Tour contender | 6.0–7.0+ |

### What FTP Is NOT

- **Not VO2max:** VO2max occurs at 110–120% FTP in most riders. FTP measures threshold; VO2max is the aerobic ceiling.
- **Not a fixed number:** FTP changes with training, fatigue, heat, altitude, and testing conditions.
- **Not perfectly equivalent to LT2:** FTP is a functional power metric; LT2 requires blood lactate measurement. They correlate but are not identical.

---

## The 7-Zone Power Model (Coggan)

The Coggan 7-zone model (TrainingPeaks standard) defines training zones as percentages of FTP:

| Zone | Name | % FTP | Physiological Target | Duration |
|------|------|-------|---------------------|---------|
| Z1 | Active Recovery | <55% | Recovery; minimal metabolic stress | Unlimited |
| Z2 | Endurance | 56–75% | Aerobic base; fat oxidation; mitochondrial development | 2–8+ hr |
| Z3 | Tempo | 76–90% | Aerobic capacity; elevated lactate, sustainable | 20 min – 2 hr |
| Z4 | Lactate Threshold | 91–105% | LT2 development; maximum sustained intensity | 10–60 min |
| Z5 | VO2 Max | 106–120% | VO2max stimulus; cardiac output maximum | 3–8 min |
| Z6 | Anaerobic Capacity | 121–150% | W' depletion; maximal glycolytic rate | 30 sec – 3 min |
| Z7 | Neuromuscular Power | >150% | Peak power; neuromuscular recruitment | <30 sec |

### Zone Application by Event

| Event Type | Primary Zones | Secondary Zones |
|-----------|---------------|----------------|
| Criterium/road race | Z5–Z6 (attacks, sprints) | Z4 (breakaway) |
| Time trial (40km) | Z4 | Z3 |
| Gran fondo (5+ hr) | Z2–Z3 | Z4 (climbs) |
| Ironman bike | Z2 | Z3 |
| Cyclocross | Z4–Z5 | Z3 |
| Track pursuit | Z5–Z6 | Z4 |

---

## Critical Power Theory — A More Complete Model

### The CP/W' Framework

Critical Power (CP) is the theoretical maximum power output that can be sustained indefinitely without fatigue. Below CP, effort is sustainable; above CP, a finite anaerobic "battery" (W') is being depleted.

**The two-parameter CP model:**
- **CP:** The asymptote of the power-duration curve. Equivalent to approximately LT2 / FTP (within ~5%).
- **W'** (W-prime): The total anaerobic work capacity above CP, measured in kilojoules. Depleted when riding above CP; recharged when riding below CP.

### Why CP is More Physiologically Complete Than FTP

FTP estimates sustainable threshold as a single number. CP/W' models the *interaction* between aerobic and anaerobic systems across all intensities — allowing prediction of:

- How long you can sustain any power above FTP
- When W' will be depleted in a race attack scenario
- How much recovery is needed to recharge W' after a hard effort

**Example:** If your W' = 20 kJ and you attack at 100W above CP for 5 minutes (consuming 30 kJ), you've exceeded your W' and will be forced to slow below CP for recovery.

- [Monod & Scherrer (1965) — The Work Capacity of a Synergistic Muscular Group](https://pubmed.ncbi.nlm.nih.gov/5850598/) — Original critical power paper.
- [Poole et al. (2016) — Critical Power: An Important Fatigue Threshold in Exercise Physiology](https://pubmed.ncbi.nlm.nih.gov/26767921/)

---

## W' — Anaerobic Work Capacity

### What W' Represents

W' is the finite quantity of work (in joules or kilojoules) that can be performed above Critical Power before exhaustion. It corresponds loosely to muscle glycogen availability for high-intensity efforts and PCr (phosphocreatine) stores, buffering capacity, and the athlete's tolerance for working above LT2.

### Typical W' Values

| Level | W' Range |
|-------|---------|
| Recreational | 10–15 kJ |
| Competitive | 15–25 kJ |
| Elite | 25–40 kJ |
| Track specialist | 35–50 kJ |

W' is more variable than CP and responds to specific anaerobic interval training. Riders with high W' can sustain more repeated attacks; those with high CP but low W' are excellent TT riders but struggle in punchy criteriums.

---

## VLamax — The Glycolytic Rate Variable

### What VLamax Measures

VLamax (maximal glycolytic rate) is the maximum rate at which the glycolytic system produces lactate — measured in mmol/L/second. It is the "ceiling" of anaerobic power production.

**The performance paradox:**
- **High VLamax** = more anaerobic power, stronger sprinting, better W'
- **High VLamax** = higher lactate production at any given aerobic intensity → raises perceived effort and elevates HR at the same power → *reduces endurance efficiency*

An ideal endurance profile (Ironman, time trial) requires **high VO2max + low VLamax** — maximising aerobic power while minimising "glycolytic noise" that consumes carbohydrate.

**Training VLamax:**
- Sprint and high-intensity interval training increases VLamax
- Zone 2 volume over extended periods reduces VLamax
- For endurance-focused riders: limit sprint work; prioritise Z2 volume and threshold

VLamax is measurable via INSCYD testing (power-based, no blood draws) or via direct lactate testing.

---

## FTP Testing Protocols

### 20-Minute Test (Most Common)

The Coggan 20-minute FTP test estimates FTP by multiplying 20-minute best average power by 0.95 (empirical correction).

**Protocol:**
1. Warm up 20 minutes, including 2 × 1 min hard efforts (95%+)
2. Ride easy for 5 minutes
3. 5-minute maximal effort (prime the aerobic system; also burns off top-end fatigue)
4. Recover 5 minutes easy
5. **20-minute all-out time trial** (start controlled; build in final 5 minutes if possible)
6. Record average power for the 20 minutes × 0.95 = estimated FTP

**Limitations:** Athletes who are naturally strong short sprinters may overestimate FTP. Athletes who are very long-event specialists may underestimate.

### Ramp Test (TrainerRoad / Zwift Default)

- Power increases by ~20W every minute until failure.
- FTP estimated as 75% of best 1-minute power.
- Advantages: Short (~15 min), low psychological stress.
- Limitations: Favours athletes with higher anaerobic capacity; may overestimate FTP for time trial specialists.

### 60-Minute Test (Gold Standard, Rarely Used)

Full 60-minute maximal effort. Average power = FTP directly.
- Most accurate but exhausting and psychologically demanding.
- Used in research settings.

---

## Power Meters — Selection Guide

### Technology Types

**Crank-based (most accurate):**
- Measures power at the pedal/crank spider. Captures power from both legs (left + right combined).
- Examples: Quarq, Power2Max, Stages (crank arm), SRM.

**Pedal-based (most convenient):**
- Portable between bikes. Easy installation.
- Examples: Garmin Vector, Favero Assioma, Look Keo Power.
- Accuracy: ±1–2% for best pedal meters. Slightly lower than crank-based under dynamic load.

**Left-only crank arm (budget option):**
- Measures left leg power and doubles it.
- Assumes 50/50 power distribution. Inaccurate for riders with significant left-right imbalance.
- Examples: Stages left-only, 4iiii left-only.

**Hub-based:**
- Extremely accurate and durable but least portable.
- Examples: PowerTap.

### Accuracy Standard

Research-grade power meters: ±1% accuracy.
Consumer grade: ±1–2% claimed; real-world ±2–3% in dynamic conditions.
For training purposes, **consistency within a device matters more than absolute accuracy**. Test at known conditions and calibrate before every ride.

### Price Ranges (USD, approximate 2026)

- Budget ($300–500): Left-only crank arms (Stages, 4iiii), some pedal meters
- Mid-range ($500–900): Pedal meters (Favero Assioma), dual-sided crank arms
- Premium ($900–1,500): Quarq, Power2Max, Garmin Vector 3
- Professional ($1,500+): SRM, customised team setups

---

## Power-Based Training Concepts

### Normalised Power (NP)

NP accounts for the physiological cost of variable-intensity riding (the metabolic cost of surging from 150W to 400W and back is not the same as sustaining 275W steadily). NP applies a 30-second rolling average and mathematical weighting that better reflects metabolic stress.

**NP > Average Power** whenever riding is variable. In criteriums and mountain stages, NP may be 20–30% higher than average power.

### Intensity Factor (IF)

IF = NP / FTP.
- IF = 1.0 means the ride was at exactly FTP equivalent effort
- IF >1.0 is only possible for very short rides (<45 min)
- Ironman bike: target IF ~0.65–0.75
- Criterium: IF 0.85–0.95+

### Training Stress Score (TSS)

TSS = (Duration in seconds × NP × IF) / (FTP × 3,600) × 100

- 100 TSS = equivalent of a 1-hour all-out effort at FTP
- 50 TSS = moderate workout
- 150+ TSS = very hard training day; expect significant fatigue
- 500+ TSS/week = sustained high training load (competitive amateur level)

---

## Structured Workout Library by Zone

### Zone 2 (Endurance Base)

**2-Hour Endurance Ride:**
- 10 min warm-up (Z1)
- 100 min sustained Z2 (56–75% FTP)
- 10 min cool-down
- Purpose: Mitochondrial biogenesis, fat oxidation

### Zone 4 (Lactate Threshold)

**Sweetspot Intervals (Z3–4 crossover):**
- 15 min warm-up
- 3 × 15 min at 88–93% FTP, 5 min Z1 recovery between
- 10 min cool-down
- Purpose: Sustained threshold development with manageable recovery

**Classic Tempo:**
- 20 min warm-up
- 2 × 20 min at 91–95% FTP, 10 min recovery
- 10 min cool-down

### Zone 5 (VO2 Max)

**Norwegian 4×4 (adapted for cycling):**
- 20 min warm-up
- 4 × 4 min at 110–120% FTP
- 3 min Z1 recovery between
- 10 min cool-down

**30/30 Intervals (Billat):**
- 15 min warm-up
- 20 min of: 30 sec at 130–150% FTP / 30 sec Z1
- 10 min cool-down

### Zone 6 (Anaerobic)

**Over-Under Intervals:**
- 15 min warm-up
- 4 × 8 min: alternate 1 min at 115% FTP / 1 min at 95% FTP
- 10 min cool-down
- Purpose: VLamax stress and tolerance at near-threshold loads

---

## Training Peaks and PMC Metrics

The Performance Management Chart (PMC) uses three interconnected metrics derived from daily TSS:

| Metric | Full Name | What It Measures | Decay |
|--------|----------|-----------------|-------|
| CTL | Chronic Training Load | Long-term fitness | 42-day exponential |
| ATL | Acute Training Load | Short-term fatigue | 7-day exponential |
| TSB | Training Stress Balance | Form (fitness − fatigue) | CTL − ATL |

### TSB Interpretation

- **TSB negative (−10 to −30):** Training/fatigue. Normal during build phase.
- **TSB near zero (−5 to +5):** Maintenance or early taper.
- **TSB positive (+5 to +25):** Fresh/peaked. Ideal for A race performance.
- **TSB very positive (+25+):** May indicate too much taper or detraining.

For most athletes, the optimal race-day TSB is **+5 to +20**.

---

## Nutrition for Power-Based Training

### Fuelling by Training Zone

| Zone | Duration | CHO Need | Fat Oxidation | Approach |
|------|---------|---------|--------------|---------|
| Z1–2 (<90 min) | Short | Low | Dominant | Can train fasted |
| Z2 (>90 min) | Long | Moderate | High | Gels from 60 min |
| Z3–4 | All | High | Moderate | Fuel before + during |
| Z5–6 | All | Very high | Low | Always fuelled |

### FTP Testing Nutrition

Never test FTP fasted. A meaningful FTP test requires maximal carbohydrate availability:
- Carbohydrate-rich meal 2–3 hours before
- 1 gel 15–20 minutes before the test effort
- Electrolyte drink during test

An FTP test performed fasted will likely underestimate FTP by 3–8%.

---

## Calculators & Tools

- [Cycling Power Zones Calculator — NorthLine](https://winsport.us/tools/performance/cycling-power-zones) — Enter your FTP to instantly generate all 7 Coggan power zones (in watts), with workout prescriptions and physiological targets for each zone.
- [Golden Cheetah](https://www.goldencheetah.org/) — Free, open-source. The most powerful non-commercial cycling analytics platform. CP, W', FTP testing, PMC, power curve, all implemented.
- [Intervals.icu](https://intervals.icu/) — Free browser-based training analytics. FTP detection, PMC chart (CTL/ATL/TSB), power zone analysis. Syncs with Garmin, Strava.
- [TrainingPeaks](https://www.trainingpeaks.com/) — The industry standard for structured training planning and PMC tracking. Premium tier required for full power analytics.
- [WKO5](https://www.trainingpeaks.com/wko/) — Advanced cycling analytics. Individualised power profiling, CP/W' modelling, FTP detection from ride history.
- [Zwift](https://www.zwift.com/) — Indoor structured training with FTP testing protocols and zone-based workout library.
- [Wahoo SYSTM](https://www.wahoofitness.com/systm) — Structured training plan platform. 4DP (Four Dimensional Power) profile measures neuromuscular, anaerobic, MAP, and FTP simultaneously.

---

## Landmark Research Papers

- [Coggan & Allen (2006) — Training and Racing with a Power Meter](https://www.amazon.com/) — Book; the foundational power training reference. 7-zone model originates here.
- [Monod & Scherrer (1965) — The Work Capacity of a Synergistic Muscular Group](https://pubmed.ncbi.nlm.nih.gov/5850598/) — Critical power theory origin.
- [Poole et al. (2016) — Critical Power: An Important Fatigue Threshold in Exercise Physiology](https://pubmed.ncbi.nlm.nih.gov/26767921/) — Modern CP framework review.
- [Vanhatalo et al. (2011) — Influence of Hyperoxia on Critical Power and W'](https://pubmed.ncbi.nlm.nih.gov/21881529/) — W' mechanism paper.
- [Helgerud et al. (2007) — Aerobic High-Intensity Intervals Improve VO2max More Than Moderate Training](https://pubmed.ncbi.nlm.nih.gov/17414804/) — Interval training RCT applicable to Z5 work.

---

## Books & Courses

- **"Training and Racing with a Power Meter"** — Hunter Allen & Andrew Coggan (3rd ed., 2019). The definitive power training text. The 7-zone model, TSS, NP, IF, PMC — all originate from or are systematised in this book.
- **"The Cyclist's Training Bible"** — Joe Friel (5th ed., 2018). Periodisation for cyclists integrating power-based training.
- **"Fast After 50"** — Joe Friel (2015). Power-based training for masters cyclists — adapting protocols for age-related physiology.
- [TrainerRoad Learn — Power Training Fundamentals](https://www.trainerroad.com/learn/) — Free educational content on FTP, training zones, and structured training.
- [Velominati — The Rules (community)](https://www.velominati.com/) — Cycling culture reference, not training science, but widely cited in cycling communities.

---

## Software & Analysis Tools

- [Golden Cheetah](https://www.goldencheetah.org/) — Free, open-source, Windows/Mac/Linux. Most powerful non-commercial cycling analytics. CP modelling, power curves, PMC.
- [Intervals.icu](https://intervals.icu/) — Free, web-based. Best free alternative to TrainingPeaks. Power zone analysis, CTL/ATL tracking.
- [TrainingPeaks](https://www.trainingpeaks.com/) — Industry standard. Subscription required for full power analytics.
- [WKO5](https://www.trainingpeaks.com/wko/) — Advanced analytics. Individualised phenotyping, CP/W' tracking, FTP auto-detection.
- [Strava Power Analysis](https://www.strava.com/) — Basic power analysis (average, normalised, segments). Free with data upload.
- [VeloViewer](https://veloviewer.com/) — Strava-linked analysis. Segment mapping, power trends.

---

## Communities

- [r/cycling — Power Training Discussion](https://reddit.com/r/cycling) — General cycling community; power training threads frequent.
- [r/velo](https://reddit.com/r/velo) — Competitive cycling community. High-quality power training discussions.
- [TrainerRoad Forum](https://www.trainerroad.com/forum/) — Structured indoor training community. FTP testing, zone work, plan adaptation — very active.
- [Golden Cheetah Users Group](https://groups.google.com/g/golden-cheetah-users) — Technical discussion for GC software users.
- [Slowtwitch Power Training](https://www.slowtwitch.com/forum/) — Triathlon cycling power discussion.
- [Cycling Analytics Community](https://www.cyclinganalytics.com/) — Data-focused cycling performance community.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Training protocols must specify the zone model being used (Coggan, Friel, or other) and cite supporting evidence. FTP-to-zone percentage tables must specify the source system. Power meter accuracy claims should reference independent validation data, not manufacturer specifications alone.

---

## License

[CC0 1.0](LICENSE) — Public domain.

---

*Last updated: 2025-10-22. Maintained by contributors. Not affiliated with any power meter manufacturer, software platform, or coaching service.*
