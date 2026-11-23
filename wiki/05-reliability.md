# 評估、限制與可靠性

## 為何需要檢查
Agent 的工具輸出可能空缺、過時或不相關；多輪決策也可能放大早期錯誤。要檢查工具呼叫是否成功、結果是否支持答案、任務是否真正達成。[S2][S3]

## 可靠性做法
- 明確成功標準與可用工具範圍。
- 將工具使用結果保留為可檢查的觀察，避免只憑最後回答判斷。
- 設定最大輪數、時間或成本及遇到不確定情況的停止/人工確認點。
- 用代表性任務評估流程；逐步增加自主程度，而非一開始就讓 Agent 做所有事。[S1][S2][S3]

## 研究結果的邊界
ReAct 與 Toolformer 研究在指定資料集與條件下測試方法，不代表所有模型、工具或部署設定都會得到同樣效果。將研究 pattern 轉成產品時，仍要對具體任務驗證。[S4][S5]

## 來源
[S1](../raw/S1-OpenAI-agents.md) · [S2](../raw/S2-Anthropic-effective-agents.md) · [S3](../raw/S3-LangGraph-workflows-agents.md) · [S4](../raw/S4-ReAct-paper.md) · [S5](../raw/S5-Toolformer-paper.md)
