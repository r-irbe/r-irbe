# Radu Irbe

Staff engineer and researcher. Distributed systems, AI infrastructure, developer tooling, formal verification.

*I like making implicit assumptions visible and testable.*

## Public Work

- [proof-skills](https://github.com/r-irbe/proof-skills) — Lean 4 / Mathlib4 agent skills, eval suite, Glicko-2 comparison
- [lean4-lsp-mcp](https://github.com/r-irbe/lean4-lsp-mcp) — MCP server for live Lean 4 proof state and C FFI
- [lifecycle-guard](https://github.com/r-irbe/lifecycle-guard) — Fail-closed policy engine for agent tool calls (allow / warn / escalate / block) (currently spec)
- [queue-reactive-book](https://github.com/r-irbe/queue-reactive-book) — C++20 limit-order-book and queue-reactive market-making simulator
- [hexcrawler](https://github.com/r-irbe/hexcrawler) — TypeScript crawler, hexagonal architecture, SSRF-safe redirects
- [r-irbe/ik_llama.cpp](https://github.com/r-irbe/ik_llama.cpp) — Contributions to high-performance local LLM inference, focusing on SOTA low-bit quantizations and CPU/GPU hybrid execution.
- [r-irbe/pi-lens](https://github.com/r-irbe/pi-lens) — Contributed Lean 4 language support for the LSP-powered extension giving AI coding agents real-time, language-aware feedback to ground reasoning and reduce hallucinations.

## Private Architecture & Research

Much of my recent work lives in private repositories or enterprise environments, spanning planetary-scale backend systems, rigorous AI governance, and formal methods:

- **Strictly Governed AI Workspaces:** Architected self-evolving, spec-driven agent harnesses for deterministic human-AI collaboration. Built private swarm governance (`pi-fleet`), fail-closed lifecycle safety nets (`pi-harness-bridge`), and traceable peer-review engines (`pi-review-kit`). 
- **Planetary-Scale Distributed Systems:** Architected and designed the platform observability, load management, QoS for a new CQRS based data platform, targeting >1B reads/hour with <2ms latency at >99.99% uptime (Microsoft). Managed Kafka/Flink stream processing pipelines executing zero-downtime, terabyte-scale 5-way joins on shared Tier-0 infrastructure (Wise).
- **Formal Verification of High-Risk AI:** Formally verifying AI system security properties using Lean 4 for high-risk applications. 
- **High-Performance Engineering:** Built deterministic platforms including a memory-mapped NVMe-resident graph engine (`rust-mmap-engine`) constrained by a Lean 4 rule engine, and mathematically verified decision engines.

<br>

Looking for work that mixes infrastructure with controlled AI-assisted development.

[irbe.ai](https://irbe.ai) · [LinkedIn](https://linkedin.com/in/raduirbe)
