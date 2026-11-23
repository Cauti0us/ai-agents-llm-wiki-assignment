# S3｜LangChain：LangGraph Workflows and agents

- **來源**：https://docs.langchain.com/oss/python/langgraph/workflows-agents
- **類型**：官方框架文件；查閱日期 2026-11-23。

## 摘要
- 文件將 workflow 描述為有預定程式路徑、按特定順序運作；agents 則動態決定自己的流程與工具使用。
- workflow/agent 都可用 LLM、工具呼叫、結構化輸出與短期記憶組合。
- 常見 pattern 包含 prompt chaining、routing、parallelization、orchestrator-worker、evaluator-optimizer；後者在生成與評估間循環，直到達到接受標準。

## 限制
這是 LangGraph 的模式指南，不代表其分類是唯一標準；本 Wiki 使用它作為具體框架說明，不推論所有 Agent 都用 LangGraph 實作。
