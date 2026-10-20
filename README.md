# Radu Irbe

Staff engineer and researcher. Distributed systems, AI infrastructure, developer tooling, formal verification.

*I like making implicit assumptions visible and testable.*

## Public

- [proof-skills](https://github.com/r-irbe/proof-skills) — Lean 4 / Mathlib4 agent skills, eval suite, Glicko-2 comparison
- [lean4-lsp-mcp](https://github.com/r-irbe/lean4-lsp-mcp) — MCP server for live Lean 4 proof state, `.ilean` navigation, tactic advisor, and C FFI. Pre-alpha.
- [lean-analyzer](https://github.com/r-irbe/lean-analyzer) — In-process abstract interpreter, relational domain solver, and zero-copy `.ilean` indexer for Lean 4 (Rust + WASM), with domain soundness proved in Lean 4.
- [pi-subagent-compact](https://github.com/r-irbe/pi-subagent-compact) — Pi extension for configurable in-process context compaction and checkpointing with passthrough fallback.
- [lifecycle-guard](https://github.com/r-irbe/lifecycle-guard) — Fail-closed policy engine for agent tool calls. Spec and design; not a shipped product.
- [queue-reactive-book](https://github.com/r-irbe/queue-reactive-book) — C++20 limit-order-book and queue-reactive market-making simulator. Throughput figures are machine-local and workload-scoped.
- [force-sqlite-to-turso](https://github.com/r-irbe/force-sqlite-to-turso) — Preload that routes an agent's existing `better-sqlite3` calls onto a single-writer libSQL server, without changing the agent.
- [hexcrawler](https://github.com/r-irbe/hexcrawler) — TypeScript crawler: hexagonal architecture, SSRF-safe redirects, per-domain circuit breakers, 1100+ tests.
- [llama.cpp-opt](https://github.com/r-irbe/llama.cpp-opt) — Optimization layer on ik_llama.cpp. NUMA-split multi-socket serving, native DeepSeek-V4.1 FP8 row decoding, io_uring weight streaming, cohort prefix sharing. `-unreal` filters low-information tokens before attention on long RAG prompts. Figures are machine-local.

## Work

Most recent work is in private repositories or enterprise environments.

- **Agent safety.** Fail-closed policy for tool calls: allow, warn, escalate, block. Hash-chained audit. Session resume from protobuf and SQLite. The public spec is `lifecycle-guard`.
- **Microsoft.** Threat landscape, agent harness, a routing simulator that found three defects (analysis tool, not a router). Infrastructure work: a C# pipeline generator in place of large YAML, and a drift detector that is now another team's.
- **Wise.** Risk and result checks on Kafka/Flink recalculation of 1–15 billion items, on shared tier-0 infrastructure. Not sole owner of the pipeline.
- **Microsoft, design.** Observability, load management, and QoS for a CQRS data platform. Design target: >1B reads/hour, <2ms, >99.99% uptime. 
- **Formal methods.** Lean 4 on security properties of a process-explainability simulator.
- **Earlier.** Data lineage across languages, delivered to banks and exchanges. Large-file upload path and support tooling at Kühne+Nagel.

Looking for work that mixes infrastructure with controlled AI-assisted development.

[irbe.ai](https://irbe.ai) · [LinkedIn](https://linkedin.com/in/raduirbe)
