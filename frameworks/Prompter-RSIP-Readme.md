# Prompter-RSIP

## Description

Prompter-RSIP stands for Role, Structure, Intent, and Purpose. This technique ensures that every prompt you issue to an LLM has clarity, task focus, and alignment with a higher-level goal.

## Why Use It

Most prompts only focus on what needs to be done (Intent). RSIP forces you to also define *how* to respond (Structure), *who* the model is pretending to be (Role), and *why* the task matters (Purpose). This drastically improves the quality and consistency of output across creative, technical, and analytical tasks.

## Examples

### 📌 Example 1 — Technical Debug Assistant

Role: You are a Linux systems expert.  
Structure: Return output in bullet points grouped by `Error`, `Cause`, and `Fix`.  
Intent: Analyze this log and find the root issue.  
Purpose: This is to reduce server downtime during deployment.

---

### 📌 Example 2 — Marketing Copy Generator

Role: You are a witty copywriter for a Gen Z skincare brand.  
Structure: Output 3 product taglines, each under 15 words.  
Intent: Create catchy headlines for a moisturizer campaign.  
Purpose: To improve CTR for our August social media push.

## Tip

RSIP works great when you’re writing prompts for others (teams, clients, agents). It builds guardrails and teaches the *why* along with the *what*.
