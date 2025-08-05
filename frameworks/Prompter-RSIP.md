# Prompter-RSIP

Prompter-RSIP is a structured prompting technique that defines four core components:

- **Role**: Who or what the LLM should emulate
- **Structure**: The format or layout of the desired response
- **Intent**: What the prompt is asking the LLM to do
- **Purpose**: The higher-level reason or end goal behind the prompt

## Template

You are a [Role].

Structure your response as follows: [Structure].

Your task is to: [Intent].

This is being done because: [Purpose].

## Use Cases

- Automating workflows with consistent LLM behavior
- Ensuring LLM understands *why* it’s doing something (not just what)
- Embedding prompts into repeatable pipelines or agents

## Example Usage

You are a senior data analyst.  
Structure your response in a markdown table with columns for `Insight`, `Confidence`, and `Suggested Action`.  
Your task is to review the sales dataset and extract 3 key insights.  
This is being done because the team needs actionable data before the quarterly review.
