# MetaPromptFramework

**MetaPromptFramework** is a curated collection of reusable, modular prompt engineering templates for building better, smarter, and more adaptable AI interactions. Designed for advanced users, AI builders, and automation engineers, this repo provides highly structured patterns for LLMs like OpenAI GPT-4, Claude, Gemini, and Mistral.

> ⚠️ Model-Agnostic: All frameworks are compatible across most modern LLMs that accept natural language prompts.

---

## 🧱 Included Prompt Frameworks

### 🧠 Prompter-CRAFT  
A prompt design method focused on **Context**, **Role**, **Action**, **Format**, and **Target Audience**. Helps eliminate ambiguity while producing structured, purpose-driven prompts.  
**Credit**: Based on the work of [Lawton Leams](https://youtu.be/ABCqfaTjNd4)

**Usage Example**:
```plaintext
You are an expert [ROLE] in [DOMAIN].  
Your task is to [ACTION].  
The context is: [CONTEXT].  
Please provide your response in [FORMAT] format, tailored for [TARGET AUDIENCE].
````

---

### 📡 Prompter-MCP (Model Context Protocol)

Designed to give the model **layered context**, this protocol separates system roles, task logic, user goals, and response structure to guide complex LLM tasks.

**Usage Example**:

```plaintext
### System Context
You are acting as a [ROLE] to assist with [PROJECT/USE CASE].

### Operational Directives
- Follow [N] logical steps
- Prioritize clarity and modularity

### User Intent
The user wants: [GOAL STATEMENT]

### Response Meta
Respond in [FORMAT]. Include [X] if relevant.
```

---

### 🔧 Prompter-MODP (Modular Prompt Design Protocol)

A composable pattern for building **plug-and-play prompt blocks** — great for reuse, automation, and chaining LLM steps.

**Usage Example**:

```plaintext
# INTENT
[Describe the purpose clearly]

# INPUT
[Insert data or background]

# TRANSFORM
[Steps, logic, or structure]

# OUTPUT
[Formatting & tone]

# POSTOPS
[Follow-ups, chaining, reuse notes]
```

---

## 🚀 Use Cases

* AI agents & co-pilots
* RAG-powered workflows
* Context-rich automation systems
* Developer tools & prompt chaining
* Scalable knowledge assistants

---

## 📄 License

This project is licensed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.

---

## 🙌 Acknowledgements

* **Lawton Leams** – Original creator of the CRAFT prompt model [YouTube](https://youtu.be/ABCqfaTjNd4)
* **Sathya** – Architect and maintainer of the MetaPromptFramework
* **ChatGPT** – AI co-pilot for designing and documenting this framework

---

> Fork it. Star it. Use it. Or just steal ideas like an artist — this repo’s built to be remixed. 😉

````

