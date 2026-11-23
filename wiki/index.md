# Wiki 索引｜AI Agents 入門

## 主題簡介
AI Agent 是能用 LLM 規劃或推進多步任務，並透過工具或環境回饋取得新資訊/採取行動的系統。本 Wiki 從初學者角度介紹 Agent 的組成、工具呼叫、行動—觀察循環、工作流程差異與可靠性界線。定義依來源與語境整理，不宣稱只有一種標準定義。[S1][S2][S3][S4]

## 需求決策
- **讀者**：Agent 新手；繁體中文教學。
- **範圍**：概念、工具使用、ReAct、workflow vs agent、評估與停止條件。
- **資料**：五份 AI Agents 原始/官方資料，逐筆 ingest，簡報引用可回查。
- **形式**：Markdown 知識庫與 10 張可離線瀏覽 HTML deck。
- **檢查**：來源追溯、觀點語境、每頁引用、結構及可讀性。

## 知識頁
- [AI Agent 基本概念](01-agent-basics.md)
- [工具呼叫與外部行動](02-tools-and-actions.md)
- [Agent 的運作循環與 ReAct](03-agent-loop-react.md)
- [Workflow、Agent 與多 Agent 模式](04-workflows-and-agents.md)
- [評估、限制與可靠性](05-reliability.md)

## 五筆已 ingest 來源
- [S1 OpenAI Agents](../raw/S1-OpenAI-agents.md)
- [S2 Anthropic Building effective agents](../raw/S2-Anthropic-effective-agents.md)
- [S3 LangGraph Workflows and agents](../raw/S3-LangGraph-workflows-agents.md)
- [S4 ReAct paper](../raw/S4-ReAct-paper.md)
- [S5 Toolformer paper](../raw/S5-Toolformer-paper.md)

## 概念連結
LLM + 任務/狀態 + 工具 + 控制流程 → 多步行動 → 觀察工具結果 → 更新下一步 → 評估/停止。Workflow 預先固定步驟；Agent 動態決定部分行動；兩者可組合，選擇取決於任務不確定性與風險。
