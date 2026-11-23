# S2｜Anthropic：Building effective agents

- **來源**：https://www.anthropic.com/research/building-effective-agents
- **發布**：2024-12-19；頁面註記部分工具生態資訊已變更，應以最新文件為準。
- **類型**：官方工程文章。

## 摘要
- 文章區分預先編碼控制路徑的 workflow 與由 LLM 動態決定流程/工具使用的 agent；更廣義的 agentic systems 可涵蓋兩者。
- 建議先用能滿足目標的最簡單解法；Agent 可能以較高延遲與成本換取表現，需要具體權衡。
- 評估者/優化者模式以明確評分標準驅動修正；Agent 應依環境回饋行動，適時回到人類確認，並設定停止條件。

## 限制
此文的概念模式可教學參考；其供應商工具資訊有時效性，不能視為當前工具選型表。
