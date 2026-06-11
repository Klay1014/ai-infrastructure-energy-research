# One-Page Summary

## Project

Temperature, Electricity Demand, And Taiwan Power Adequacy: A Public-Signal Memo On Heat, Cooling Load, Peak Risk, And AI Infrastructure Constraints

## Research Question

How does rising temperature in Taiwan affect cooling demand, peak electricity load, night-peak risk, and the adequacy of the power system for AI infrastructure and semiconductor growth?

## Core Thesis

Taiwan's power adequacy question should not be reduced to a single annual electricity number. The more decision-relevant framework separates:

```text
annual electricity demand
-> summer peak load
-> night peak after solar falls
-> operating reserve margin
-> clean-power availability
-> grid, fuel, and local delivery constraints
```

Temperature is the primary environmental signal in this memo. Heat becomes an infrastructure constraint through cooling demand, warm nights, data center cooling, and the timing of electricity load.

## Evidence Base

- IEA forecasts global electricity demand to grow at an average annual rate of 3.6% during 2026-2030, driven by industry, EVs, air conditioning, and data centers.
- CWA reports Taiwan's 2024 annual mean temperature was 24.6 C, 0.7 C above the 1991-2020 climate normal and the highest in the record used in the report.
- CWA's high-temperature warning system uses 36 C and 38 C thresholds, making extreme heat a public operational signal rather than only a climate statistic.
- MOEA/Taipower stated that Taiwan's 2026 peak load was expected at 42.94 GW and night peak at 38.53 GW, with planned supply additions and reserve-margin targets.
- Taipower defines operating reserve margin as a daily reliability indicator based on available net peak supply capability minus instantaneous peak load.
- MOEA stated that 2025 actual generation reached 288.9 TWh, 31.4 TWh above the earlier estimate used for the 2025 renewable-share target context, citing semiconductor and electronics-led demand growth.

## Bottleneck Framework

| Layer | Question | Public Signal |
|---|---|---|
| Temperature | Is heat exposure increasing? | Annual temperature anomaly, hot days, warm nights, heat warnings |
| Cooling load | Does heat convert into electricity demand? | Summer peak load, cooling degree days, HVAC demand response |
| Day peak | Does afternoon demand strain capacity? | Taipower daily peak load and operating reserve margin |
| Night peak | Does demand persist after solar falls? | Night peak load, evening ramp, storage and gas availability |
| AI/semiconductor load | Are industrial loads growing faster than expected? | MOEA demand commentary, science park/fab/data center announcements |
| Clean power | Can load growth be supplied with low-carbon electricity? | Renewable generation, corporate procurement, storage additions |
| Resilience | Can the system handle shocks? | Fuel inventory, plant outages, grid constraints, demand response |

## What The Memo Does Not Claim

- It does not claim Taiwan will definitely face an electricity shortage.
- It does not estimate an exact MW-per-degree temperature response.
- It does not treat annual electricity adequacy and peak adequacy as the same thing.
- It does not assume AI data center load can be inferred directly from global AI demand.
- It does not make policy recommendations beyond a public-signal tracking framework.

## Decision-Relevant Output

The final product is a quarterly public-signal monitor that labels Taiwan's temperature-power risk as:

```text
Easing / Stable tightness / Worsening / Unclear
```

Each label should be backed by source-linked evidence and should specify which layer is tight: heat exposure, cooling load, day peak, night peak, clean-power availability, or grid/fuel resilience.
