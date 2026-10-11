# Fabio Brasil

**Senior AI Engineer** · Agents, RAG & LLM platforms · Florianópolis, Brasil

Desenho e entrego sistemas de IA em produção: agentes com **LangGraph**, orquestração **LangChain**, **RAG** híbrido, **MCP**, **OpenAI SDK** e observabilidade (**Datadog**, Azure Monitor). Backend sênior em Python e TypeScript — o modelo não substitui arquitetura, contrato nem política.

Faço o caminho inteiro: ingestão → retrieval → tool calling → guardrail → telemetria. O LLM gera ou classifica; o código autoriza, mede e falha de forma previsível.

[LinkedIn](https://www.linkedin.com/in/fabiobrasil/) · [fabiobfelix6@gmail.com](mailto:fabiobfelix6@gmail.com)

---

## Foco

- **Agentes** — grafos LangGraph, tools tipadas, estado explícito, human-in-the-loop quando a ação é destrutiva.
- **RAG** — embeddings + retrieval semântico combinados com SQL/pandas (não é só buscar trecho em vector store).
- **MCP** — tools semânticas para IDE/agente consultar logs, dados e APIs sem KQL/SQL solto.
- **Guardrails** — decisão estruturada (`allow` / `deny` / `review`) antes de tool, resposta ou publicação.
- **Observabilidade** — traces, correlation id, latência, erro e custo no Datadog e no Application Insights.
- **Plataforma** — FastAPI, NestJS, clean architecture, Docker, Azure.

O GitHub público é recorte de estudo e PoC. Código de cliente não está aqui.

---

## Stack

| Camada | Ferramentas |
| --- | --- |
| LLMs & SDK | OpenAI SDK, modelos GPT, integrações com LLMs de provedor |
| Agentes | LangGraph, LangChain, tool calling, MCP servers |
| RAG | embeddings, vector store, hybrid retrieval, DuckDB/pandas, ChromaDB |
| Guardrails | políticas determinísticas, Jev/TypeSafe (decisão tipada) |
| Observability | Datadog, Azure Application Insights, Log Analytics, logs JSON, correlation id |
| Backend | Python, FastAPI, Pydantic, NestJS, TypeScript, Node.js |
| Dados | PostgreSQL, DuckDB, pandas |
| Cloud | Azure (Entra ID, App Insights), Docker, APIs REST |

---

## Projetos

| Repo | O que é |
| --- | --- |
| [Noulgate](https://github.com/fabiobrasil1/Noulgate) | Guardrail desacoplado para agentes e tools — Jev julga, o código decide `allow` / `deny` / `review`. |
| [azure-observability-mcp-server](https://github.com/fabiobrasil1/azure-observability-mcp-server) | MCP de observabilidade: tools semânticas sobre App Insights/Azure Monitor, sem expor KQL cru. |
| [hybrid-rag-excel-analyst](https://github.com/fabiobrasil1/hybrid-rag-excel-analyst) | RAG híbrido + OpenAI: linguagem natural sobre planilha com cálculo real (DuckDB/pandas). |
| [mcp-log-agent](https://github.com/fabiobrasil1/mcp-log-agent) | NestJS instrumentado para diagnóstico: Application Insights, `correlationId`, logs estruturados. |
| [distributed-inventory-fastapi](https://github.com/fabiobrasil1/distributed-inventory-fastapi) | Estoque distribuído: LWW, idempotência, ports/adapters, Docker, testes. |

---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=fabiobrasil1&show_icons=true&theme=transparent&hide_title=true)
![Top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=fabiobrasil1&layout=compact&langs_count=6&theme=transparent&hide_title=true)
