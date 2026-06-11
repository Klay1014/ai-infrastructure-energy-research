# AI Infrastructure And Energy Constraint Research Portfolio

This repository contains public-signal research memos on AI infrastructure bottlenecks, semiconductor supply chains, electricity demand, and temperature-driven power adequacy risks.

The goal is not to forecast stock prices or make proprietary market claims. The goal is to demonstrate a research workflow:

```text
research question
-> source map
-> evidence table
-> causal bottleneck framework
-> cited memo
-> claim audit
```

## Projects

### Project A: Why HBM Became The Bottleneck Of AI Scaling

Status: Complete Markdown/GitHub MVP

This is the main completed project in the repository. It decomposes the HBM bottleneck into AI demand, accelerator architecture, HBM supply, qualification cycles, advanced packaging, and data center deployment constraints.

Start here:

- [One-page summary](project_a_hbm_memo/docs/one_page_summary.md)
- [Chinese summary](project_a_hbm_memo/docs/chinese_summary.md)
- [Full cited memo](project_a_hbm_memo/docs/memo_cited_v1.md)
- [Evidence table](project_a_hbm_memo/data/evidence_table.csv)
- [Claim audit](project_a_hbm_memo/docs/claim_audit.md)
- [Completion audit](project_a_hbm_memo/docs/completion_audit.md)
- [Figures](project_a_hbm_memo/figures/README.md)

Core question:

> Why did HBM become a visible constraint in AI infrastructure scaling, and what public signals can help distinguish temporary tightness from a structurally constrained bottleneck?

### Project B: Global Electricity Demand And Taiwan Power Adequacy

Status: Complete Markdown/GitHub MVP

This project examines how rising temperature, cooling demand, AI infrastructure, and semiconductor growth can stress Taiwan's electricity system. It separates annual demand, peak load, night peak, operating reserve, clean-power supply, fuel resilience, and grid constraints.

Start here:

- [One-page summary](project_b_power_gap_memo/docs/one_page_summary.md)
- [Full cited memo](project_b_power_gap_memo/docs/memo_cited_v1.md)
- [Evidence table](project_b_power_gap_memo/data/evidence_table.csv)
- [Claim audit](project_b_power_gap_memo/docs/claim_audit.md)
- [Completion audit](project_b_power_gap_memo/docs/completion_audit.md)
- [Figures](project_b_power_gap_memo/figures/README.md)
- [Project B README](project_b_power_gap_memo/README.md)
- [Power adequacy memo outline](project_b_power_gap_memo/docs/memo_outline.md)
- [Power source map](project_b_power_gap_memo/data/source_map.csv)
- [Power figure plan](project_b_power_gap_memo/docs/figure_plan.md)

Core question:

> How does rising temperature in Taiwan affect cooling demand, peak electricity load, night-peak risk, and the adequacy of the power system for AI infrastructure and semiconductor growth?

### Project B Environmental Branch: Temperature Risk And Electricity Demand In Taiwan

Status: Integrated into Project B MVP

This branch provided the temperature-first framing that is now integrated into Project B's cited memo. It links heat, cooling load, peak demand, night peak, and power adequacy.

Start here:

- [Temperature memo v1](project_b_power_gap_memo/docs/temperature_environment_memo_v1.md)
- [Temperature outline](project_b_power_gap_memo/docs/temperature_environment_report_outline.md)
- [Temperature evidence table](project_b_power_gap_memo/data/temperature_evidence_table.csv)
- [Temperature source map](project_b_power_gap_memo/data/temperature_source_map.csv)
- [Temperature figure plan](project_b_power_gap_memo/docs/temperature_figure_plan.md)

Core question:

> How does rising temperature in Taiwan affect cooling demand, peak electricity load, and power adequacy risk?

## What This Portfolio Is Designed To Show

- Ability to decompose complex technology infrastructure problems
- Source discipline using public company, official government, and technical sources
- Clear separation of fact, inference, and hypothesis
- Causal decision frameworks rather than naive forecasting models
- Awareness of uncertainty and public-data limitations

## What This Portfolio Does Not Claim

- It does not forecast HBM prices.
- It does not recommend semiconductor stocks.
- It does not claim proprietary knowledge of capacity, allocation, yield, or contract pricing.
- It does not reduce Taiwan's power adequacy question to a single annual electricity number.
- It does not claim exact MW-per-degree temperature response without a dedicated historical model.

## Repository Map

```text
project_a_hbm_memo/
  README.md
  docs/
    one_page_summary.md
    chinese_summary.md
    memo_cited_v1.md
    claim_audit.md
    completion_audit.md
  data/
    evidence_table.csv
    source_map.csv
  figures/

project_b_power_gap_memo/
  README.md
  docs/
    one_page_summary.md
    memo_cited_v1.md
    claim_audit.md
    completion_audit.md
    memo_outline.md
    temperature_environment_memo_v1.md
    temperature_environment_report_outline.md
  data/
    evidence_table.csv
    source_map.csv
    temperature_source_map.csv
    temperature_evidence_table.csv
  figures/
```

## Suggested Reading Order

1. Read Project A's [one-page summary](project_a_hbm_memo/docs/one_page_summary.md).
2. If you prefer Chinese context first, read Project A's [Chinese summary](project_a_hbm_memo/docs/chinese_summary.md).
3. Skim Project A's [full cited memo](project_a_hbm_memo/docs/memo_cited_v1.md).
4. Inspect Project A's [evidence table](project_a_hbm_memo/data/evidence_table.csv) and [claim audit](project_a_hbm_memo/docs/claim_audit.md).
5. Read Project B's [one-page summary](project_b_power_gap_memo/docs/one_page_summary.md).
6. Skim Project B's [full cited memo](project_b_power_gap_memo/docs/memo_cited_v1.md).
7. Inspect Project B's [evidence table](project_b_power_gap_memo/data/evidence_table.csv) and [claim audit](project_b_power_gap_memo/docs/claim_audit.md).
