# Perfect Prompts - AI Agent Orchestration (n8n)

This n8n workflow uses a mixture of multiple AI agents and models to transform vague user inputs into highly structured, actionable prompts using the **RISEN** framework (Role, Instruction, Steps, End goal, Narrowing of scope).

## What it does
- Receives user input through a webhook
- Distributes the input across four specialized AI agents (each focused on a different skill set)
- Aggregates their outputs intelligently
- Synthesizes a final "Perfect Prompt" ready for high-quality AI tasks

## Technologies Used
- n8n (workflow orchestration)
- LangChain nodes for agent management
- OpenRouter LLMs (Gemini, DeepSeek, Phi-3, Dolphin)
- RISEN framework for prompt refinement
- JSON merging and aggregation logic

## Files
- **perfect-prompts-n8n-workflow.json** — the exported n8n workflow file

## Why this matters
This project demonstrates how multiple AI models can collaborate to enhance user instructions, leading to more precise and effective AI interactions.  
It highlights real-world skills in building smart, modular AI pipelines ready for production environments.

---

*Demo built for AI Agent Implementation Manager portfolio presentation.*
