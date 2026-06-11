# Temperature, Electricity Demand, And Taiwan Power Adequacy

Subtitle: A Public-Signal Memo On Heat, Cooling Load, Peak Risk, And AI Infrastructure Constraints

## 1. Executive Summary

Taiwan's electricity adequacy should be analyzed through temperature-driven peak risk, not only annual electricity demand. The strongest public evidence supports a cautious thesis: rising temperature can turn electricity from a background utility input into an AI infrastructure and semiconductor constraint when heat, cooling demand, peak load, night peak, and supply-delivery limits align.

This memo does not claim that Taiwan will definitely face an electricity shortage. It argues that the right public-signal framework separates several different gaps: annual energy, summer peak capacity, night-peak capacity, clean-power availability, grid/fuel resilience, and local delivery constraints.

Global context matters because electricity demand is accelerating. IEA forecasts global electricity demand to grow at an average annual rate of 3.6% during 2026-2030, supported by industry, electric vehicles, air conditioning, and data centers.[^iea-elec-2026] IEA also highlights grid and flexibility constraints, including large global grid-connection queues and the need for higher grid investment.[^iea-elec-2026-grid] For Taiwan, the global trend matters because AI infrastructure and advanced semiconductor manufacturing are both electricity-intensive and geographically concentrated.

Taiwan-specific public evidence points to a temperature-power chain. CWA reports that Taiwan's 2024 annual mean temperature was 24.6 C, 0.7 C above the 1991-2020 climate normal and the highest in the record used in the report.[^cwa-2024] CWA's high-temperature warning system uses thresholds such as 36 C and 38 C, making extreme heat a practical operational signal.[^cwa-warning] MOEA/Taipower stated that Taiwan's 2026 peak load was expected at 42.94 GW and night peak load at 38.53 GW, while planning new supply and reserve-margin buffers.[^moea-2026-supply] Taipower defines operating reserve margin as a daily reliability metric based on net peak supply capability minus instantaneous peak load.[^taipower-reserve]

The decision-relevant output is not a one-time forecast. It is a public-signal monitor that can classify whether Taiwan's temperature-power risk is easing, stable, worsening, or unclear, and which layer is driving the risk.

## 2. Why Temperature Belongs In An AI Infrastructure Memo

Project A showed that AI scaling can be constrained by HBM, advanced packaging, and data center deployment. Project B extends that chain downstream:

```text
AI demand
-> chips and servers
-> data centers and fabs
-> electricity demand
-> cooling load
-> peak and night-peak risk
-> grid, fuel, and clean-power constraints
```

Temperature is not just an environmental background variable. It affects electricity demand through air conditioning, commercial HVAC, industrial cooling, data center cooling, and health-related cooling access. A hotter year may raise annual demand, but the more operationally important event is often a hot afternoon or warm night when cooling load persists and reserve margin tightens.

This is why the memo is temperature-first. The question is not "Does Taiwan have enough annual electricity?" The sharper question is:

```text
Under which temperature, load, and supply conditions does Taiwan's power system become tight enough to constrain AI infrastructure, semiconductor production, or public resilience?
```

## 3. Global Electricity Demand Context

IEA's Electricity 2026 report frames the global backdrop: electricity demand is forecast to grow strongly through 2030, with a 3.6% average annual growth rate during 2026-2030.[^iea-elec-2026] The report identifies industry, electric vehicles, air conditioning, and data centers as important drivers. It also notes that advanced-economy electricity demand is rising again after a long period of stagnation, partly due to AI, data centers, and advanced manufacturing.

The global signal should be used carefully. IEA's forecast does not directly predict Taiwan's electricity gap. It does, however, show that electricity demand is becoming a strategic constraint in the same domains that matter for Taiwan: advanced manufacturing, cooling, data centers, and power-system flexibility.

