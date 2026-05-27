# Claim Audit

Scope: `docs/memo_cited_v1.md`

Rules used:

- [F] Fact: directly supported by a named public source in `data/evidence_table.csv`.
- [I] Inference: reasonable interpretation from one or more facts, but not directly stated by a source.
- [H] Hypothesis: forward-looking or conditional claim that belongs in risk, limitations, or what-to-track sections.

## Executive Summary Claims

| Claim | Label | Supporting evidence ID | Source quality | Risk of overclaiming | Suggested revision |
|---|---|---|---|---|---|
| HBM has become one of the most visible bottlenecks in AI infrastructure scaling. | [I] | NVIDIA Q4 FY2026 results; Micron FQ2 2026 prepared remarks; TSMC Q1 2026 transcript; supplier HBM milestones | Primary + industry | Medium | "Public signals suggest HBM is one visible constraint within AI infrastructure scaling." |
| Modern AI accelerators increasingly depend on memory capacity and bandwidth, not only raw compute. | [I] | NVIDIA H200 product page; AMD MI350 product page; Amazon Q4/FY2025 results | Primary | Low-medium | "Public accelerator specs increasingly emphasize HBM capacity and memory bandwidth alongside compute." |
| HBM sits inside a coupled constraint chain from AI demand to accelerators, HBM, packaging, and data center infrastructure. | [I] | NVIDIA/AMD revenue; hyperscaler capex; Micron HBM; TSMC packaging comments | Primary | Low-medium | Keep, but frame as the memo's analytical framework rather than established fact. |
| AI demand drives accelerator demand. | [I] | NVIDIA Q4 FY2026 results; AMD Q1 2026 results; hyperscaler capex | Primary | Low | "Public revenue and capex signals are consistent with AI demand driving accelerator demand." |
| Accelerator roadmaps increase HBM intensity. | [I] | NVIDIA H200 specs; AMD MI350 specs; Amazon Trainium4 comment | Primary | Medium | "Recent public accelerator specs point to high and rising visibility of HBM capacity and bandwidth." |
| HBM supply depends on advanced DRAM capacity, stacking yield, and qualification. | [I] | Micron FQ2 2026 remarks; SK hynix HBM3E; Samsung HBM4; TrendForce validation note | Primary + industry | Medium | "The memo treats HBM supply as dependent on DRAM capacity, stacking, yield, and qualification; public sources directly support capacity and qualification milestones, while yield is not publicly quantified." |
| Finished accelerator output depends on advanced packaging. | [I] | TSMC Q1 2026 transcript | Primary | Medium | "Advanced packaging can constrain finished accelerator output, based on TSMC's tightness commentary." |
| Deployment ultimately depends on data center power and cooling. | [I]/[H] | Hyperscaler capex only; no direct power/cooling source in evidence table | Primary but indirect | High | "Deployment may also be constrained by data center infrastructure such as power and cooling; this memo treats that as a downstream risk to track." |
| NVIDIA reported Q4 FY2026 Data Center revenue of $62.3B, up 75% YoY. | [F] | NVIDIA Q4 FY2026 results | Primary | Low | Keep. |
| AMD described AI infrastructure as a key growth driver in Q1 2026. | [F] | AMD Q1 2026 results | Primary | Low | Keep. |
| Meta guided 2026 capex of $115B-$135B. | [F] | Meta Q4/FY2025 results | Primary | Low | Keep. |
| Alphabet guided 2026 capex of $175B-$185B. | [F] | Alphabet Q4/FY2025 results | Primary | Low | Keep if verified directly in source; cite primary source only. |
| Amazon expected about $200B of 2026 capex across Amazon. | [F] | Amazon Q4/FY2025 results | Primary | Low-medium | Keep but say "across Amazon" every time; not AWS-only or AI-only. |
| Hyperscaler capex figures are demand-side proxies, not HBM unit estimates. | [I] | Limitations embedded in evidence table | Analyst framing from primary sources | Low | Keep. This is a useful guardrail. |
| SK hynix, Samsung, and Micron have disclosed HBM product and shipment milestones. | [F] | SK hynix HBM3E release; Samsung HBM4 release; Micron FQ2 2026 remarks | Primary | Low | Keep. |
| Micron identified cleanroom constraints, long construction lead times, higher HBM trade ratio, higher HBM growth rates, and declining bits-per-wafer growth as memory supply constraints. | [F] | Micron FQ2 2026 remarks | Primary | Low | Keep, but attribute as Micron's view. |
| TSMC indicated advanced packaging capacity remains very tight. | [F] | TSMC Q1 2026 transcript | Primary transcript | Low | Keep. |
| The bottleneck is not simply HBM wafer output. | [I] | Micron constraints + TSMC packaging comments + HBM supplier milestones | Primary | Low-medium | "These signals suggest the constraint is broader than HBM wafer output alone." |
| The framework classifies the bottleneck as easing, persisting, worsening, or unclear. | [I] | Internal method | N/A | Low | Keep as proposed methodology, not external fact. |

