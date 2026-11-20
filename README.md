# Paris Arcos

**AI Engineer & Technical Lead · Production AI agents, RAG and cloud delivery**

I build AI assistants that use product context and tools, and lead software delivery from technical discovery through rollout. I'm interested in AI Engineer, Technical Lead and Forward Deployed Engineer roles, working remotely from the Canary Islands.

[LinkedIn](https://www.linkedin.com/in/paris-arcos-martin/)

## Selected projects

### [Economicón — FinOps assistant](https://github.com/EconomiconFinOps/tfm-economicon)

A collaborative project for querying Azure cloud costs and internal documents with citations. I led delivery of the RAG chat and designed structure-aware chunking, hybrid search with reciprocal rank fusion (RRF), tenant isolation, and privacy and spend controls with LiteLLM. I validated how the assistant responds, asks for clarification or abstains when evidence is incomplete.

[Run locally](https://github.com/EconomiconFinOps/tfm-economicon#como-correrlo) · [28-case evaluation suite](https://github.com/EconomiconFinOps/tfm-economicon/blob/main/docs/validation/README.md) · [Evaluation dashboard and results](https://github.com/EconomiconFinOps/tfm-economicon/blob/main/docs/validation/evaluation-dashboard.md)

### [PARES — AI architecture for historical archives](https://github.com/ParisArcos/pares-architecture)

A reference design for turning 16th-century scans into searchable records with citations to individual folios. SQL retrieves all supported facts and their citations. Vector search adds related context. The design includes human review and rechecks access before serving a PDF.

### [Dialogflow — Roadside assistance voice assistant](https://github.com/ParisArcos/dialogflow)

A voice prototype for checking coverage and requesting a simulated tow truck. Dialogflow ES handles the conversation and FastAPI validates coverage and confirmation. Gemini answers separate policy questions using text extracted with Tesseract.

## Professional experience

- **Athlera.** Led a four-person team and built AI components and integrations for a Next.js product. The assistants used LangChain, LangGraph and the OpenAI API, with on-screen context, user data and tools.
- **Ludus.** Led the three-person web team. Compared technical options with management, estimated costs and delivery timelines, and turned decisions into implementation plans. Unified access to four platforms and led the migration from AWS EC2 to Azure with automated deployments and rollbacks.
- **isEazy.** Analysed a Next.js platform and Amazon Bedrock components. Designed prompts and specified workflows for generating training materials with quality checks and human review.

## How I deliver with agents

I adapted a development harness that takes changes from OpenSpec and Trello through implementation, independent technical review and functional validation. I use MCP and role-specific skills to give agents the tools they need, keep context in the repository, Notion and Engram, and use GitHub checks and Tempo measurements to verify delivery and track time and token usage.
