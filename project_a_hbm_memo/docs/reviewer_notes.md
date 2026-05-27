# Skeptical Reviewer Notes

Role: semiconductor industry analyst reviewing the memo harshly.

## High-Severity Issues

### 1. Some capex numbers are too easy to overinterpret

Why it matters:

Hyperscaler capex is not equivalent to GPU demand or HBM demand. It includes buildings, servers, networking, leases, power equipment, internal chips, logistics, and non-AI infrastructure.

How to fix:

Whenever capex is used, explicitly call it a demand-side proxy. Add a sentence that the memo does not convert capex dollars into HBM units.

Source or data to strengthen:

10-K / 10-Q capex footnotes, earnings call transcripts, management commentary separating AI infrastructure from other capex where available.

### 2. "HBM became the bottleneck" may sound too singular

Why it matters:

The memo's own framework says the bottleneck can be HBM die capacity, packaging, qualification, or power/cooling. The title is fine, but the analysis should avoid implying HBM alone is always the binding constraint.

How to fix:

Use language like "HBM became one of the visible bottlenecks" and "HBM sits inside a coupled bottleneck chain." Keep the title but nuance the executive summary.

Source or data to strengthen:

TSMC advanced packaging comments, memory vendor HBM qualification language, hyperscaler power/cooling commentary.

### 3. Supplier announcements should not be treated as available capacity

Why it matters:

Sampling, qualification, design-in, mass production, and commercial shipment are different stages. A supplier can announce HBM4 without materially relieving near-term supply.

How to fix:

Add a milestone ladder figure or paragraph: sampling -> qualification -> design-in -> volume shipment -> platform deployment.

Source or data to strengthen:

Company releases, earnings transcripts, customer platform announcements, third-party teardown or supply-chain commentary where public.

### 4. Need clearer distinction between DRAM, NAND, HBM, and advanced packaging

Why it matters:

A knowledgeable reader will punish sloppy memory taxonomy. Micron's remarks mention DRAM and NAND tightness, but HBM is a DRAM-derived stacked product with different constraints.

How to fix:

Add a small taxonomy box:

- DRAM: volatile memory category
- HBM: stacked DRAM optimized for high bandwidth near accelerators
- NAND: non-volatile storage memory
- Advanced packaging: integration layer, not memory

Source or data to strengthen:

JEDEC definitions, vendor product pages, TSMC packaging materials.

## Medium-Severity Issues

### 5. The memo needs a sharper "so what?"

Why it matters:

Hiring managers want to know what decision the framework supports. Right now it explains the system well, but the decision relevance could be more explicit.

How to fix:

Add a section called "Decision-Relevant Use Cases":

- Supplier monitoring
- Infrastructure planning
- Competitive analysis
- Data product roadmap
- Research agenda for public-market analysts

Source or data to strengthen:

No new source required; this is framing.

### 6. Public signal dashboard needs prioritization

Why it matters:

Too many signals can become a laundry list. A good researcher ranks which signals are leading, coincident, or lagging.

How to fix:

Classify signals:

- Leading: capex guidance, product roadmap, facility expansion, qualification language
- Coincident: data center revenue, volume shipment language
- Lagging: reported revenue, annual capex, broad memory pricing

Source or data to strengthen:

Existing evidence table is enough for v1.

### 7. Need more explicit uncertainty language around TrendForce

Why it matters:

TrendForce is useful, but public summaries are partial and some data is likely paid. Do not over-rely on exact forecasts.

How to fix:

Use TrendForce as directional support only and mark forecasts as third-party estimates.

Source or data to strengthen:

Company disclosures first; industry research second.

## Low-Severity Issues

### 8. The memo could sound too text-heavy

Why it matters:

Portfolio readers skim. The first page needs a figure or signal table.

How to fix:

Put Figure 1 or a short "signal summary" table near the top.

Source or data to strengthen:

No new source required.

### 9. Add one paragraph on why this is not a stock memo

Why it matters:

The topic naturally touches public companies. The portfolio should make clear this is industry research, not investment advice.

How to fix:

Keep "No price forecast, no stock calls" in limitations and README.

Source or data to strengthen:

No source required.

### 10. Some technical explanations need one-sentence definitions

Why it matters:

Non-specialist readers may not know TSV, CoWoS, or OSAT.

How to fix:

Add a glossary:

- TSV: through-silicon via, vertical connection through stacked dies
- CoWoS: TSMC advanced packaging approach used to integrate logic and HBM
- OSAT: outsourced semiconductor assembly and test provider

Source or data to strengthen:

JEDEC, TSMC packaging pages, vendor explainers.

## Recommended Revision Priorities

1. Nuance the title claim in the executive summary.
2. Add a taxonomy/glossary box.
3. Add a qualification milestone ladder.
4. Add decision-relevant use cases.
5. Reclassify dashboard signals as leading/coincident/lagging.

