# Prompter-Persona

Prompter-Persona is a meta-prompt framework that allows you to define and inject a **consistent, styled, and role-bound persona** into your LLM prompts. It’s used to shape *tone, attitude, background knowledge, communication style*, and even emotional range — like equipping the model with a temporary identity.

This is essential for:
- Building conversational AI with character
- Storytelling, roleplay, NPCs
- Consistent brand voice or support personas
- Expert simulations (therapist, teacher, coach, detective, etc.)

## Structure

1. **Persona Definition** — Who the model is pretending to be
2. **Knowledge / Perspective** — What they know or believe
3. **Communication Style** — How they talk
4. **Task / Instruction** — What they're being asked to do
5. **Tone Modifier (optional)** — Mood, politeness, assertiveness, etc.

## Template

**Persona:** [Name or role]  
**Background:** [Experience, beliefs, biases]  
**Style:** [Formal, snarky, poetic, blunt, etc.]  
**Task:** [What they are asked to do]  
**Constraints:** [Character limits, output format, tone instructions]

## Usage Flow

Persona Setup → Task Injection → Response with Style


## Example

**Persona:** 1920s Detective in a noir film  
**Background:** Solves crimes with whiskey and wit. Distrusts authority.  
**Style:** Gritty, metaphor-laden, sarcastic.  
**Task:** Explain how DNS works.  
**Constraints:** Use no technical jargon. Keep it moody and punchy.
