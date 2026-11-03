```
  ██████╗ ███████╗ ██████╗  ██╗
  ╚════██╗██╔════╝██╔═████╗███║
   █████╔╝███████╗██║██╔██║╚██║
  ██╔═══╝ ╚════██║████╔╝██║ ██║
  ███████╗███████║╚██████╔╝ ██║
  ╚══════╝╚══════╝ ╚═════╝  ╚═╝
```

**Local-first RAG systems & LLM evaluation.**
Building RAG systems is easy. Knowing if they actually work is hard — that's what I work on.

### `> whoami.yml`
```yaml
name: Abdel
role: AI Engineer — local-first RAG & LLM evaluation
based: Lyon, France
status: Available — freelance or full-time

focus:
  - On-premise / local LLM systems (no data leaves the building)
  - RAG evaluation, benchmarking & CI quality gates
  - Multi-agent systems in production
```

---

### `> cat flagship/ragnarok-ai.md`

[![PyPI](https://img.shields.io/pypi/v/ragnarok-ai?color=blue)](https://pypi.org/project/ragnarok-ai/)
[![Stars](https://img.shields.io/github/stars/2501Pr0ject/RAGnarok-AI?style=flat)](https://github.com/2501Pr0ject/RAGnarok-AI)
[![License](https://img.shields.io/badge/license-AGPL--3.0-green)](https://github.com/2501Pr0ject/RAGnarok-AI/blob/main/LICENSE)

**[RAGnarok-AI](https://github.com/2501Pr0ject/RAGnarok-AI)** — a lightweight, local-first framework to evaluate RAG pipelines. 100% local, no API keys required.

- **Retrieval & generation metrics** — precision, recall, MRR, NDCG, faithfulness, relevance, hallucination
- **Local LLM-as-judge** — Prometheus 2 via Ollama, calibrated against your own labels
- **Built for real pipelines** — checkpointing, CLI, Qdrant / Chroma / FAISS / pgvector, LangChain / LlamaIndex / DSPy
- **CI quality gate** — [GitHub Action](https://github.com/2501Pr0ject/ragnarok-evaluate-action) that flags RAG regressions on every PR
- **Community-driven** — external contributors, including a domain-specific medical mode

```bash
pip install ragnarok-ai
ragnarok evaluate --demo
```

---

### `> ls -la projects/`

| Project | What it is | Stack |
|---------|-----------|-------|
| [**RAGnarok-AI**](https://github.com/2501Pr0ject/RAGnarok-AI) | Local-first RAG evaluation framework (PyPI) | Python, Ollama, Prometheus 2 |
| [**RustSensei**](https://github.com/2501Pr0ject/RustSensei) | 100% local assistant to learn Rust in French, evaluated release by release | llama.cpp, RAG, Apple Silicon |
| [Space Coders Agency](https://2501project.dev/projects/space-coders-agency) | EdTech platform orchestrating 9 specialized agents | LangGraph, RAG, Redis, React |
| [DontREADME](https://github.com/2501Pr0ject/DontREADME) | RAG chatbot for PDF / DOCX document analysis | Mistral AI, ChromaDB |
| [Plateforme Iliad](https://2501project.dev/projects/plateforme-iliad) | Analytics platform for training data | DBT, Prefect, Angular |
| [Homelab](https://2501project.dev/projects/homelab) | Self-hosted infra on Raspberry Pi 5 (hosts my portfolio) | Docker, Grafana, Cloudflare |

### `> cat stack.json`

```json
{
  "local_llm": ["Ollama", "llama.cpp", "Fine-tuning"],
  "rag": ["LangChain", "LangGraph", "Qdrant", "pgvector", "ChromaDB", "FAISS", "BM25", "Redis"],
  "evaluation": ["RAGnarok-AI", "LLM-as-judge", "CI quality gates"],
  "languages": ["Python", "TypeScript", "Bash", "SQL"],
  "data": ["DBT", "Prefect", "DuckDB", "PostgreSQL", "MongoDB"],
  "devops": ["Docker", "GitHub Actions", "Cloudflare", "Nginx"]
}
```

### `> curl contact.json`

```json
{
  "portfolio": "https://2501project.dev",
  "huggingface": ["https://huggingface.co/The2501Pr0ject", "https://huggingface.co/ragnarok-ai"],
  "linkedin": "https://www.linkedin.com/in/abdelatif-touati-428808305/"
}
```

![Snake animation](https://raw.githubusercontent.com/2501Pr0ject/2501Pr0ject/output/github-snake-dark.svg)
