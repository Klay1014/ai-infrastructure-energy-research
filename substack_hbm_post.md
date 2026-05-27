# Why HBM Became The Bottleneck Of AI Scaling

Subtitle: A public-signal research memo on AI infrastructure, memory supply, and capacity constraints

AI scaling is often described as a GPU story. That is only partly right.

Modern AI accelerators increasingly compete on memory capacity and bandwidth, not only raw compute. NVIDIA H200, AMD MI350, and rack-scale AI systems all make HBM capacity and bandwidth part of the core platform story. That makes HBM a useful lens for understanding why AI infrastructure is becoming harder to scale.

But "HBM shortage" is too vague. The more useful framework is a chain:

```text
AI demand
-> accelerator platforms
-> HBM capacity and bandwidth
-> advanced packaging
-> server and rack integration
-> data center power and cooling
```

The bottleneck can appear at any layer.

Public signals suggest demand remains strong. NVIDIA reported Q4 FY2026 Data Center revenue of $62.3B, up 75% year over year. AMD described AI infrastructure as a key growth driver. Meta, Alphabet, and Amazon have all guided to very large infrastructure capex. These numbers do not directly measure HBM demand, but they are demand-side signals.

On the supply side, SK hynix, Samsung, and Micron have all disclosed HBM product or shipment milestones. Micron has also pointed to cleanroom constraints, long construction lead times, higher HBM trade ratio, and declining bits-per-wafer growth as supply constraints. TSMC has described advanced packaging capacity as very tight.

The important point is this:

```text
HBM is not a standalone commodity shortage.
It is part of a coupled AI infrastructure constraint.
```

A serious public-signal framework should track:

- Hyperscaler capex
- NVIDIA and AMD data center revenue
- HBM supplier qualification and shipment language
- TSMC advanced packaging commentary
- AI server shipment estimates
- Data center power and cooling constraints
- Memory inventory and pricing commentary

It should not pretend to forecast HBM prices from public financial data. Public sources usually do not reveal exact allocation, yield, contract pricing, or CoWoS capacity.

The better output is a bottleneck status label:

```text
Easing / Stable tightness / Worsening / Unclear
```

Each label should link back to public evidence.

I built the full version as a research-process portfolio project: source map, evidence table, cited memo, figures, and claim audit. The goal is to show how public information can be organized into a causal decision framework without making proprietary-data claims.

Full memo and evidence table: [GitHub link here]

