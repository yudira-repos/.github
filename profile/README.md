# Yudira

**Governed AI agents and the platforms underneath them.**

I'm **Ravi Nukala**, a platform engineer and architect with 20+ years building distributed systems in regulated fintech and financial operations. At BlackLine I architected a production agentic AI platform (multi-agent orchestration, policy enforcement, human-in-the-loop review, and full auditability) that runs regulated financial workflows. This org is where I build in the open on the same problems: what it takes to let an agent act in production, safely.

[LinkedIn](https://www.linkedin.com/in/nukalaravi)

---

### Featured work

**[agent-forge](https://github.com/yudira-repos/agent-forge)** · Python · alpha  
An open enterprise agent framework covering the parts LLM SDKs leave out: signed agent identity and RBAC, a policy and governance engine, human-in-the-loop approval gates, a hash-chained audit log you can verify and replay, and per-agent OpenTelemetry traces. It runs on Claude, OpenAI, LangGraph or Vertex Gemini. CI and 70 tests.

**[epyhia](https://github.com/yudira-repos/epyhia)** · Python  
A one-person AI agency: a plain-language brief goes in, and a live site, a launch marketing pack and a working test-mode Stripe checkout come out. Four agents on deliberately chosen model tiers, with every side effect passing through one approval gate. The first commit is [DESIGN.md](https://github.com/yudira-repos/epyhia/blob/main/DESIGN.md), the architecture argument, written before any code.

**[harness-engineering](https://github.com/yudira-repos/harness-engineering)** · Python · no dependencies  
A small, fully offline agent harness you can read in an afternoon, built around a kids' AI tutor. It covers eight concepts (agent loop, tools, context, memory, guardrails, reliability, tracing, evals), each with a runnable example and tests. Companion code for the post *Harness Engineering: Everything Around the Model*.

**[life-os-spa](https://github.com/yudira-repos/life-os-spa)** · TypeScript / Next.js  
LifeOS V1: one household app covering Kids, Property, Travel, Health and Finance modules behind Google sign-in, on Postgres and Redis, deployed with Docker on Railway.

---

### What I care about

- **Agents act only through gates.** Identity, scopes and policy are enforced in code, not asked for in a prompt.
- **If you can't replay it, you can't trust it.** Audit trails and traces are designed in from the first commit.
- **Design before code.** The architecture and its failure modes are written down first.

*Built with AI pair programming. Every design decision is mine.*
