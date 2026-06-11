# Claim Audit

## Audit Rules

- `[F] Fact`: directly supported by a public source in `data/evidence_table.csv`.
- `[I] Inference`: a cautious interpretation from one or more facts.
- `[H] Hypothesis`: a scenario or testable claim for future tracking.
- Unsupported claims should be removed or downgraded.
- Exact MW-per-degree, data-center load, or shortage claims require stronger data than this memo currently has.

## Claim Table

| Claim | Label | Evidence ID | Source Quality | Overclaim Risk | Suggested Revision |
|---|---|---|---|---|---|
| IEA forecasts global electricity demand to grow 3.6% per year during 2026-2030. | [F] | P01 | Primary international agency | Low | Keep as global context, not Taiwan forecast. |
| Industry, EVs, air conditioning, and data centers are important drivers of global electricity demand growth. | [F] | P01 | Primary international agency | Low | Keep. |
| Global power systems increasingly face grid and flexibility constraints. | [F] | P02 | Primary international agency | Low | Keep as global structural context. |
| Taiwan's power adequacy should not be evaluated by annual electricity alone. | [I] | P07, P08, P09 | Official utility/government | Low-medium | Keep; explicitly explain annual versus peak versus night peak. |
| Taiwan's 2024 annual mean temperature was 24.6 C and above the 1991-2020 normal. | [F] | P03 | Official climate agency | Low | Keep. |
| Extreme heat indicators are more useful than annual average temperature for power-system stress. | [I] | P03, P04, P05 | Official climate/science sources | Low-medium | Keep; say "more useful for peak-risk analysis." |
| CWA warning thresholds make heat a public operational signal. | [I] | P04 | Official weather agency | Low | Keep. |
| Rising temperature can raise cooling demand and affect peak load. | [I] | P04, P10, P15 | Official/academic | Medium | Keep cautious; avoid exact coefficient unless qualified. |
| A 1 C temperature rise can raise Taiwan load by about 600 MW around early afternoon. | [F] | P10 | Utility magazine / secondary | Medium-high | Use only as directional context; do not make it a model input without validation. |
| Taiwan's 2026 peak load was expected at 42.94 GW and night peak at 38.53 GW. | [F] | P07 | Official government/utility | Low | Keep. |
| Day peak reserve above 10% and night peak reserve above 7% are official planning targets in the cited statement. | [F] | P07 | Official government/utility | Low | Keep as official baseline, not independent proof. |
| Night peak can become more important as solar supports daytime demand but falls in the evening. | [I] | P09, P12 | Utility/government | Medium | Keep; ask for load-shape data in next version. |
| Semiconductor and electronics demand can move Taiwan's electricity baseline materially. | [I] | P11 | Official government | Medium | Keep; avoid exact sectoral allocation. |
| Taiwan will definitely face an electricity shortage because of AI. | [H] | Unsupported | None | High | Do not use. Replace with scenario-based risk language. |
| AI data center load should be treated as a scenario input unless project-level public data is available. | [I] | P01, P02, P11 | IEA/government | Low-medium | Keep. |
| Clean-power adequacy is different from total-power adequacy. | [I] | P11, P12 | Official government | Low-medium | Keep; needs corporate procurement data in future version. |
| The highest-risk case is heat plus supply/grid delay. | [H] | P03, P07, P08, P09 | Scenario synthesis | Medium | Keep in scenario/risk sections only. |
| A quarterly public-signal monitor is more defensible than a one-time shortage forecast. | [I] | All evidence table | Research design | Low | Keep as portfolio positioning. |

## Reviewer Notes

The memo is strongest where it distinguishes annual energy, peak capacity, night peak, and operating reserve. It is weakest if it tries to quantify exact load response to temperature or AI data center demand without hourly data.

The phrase "energy gap" should always specify the layer:

```text
annual energy gap
peak capacity gap
night-peak gap
clean-power gap
grid/local delivery gap
fuel/resilience gap
```

Do not let the memo become a generic climate article. The edge is the conversion from temperature signal to power-system bottleneck.
