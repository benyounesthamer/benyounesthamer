## Hi, I'm Thamer 👋

Final-year **AI & Data Science engineering student** in Tunisia, building **LLM agents for software quality and banking compliance**.

I like AI systems that can be checked: agents whose actions are grounded in what they observe, answers that cite their sources, and benchmarks that report the misses as well as the hits.

### Featured projects

**[agentic-qa](https://github.com/benyounesthamer/agentic-qa)**: an AI agent that tests web apps like a QA engineer
- Explores a realistic online-banking app, writes Playwright tests from a user story, runs them and repairs its own failures
- Reports real application bugs with its reasoning and a screenshot, and never weakens a test to make it pass
- Found an unplanted security defect in its own demo app (account balances visible via the Back button after logout)
- `LangGraph` `Playwright` `pytest` `FastAPI`

**[bank-compliance-assistant](https://github.com/benyounesthamer/bank-compliance-assistant)**: compliance gap analysis and cited answers on Tunisian banking regulation · [demo](https://huggingface.co/spaces/Thaamer/bank-compliance-assistant)
- Checks a bank's internal policy against a central-bank circular, obligation by obligation: found 17 of 17 planted gaps, with every piece of evidence verified against the policy
- Hybrid search (BM25 + multilingual embeddings + reranking) in French, English and Arabic: right article first for 86% of questions, up from 55% with keywords alone
- `RAG` `FastAPI` `fastembed` `Groq`

**[mfi-warehouse-mcp](https://github.com/benyounesthamer/mfi-warehouse-mcp)**: a safe MCP server that lets AI agents analyse a microfinance data warehouse
- Read-only by design: SQL parser, table allowlist and a locked database connection, tested against 25 attacks
- A semantic layer of official KPIs (PAR30, PAR90, write-offs) took a model from 5 to 13 correct answers out of 14 on KPI questions
- `MCP` `DuckDB` `sqlglot` `pytest`

### Experience
- **Business Intelligence intern, ADVANS Tunisie (microfinance)**: ETL with SSIS, data warehouse, Power BI risk dashboards
- **Founder, Atlas Group**: websites and automation for beauty and wellness brands

### Stack
`Python` `LangGraph` `RAG` `MCP` `Playwright` `pytest` `FastAPI` `SQL` `DuckDB` `Power BI` `GitHub Actions`

### Find me
[LinkedIn](https://www.linkedin.com/in/thamer-benyounes) · Open to a **6-month end-of-studies internship (PFE)** in AI engineering · Tunisia, France or remote
