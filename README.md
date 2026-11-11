# Radu Irbe

**AI & Platform & Systems & Formal Verification Engineer** — *Building fast, secure, verifiable, and reliable infrastructure for AI agents, local LLM inference, and low-latency systems.*

---

| Project | What Problem It Solves | Quick Start / Key Gain |
| :--- | :--- | :--- |
| [**`llama.cpp-opt`**](https://github.com/r-irbe/llama.cpp-opt) | Run 30B-2.4T models on 1 GPU + system RAM, fit 1M tokens on a 24 GB card, and serve agent swarms without cloud bills. | **+50%** hybrid CPU+GPU speed vs upstream (set to private). |
| [**`ctx-capsule`**](https://github.com/r-irbe/ctx-capsule) | Pack 256K-10M tokens into coding agents without lossy summaries and wire 8 agent CLIs (`Claude`, `Cursor`, `Pi`, `Codex`) in one command. | `npx @r-irbe/ctx-capsule init` + live fullscreen TUI & zero-downtime model switching. |
| :--- | :--- | :--- |
| [**`lifecycle-guard`**](https://github.com/r-irbe/lifecycle-guard) | Stop coding agents from running `git push --force`, leaking secrets, or editing test scripts to fake passing builds. | Fail-closed `allow / warn / escalate / block` verdicts + SHA-256 audit chain across IDE, Git hooks & CI. |
| [**`force-sqlite-to-turso`**](https://github.com/r-irbe/force-sqlite-to-turso) | Eliminate `SQLITE_BUSY` database lock crashes when running 15+ parallel coding agents on one machine. | Zero-code-change `NODE_OPTIONS` preload routing synchronous `better-sqlite3` to a single-writer server. |
| [**`pi-subagent-compact`**](https://github.com/r-irbe/pi-subagent-compact) | Keep long-running `pi` sessions from losing task state when conversation history is compacted. | Custom checkpoint templates (`Active goal`, `modified-files`, `Pick up here`) + local model support. |
| :--- | :--- | :--- |
| [**`lean4-lsp-mcp`**](https://github.com/r-irbe/lean4-lsp-mcp) | Give AI agents instant Lean 4 proof goals, sub-5ms offline `.ilean` navigation, and automatic counterexample checks. | `npx lean4-lsp-mcp` -- 21 MCP tools so agents stop running slow full-project `lake build` loops. |
| [**`pi-lens Lean4 fork`**](https://github.com/r-irbe/pi-lens) | Catch broken imports, type errors, and downstream impact cascades the moment an agent edits a file. | |
| [**`proof-skills`**](https://github.com/r-irbe/proof-skills) | Teach any coding agent modern Lean 4 & Mathlib4 tactics and enforce zero-`sorry`, zero-custom-axiom quality gates. | `apm install r-irbe/proof-skills` -- 65 modular skills + 5-role prover swarm + pure-Python CI gates. |
| :--- | :--- | :--- |
| [**`queue-reactive-book`**](https://github.com/r-irbe/queue-reactive-book) | Measure how order-entry latency trades off against spread capture and adverse selection in electronic markets. | **150.7M cancels/sec (6.6 ns/op)** and **220M queue-ahead queries/sec** in C++20, now private repo. |
| [**`hexcrawler`**](https://github.com/r-irbe/hexcrawler) | Crawl thousands of untrusted domains without SSRF redirect exploits or one slow site blocking the queue. | Every-hop RFC 6890 SSRF defense, per-domain circuit breakers, and 1,100+ zero-mock tests. |
| [**`dlx`**](https://github.com/r-irbe/dlx) | Solve exact-cover, scheduling, and combinatorial puzzles (Knuth Algorithm X & C) in Java without heap exhaustion. | **50x-100x faster** flat `int[]` matrix + stackless backtracking + memory-mapped solution storage. |

[LinkedIn](https://linkedin.com/in/raduirbe)
