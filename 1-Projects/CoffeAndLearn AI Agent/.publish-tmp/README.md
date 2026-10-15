# The Missing Map of AI Agents

> **Volume 1: The Static Architecture**
>
> *An Architect's Field Guide* — **Stephen Wang**, System & Enterprise Architect

AI is full of buzzwords: *AI agents, RAG, MCP, Skills, Prompt Engineering, Context Engineering, Agent Loops, Harnesses*. The problem is not that these concepts are difficult — it is that they are rarely presented as one unified, cohesive systems map.

This field guide builds that map. It explains each major concept in plain systems-engineering terms and shows how it all fits together — from the LLM foundation to context engineering, memory, skills, tools, MCP, and the production harness.

> **Status:** Volume 1 complete · Volume 2 (The Runtime Engine) in planning

---

## What's Inside

Covering 6 chapters in roughly 15 minutes of reading:

- **Chapter 1 — The Foundation: What Is an LLM?** — The LLM is not magic: a small inference program reading an enormous parameter file. A stateless reasoning engine waiting for context.
- **Chapter 2 — The Agent: Making LLMs Useful** — The foundational equation: `Agent = LLM + Context + Tools`.
- **Chapter 3 — Context Engineering: Managing the Agent's Information** — Session working memory, cross-session memory, knowledge bases & RAG, skills, and the knowledge-vs-skills distinction.
- **Chapter 4 — Tools and MCP: The Agent's Bridge to the Outside World** — Tools as the action layer and MCP as the open "USB standard" for universal tool connectivity.
- **Chapter 5 — Harness Engineering: Putting It All Together** — The upgraded production equation: `Agent = LLM + Harness`.
- **Chapter 6 — Synthesis: Putting the Buzzwords on the Map** — A clean architectural compass placing every term in its structural role.

## Read It

- 📖 **Full text:** [`book/the-missing-map-of-ai-agents-part-1.md`](book/the-missing-map-of-ai-agents-part-1.md)
- 📄 **PDF booklet:** [`book/the-missing-map-of-ai-agents-part-1.pdf`](book/the-missing-map-of-ai-agents-part-1.pdf)
- 🗺️ **Diagrams:** [`assets/`](assets/)

## The Core Equations

```text
LLM = Inference Code + Parameters (Weights)

Agent = LLM + Context + Tools

Agent = LLM + Harness

Harness = Context Management + Tool Interfaces + Reliability & Guardrails
```

## Diagrams

All 11 diagrams live in [`assets/`](assets/), including:

| Diagram | What it maps |
|---|---|
| `ai-buzzwords-landscape.png` | The whole buzzword landscape at a glance |
| `ai-ml-dl-llm-hierarchy.png` | AI ⊃ ML ⊃ DL ⊃ LLMs family tree |
| `agent-architecture-equation.png` | Agent = LLM + Context + Tools |
| `structured-context-stack.png` | System prompt, tools, history, status bar |
| `rag-knowledge-retrieval-flow.png` | External knowledge retrieval |
| `agent-skills-progressive-disclosure.png` | On-demand skill loading |
| `tools-agent-action-bridge.png` | Tools as the environment bridge |
| `harness-engineering-architecture.png` | Agent = LLM + Harness |

## Roadmap

- **Volume 1: The Static Architecture** — ✅ Published
- **Volume 2: The Runtime Engine** — ⏳ In planning: function calling, the ReAct pattern, agent loops, loop engineering, and the enterprise harness.

## About the Author

**Stephen Wang** is a software and enterprise systems architect with over 20 years of experience designing mission-critical architectures across enterprise platforms, autonomous-driving computer vision systems, and modern AI-native applications. He writes about the architectural transition from traditional deterministic systems to probabilistic AI agent loops.

This guide was born out of whiteboard discussions with engineering peers to build a shared map of the AI landscape.

## License

MIT — see [`LICENSE`](LICENSE). Share freely with attribution.
