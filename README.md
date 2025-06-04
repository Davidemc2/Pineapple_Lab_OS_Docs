# 🧠 Modular Prompt Engineering Blueprint

Welcome to the official prompt engineering framework from **Pineapple Labs** — a battle-tested, modular guide for building high-performance AI systems using GPT-4, Claude, and DeepSeek.

---

## 🚀 Overview

This repo provides a production-grade blueprint for designing and scaling **structured, testable prompts** across different LLM platforms. It enables developers, researchers, and product teams to:

- Build **niche AI agents** with strong behavior alignment
- Version and test prompts like code
- Embed prompt memory in systems like OS Brick, LangChain, or MemGPT
- Prevent hallucinations, overgeneration, and prompt drift

---

## 🧱 Architecture

Our system is based on 6 modular components:

1. **System Declaration** – Define role, domain, and tone
2. **Instruction Block** – State the exact task
3. **Logic Flow** – Use chain-of-thought or IF/ELSE logic
4. **Input / Output Segmentation** – Prevent context bleed
5. **Formatting Constraints** – JSON / Markdown / length
6. **Evaluation Clause** – Gracefully handle uncertainty

> 💡 Prompts are treated as structured functions, not just raw text.

---

## 📦 Included Files

| File / Folder         | Purpose                                                |
|-----------------------|--------------------------------------------------------|
| `Prompting_Blueprint_Guide.md` | Core guide to modular prompt engineering             |
| `examples/`            | Domain-specific prompts for finance, law, tech, etc.  |
| `prompt_registry.json` | Optional JSON structure for loading prompts in-code   |
| `CONTRIBUTING.md`     | Contribution guidelines                                |
| `SECURITY.md`         | Prompt injection safety + validation rules             |

---

## 🧑‍💻 Quickstart

1. Clone the repo
2. Use the blueprint to design your first prompt
3. Copy into your LLM stack (OpenAI, Claude, DeepSeek, OS Brick)
4. Evaluate using our checklist
5. Iterate or commit to your `prompt_registry.json`

---

## 📊 Evaluation Checklist

- ✅ Clear instructions
- 🔁 Consistent output (regenerate 3–5x)
- 📎 Correct format and tone
- 🧠 Hallucination-safe
- 🧩 Reusable logic blocks

---

## 📚 Sources & Inspirations

- [Anthropic Claude Prompting Best Practices](https://docs.anthropic.com/claude/prompt-engineering)
- [OpenAI Function Calling & Prompting Docs](https://platform.openai.com/docs)
- [Deepgram Prompt Engineering Masterclass](https://deepgram.com/learn/prompt-engineering-masterclass)
- *Designing Machine Learning Systems* – Chip Huyen
- *Prompt Engineering Guide* – CrossML
- Pineapple Labs internal OS Brick research

---

## 🛡 Security Note

Use `SECURITY.md` to understand prompt injection threats and best practices for LLMs with memory or user-provided inputs.

---

## 🧪 Want to Contribute?

We welcome PRs with:
- New vertical-specific prompts
- Output format validators
- LLM evaluation scripts
- Agent persona blueprints

Read `CONTRIBUTING.md` to learn how.

---

## 🧬 Part of the Pineapple Labs White Paper System

This project is the seed of our open-source research initiative into secure, memory-retaining, modular AI agents. Expect future white papers, research tools, and API integrations.

> Designed by OS Brick. Powered by prompt composability. Built for real systems.

---
