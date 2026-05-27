# One-Page Summary

## Project

Why HBM Became the Bottleneck of AI Scaling: A Public-Signal Research Memo on AI Infrastructure, Memory Supply, and Capacity Constraints

## Research Question

Why did HBM become a visible constraint in AI infrastructure scaling, and what public signals can help distinguish between temporary tightness and a structurally constrained bottleneck?

## Core Thesis

HBM is not a standalone shortage story. Public signals suggest it sits inside a coupled AI infrastructure chain:

```text
AI demand -> accelerator platforms -> HBM capacity and bandwidth -> advanced packaging -> data center deployment
```

The bottleneck can appear at any layer. A credible public-signal memo should therefore track HBM supply, qualification, packaging capacity, hyperscaler capex, accelerator roadmaps, and data center power/cooling together.

## Evidence Base

- NVIDIA reported Q4 FY2026 Data Center revenue of $62.3B, up 75% year over year.
- AMD described AI infrastructure demand as a key growth driver in Q1 2026.
- Meta guided 2026 capex of $115B-$135B.
- Alphabet guided 2026 capex of $175B-$185B.
- Amazon expected about $200B of 2026 capex across Amazon.
- NVIDIA H200 and AMD MI350 specifications show high HBM capacity and bandwidth as central accelerator attributes.
- SK hynix, Samsung, and Micron have all disclosed HBM product or shipment milestones.
- TSMC has described advanced packaging capacity as very tight.
- Microsoft describes AI datacenter deployment around power, cooling, networking, and rapid generational upgrades.

## Bottleneck Framework

| Layer | Bottleneck Mechanism | Public Signal |
|---|---|---|
| Demand | Hyperscaler AI infrastructure buildout | Capex guidance, cloud AI revenue |
| Accelerators | GPU/ASIC platform ramps | NVIDIA/AMD Data Center revenue, product launches |
| HBM intensity | More HBM per accelerator or rack | HBM capacity and bandwidth specs |
| HBM supply | Advanced DRAM capacity and stacking | HBM3E/HBM4 shipment and qualification language |
| Packaging | CoWoS and equivalent integration capacity | TSMC advanced packaging commentary |
| Deployment | Power, cooling, land, grid connection | Data center capex and infrastructure commentary |

## What The Memo Does Not Claim

- It does not forecast HBM prices.
- It does not make stock recommendations.
- It does not claim to know exact HBM allocation, contract pricing, yield, or CoWoS capacity.
- It does not treat all DRAM, NAND, HBM, and packaging constraints as the same thing.

## Decision-Relevant Output

The final product is a quarterly public-signal framework that labels the bottleneck as:

```text
Easing / Stable tightness / Worsening / Unclear
```

Each label should be backed by source-linked public evidence, not proprietary-data claims.
