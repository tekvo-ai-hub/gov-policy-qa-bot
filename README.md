# Policy Document Q&A Bot

**Industry:** Government

**Repository:** [tekvo-ai-hub/gov-policy-qa-bot](https://github.com/tekvo-ai-hub/gov-policy-qa-bot)

## Description
A privacy-centric Q&A tool for navigating internal policy guidance.

## Requirements
### Functional
- Upload internal documents.
- Answer regulation-based queries.
- Show source citations.
### Non-Functional
- Air-gapped compatibility.
- Multi-department use.
- Simple interface.
## Solution Design
**LLM:** LLaMA 3 Instruct
**Vector DB:** Qdrant

### Components
- Uploader
- Vector Search
- Citation Generator
- Q&A Responder
### Data Flow
$ PDF → Embed → Search → Prompt → LLM → Response

### Tech Stack
- **Frontend:** Angular
- **Backend:** NestJS
- **Storage:** MongoDB
- **Deployment:** On-prem Kubernetes
