# Radu Irbe

Staff engineer and researcher working across formal verification, deterministic agent governance, and low-latency distributed systems.
*Making implicit system assumptions explicit, machine-checkable, and bounded under load.*

## Public Projects

### Lean 4 & Formal Verification

| Project | Focus |
| :--- | :--- |
| [proof-skills](https://github.com/r-irbe/proof-skills) | 75 Lean 4 / Mathlib4 proof engineering skills, 200+ templates, AltProof tactic advisor, and Glicko-2 evaluation suite. |
| [lean4-lsp-mcp](https://github.com/r-irbe/lean4-lsp-mcp) | 21-tool MCP server for live Lean 4 proof state, offline `.ilean` navigation, Galois-pruned counterexample search, and tactic cost ranking. |
| [lean-analyzer](https://github.com/r-irbe/lean-analyzer) | In-process abstract interpreter, relational domain solver, and zero-copy `.ilean` indexer for Lean 4 (Rust + WASM), with abstract domain soundness proved in Lean 4. |

### Agent Governance & Tooling

| Project | Focus |
| :--- | :--- |
| [lifecycle-guard](https://github.com/r-irbe/lifecycle-guard) | Fail-closed policy validator, JSON schemas, and SDLC gate CLI (`allow` / `warn` / `escalate` / `block`) for autonomous coding agents. |
| [pi-lens](https://github.com/r-irbe/pi-lens) | Codebase indexing, AST-grep structural analysis, and latency/diagnostics MCP server for coding agents. |
| [pi-subagent-compact](https://github.com/r-irbe/pi-subagent-compact) | In-process context compaction and deterministic checkpointing extension with passthrough fallback. |
| [force-sqlite-to-turso](https://github.com/r-irbe/force-sqlite-to-turso) | Zero-code-change Node.js preload routing `better-sqlite3` calls onto a single-writer libSQL/Turso server for multi-agent concurrency. |
| [hexcrawler](https://github.com/r-irbe/hexcrawler) | TypeScript crawler built on hexagonal architecture with SSRF-safe redirects, per-domain circuit breakers, and 1,100+ tests. |

### Low-Latency & Systems Infrastructure

| Project | Focus |
| :--- | :--- |
| [queue-reactive-book](https://github.com/r-irbe/queue-reactive-book) | Zero-heap-allocation C++20 limit-order-book and queue-reactive Poisson market-making simulator. Throughput figures are machine-local and workload-scoped. |
| [llama.cpp-opt](https://github.com/r-irbe/llama.cpp-opt) | Optimization layer on `ik_llama.cpp`: NUMA-split multi-socket serving, native DeepSeek-V4.1 FP8 row decoding, `io_uring` weight streaming, cohort prefix sharing, and `-unreal` pre-attention token filtering. |

## Work

Most recent work is in private repositories or enterprise environments.

- **Agent safety.** Fail-closed policy for tool calls: allow, warn, escalate, block. Hash-chained audit. Session resume from protobuf and SQLite. The public spec and CLI live in `lifecycle-guard`.
- **Microsoft.** Threat landscape, agent harness, a routing simulator that found three defects (analysis tool, not a router). Infrastructure work: a C# pipeline generator in place of large YAML, and a drift detector that is now another team's.
- **Wise.** Risk and result checks on Kafka/Flink recalculation of 1-15 billion items, on shared tier-0 infrastructure. Not sole owner of the pipeline.
- **Microsoft, design.** Observability, load management, and QoS for a CQRS data platform. Design target: >1B reads/hour, <2ms, >99.99% uptime.
- **Formal methods.** Lean 4 formalization of security, provenance, and convergence properties for an epistemic analysis and process-explainability workbench.
- **Earlier.** Data lineage across languages, delivered to banks and exchanges. Large-file upload path and support tooling at Kühne+Nagel.

Looking for work that mixes infrastructure with controlled AI-assisted development.

[irbe.ai](https://irbe.ai) · [LinkedIn](https://linkedin.com/in/raduirbe)