## Technical And Supply Chain Claims

| Claim | Label | Supporting evidence ID | Source quality | Risk of overclaiming | Suggested revision |
|---|---|---|---|---|---|
| HBM is a specialized stacked form of DRAM. | [F] | JEDEC home and HBM standards area; vendor pages | Standards + primary | Low | Keep. |
| General DRAM tightness is not identical to HBM tightness. | [I] | Micron DRAM/NAND remarks; taxonomy | Primary + analyst framing | Low | Keep. |
| Advanced packaging can limit finished accelerator output even when HBM dies are available. | [I] | TSMC Q1 2026 transcript | Primary | Medium | Keep with "can"; do not say it always does. |
| CoWoS is TSMC's advanced packaging family often associated with AI accelerators. | [F]/[I] | TSMC transcript; source map | Primary but not fully defined in evidence table | Medium | Add a stronger TSMC CoWoS explainer source if this becomes a formal PDF. |
| AI accelerators need memory capacity and bandwidth to keep compute units fed. | [I] | NVIDIA H200; AMD MI350; Amazon Trainium4 | Primary specs | Medium | "AI accelerator vendors emphasize memory capacity and bandwidth as key platform attributes." |
| NVIDIA H200 offers 141GB HBM3e at 4.8TB/s. | [F] | NVIDIA H200 product page | Primary | Low | Keep. |
| AMD MI350 eight-GPU platform has 2.3TB HBM3E and 64TB/s aggregate bandwidth. | [F] | AMD MI350 product page | Primary | Low | Keep. |
| Amazon said Trainium4 will deliver 4x more memory bandwidth and 2x HBM capacity than Trainium3. | [F] | Amazon Q4/FY2025 results | Primary | Low | Keep, but note it is AWS custom silicon, not NVIDIA GPU demand. |
| These specs show platform performance is increasingly marketed around memory capacity and bandwidth. | [I] | NVIDIA H200; AMD MI350; Amazon Trainium4 | Primary | Low-medium | Keep. |
| HBM demand pressure depends on accelerator units, HBM capacity per accelerator, qualification mix, and packaging availability. | [I] | Derived framework | Analyst framework | Low-medium | Keep as simplified framework, not equation for measurement. |

## Bottleneck Decomposition Claims

| Claim | Label | Supporting evidence ID | Source quality | Risk of overclaiming | Suggested revision |
|---|---|---|---|---|---|
| NVIDIA and hyperscaler capex indicate strong AI infrastructure demand. | [I] | NVIDIA Q4 FY2026; Meta; Alphabet; Amazon; Microsoft | Primary | Medium | "Indicate strong public demand signals for AI infrastructure." |
| Public demand signals remain strong enough to keep pressure on accelerator, memory, packaging, and deployment capacity. | [I] | NVIDIA/AMD + hyperscaler capex + Micron/TSMC constraints | Primary | Medium | "Are consistent with continued pressure..." |
| Product roadmaps suggest memory capacity and bandwidth are rising in importance. | [I] | NVIDIA H200; AMD MI350; Amazon Trainium4 | Primary | Low-medium | Keep. |
| HBM demand can remain elevated even if accelerator unit growth normalizes. | [H] | Product specs only; no unit growth or elasticity data | Primary but indirect | Medium-high | Move to risk/what-to-track or phrase as "could remain elevated." |
| HBM depends on advanced DRAM capacity. | [F]/[I] | Micron FQ2 2026 remarks; JEDEC | Primary | Low | Keep. |
| Micron's commentary supports a capacity bottleneck view. | [I] | Micron FQ2 2026 remarks | Primary | Low-medium | "Supports one vendor's view that memory supply constraints are meaningful." |
| Supplier announcements should be read as milestones, not automatically available capacity. | [I] | Evidence table limitations | Analyst framing | Low | Keep. Excellent guardrail. |
| Missing public data includes allocation size, yield, and supplier qualification by platform. | [F]/[I] | Absence in public sources; evidence limitations | N/A | Low | Keep. |
| Advanced packaging can be a separate binding constraint. | [I] | TSMC Q1 2026 transcript | Primary | Low-medium | Keep with "can." |
| HBM cannot be analyzed as a standalone commodity. | [I] | TSMC packaging + supplier qualification + platform specs | Primary | Low-medium | "HBM should not be analyzed only as a standalone commodity input." |
| Supply expansion is underway, but timing matters. | [I] | Micron Singapore 2027; TSMC capex | Primary | Low | Keep. |
| TSMC expects capex over next three years significantly higher than prior three. | [F] | TSMC Q1 2026 transcript | Primary | Low | Keep. |
| Advanced HBM supply is tied to specific platforms and customers. | [I] | Micron Vera Rubin; TrendForce Rubin; Google Vera Rubin | Primary + industry | Medium | "Some public HBM disclosures are tied to specific accelerator platforms." |
| The bottleneck can migrate downstream to power/cooling. | [H] | Indirect capex only | Weak/indirect | High | Move firmly into "risk to track" unless adding direct power/cooling sources. |

