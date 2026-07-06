# Sammy Tourani

Software engineering student at McMaster building **AI infrastructure**, **developer tooling**, **eval systems**, and **RAG platforms**.

I care about the layer that makes AI systems actually useful: correctness, tool-use, permissions, latency, cost, and production reliability.

[Email](mailto:sammytourani@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sammy-tourani) · [GitHub](https://github.com/SammyTourani)

---

## Current focus

- **Agent evals:** adversarial correctness, reward-hack detection, withheld tests, metamorphic properties, differential checks.
- **Tool-use infrastructure:** dependency graphs, preconditions, multi-step workflows, MCP-style orchestration.
- **Production AI systems:** RAG, permissions, observability, latency, cost, and reliability.
- **Developer tooling:** systems that help engineers ship faster without giving up correctness.

---

## Best proof-of-work

### [Tripwire](https://github.com/SammyTourani/tripwire) — eval infrastructure for reward-hacked AI code optimization

A layered correctness oracle for AI optimization loops. Tripwire rejects candidates that pass visible tests but fail on withheld adversarial inputs before any speedup earns reward.

- Published as a PyPI CLI: [`tripwire-oracle`](https://pypi.org/project/tripwire-oracle/)
- Drop-in OpenEvolve evaluator
- Four-layer verifier: canonical checks, metamorphic properties, withheld-input differential testing, isolated timing
- Benchmark: ships **0 of 13 planted reward hacks** while preserving **100% of valid speedups**
- Live visualizer replays a Claude-proposed optimization that reached a verified **200x speedup**

**Why it matters:** frontier agents increasingly write and optimize code. Tripwire is the guardrail that tells the loop whether a speedup is real or a reward hack.

---

### [Plexus](https://github.com/SammyTourani/plexus) — dependency layer for agentic tool pipelines

A tool-planning graph that tells agents which tools must run before others. Semantic tool retrieval finds *which* tools are relevant; Plexus adds the missing execution-order layer.

- Analyzed **1,296 real Composio tools** across Google Workspace and GitHub
- Derived **520 producer-to-consumer dependency edges**
- Classifies required inputs as `tool`, `user`, or `tool_or_user`
- Combines schema/description parsing, targeted rules, slug heuristics, and LLM semantic matching
- Ships with golden-set validation and a live graph explorer

**Why it matters:** agents fail when they call tools with missing IDs, thread handles, file handles, or artifact IDs. Plexus makes those preconditions explicit before execution.

---

### Enterprise RAG / AI retrieval systems

Built internal retrieval tooling for regulated engineering documents.

- Indexed large confidential engineering corpora for permissioned semantic search
- Built ingestion across parsing, metadata extraction, chunking, embeddings, and retrieval
- Worked with role-based access control so users could only query authorized documents
- Integrated AI-assisted lookup and triage workflows for engineering research

---

### LLM systems optimization

Built infrastructure for reducing repeated LLM calls and improving response latency.

- Hybrid semantic cache with Redis, PostgreSQL, and pgvector
- Reduced repeated LLM-call token costs by **75%**
- Cut cache-hit latency from **1.4s to <150ms**
- Supported high-throughput API workloads with Dockerized FastAPI services

---

## Stack

**Languages:** Python, TypeScript, JavaScript, Ruby, SQL, Bash, Swift  
**AI / agents:** Claude Code, MCP, RAG, evals, agent orchestration, PyTorch, OpenCV  
**Infra:** Kubernetes, Docker, Terraform, AWS, Azure, CI/CD, Redis, PostgreSQL, pgvector  
**Focus:** eval infrastructure, tool-use planning, RAG systems, developer tooling, production reliability

---

## Background

- B.Eng. Software Engineering, McMaster University, expected Apr 2028
- GPA: 11.8 / 12.0; Dean's Honour List
- Loran Scholar Finalist
- Y Combinator AI Startup School, selected attendee, 2025 and 2026
- Certified Kubernetes Administrator

---

## Notes for recruiters / builders

The strongest fit is work on:

- eval systems
- AI developer tools
- RAG / knowledge infrastructure
- agent tooling
- platform engineering for AI products

If your team is turning AI systems from demos into reliable products, I want to talk.
