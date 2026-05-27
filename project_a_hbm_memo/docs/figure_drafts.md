# Figure Drafts

These are draft figures for the portfolio memo. They are designed to explain structure and bottlenecks, not to imply fake numerical precision.

## Figure 1: AI Scaling Demand Chain

Question answered: How does AI model demand turn into an HBM and infrastructure bottleneck?

```mermaid
flowchart LR
    A["Model and product demand"] --> B["Hyperscaler AI capex"]
    B --> C["GPU / accelerator platforms"]
    C --> D["HBM capacity and bandwidth"]
    D --> E["Advanced packaging"]
    E --> F["Server and rack integration"]
    F --> G["Data center power and cooling"]

    C -. "NVIDIA / AMD / custom ASICs" .-> C1["Accelerator roadmap"]
    D -. "SK hynix / Samsung / Micron" .-> D1["HBM3E / HBM4 qualification"]
    E -. "TSMC CoWoS / OSAT partners" .-> E1["Packaging capacity"]
```

One-sentence takeaway: AI scaling is constrained by a linked infrastructure chain, not by GPUs alone.

## Figure 2: HBM Supply Chain Map

Question answered: Which actors control which part of the HBM bottleneck?

```mermaid
flowchart TB
    subgraph Demand["Demand"]
        H1["Microsoft"]
        H2["Alphabet / Google"]
        H3["Amazon / AWS"]
        H4["Meta"]
    end

    subgraph Platforms["Accelerator Platforms"]
        P1["NVIDIA GPUs"]
        P2["AMD Instinct"]
        P3["Google TPU"]
        P4["AWS Trainium"]
        P5["Custom ASICs"]
    end

    subgraph Memory["HBM Suppliers"]
        M1["SK hynix"]
        M2["Samsung"]
        M3["Micron"]
    end

    subgraph Packaging["Foundry and Advanced Packaging"]
        F1["TSMC"]
        F2["Samsung Foundry"]
        F3["Intel Foundry"]
        F4["ASE / Amkor / OSAT ecosystem"]
    end

    subgraph Deployment["Deployment"]
        D1["AI servers"]
        D2["Rack-scale systems"]
        D3["Power and cooling"]
    end

    Demand --> Platforms
    Platforms --> Memory
    Platforms --> Packaging
    Memory --> Packaging
    Packaging --> Deployment
```

One-sentence takeaway: HBM supply depends on coordination across customers, accelerator platforms, memory vendors, and packaging capacity.

## Figure 3: Bottleneck Decomposition

Question answered: What does "HBM shortage" actually mean?

```mermaid
flowchart LR
    B["HBM bottleneck"] --> B1["Demand pull"]
    B --> B2["HBM die capacity"]
    B --> B3["Stacking and yield"]
    B --> B4["Qualification cycle"]
    B --> B5["Advanced packaging"]
    B --> B6["Capex lead time"]
    B --> B7["Customer allocation"]
    B --> B8["Power and cooling"]

    B1 --> S1["Hyperscaler capex; data center revenue"]
    B2 --> S2["DRAM capex; wafer allocation"]
    B3 --> S3["HBM3E/HBM4 ramp language"]
    B4 --> S4["Sampling; qualified; designed-in; volume shipment"]
    B5 --> S5["TSMC CoWoS / advanced packaging comments"]
    B6 --> S6["Facility timing; cleanroom constraints"]
    B7 --> S7["Platform-specific design-ins"]
    B8 --> S8["Data center buildout; power procurement"]
```

One-sentence takeaway: A credible HBM memo should decompose the bottleneck instead of treating it as one vague shortage.

## Figure 4: Public Signal Dashboard Mock

Question answered: What should a lightweight public-signal monitoring product track?

```mermaid
flowchart TB
    Dashboard["Quarterly Public Signal Dashboard"]

    Dashboard --> A["Demand"]
    Dashboard --> B["Accelerators"]
    Dashboard --> C["HBM Supply"]
    Dashboard --> D["Packaging"]
    Dashboard --> E["Deployment"]
    Dashboard --> F["Risk Label"]

    A --> A1["Hyperscaler capex guidance"]
    A --> A2["Cloud AI revenue commentary"]

    B --> B1["NVIDIA Data Center revenue"]
    B --> B2["AMD Data Center revenue"]
    B --> B3["Accelerator memory specs"]

    C --> C1["HBM3E/HBM4 shipment language"]
    C --> C2["Supplier qualification status"]

    D --> D1["TSMC advanced packaging comments"]
    D --> D2["OSAT capacity expansion"]

    E --> E1["AI server shipment estimates"]
    E --> E2["Power and cooling constraints"]

    F --> F1["Easing"]
    F --> F2["Stable tightness"]
    F --> F3["Worsening"]
    F --> F4["Unclear"]
```

One-sentence takeaway: The portfolio product should classify bottleneck direction from public signals, not pretend to estimate exact HBM allocation.

## Figure 5: Risk Matrix

Question answered: What would change the bottleneck thesis?

| Demand Strength | Supply Response | Scenario | Interpretation |
|---|---|---|---|
| Accelerating | Slow | Bottleneck worsens | HBM, packaging, and data center constraints remain tight |
| Strong | Moderate | Bottleneck persists | Supply growth is absorbed by AI demand and higher HBM intensity |
| Stable or moderating | Fast | Bottleneck eases | Multiple qualified suppliers and packaging expansion reduce pressure |
| Slowing | Fast | Overbuild risk | Supply arrives after demand slows, reviving memory-cycle downside |

One-sentence takeaway: The question is whether supply response catches demand before memory intensity and deployment demand move higher.

