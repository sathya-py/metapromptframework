# Prompter-Agent

Prompter-Agent is a prompt engineering blueprint for simulating or orchestrating **autonomous agents** within a single or multi-step LLM interaction. It’s designed to emulate multi-role behaviors such as planners, executors, critics, or memory nodes — with modular task prompts and controlled output structure.

This meta-pattern works well in:
- Agent-based architectures (LLM + tools)
- Simulations (NPCs, advisors, committee roles)
- Self-planning LLM loops
- Interactive personas with memory

## Core Elements

1. **Agent Identity** – Define who this agent is (role, domain, behavior)
2. **Agent Task** – The specific thing this agent is responsible for
3. **Input Context** – What the agent knows, sees, or remembers
4. **Response Format** – Controlled or composable output structure
5. **Inter-Agent Hooks** – Optional outputs meant to be passed to other agents

## Template

Agent Name: [Identifier or role]  
Domain: [Expertise or specialization]  
Task: [Clear responsibility or function]  
Input: [Context, data, or question]  
Constraints: [Style, structure, or limitations]  
Output Format: [Optional JSON, markdown, or bullet pattern]

## Example

Agent Name: ReviewerBot9000  
Domain: Software Engineering  
Task: Review the following code for security issues.  
Input: Python code snippet  
Constraints: Be critical but constructive. Highlight only major issues.  
Output Format:  
- Issues Found  
- Severity  
- Recommendation