The second global signal is grid stress. IEA notes that grids and flexibility are moving to the center of power-system planning, and that many projects involving renewables, storage, and large loads such as data centers remain stalled in grid-connection queues worldwide.[^iea-elec-2026-grid] This matters because AI infrastructure is not only a generation problem. A data center or fab needs power at a specific location, with reliable capacity and cooling support.

## 4. Taiwan Temperature Baseline

CWA's 2024 climate analysis reports that Taiwan's 2024 annual mean temperature, based on 11 lowland stations, was 24.6 C. That was 0.7 C above the 1991-2020 climate normal and ranked first in the report's historical record.[^cwa-2024]

This is a useful baseline, but annual average temperature is not enough for power adequacy analysis. Electricity systems respond to the timing and intensity of heat. A more useful public-signal set includes:

- days above 36 C
- high-temperature warnings
- warm nights
- heat wave duration
- cooling degree days
- city-level heat-island exposure

CWA's high-temperature warning thresholds are useful because they translate heat into an operational public signal. CWA defines yellow, orange, and red warning levels using thresholds such as 36 C and 38 C and duration conditions.[^cwa-warning] The National Climate Change Scientific Report also emphasizes extreme temperature indicators such as daily maximum temperature, daily minimum temperature, warm days, warm nights, and heat-wave duration.[^climate-report]

## 5. Temperature-To-Load Mechanism

The causal chain is:

```text
rising temperature
-> more hot days, heat waves, and warm nights
-> higher cooling demand
-> higher afternoon load and persistent evening load
-> lower reserve margin if supply does not rise with demand
```

The key distinction is annual demand versus peak demand. Annual electricity demand measures total energy over time. Peak load measures the maximum system stress moment. Night peak matters because solar generation falls while cooling demand can remain elevated after a hot day.

Taipower-related public materials describe a shift from past day-peak challenges toward night-peak challenges as daytime solar output helps but evening dispatch becomes more important.[^taipower-night-peak] A Taipower magazine article also reports that Taiwan's summer peak load is strongly affected by air conditioning and cites an approximate 600 MW load increase for a 1 C temperature rise around early afternoon.[^taipower-hvac] This coefficient should be treated as directional unless the underlying methodology is rebuilt with hourly temperature and load data.

For this memo, the safer model is conceptual:

```text
temperature-sensitive load =
cooling adoption
x cooling usage intensity
x humidity and heat stress
x building efficiency
x industrial and data center cooling needs
x time of day
```

## 6. Taiwan Power Adequacy Is Not One Number

MOEA/Taipower stated that Taiwan's 2026 peak load was expected at 42.94 GW and night peak load at 38.53 GW. They also stated that planned renewable additions and four new units totaling 5.2 GW, together with pumped hydro, storage, and demand management, were expected to maintain day peak reserve above 10% and night peak reserve above 7%.[^moea-2026-supply]

This is the official baseline. It should be treated as an important public signal, not as the end of the analysis. A research memo should ask what happens if:

- high-temperature days cluster
- warm nights keep cooling load high after solar output falls
- industrial or data center load grows faster than the official baseline
- new generation, storage, or grid delivery slips
- local grid constraints matter more than national supply totals

Taipower's operating reserve definition is useful here. Operating reserve is daily dispatchable supply margin: net peak supply capability minus instantaneous peak load.[^taipower-reserve] This makes the daily reserve margin a more operationally relevant signal than annual generation when analyzing heat waves.

## 7. Semiconductor And AI Load Pressure

Taiwan's exposure is not only household cooling. Semiconductor and electronics production are central to Taiwan's electricity demand story. MOEA stated in April 2026 that 2025 actual power generation reached 288.9 TWh, compared with an earlier 257.5 TWh estimate used in the context of the 2025 renewable-share target. MOEA attributed the larger-than-expected demand context to strong economic growth and manufacturing activity, including semiconductor and electronics supply chains.[^moea-renewable-review]

This does not prove that semiconductor or AI data center load will create a shortage. It does show that official demand baselines can move materially when advanced manufacturing grows faster than expected. For Project B, the right use of this source is as a forecast-risk signal: demand assumptions should be stress-tested rather than treated as fixed.

