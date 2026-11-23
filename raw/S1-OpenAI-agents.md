# S1｜OpenAI API：Agents

- **來源**：https://developers.openai.com/api/docs/guides/agents
- **類型**：官方開發文件；查閱日期 2026-11-23。

## 摘要
- OpenAI 文件將 Agents 說明為能用工具規劃/完成任務、與其他 agent 合作並在步驟間維持上下文的系統。
- 文件提醒依需求選執行環境；Agents API、Agents SDK 與 Responses API 的管理責任、執行環境、狀態保存方式不同。
- SDK runner 負責 agent loop 和 handoffs；應依使用的 runtime 查對應 state/session 規則。

## 限制
這是特定供應商的產品文件，API 和功能會變動；本 Wiki 只取一般概念，不把介面細節當通用定義。
