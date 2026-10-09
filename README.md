# Hi, I'm Santiago 👋

Cloud & Automation Engineer with hands-on experience in RPA, digital transformation, and AI-assisted automation. I worked at **Continental** as an Operational Efficiency Intern, building end-to-end RPA workflows (UiPath) and AI-powered document processing for Finance and Operations. These days I build AI agents on **Google ADK and GCP**, and keep going deeper into n8n and local-first AI automation — which is what this portfolio is about.

I care about automations that are actually production-minded: input validation, explicit error handling, and — whenever it makes sense — keeping data local instead of shipping it to a third-party API. Background in Software Development Engineering (Universidad TecMilenio, Mexico) with an exchange semester in Computer Science at Kaunas University of Technology, Lithuania.

## Projects

| Project | Description | Stack |
|---|---|---|
| [guardian-devsecops](https://github.com/SantiagoE-n/guardian-devsecops) | DevSecOps platform with memory. Scans every pull request for vulnerabilities and investigates production incidents on its own — then correlates both through a shared vector store, flagging outages that an unattended security warning could have prevented. Every model runs locally. | n8n · Qdrant · Ollama · Docker · GitHub Actions · Trivy |
| [counterflow-pos](https://github.com/SantiagoE-n/counterflow-pos) | Point-of-sale & inventory platform for small retail stores — a genericized portfolio copy of a real client project, same architecture and code running in production. | FastAPI · React/TypeScript · Tauri |
| [n8n-telegram-rag-agent](https://github.com/SantiagoE-n/n8n-telegram-rag-agent) | Telegram chatbot with real RAG: documents are chunked, embedded, and stored in a self-hosted Qdrant vector database, then retrieved on demand via tool calling — same local-first philosophy, built to actually scale past a single small document. | n8n · Qdrant · Ollama Embeddings · Telegram Bot API |
| [n8n-local-pdf-agent](https://github.com/SantiagoE-n/n8n-local-pdf-agent) | AI agent that answers questions about PDF documents using a 100% local LLM (Ollama) — no data leaves the machine. Includes full error handling with correct HTTP status codes per failure type. | n8n · Webhook · AI Agent · Ollama |
| [n8n-lead-capture-airtable](https://github.com/SantiagoE-n/n8n-lead-capture-airtable) | Business automation, no AI involved: a lead capture form gets validated, saved to Airtable via a real OAuth2 integration, and the team gets notified on Telegram instantly. | n8n · Webhook · Airtable (OAuth2) · Telegram |

## Stack

**Automation & AI:** n8n · UiPath (Studio & Orchestrator) · Google ADK · LangChain (via n8n AI Agent) · Ollama · Qdrant · Webhooks & REST APIs · OAuth2
**Development:** Python (FastAPI) · C# · JavaScript/TypeScript/React · Tauri · SQL
**DevOps & Cloud:** Docker & Compose · GitHub Actions · Trivy · AWS (EC2, S3, Lambda, Athena) · GCP (Cloud Run, Cloud build, FireStore)

## Certifications

- UiPath Automation Developer
- AWS Data Engineering
- UiPath Academy Specialized AI Associate Training
- Cisco Introduction to Cybersecurity

## What I'm working on now

Going deeper into DevSecOps and agent architectures — most recently Guardian, plus AI agents built on Google ADK. Next up: moving the n8n workflows off a tunnel onto real infrastructure, and tightening access control across the existing projects.

## Contact

[LinkedIn](https://www.linkedin.com/in/santiago-aar%C3%B3n-enr%C3%ADquez-oros-567294251/) · [santiagoenriquez001@icloud.com](mailto:santiagoenriquez001@icloud.com)
