# Hsie I Hsuan (Toni)

### Senior AI Solutions Architect | Enterprise AI, Agents, RAG & ERP Integration

São Paulo, Brazil · English / Português

[LinkedIn](https://www.linkedin.com/in/hsieihsuan)

## About me

I turn business requirements into AI solutions that connect people, enterprise data, and existing systems.

I have 20+ years of experience in IT, including 15+ years in enterprise technology. My background combines solutions architecture, pre-sales, regional service operations, and ERP integration. Today, my focus is on generative AI, agents, and automation that fit real business workflows.

I work across architecture and implementation: defining the problem, choosing the approach, building a demo, and planning integration and deployment. My enterprise experience includes Oracle Cloud, JD Edwards, and SaaS environments.

## Selected projects

DataTalk, ERP Support Extension and JD Edwards Integration Suite have public repositories linked below. The other projects remain part of my private portfolio, with no public code or demo walkthroughs linked here yet.

### DataTalk - Natural-language analytics for Oracle

[Public repository](https://github.com/hsieihsuan1/enterprise-nl2sql-assistant)

A demo that lets business users ask questions about sales data and see SQL, results, charts, and explanations in a Streamlit interface.

- Oracle Autonomous Database integration, with a local mock dataset for demonstrations.
- SQL validation, table allowlists, and row limits before query execution.
- Separate layers for schema context, query generation, validation, data access, and visualization.

**Stack:** Python, LangChain, Streamlit, Oracle Database, DuckDB, Plotly.

**Architecture focus:** making structured enterprise data accessible while keeping query execution controlled. This is a demo, not a claim of production-grade SQL security.

### ERP Support Extension - AI support inside the application

[Public repository](https://github.com/hsieihsuan1/erp-ai-support-copilot)

A browser extension designed to bring first-level support into ERP screens, using application context and a document-based knowledge base.

- Context-aware assistance for Oracle Fusion, SAP, and Workday web interfaces.
- RAG over company documentation, with an Oracle Autonomous Database backend.
- ServiceNow and Jira integration for escalation to human support.

**Stack:** JavaScript, Python, FastAPI, Gemini, Oracle Autonomous Database, RAG.

**Architecture focus:** connecting AI assistance to existing support workflows, with company-level data separation and escalation paths.

### Oracle AI Data Platform - ERP data and documents in one workspace

A demo that combines JD Edwards data, Oracle Fusion financial records, and internal documents for natural-language queries and semantic retrieval.

- Select AI for natural-language queries and Vector Search for document retrieval.
- Mock ERP and financial data for demonstrations without live customer systems.
- Terraform and provisioning scripts for setting up the demo environment.

**Stack:** Python, Oracle AIDP, Autonomous Database, OCI Object Storage, Terraform, Jupyter.

**Architecture focus:** bringing structured and unstructured enterprise data together, from ingestion to the user interface.

### JD Edwards Integration Suite - ERP through modern interfaces

[Public repository](https://github.com/hsieihsuan1/jde-integration-suite)

The public repository is a cleaned-up, mock-backed version of the IoT map and a stock-lookup command line tool. The Telegram and WhatsApp channels described below are not part of it.

Two demonstrations built around JD Edwards Orchestrator: a multichannel stock-availability bot and an interactive IoT map for equipment movement and meter readings.

- Stock queries through Telegram and WhatsApp, with a reusable integration core.
- Orchestrator endpoints described through OpenAPI contracts.
- Web-based equipment and meter-reading demo.

**Stack:** Python, Flask, JD Edwards Orchestrator, OpenAPI, Telegram, WhatsApp, HTML/CSS/JavaScript.

**Architecture focus:** exposing ERP capabilities through new interfaces without replacing the ERP core.

### AI Solution Builder - From business problem to solution blueprint

An MVP workspace that turns business and functional requirements into editable solution artifacts: technical specifications, implementation approach, security considerations, test strategy, deployment planning, metrics, and improvement plans.

- Guided requirements capture and editable AI-generated sections.
- SQLite persistence and a sample project for local demonstration.
- Gemini integration, with an optional OpenAI-compatible provider and a local fallback.

**Stack:** Next.js, TypeScript, React, SQLite, Gemini.

**Architecture focus:** supporting the early stages of solution design. Authentication, billing, and advanced collaboration are outside the MVP scope.

### AI Financial Manager - Conversational expense tracking

A Telegram assistant for recording income and expenses from text and images, then querying the history stored in Google Sheets.

- LangGraph workflow for extraction, field validation, and transaction recording.
- Configurable keyword rules alongside model-based classification.
- LLM tracing and token/cost instrumentation.

**Stack:** Python, Gemini, LangGraph, Telegram, Google Sheets, LangSmith.

**Architecture focus:** combining deterministic rules and AI extraction in a practical data-entry workflow. This project is presented as expense tracking, not investment advice; any public examples should use synthetic financial data.

### AI Leisure Planner - Context-aware planning

A Telegram assistant that collects location, companions, budget, and preferences to suggest activities, with separate plans for good weather and rain.

- Multi-turn conversation flow and persistent preference memory.
- Weather context and distance-based filtering.
- Scheduled suggestions beyond the initial conversation.

**Stack:** Python, Gemini, LangGraph, Telegram, SQLite, geopy, APScheduler.

**Architecture focus:** stateful conversations, external context, personalization, and scheduled interactions. This is a consumer application illustrating patterns that can also apply to enterprise assistants.

## Technical focus

- **AI:** generative AI, LLM applications, RAG, LangChain, LangGraph, tool-using agents, NL2SQL.
- **Enterprise integration:** JD Edwards Orchestrator, Oracle SaaS, REST APIs, OpenAPI.
- **Cloud and delivery:** OCI, Autonomous Database, Docker, Linux, Terraform.
- **Implementation:** Python, TypeScript/JavaScript, FastAPI, Streamlit, Next.js, Playwright/Puppeteer.

## Connect

For conversations about enterprise AI, solutions architecture, and ERP integration, find me on [LinkedIn](https://www.linkedin.com/in/hsieihsuan).

---

<details>
<summary>Português</summary>

## Sobre mim

Transformo requisitos de negócio em soluções de IA que conectam pessoas, dados corporativos e sistemas existentes.

Tenho mais de 20 anos de experiência em TI, incluindo mais de 15 em tecnologia empresarial. Minha trajetória combina arquitetura de soluções, pré-vendas, operações regionais de serviços e integração de ERP. Hoje, meu foco está em IA generativa, agentes e automação aplicados a processos de negócio.

Atuo da arquitetura à implementação: definir o problema, escolher a abordagem, construir uma demonstração e planejar integração e implantação. Minha experiência enterprise inclui Oracle Cloud, JD Edwards e ambientes SaaS.

## Projetos selecionados

O DataTalk, o ERP Support Extension e o JD Edwards Integration Suite têm repositórios públicos indicados abaixo. Os demais projetos continuam no meu portfólio privado, sem código público ou roteiros de demonstração vinculados aqui por enquanto.

### DataTalk - Analytics em linguagem natural para Oracle

[Repositório público](https://github.com/hsieihsuan1/enterprise-nl2sql-assistant)

Demo para fazer perguntas sobre dados de vendas e visualizar SQL, resultados, gráficos e explicações em uma interface Streamlit. Integra Oracle Autonomous Database e oferece um dataset mock local para demonstração.

O foco de arquitetura é facilitar o acesso a dados estruturados com validação de SQL, tabelas permitidas e limites de consulta. É uma demo, não uma garantia de segurança SQL de produção.

**Stack:** Python, LangChain, Streamlit, Oracle Database, DuckDB e Plotly.

### ERP Support Extension - Suporte com IA dentro do ERP

[Repositório público](https://github.com/hsieihsuan1/erp-ai-support-copilot)

Extensão de navegador para oferecer suporte de primeiro nível no contexto de telas de Oracle Fusion, SAP e Workday. Usa RAG sobre documentação da empresa, backend em Oracle Autonomous Database e integração com ServiceNow/Jira para encaminhar casos ao suporte humano.

O foco de arquitetura é integrar a assistência de IA ao fluxo de suporte existente, com separação de dados por empresa e caminhos de escalonamento.

**Stack:** JavaScript, Python, FastAPI, Gemini, Oracle Autonomous Database e RAG.

### Oracle AI Data Platform - Dados de ERP e documentos em um só workspace

Demo que combina dados de JD Edwards, registros financeiros do Oracle Fusion e documentos internos para consultas em linguagem natural e busca semântica. Usa Select AI, Vector Search, dados mock e provisionamento com Terraform.

O foco de arquitetura é reunir dados estruturados e documentos corporativos, da ingestão à interface de consulta.

**Stack:** Python, Oracle AIDP, Autonomous Database, OCI Object Storage, Terraform e Jupyter.

### JD Edwards Integration Suite - ERP por interfaces modernas

[Repositório público](https://github.com/hsieihsuan1/jde-integration-suite)

O repositório público é uma versão revisada, com dados mock, do mapa IoT e de uma ferramenta de consulta de estoque por linha de comando. Os canais Telegram e WhatsApp descritos abaixo não fazem parte dele.

Duas demonstrações com JD Edwards Orchestrator: bot multicanal de consulta de estoque por Telegram e WhatsApp, e mapa interativo de IoT para movimentação de equipamentos e atualização de medidores. Os endpoints são descritos por contratos OpenAPI.

O foco de arquitetura é expor capacidades do ERP por novas interfaces sem substituir seu núcleo.

**Stack:** Python, Flask, JD Edwards Orchestrator, OpenAPI, Telegram, WhatsApp e HTML/CSS/JavaScript.

### AI Solution Builder - Do problema de negócio ao blueprint

MVP que transforma requisitos de negócio e funcionais em artefatos editáveis: especificação técnica, abordagem de implementação, segurança, testes, planejamento de implantação, métricas e evolução. Inclui persistência em SQLite, projeto de exemplo e integração com Gemini ou provedor compatível com OpenAI.

O foco é apoiar o início do desenho de soluções. Autenticação, billing e colaboração avançada estão fora do escopo do MVP.

**Stack:** Next.js, TypeScript, React, SQLite e Gemini.

### AI Financial Manager - Registro de despesas por conversa

Assistente no Telegram para registrar receitas e despesas a partir de texto e imagens, e consultar o histórico no Google Sheets. Combina regras configuráveis e classificação por IA, com validação de campos, rastreamento de chamadas e instrumentação de tokens/custos.

O foco de arquitetura é automatizar entrada de dados com regras determinísticas e extração por IA. O caso é apresentado como controle de despesas, não aconselhamento de investimentos; exemplos públicos devem usar dados financeiros sintéticos.

**Stack:** Python, Gemini, LangGraph, Telegram, Google Sheets e LangSmith.

### AI Leisure Planner - Planejamento com contexto

Assistente no Telegram que coleta localização, companhia, orçamento e preferências para sugerir atividades, com planos para tempo bom e chuva. Inclui memória de preferências, contexto meteorológico, filtro por distância e sugestões agendadas.

O foco de arquitetura é demonstrar conversas com estado, contexto externo, personalização e interações agendadas. É uma aplicação de consumo com padrões que também podem ser usados em assistentes enterprise.

**Stack:** Python, Gemini, LangGraph, Telegram, SQLite, geopy e APScheduler.

## Foco técnico

- **IA:** IA generativa, aplicações com LLMs, RAG, LangChain, LangGraph, agentes com ferramentas e NL2SQL.
- **Integração enterprise:** JD Edwards Orchestrator, Oracle SaaS, REST APIs e OpenAPI.
- **Cloud e entrega:** OCI, Autonomous Database, Docker, Linux e Terraform.
- **Implementação:** Python, TypeScript/JavaScript, FastAPI, Streamlit, Next.js e Playwright/Puppeteer.

## Contato

Para conversar sobre IA enterprise, arquitetura de soluções e integração de ERP: [LinkedIn](https://www.linkedin.com/in/hsieihsuan).

</details>