AI data centers add a second source of uncertainty. Public sources can identify global data center demand growth, local project announcements, and utility connection issues, but they usually do not reveal project-level load, power purchase terms, cooling design, or backup generation strategy. Therefore, AI load should be treated as a scenario input unless supported by official project data.

## 8. Gap Decomposition

The word "gap" should be decomposed:

| Gap Type | Question | Why It Matters |
|---|---|---|
| Annual energy gap | Is yearly generation enough for yearly consumption? | Useful for macro balance, but can miss peak stress |
| Summer peak gap | Is firm capacity enough during the hottest high-load hours? | Determines reliability during heat events |
| Night-peak gap | Is evening supply enough after solar output falls? | Captures warm-night and solar-ramp risk |
| Clean-power gap | Can new load be served with low-carbon electricity? | Matters for semiconductor customers and RE100-style commitments |
| Grid/local gap | Can power reach the right location at the right time? | Data centers and fabs are geographically concentrated |
| Fuel/resilience gap | Can the system withstand fuel, outage, or weather shocks? | Generation on paper may not equal available supply in stress events |

This decomposition prevents a common mistake: declaring "enough electricity" or "not enough electricity" without specifying the constraint layer.

## 9. Scenario Framework

Use scenarios, not a fake-precise forecast.

### Scenario A: Official Baseline Holds

Peak and night-peak demand remain close to MOEA/Taipower planning assumptions. New generation, storage, pumped hydro, and demand response arrive broadly on schedule. Temperature is hot but within recent operating experience.

Interpretation: risk is manageable, but still requires daily monitoring during heat waves.

### Scenario B: Heat Wave Plus Warm Nights

High daytime temperatures are followed by elevated nighttime minimum temperatures. Cooling demand persists after solar output declines.

Interpretation: night peak becomes the more important bottleneck. Operating reserve margin and evening ramp signals matter more than annual electricity totals.

### Scenario C: High AI/Semiconductor Load Growth

Industrial, fab, and data center load grows faster than expected. Annual electricity demand and peak load both rise above official baseline assumptions.

Interpretation: the risk is not simply a summer weather event. It becomes a structural demand-growth issue.

### Scenario D: Heat Plus Supply Or Grid Delay

High temperature aligns with delayed capacity, lower renewable output, plant outage, transmission constraint, or fuel stress.

Interpretation: this is the highest-risk scenario because demand-side and supply-side stress align.

## 10. Public Signal Framework

| Signal | Timing Type | What To Extract | Interpretation |
|---|---|---|---|
| CWA high-temperature warnings | Leading/real-time | 36 C and 38 C alerts, duration, affected counties | Heat exposure and cooling trigger |
| Warm nights / minimum temperature | Leading | Nighttime heat persistence | Night-peak risk |
| Taipower peak load | Coincident | Daily peak load and time of peak | System stress |
| Taipower operating reserve margin | Coincident | Daily reserve margin and color status | Reliability buffer |
| MOEA/Taipower supply guidance | Leading | Peak forecast, night-peak forecast, new capacity | Official baseline |
| New capacity online | Leading/coincident | Gas units, storage, renewables, pumped hydro | Supply relief |
| Semiconductor and data center announcements | Leading | Location, power demand, timing if disclosed | Load growth risk |
| Renewable generation and storage additions | Leading/coincident | Daytime solar support and evening flexibility | Clean-power and night-peak relief |
| Demand response activation | Coincident | Frequency, size, event timing | Tightness signal |

## 11. Risk Matrix

