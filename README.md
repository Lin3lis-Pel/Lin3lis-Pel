### Hi, I'm Linas Peleckas 👋

I'm an applied AI engineer. I build LLM agents and RAG systems that are evaluated, traced and deployed, with a focus on **finance**.

**Previously:** debt capital markets at a Lithuanian bank (12+ bond issuances, €170M+), financial risk (Python Monte Carlo VaR) and investment analysis (Airbyte → BigQuery → dbt pipelines). Now studying Data Science & AI Engineering at Turing College.

<a href="https://www.linkedin.com/in/linas-peleckas-90a7a9184/"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

---

#### What I've built

- 🛡️ [**gcp-infra-review-agent**](https://github.com/Lin3lis-Pel/AI_Agents): a LangGraph agent that reviews Terraform before `apply`. It checks security, estimates cost and runs agentic RAG over the GCP docs, with a human-in-the-loop step. It runs over MCP for coding agents and has a web UI for people.
- 🎬 [**movie-research-copilot**](https://github.com/Lin3lis-Pel/RAG) ([live](https://ai-devops-508221.web.app)): hybrid RAG (pgvector + full-text + RRF) over 10k critic reviews, with SQL tools served over MCP and a 49-question eval set. FastAPI on Cloud Run.
- 🍳 [**fridge-agent**](https://github.com/Lin3lis-Pel/Fridge2Fork) ([live](https://fridgeagent-30975867572.europe-north1.run.app)): a four-agent vision workflow that turns photos of a fridge into recipes. Runs on Vertex AI or local Ollama.
- 📈 [**nvda-rl-trading**](https://github.com/Lin3lis-Pel/RL_TC): market-regime discovery (k-means, PCA) plus Q-learning and PPO trading agents, compared with buy-and-hold.

**Stack:** Python · LangChain / LangGraph · MCP · FastAPI · PostgreSQL + pgvector · Next.js · Docker · Google Cloud Run · LangSmith
