# Temperature, Electricity Demand, And Taiwan Power Adequacy

Public-signal research memo on heat, cooling load, peak risk, and AI infrastructure constraints in Taiwan.

## Status

Complete Markdown/GitHub MVP.

## Project Direction

This project asks whether Taiwan's electricity system is sufficient for the next phase of AI and semiconductor growth under rising temperature risk. It should not be framed as a simple "Taiwan will run out of power" claim. The right framing is a temperature-power adequacy and bottleneck framework:

```text
Rising temperature
-> cooling demand
-> afternoon peak and night peak
-> AI/data center and advanced manufacturing load
-> Taiwan semiconductor and AI infrastructure demand
-> annual electricity supply
-> peak load and night peak
-> reserve margin
-> grid, fuel, renewable, and clean-power constraints
```

## Research Question

How does rising temperature in Taiwan affect cooling demand, peak electricity load, night-peak risk, and the adequacy of the power system for AI infrastructure and semiconductor growth?

## Current Final Package

- `docs/one_page_summary.md`: one-page portfolio summary
- `docs/memo_cited_v1.md`: citation-ready memo
- `data/evidence_table.csv`: source-linked public evidence table
- `docs/claim_audit.md`: fact/inference/hypothesis audit
- `docs/completion_audit.md`: completion checklist
- `figures/`: Mermaid and Markdown figure drafts

Supporting work files:

- `docs/memo_outline.md`: original project outline
- `docs/temperature_environment_memo_v1.md`: early temperature-first memo
- `docs/temperature_environment_report_outline.md`: early environmental report outline
- `data/source_map.csv`: power adequacy source map
- `data/temperature_source_map.csv`: temperature source map
- `data/temperature_evidence_table.csv`: early temperature evidence table

## What "Energy Gap" Means Here

Do not use only annual generation minus annual consumption. Taiwan's risk is more specific:

- Annual energy gap: total yearly demand exceeds total available generation.
- Peak capacity gap: peak load approaches or exceeds available dispatchable capacity.
- Night-peak gap: solar output falls while industrial and cooling loads remain high.
- Clean-power gap: semiconductor customers need low-carbon electricity faster than Taiwan can supply it.
- Grid/fuel resilience gap: generation exists on paper but is limited by grid, LNG, coal, outage, or transmission constraints.

## Deliverable

A 6-10 page memo with:

1. Executive summary
2. Global electricity demand context
3. Taiwan electricity profile
4. AI/semiconductor demand drivers
5. Supply adequacy and reserve margin framework
6. Energy gap scenario model
7. Risk matrix
8. What to track next
9. Limitations

This is complete in `docs/memo_cited_v1.md`.

## Current Best Sources To Start

- IEA Electricity 2026
- IEA Electricity Mid-Year Update 2025
- Our World in Data Taiwan energy profile
- Taiwan MOEA / Energy Administration energy statistics
- Taipower daily reserve margin and supply-demand data
- Taipower / MOEA statements on 2026 peak and night-peak reserve
- Taiwan renewable energy statistics
- EIA Taiwan country energy analysis

## Key Guardrails

- Do not declare "Taiwan will lack electricity" without scenario assumptions.
- Separate annual energy sufficiency from peak capacity sufficiency.
- Separate operating reserve margin from planning reserve margin.
- Separate total power supply from clean-power availability.
- Treat AI/data center load estimates as scenarios unless official or directly sourced.

## Suggested Portfolio Positioning

AI Infrastructure Energy Constraint Research.

Secondary positioning:

Public-signal power adequacy framework for semiconductor and AI infrastructure planning.

## Current Best Version

Use `docs/memo_cited_v1.md` as the current memo draft. Use `docs/one_page_summary.md` as the portfolio entry point.
