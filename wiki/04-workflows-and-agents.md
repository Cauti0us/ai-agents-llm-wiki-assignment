# Workflow、Agent 與多 Agent 模式

## 預設路徑 vs 動態決定
Anthropic 與 LangGraph 文件都用 workflow 表示預先安排的步驟，用 agent 表示由模型動態決定部分流程與工具使用。[S2][S3]

- **Workflow**：步驟可預先拆清、順序穩定，較容易預測和檢查。
- **Agent**：下一步取決於任務與工具觀察，適合需要彈性決策的多步任務。
- **混合**：大流程固定，部分節點讓 Agent 動態查詢/操作。

## 常見 workflow pattern
LangGraph 文件舉例 prompt chaining、routing、parallelization、orchestrator-worker、evaluator-optimizer 等，可按任務的拆解方式和驗收標準挑選。[S3]

## 多 Agent
多 agent 能分工，但增加 handoff、共享狀態與整合複雜度。應先確認子任務確實可分、輸入/輸出有契約，並指定誰負責最終答覆；多 Agent 並非任務自然更好的選項。[S1][S2]

## 來源
[S1](../raw/S1-OpenAI-agents.md) · [S2](../raw/S2-Anthropic-effective-agents.md) · [S3](../raw/S3-LangGraph-workflows-agents.md)
