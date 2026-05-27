# Why HBM Became the Bottleneck of AI Scaling

Public-signal research memo on AI infrastructure, memory supply, and capacity constraints.

## Project Goal

This 7-day MVP is a portfolio research project. The goal is not to forecast HBM prices or make stock calls. The goal is to show that I can decompose a complex AI infrastructure bottleneck into demand, supply, capacity, and uncertainty components using credible public signals.

## Sharp Research Question

Why did high-bandwidth memory become a binding constraint in AI infrastructure scaling, and what public signals can help distinguish between temporary supply tightness and a structurally constrained bottleneck?

## Final Deliverable

A 6-10 page memo for a hiring manager or research lead in AI infrastructure, semiconductor strategy, data science, or technology industry research.

Current final package:

- `docs/memo_cited_v1.md`: citation-ready memo
- `docs/one_page_summary.md`: one-page portfolio summary
- `figures/`: Mermaid and Markdown figure files
- `data/evidence_table.csv`: source-linked public evidence table

Supporting work files:

These are kept as an audit trail. Do not treat earlier drafts as the final memo.

- `docs/memo_outline.md`: memo structure and argument flow
- `data/source_map.csv`: source map and signal extraction plan
- `docs/supply_chain_and_bottlenecks.md`: causal framework and bottleneck decomposition
- `docs/memo_draft_v1.md`: first full memo draft
- `docs/reviewer_notes.md`: skeptical analyst review notes
- `docs/memo_draft_v2.md`: revised memo draft
- `docs/figure_drafts.md`: Mermaid figure drafts

## Core Thesis Draft

HBM matters because AI accelerators increasingly need high memory bandwidth and capacity to keep compute units fed. The bottleneck is not only "memory demand is high"; it is a coupled constraint across HBM die capacity, stacking and yield, customer qualification, advanced packaging capacity, accelerator roadmaps, hyperscaler capex, and data center power/cooling. Public data cannot precisely forecast HBM pricing, but it can support a causal bottleneck framework and a monitoring system for supply relief versus worsening tightness.

## 7-Day Execution Plan

| Day | Output | Focus |
|---|---|---|
| 1 | Outline + source map | Complete |
| 2 | Evidence table | Complete: 33 public evidence rows with stable IDs |
| 3 | Supply chain + bottleneck decomposition | Complete |
| 4 | Figure drafts | Complete: 5 Mermaid/table figure drafts |
| 5 | Executive summary + risk matrix | Complete in `memo_cited_v1.md` |
| 6 | Harsh review pass | Complete in `reviewer_notes.md` |
| 7 | Final packaging | Complete for Markdown/GitHub/Notion; PDF export optional |

## Rules For The Memo

- Do not claim exact market share, price, capacity, or forecast unless sourced.
- Separate facts, inference, and speculation.
- Use public sources only.
- Prefer primary company materials over media summaries.
- Treat paid industry research as directional unless the exact data is publicly available.
- Avoid stock recommendations.

## Current Best Version

Use `docs/memo_cited_v1.md` as the current memo draft.

Recommended next polish pass:

- Render Mermaid figure files to PNG/SVG if Mermaid CLI becomes available.
- Export `docs/memo_cited_v1.md` as PDF or publish it as a Notion page.
- Add a short Chinese abstract if the final portfolio audience includes Taiwan-based readers.

## Suggested Portfolio Presentation

For GitHub:

1. Put `docs/one_page_summary.md` near the top of the repository or paste it into the README.
2. Link to `docs/memo_cited_v1.md` as the full memo.
3. Keep `data/evidence_table.csv` visible to show source discipline.
4. Include the `figures/` Mermaid files as transparent, editable diagram sources.

For Notion:

1. Use `docs/one_page_summary.md` as the landing section.
2. Paste `docs/memo_cited_v1.md` below it.
3. Convert the figure files into Mermaid blocks or simple tables.
4. Add a collapsible section for the evidence table.

For PDF:

1. Use `docs/memo_cited_v1.md` as the base.
2. Insert the five figures after sections 3, 4, 6, and 7.
3. Keep references at the end.
