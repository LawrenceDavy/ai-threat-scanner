# ai-threat-scanner

> Open-source CLI framework for automated vulnerability testing of LLM-powered applications.

**Status: Active development — v0.1 in progress**

## What this is

A lightweight, extensible security testing framework for teams building with LLMs. Maps findings to OWASP LLM Top 10 (2025) and MITRE ATLAS. Runs locally against Ollama or any OpenAI-compatible endpoint.

## Why this exists

PyRIT is powerful but Azure-centric. Garak is broad but reporting is weak. Promptfoo is QA, not security. There's a gap for a tool that a security team can run in 10 minutes and get actionable findings. This is that tool.

## Roadmap

- [ ] v0.1 — Prompt injection, system prompt extraction, data leakage. CLI + JSON reports. (Weeks 3-6)
- [ ] v0.2 — Multi-turn attack chains, MITRE ATLAS mapping, configurable profiles. (Weeks 7-10)
- [ ] v0.3 — Agent/RAG attacks: indirect prompt injection, tool poisoning. (Weeks 11-16)
- [ ] v1.0 — Plugin architecture, CI/CD integration, PDF reports. (Weeks 17-22)

## Quick start (coming Week 3)
```bash
pip install ai-threat-scanner
ats scan --target http://localhost:11434 --profile owasp-llm-top10
```

## Contributing

Not ready for contributions yet. Watch this repo — first issues will be posted Week 3.

## Author

Lawrence Davy — AI Security researcher. [LinkedIn](YOUR_LINKEDIN_URL)
```

Commit message: `docs: initial project scaffold and roadmap`

**Day 2 — LinkedIn:**

This is your most important sales page. Every hiring manager will look at it. Here's exactly what to write:

**Headline** (220 chars max, this is what shows in search):
```
AI Security Researcher | Building open-source LLM vulnerability testing tools | Red teaming language models | OWASP LLM Top 10
```

**About section** (first 3 lines show before "see more" — make them count):
```
I'm building the tools that security teams need to test LLM-powered applications before attackers do.

My background is 10 years as a professional chef — which sounds irrelevant until you understand that professional kitchens run on systems thinking, zero-tolerance quality standards, and performing under pressure when failure costs real people real things. Those skills transfer directly to security work.

I'm currently building ai-threat-scanner: an open-source CLI framework for automated vulnerability testing of LLM applications, mapped to OWASP LLM Top 10 and MITRE ATLAS. I document everything I learn publicly — techniques, failures, findings.

Technical focus: prompt injection, system prompt extraction, indirect prompt injection in RAG systems, agentic AI security testing.

I'm building in public. If you're working in AI security and want to watch someone go from zero to dangerous in real time, follow along.

GitHub: github.com/LawrenceDavy
```

**Experience:** Keep your chef roles. Retitle the most recent one:
```
Head Chef / Operations Lead — [Restaurant Name]
Managed high-stakes real-time systems under pressure. Built and optimised repeatable processes for quality-critical production environments. Led teams under conditions where failure has immediate, visible consequences. [Keep 2-3 bullet points about actual responsibilities — don't pretend you were doing security]
