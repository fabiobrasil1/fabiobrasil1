# Fabio Brasil

**Backend Engineer** · Cloud & AI · Florianópolis, Brasil

Construo APIs e sistemas distribuídos, e a camada em volta de modelos: servidores MCP, RAG híbrido e **guardrails de decisão** que o código consome. Trabalho com Python e TypeScript, clean architecture e observabilidade na Azure.

Atualmente em [Dataside](https://github.com/fabiobrasil1). O que está no GitHub é estudo, PoC e ferramenta pessoal — não código de cliente.

[LinkedIn](https://www.linkedin.com/in/fabiobrasil/) · [fabiobfelix6@gmail.com](mailto:fabiobfelix6@gmail.com)

---

## Em destaque

Projetos escolhidos a partir do código público (não scaffolds de tutorial).

| Repo | O que é | Stack no código |
| --- | --- | --- |
| [Noulgate](https://github.com/fabiobrasil1/Noulgate) | Guardrail desacoplado: qualquer sistema pergunta se uma ação pode seguir; Jev (TypeSafe) julga, o código devolve `allow` / `deny` / `review`. | Python, Jev, política determinística |
| [azure-observability-mcp-server](https://github.com/fabiobrasil1/azure-observability-mcp-server) | Servidor MCP que consulta Application Insights / Azure Monitor com tools semânticas — o LLM não escreve KQL. | Python, MCP, Azure, Entra ID |
| [hybrid-rag-excel-analyst](https://github.com/fabiobrasil1/hybrid-rag-excel-analyst) | RAG híbrido em planilha: linguagem natural + cálculo real (pandas/DuckDB), não só busca vetorial. | Python, FastAPI/Streamlit, DuckDB, ChromaDB, OpenAI |
| [mcp-log-agent](https://github.com/fabiobrasil1/mcp-log-agent) | API NestJS instrumentada para App Insights: `correlationId`, logs JSON, telemetria alinhada ao MCP de logs. | NestJS, TypeScript, Azure Application Insights |
| [distributed-inventory-fastapi](https://github.com/fabiobrasil1/distributed-inventory-fastapi) | Estoque distribuído com escrita local, sync LWW, idempotência, ports/adapters e testes. | FastAPI, Docker, pytest |

---

## Stack (o que aparece nos repos)

**Backend:** Python · FastAPI · Pydantic · NestJS · TypeScript · Node.js

**Dados:** PostgreSQL · pandas · DuckDB

**Cloud e ops:** Azure (App Insights, Log Analytics, Entra ID) · Docker · logs estruturados

**IA aplicada:** MCP · RAG híbrido · embeddings/ChromaDB · Jev (decisão tipada, não chat)

Também há trabalho mais antigo em Nest + RabbitMQ, Django, Spring e Flutter — scaffolds e estudos, não a vitrine atual.

---

## GitHub

![GitHub stats](https://github-readme-stats.vercel.app/api?username=fabiobrasil1&show_icons=true&theme=transparent&hide_title=true)
![Top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=fabiobrasil1&layout=compact&langs_count=6&theme=transparent&hide_title=true)

---

*Building systems where models judge, code decides, and APIs stay observable.*
