# Memo Outline

Title: Why HBM Became the Bottleneck of AI Scaling

Subtitle: A Public-Signal Research Memo on AI Infrastructure, Memory Supply, and Capacity Constraints

## 1. Executive Summary

Purpose: Explain the memo's answer in one page.

Draft points:

- HBM is a critical input for modern AI accelerators because model training and inference often require high memory bandwidth, not only raw compute.
- The bottleneck is multi-layered: memory die output, TSV/stacking complexity, yield, customer qualification, advanced packaging, accelerator availability, and data center infrastructure all interact.
- The main beneficiaries are firms with scarce HBM capability, qualified supply, advanced packaging access, or control over AI accelerator platforms.
- The main pressure points are customers exposed to long qualification cycles, concentrated supply, or fast-changing accelerator roadmaps.
- Public signals can track bottleneck direction, but they cannot cleanly forecast HBM prices without proprietary capacity, allocation, and contract data.

## 2. Why Memory Bandwidth Matters For AI Scaling

Question: Why does HBM matter instead of just "more GPUs"?

Include:

- Compute units can be underutilized if memory bandwidth cannot feed data fast enough.
- HBM provides much higher bandwidth than conventional DRAM by stacking DRAM dies close to the logic processor.
- AI accelerators increasingly advertise HBM capacity and bandwidth as headline specifications.

Evidence to collect:

- NVIDIA H100/H200/Blackwell data sheets
- AMD Instinct MI300/MI325/MI350 platform materials
- JEDEC or technical explainers on HBM architecture

## 3. The HBM Supply Chain

Question: Who controls which part of the constraint?

Actors:

- HBM suppliers: SK hynix, Samsung, Micron
- Accelerator vendors: NVIDIA, AMD, custom ASIC providers
- Foundry and advanced packaging: TSMC, possibly Samsung Foundry and Intel Foundry depending on scope
- OSAT and packaging ecosystem: ASE, Amkor, equipment and substrate suppliers
- Customers: Microsoft, Alphabet/Google, Amazon/AWS, Meta, Oracle, other AI cloud providers

Core idea:

HBM is not a standalone commodity input. It is co-designed, qualified, packaged, and allocated around specific accelerator platforms and customer roadmaps.

## 4. Bottleneck Decomposition

Break the bottleneck into seven layers:

| Layer | Constraint | Public signals |
|---|---|---|
| AI demand | Hyperscaler AI infrastructure buildout | Capex guidance, data center additions, AI server commentary |
| Accelerator demand | GPU/ASIC unit and platform ramps | NVIDIA/AMD data center revenue, backlog language, platform launches |
| HBM die capacity | Advanced DRAM wafer allocation | Memory vendor capex, advanced-node DRAM commentary |
| HBM stacking/yield | TSV, thin die, thermal/mechanical complexity | Vendor product ramp comments, qualification timing, yield language |
| Packaging | CoWoS/advanced packaging bottlenecks | TSMC advanced packaging comments, capacity expansion news |
| Qualification | Customer approval cycles | "Qualified by customers", "sampling", "mass production", "designed into" language |
| Data center constraints | Power, cooling, land, grid connection | Hyperscaler capex, power procurement, liquid cooling commentary |

## 5. Public Signal Framework

Question: What should a public-market observer track without pretending to have proprietary data?

Signal buckets:

- Hyperscaler capex and AI infrastructure guidance
- NVIDIA and AMD data center revenue and accelerator roadmap language
- Memory vendor HBM commentary from SK hynix, Samsung, Micron
- TSMC CoWoS and advanced packaging capacity commentary
- AI server shipment estimates from TrendForce, Omdia, IDC, Gartner, or S&P summaries
- DRAM/HBM price commentary where publicly accessible
- Inventory cycle and lead-time commentary
- Capacity expansion, equipment orders, hiring, and facility news

## 6. Risk Matrix

Question: What would make the bottleneck better or worse?

| Signal | Supply relief interpretation | Bottleneck worsening interpretation |
|---|---|---|
| Memory vendors announce HBM qualification and volume ramp | More qualified supply sources | Ramp delayed, concentrated with one vendor |
| TSMC reports advanced packaging expansion | Packaging constraint eases over time | Demand continues to exceed added capacity |
| Hyperscaler capex rises | Strong demand validates supply buildout | Demand outpaces HBM and packaging capacity |
| AI accelerator roadmaps add more HBM per accelerator | Better performance per system | Higher HBM intensity per accelerator worsens pressure |
| DRAM cycle tightens broadly | More capex incentive | Conventional DRAM competes for wafer allocation |
| Data center power constraints increase | Slows deployment, may relieve component pressure | Creates new bottleneck after components are secured |

## 7. What I Would Track Next

Turn the memo into a data product:

- Quarterly source table that tracks capex, data center revenue, HBM comments, CoWoS comments, and AI server shipment estimates.
- Event timeline of HBM product qualifications and capacity announcements.
- Bottleneck scorecard with qualitative direction: easing, stable, worsening, unclear.
- Optional dashboard mock, but only after the memo's causal framework is strong.

## 8. Limitations

Be explicit:

- Public sources do not reveal exact customer allocations, contract prices, yield, usable capacity, or long-term supply agreements.
- Industry research summaries may be directional and partially paywalled.
- Company commentary has strategic bias.
- Media reports may mix confirmed facts with analyst estimates.
- The memo evaluates bottleneck structure, not investment recommendations.

