# 🧩 MetaPromptFramework

**MetaPromptFramework** — a pragmatic, modular library of reusable prompt engineering templates and patterns for building reliable, composable, and production-ready LLM interactions. Built for AI builders, product teams, and engineers who want predictable LLM behavior fast.

> **🤖 Model-agnostic:** Works with any modern LLM (OpenAI, Anthropic, Google, Mistral, etc.).

---

## ⚡ TL;DR

* **🎯 Goal:** Make it trivial to design, test, and reuse high‑quality prompts.
* **🚀 Quick start:** Copy a template from `/frameworks/`, fill placeholders, send to your LLM.
* **💡 Why:** Structured prompts = less iteration, fewer hallucinations, better scaling.

---

## 🧱 Frameworks Inside

* 📝 **Prompter-CRAFT** — Context / Role / Action / Format / Target Audience
* 🛰️ **Prompter-MCP** — Layered system, user, directives
* 🧩 **Prompter-MODP** — Modular blocks for reuse & chaining
* 🔍 **Prompter-ReAct** — Reason + Action (tool agent pattern)
* 🧠 **Prompter-CoT** — Chain-of-Thought reasoning
* 🌳 **Prompter-ToT** — Tree-of-Thought exploration
* 🤖 **Prompter-Agent** — Agent orchestration configs
* 🔄 **Prompter-Reflect** — Self-review loops
* 🎭 **Prompter-Persona** — Persona + tone control
* ⚡ **RSIP, Lazy, Compose, PHP** — smaller focused patterns

---

## 🚀 Quick Start (60s)

```bash
# 1. Clone the repo
git clone https://github.com/sathya-py/metapromptframework
cd metapromptframework
```

```python
from pathlib import Path

template = Path('frameworks/Prompter-CRAFT.md').read_text()

prompt = (template
    .replace('[ROLE]', 'Product Manager')
    .replace('[DOMAIN]', 'SaaS billing')
    .replace('[ACTION]', 'write a 1-page spec')
    .replace('[CONTEXT]', 'customer confusion on invoices')
    .replace('[FORMAT]', 'markdown')
    .replace('[TARGET AUDIENCE]', 'engineering & design teams')
)
print(prompt)
```

---

## 🧭 Decision Guide

| 🎯 Goal                           | 🛠️ Pattern   | 💡 Why                           |
| --------------------------------- | ------------- | -------------------------------- |
| 📄 Strictly formatted deliverable | CRAFT         | Role + format + audience clarity |
| 🔍 Transparent reasoning          | CoT / ToT     | Step-by-step or branching logic  |
| ⚙️ Tool/API calls                 | ReAct / Agent | Action + observation loops       |
| 🧩 Pipeline building              | MODP          | Modular block composition        |
| 🔄 Quality iteration              | Reflect       | Self-review improvement          |
| 💡 Creative freedom               | Lazy          | Minimal constraints              |

---

## 📚 Example Gallery

### 📝 CRAFT — Persona Email Generator

**Template:**

```
You are an expert [ROLE] in [DOMAIN].
Your task is to [ACTION].
Context: [CONTEXT]
Provide output in [FORMAT] for [TARGET AUDIENCE].
```

**Example Filled:**

```
You are an expert Product Marketer in SaaS billing...
```

---

### 🔍 ReAct — Search Tool Agent

```
System: You can use [search(query)], [fetch_url(url)].
User: Find the migration guide for X and summarize.
```

---

### 🧠 CoT — Complex Reasoning

```
Explain your reasoning step-by-step, then give the answer.
Question: [YOUR QUESTION]
--
Reasoning:
1.
2.
3.
Final Answer:
```

---

## ✅ Best Practices

* ⚠️ Validate outputs before using
* 🛡️ Avoid PII in templates
* 🔍 Log & instrument prompts for cost, latency, correctness
* 📸 Snapshot test important templates

---

## 🛠️ Roadmap

* 🎯 v0.1.0 — Initial stable set + examples
* 📦 v0.2.0 — CLI renderer, pip module
* 🧪 v1.0.0 — Stable API, docs site, CI tests

---

## 📜 License

MIT — see `LICENSE`

---

## 🙌 Acknowledgements

* Lawton Leams — CRAFT inspiration
* Sathya — Project creator

---

**Last updated:** Suggested version v0.1.0
