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

## 🧠 Advanced Meta-Prompt Library

Each of the following prompt styles comes with its own `.md` and `-ReadMe.md` file inside the `/frameworks/` folder, providing structure, flow, and real examples.

| Name               | Description                                             |
| ------------------ | ------------------------------------------------------- |
| `Prompter-RSIP`    | Role-Structure-Intent-Purpose for concise, scoped tasks |
| `Prompter-ToT`     | Tree-of-Thought reasoning to branch ideas recursively   |
| `Prompter-ReAct`   | Reasoning + Acting hybrid prompts with tool hooks       |
| `Prompter-CoT`     | Chain-of-Thought step-by-step reasoning prompts         |
| `Prompter-Lazy`    | One-liner prompts designed for maximal model freedom    |
| `Prompter-Agent`   | Modular agent prompting blueprint with behavior configs |
| `Prompter-Reflect` | Iterative self-reviewing prompt cycles for improvement  |
| `Prompter-PHP`     | Prompt Hooks Protocol — injection-ready prompt wrappers |
| `Prompter-Compose` | Prompt composability pattern for nesting & flow         |
| `Prompter-Persona` | Persona-driven prompts to guide behavior + tone         |

All files follow the `Prompter-XXXX.md` + `Prompter-XXXX-ReadMe.md` format for easy use and git-friendly integration.

---

## 🚀 Use Cases

* AI agents & co-pilots
* RAG-powered workflows
* Context-rich automation systems
* Developer tools & prompt chaining
* Scalable knowledge assistants
* 🧪 LLM behavior testing and iteration

---

## 📂 Project Structure

```plaintext
📁 MetaPromptFramework/
├── README.md
├── LICENSE
└── frameworks/
    ├── Prompter-CRAFT.md
    ├── Prompter-MCP.md
    ├── Prompter-MODP.md
    ├── Prompter-RSIP.md
    ├── Prompter-ToT.md
    ├── Prompter-ReAct.md
    ├── Prompter-CoT.md
    ├── Prompter-Lazy.md
    ├── Prompter-Agent.md
    ├── Prompter-Reflect.md
    ├── Prompter-PHP.md
    ├── Prompter-Compose.md
    ├── Prompter-Persona.md
    ├── Prompter-CRAFT-ReadMe.md
    ├── Prompter-MCP-ReadMe.md
    ├── ... (rest of ReadMe files)
```

---

## 📄 License

This project is licensed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.

---

## 🙌 Acknowledgements

* **Lawton Leams** – Creator of the CRAFT prompt model ([YouTube](https://youtu.be/ABCqfaTjNd4))
* **Sathya** – Architect and maintainer of the MetaPromptFramework
* **ChatGPT** – AI co-pilot for documenting and structuring this prompt framework journey