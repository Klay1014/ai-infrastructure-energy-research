# 中文摘要

## 專案題目

為什麼 HBM 成為 AI 擴張瓶頸：從公開訊號分析 AI 基礎設施、記憶體供給與產能限制

## 這份研究在回答什麼

這份 memo 想回答一個產業研究問題：

```text
為什麼 HBM 會成為 AI infrastructure scaling 裡面被市場反覆提到的限制，
以及哪些公開訊號可以幫助我們判斷瓶頸是在惡化、舒緩，還是轉移到其他環節？
```

它不是 HBM 價格預測，也不是股票推薦。重點是展示如何把混亂的 AI、GPU、記憶體、封裝與資料中心資訊整理成一個可驗證的 causal bottleneck framework。

## 核心結論

HBM 不是一個孤立的短缺故事。它位在一條互相耦合的 AI infrastructure constraint chain 裡：

```text
AI demand
-> accelerator platforms
-> HBM capacity and bandwidth
-> HBM supplier qualification
-> advanced packaging / CoWoS
-> data center power and cooling
```

所以比較穩健的說法不是「HBM 單獨限制 AI」，而是：

```text
HBM 是 AI 擴張過程中最可見的瓶頸之一，
但它必須和 advanced packaging、GPU platform roadmap、hyperscaler capex、
以及資料中心電力/冷卻限制一起分析。
```

## 主要發現

1. **AI accelerator 越來越依賴 memory bandwidth**

   NVIDIA H200、AMD MI350、AWS Trainium 等平台都把 HBM 容量與頻寬作為重要規格。這代表 AI scaling 不只是算力問題，也受到記憶體容量與頻寬限制。

2. **HBM 供給不等於一般 DRAM 供給**

   HBM 是 stacked DRAM，還牽涉 die capacity、stacking、yield、customer qualification、design-in 和 volume shipment。供應商宣布量產或送樣，不等於所有客戶都能立刻取得充足供給。

3. **Advanced packaging 可能成為同等重要的限制**

   即使 HBM dies 可用，如果 CoWoS 或其他 advanced packaging capacity 不足，finished accelerator output 仍可能受限。

4. **Hyperscaler capex 是需求訊號，但不能直接換算成 HBM 需求**

   Meta、Alphabet、Amazon 等公司的 capex guidance 可以作為 AI infrastructure demand proxy，但 capex 包含資料中心、網路、電力、冷卻、土地與其他基礎設施，不能直接換算成 GPU units 或 HBM bits。

5. **瓶頸可能會轉移**

   如果 HBM 和封裝產能逐步改善，下一層限制可能變成 data center power、cooling、grid connection、土地或能源取得。

## 這份作品展示的能力

- 把 AI infrastructure 問題拆成 demand、supply、capacity、qualification 和 deployment constraints
- 用公開公司資料、官方資料和產業研究摘要建立 source map
- 建立 evidence table，而不是只寫沒有來源的結論
- 把事實、推論和假設分開
- 避免把 HBM、DRAM、NAND、GPU 和 CoWoS 混成同一個概念
- 把產業資訊整理成 decision-relevant monitoring framework

## 最適合怎麼讀

1. 先讀 `docs/one_page_summary.md`
2. 再讀 `docs/memo_cited_v1.md`
3. 查看 `data/evidence_table.csv` 確認來源
4. 查看 `docs/claim_audit.md` 看哪些句子是 fact、inference 或 hypothesis

## 一句話總結

這份 Project A 的重點不是預測 HBM 價格，而是建立一個公開訊號研究框架，判斷 AI infrastructure 的瓶頸目前卡在 HBM、封裝、平台 qualification，還是正在往資料中心電力與冷卻限制轉移。