| Scenario | Temperature Signal | Electricity Signal | Interpretation |
|---|---|---|---|
| Risk worsens | More high-temperature warnings and warm nights | Peak load rises, reserve margin falls | Heat is converting into system stress |
| Night-peak risk rises | Warm nights persist | Evening load remains high after solar falls | Solar helps day peak but not enough for evening |
| Structural demand risk rises | AI/fab load announcements accelerate | Official demand forecast revised upward | Industrial load is outrunning baseline assumptions |
| Supply relief improves | Normal heat conditions | New units, storage, and demand response arrive on schedule | Official baseline becomes more credible |
| Clean-power gap widens | Heat raises total load | Renewable growth lags corporate demand | Total electricity may be available, but not clean enough |
| Unclear | Mixed temperature and load signals | Reserve margin volatile | More time-stamped data needed |

## 12. What I Would Track Next

The next version should maintain a monthly or quarterly tracker:

- CWA temperature anomaly
- CWA high-temperature warnings
- hot days and warm nights
- Taipower daily peak load
- day peak versus night peak
- operating reserve margin
- renewable generation and storage additions
- new gas and pumped-hydro capacity milestones
- semiconductor and data center load announcements
- demand response events
- clean-power procurement signals

The output should be a status label:

```text
Easing / Stable tightness / Worsening / Unclear
```

Each label should state which layer is driving the classification.

## 13. Limitations

This memo uses public evidence only. It does not have project-level data center load, fab-level power contracts, detailed grid-connection studies, hourly temperature-load regressions, or proprietary utility planning data.

The memo also avoids exact MW-per-degree claims except as directional context. A defensible quantitative model would require historical hourly CWA temperature data, humidity, holidays, day-of-week effects, Taipower hourly load, solar/wind output, industrial activity, and demand-response events.

The strongest supported conclusion is structural: Taiwan's AI infrastructure and semiconductor power risk should be monitored through temperature, cooling load, peak and night-peak conditions, operating reserve, clean-power availability, and grid/fuel resilience together.

## References

[^iea-elec-2026]: IEA, "Electricity 2026: Executive summary," 2026. https://www.iea.org/reports/electricity-2026/executive-summary

[^iea-elec-2026-grid]: IEA, "Electricity 2026: Executive summary," section on grids and flexibility, 2026. https://www.iea.org/reports/electricity-2026/executive-summary

[^cwa-2024]: Central Weather Administration, "2024 Taiwan Climate Analysis," 2025. https://www.cwa.gov.tw/Data/climate/Watch/twn/twn-monitor_2024-0.pdf

[^cwa-warning]: Central Weather Administration, "High Temperature Information," accessed 2026-06-12. https://www.cwa.gov.tw/V8/C/P/Warning/W29.html

[^climate-report]: National Climate Change Scientific Report 2024, Chapter 2, 2024. https://www.nera.gov.tw/upload/cmNormalFile/2024-08-28/589f6935-f10f-4169-8655-c33755d2d6a2/%E7%AC%AC2%E7%AB%A0.pdf

[^moea-2026-supply]: MOEA/Taipower, "Taipower closely monitors Middle East situation and maintains stable power supply," 2026-03-24. https://www.moea.gov.tw/MNS/POPULACE/news/News.aspx?kind=1&menu_id=40&news_id=122193

[^taipower-reserve]: Taipower, "Today's estimated peak operating reserve margin," accessed 2026-06-12. https://www.taipower.com.tw/d006/loadGraph/loadGraph/load_reserveT_.html

[^taipower-night-peak]: Taipower Journal, article on Taiwan's supply stability and night-peak transition, accessed 2026-05-27. https://service.taipower.com.tw/tpcjournal/article/7235

[^taipower-hvac]: Taipower Magazine, issue 819, article on HVAC demand response, accessed 2026-05-27. https://www.taipower.com.tw/media/f1oehghv/819%E6%9C%9F11%E6%9C%88%E8%99%9F-%E5%85%A8%E6%96%87%E8%A8%82%E9%96%B1%E7%89%88.pdf?mediaDL=true

[^moea-renewable-review]: MOEA Energy Administration, "Energy promotion indicators reviewed pragmatically," 2026-04-17. https://www.moea.gov.tw/MNS/Populace/news/News.aspx?kind=1&menu_id=40&news_id=122430
