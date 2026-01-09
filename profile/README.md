# AgenWatch

Runtime-enforced execution governance for AI agents.

AgenWatch is a Python execution kernel that guarantees agents stop when they must.
Budgets, iteration limits, and execution boundaries are enforced at runtime —
before tools or LLM calls occur.

## What We Build
- Deterministic execution kernels for AI agents
- Runtime-enforced budget and iteration limits
- Governance layers for agent frameworks

## What We Don’t Build
- Prompt frameworks
- UI dashboards
- Agent orchestration platforms

## How It’s Used
AgenWatch is designed to sit underneath frameworks like LangChain or CrewAI,
providing hard execution guarantees while they handle reasoning and workflows.

## Learn More
→ SDK & Docs: https://github.com/agenwatch/agenwatch  
→ Architecture: https://github.com/agenwatch/agenwatch/blob/main/ARCHITECTURE.md