## Public Signal And Risk Claims

| Claim | Label | Supporting evidence ID | Source quality | Risk of overclaiming | Suggested revision |
|---|---|---|---|---|---|
| Hyperscaler capex guidance is a leading demand signal. | [I] | Meta; Alphabet; Amazon; Microsoft | Primary | Low | Keep. |
| Product roadmap specs are a leading signal for HBM intensity. | [I] | NVIDIA H200; AMD MI350; Amazon Trainium4 | Primary | Low | Keep. |
| Facility expansion is a leading signal for future supply relief. | [I] | Micron Singapore; TSMC capex | Primary | Low | Keep. |
| Qualification language indicates supplier maturity. | [I] | SK hynix; Samsung; Micron; TrendForce | Primary + industry | Low | Keep. |
| Memory pricing/inventory is lagging. | [I] | Not directly developed in evidence table | Weak | Medium | Keep only as framework item; mark as to-be-collected evidence. |
| Data center power/cooling is a leading/coincident deployment constraint signal. | [H] | No direct source in evidence table | Weak | High | Mark as "future tracking category" rather than current supported claim. |
| Bottleneck worsens if capex and accelerator demand accelerate while HBM validation delays and packaging remains tight. | [H] | Framework from evidence | N/A | Low | Fine in risk matrix. |
| Overbuild risk returns if AI capex slows while memory/packaging capacity arrives late. | [H] | Framework from memory cycle logic | N/A | Medium | Fine in risk matrix, but avoid presenting as current conclusion. |

## Unsupported Or Weakly Supported Claims To Fix First

1. "Deployment ultimately depends on data center power and cooling."
   - Status: [I]/[H], weakly supported in current evidence table.
   - Fix: move to "risk to track" or add direct sources on power/cooling constraints.

2. "HBM demand can remain elevated even if accelerator unit growth normalizes."
   - Status: [H].
   - Fix: phrase as a scenario, not a conclusion.

3. "Customer concentration" section.
   - Status: mostly [I].
   - Fix: make it narrower: "some public HBM disclosures are platform-specific." Avoid implying broad allocation concentration without source.

4. "Memory pricing/inventory" as signal bucket.
   - Status: reasonable framework, but under-sourced.
   - Fix: label as data-to-collect, or add public DRAM/HBM pricing commentary sources.

5. CoWoS definition.
   - Status: directionally right, but under-cited.
   - Fix: add a TSMC advanced packaging explainer source if making final PDF.

## Post-Audit Fix Status

Applied after this audit:

- Executive summary first sentence was downgraded from "HBM has become one of the most visible bottlenecks" to "Public signals suggest HBM is one visible constraint."
- Power/cooling was moved from a hard downstream conclusion to a deployment risk and future tracking category.
- Microsoft official sources were added for AI datacenter power/cooling requirements.
- TSMC official 3DFabric and CoWoS sources were added for advanced packaging definitions.
- "Customer concentration" was narrowed to "platform-specific qualification and allocation uncertainty."
- Evidence table now uses stable IDs `E01-E33`.

## Overall Audit Judgment

The project is structurally strong and has moved beyond a generic AI hype memo. The strongest parts are:

- Clear research question
- Causal bottleneck decomposition
- Source-linked evidence table
- Explicit refusal to forecast HBM prices or stocks
- Distinction between HBM, DRAM, NAND, GPU, and packaging

The remaining risk is not lack of content. The risk is a few analytical claims being stated too confidently from indirect public evidence. The memo should downgrade those claims into "public signals suggest," "can," "may," or "risk to track."
