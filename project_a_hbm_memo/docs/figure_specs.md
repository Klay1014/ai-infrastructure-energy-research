# Figure Specs

## Figure 1: AI Scaling Demand Chain

Question: How does model demand turn into an HBM bottleneck?

Suggested chart type: left-to-right causal flow diagram.

Layout:

AI model demand -> accelerator demand -> HBM capacity/bandwidth -> advanced packaging -> foundry capacity -> data center power/cooling.

Data needed:

- Public accelerator specs
- Hyperscaler capex commentary
- NVIDIA/AMD data center revenue
- TSMC advanced packaging commentary

Takeaway:

AI scaling is constrained by a linked infrastructure chain, not by GPUs alone.

## Figure 2: HBM Supply Chain Map

Question: Which firms control which layers of the HBM ecosystem?

Suggested chart type: layered ecosystem map.

Layout:

Demand: hyperscalers and AI labs
Platforms: NVIDIA, AMD, custom ASICs
Memory: SK hynix, Samsung, Micron
Packaging/foundry: TSMC, Samsung, Intel, OSAT partners
Infrastructure: data centers, power, cooling

Takeaway:

HBM supply depends on coordination across memory vendors, accelerator platforms, packaging, and end customers.

## Figure 3: Bottleneck Decomposition Matrix

Question: Where can constraint appear, and what public signals reveal it?

Suggested chart type: matrix.

Rows:

- HBM die capacity
- Yield/stacking
- Qualification
- CoWoS/advanced packaging
- Accelerator platform ramp
- Data center power/cooling

Columns:

- Mechanism
- Public signal
- Easing signal
- Worsening signal

Takeaway:

The phrase "HBM shortage" hides several distinct bottlenecks with different evidence.

## Figure 4: Public Signal Dashboard Mock

Question: What would a lightweight monitoring product track each quarter?

Suggested chart type: dashboard mock, not a fake live dashboard.

Panels:

- Hyperscaler capex guidance
- NVIDIA/AMD data center revenue trend
- Memory vendor HBM commentary
- TSMC advanced packaging commentary
- AI server shipment estimate
- Qualitative bottleneck status

Takeaway:

A useful public-signal product should track direction and uncertainty, not pretend to estimate exact HBM allocation.

## Figure 5: Risk Matrix

Question: What would change the bottleneck thesis?

Suggested chart type: 2x2 or table.

Axes:

- Demand strength: moderating vs accelerating
- Supply response: slow vs fast

Quadrants:

- Bottleneck worsens
- Bottleneck persists
- Bottleneck eases with demand intact
- Oversupply/overbuild risk

Takeaway:

The key research question is not "is AI hot?" but whether supply response catches up before demand or architecture intensity moves higher.

