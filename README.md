# Radu Irbe

Staff engineer and researcher.

*Making implicit system assumptions explicit, machine-checkable, and bounded under load.*

## Public Projects

### Lean 4 & Formal Verification

| Project | Focus |
| :--- | :--- |
| [proof-skills](https://github.com/r-irbe/proof-skills) | Lean 4 / Mathlib4 proof engineering skills, templates, AltProof tactic advisor, and LLM evaluation suite. |
| [lean4-lsp-mcp](https://github.com/r-irbe/lean4-lsp-mcp) | MCP server for live Lean 4 proof state, offline `.ilean` navigation, counterexample search, and tactic cost ranking. |
| [lean-analyzer](https://github.com/r-irbe/lean-analyzer) | In-process abstract interpreter, relational domain solver, and zero-copy `.ilean` indexer for Lean 4 (Rust + WASM), with abstract domain soundness proved in Lean 4. |

### Agent Governance & Tooling

| Project | Focus |
| :--- | :--- |
| [lifecycle-guard](https://github.com/r-irbe/lifecycle-guard) | Fail-closed policy validator, JSON schemas, and SDLC gate CLI (`allow` / `warn` / `escalate` / `block`) for autonomous coding agents. |
| [pi-lens](https://github.com/r-irbe/pi-lens) | Extensive Lean 4 support. Has codebase indexing, AST-grep structural analysis, and latency/diagnostics MCP server for coding agents. |
| [pi-subagent-compact](https://github.com/r-irbe/pi-subagent-compact) | In-process context compaction and deterministic checkpointing extension with passthrough fallback. |
| [force-sqlite-to-turso](https://github.com/r-irbe/force-sqlite-to-turso) | Zero-code-change Node.js preload routing `better-sqlite3` calls onto a single-writer libSQL/Turso server for multi-agent concurrency. |
| [hexcrawler](https://github.com/r-irbe/hexcrawler) | Crawler with SSRF-safe redirects, per-domain circuit breakers. |

### Low-Latency & Systems Infrastructure

| Project | Focus |
| :--- | :--- |
| [queue-reactive-book](https://github.com/r-irbe/queue-reactive-book) | Zero-heap-allocation C++20 limit-order-book and queue-reactive Poisson market-making simulator. |
| [llama.cpp-opt](https://github.com/r-irbe/llama.cpp-opt) | Optimization layer on `ik_llama.cpp`: NUMA-split multi-socket serving, native DeepSeek-V4.1 FP8 row decoding, `io_uring` weight streaming, cohort prefix sharing, and `-unreal` pre-attention token filtering. |

## Work

Most recent work is in private repositories or enterprise environments.

- **Agent safety.** Fail-closed policy for tool calls: allow, warn, escalate, block. Hash-chained audit. Session resume from protobuf and SQLite. The public spec and CLI live in `lifecycle-guard`.
- **Microsoft.** Threat landscape, agent harness, a routing simulator that found three defects. Infrastructure work: a C# pipeline generator in place of large YAML, and an infrastructure drift detector.
- **Microsoft, design.** Observability, load management, and QoS for a CQRS data platform. Design target: >1B reads/hour, <2ms, >99.99% uptime.
- **Formal methods.** Lean 4 formalization of security, provenance, and convergence properties for an epistemic analysis and AI process-explainability workbench.
- **Earlier.** Data lineage across languages, delivered to banks and exchanges.

[irbe.ai](https://irbe.ai) · [LinkedIn](https://linkedin.com/in/raduirbe)

