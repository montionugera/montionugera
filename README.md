# Pasit Nusso (Mont)

**Senior Systems & Full-Stack Engineer** · Bangkok, Thailand  
Building static analysis engines, high-throughput data & real-time multiplayer systems, and autonomous agentic developer tooling across **Rust**, **Go**, **TypeScript**, and **Python**.

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged+-user%3Amontionugera)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged+-user%3Amontionugera)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged+-user%3Amontionugera)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged+-user%3Amontionugera)
[![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)](https://github.com/montionugera)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://github.com/montionugera)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://github.com/montionugera)

---

### Open Source Contributions ([119+ Merged External PRs](https://github.com/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged+-user%3Amontionugera) across 60+ Repositories)

#### Core & Multi-PR Upstream Contributions
| Project | Stack | Contributions & Focus |
| :--- | :--- | :--- |
| **[`yukikotani231/sqlsift`](https://github.com/yukikotani231/sqlsift/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged)** | Rust (`sqlsift-core`, `cli`, `lsp`, `wasm`) | **34 merged PRs** — Schema catalog & SQL static analyzer: `CHECK` constraint literal evaluation (`E0037` [#383](https://github.com/yukikotani231/sqlsift/pull/383)), window functions (`NTILE`, `NTH_VALUE`), `UPDATE ... FROM` / `USING` resolution, PostgreSQL/MySQL/SQLite dialect parity, and LSP/CLI diagnostics. |
| **[`your-moon/tern`](https://github.com/your-moon/tern/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged)** | Rust | **9 merged PRs** — Terminal UI & migration engine: WCAG contrast guards ([#70](https://github.com/your-moon/tern/pull/70)), TUI rendering, and schema inspection. |
| **[`Shalimov04/mcp-airlock`](https://github.com/Shalimov04/mcp-airlock/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged)** | Python | **5 merged PRs** — Model Context Protocol (MCP) security proxy: self-healing `airlock_audit` persistence ([#113](https://github.com/Shalimov04/mcp-airlock/pull/113)), trust-header verification, and policy enforcement. |
| **[`riosgabriel/vereda`](https://github.com/riosgabriel/vereda/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged)** & **[`Alimzy/stellar-vesting`](https://github.com/Alimzy/stellar-vesting/pulls?q=is%3Apr+author%3Amontionugera+is%3Amerged)** | Python / Rust (Soroban WASM) | **4 merged PRs** — HTTP method security guards (`TRACE`/`CONNECT` rejection [#158](https://github.com/riosgabriel/vereda/pull/158)) and Soroban smart-contract WASM binary size gates ([#14](https://github.com/Alimzy/stellar-vesting/pull/14)). |

#### Selected Merged & Active Ecosystem PRs
- **Rust & Systems Tooling**
  - **[`servo/rust-smallvec`](https://github.com/servo/rust-smallvec/pull/770)** *(1.8k★ · 180M+ crates.io downloads)* — Core module refactoring in Servo's stack-allocated vector library.
  - **[`LargeModGames/spotatui`](https://github.com/LargeModGames/spotatui/pull/893)** *(1.7k★)* — Theme-aware glyph rendering for TUI sidebar navigation.
  - **[`nelsonPires5/herdr-board`](https://github.com/nelsonPires5/herdr-board/pull/102)** — Herdr `0.8.2` / socket protocol v20 compatibility.
  - **[`OpenKnight-Foundation/KnightVerse`](https://github.com/OpenKnight-Foundation/KnightVerse/pull/1496)** — Primary PostgreSQL & Redis readiness health-check endpoint.
  - **Active upstream PRs**: **[`astral-sh/uv#22836`](https://github.com/astral-sh/uv/pull/22836)** *(85k★ — preserve `3.13t`/`3.14t` free-threaded variants in `uv python upgrade`)* · **[`jangtrinh/design-os-studio#771`](https://github.com/jangtrinh/design-os-studio/pull/771)** *(Figma export render-bounds engine for shadows, strokes, and groups)*.
- **Go & Cloud-Native Infrastructure**
  - **[`eugenioenko/ttt`](https://github.com/eugenioenko/ttt/pull/970)** *(680★)* — Configurable `editor.largeFiles.wordWrapMaxMB` threshold for large-file performance.
  - **[`u-root/gobusybox`](https://github.com/u-root/gobusybox/pull/157)** *(200★)* — Modernize `bb` and `makebb` multi-binary builders to the Go `os` filesystem API.
  - **[`Goldziher/ai-rulez`](https://github.com/Goldziher/ai-rulez/pull/471)** *(165★)* — Rule engine attribution and licensing metadata.
  - **[`agentkourier/agent-kourier`](https://github.com/agentkourier/agent-kourier/pull/46)** — First-install `agent-kourier init` configuration generator & validator.
  - **Active upstream PRs**: **[`litmuschaos/litmus#5677`](https://github.com/litmuschaos/litmus/pull/5677)** *(5.7k★, CNCF — preserve reference-based `CronWorkflow` manifests in `ProcessExperimentUpdate`)* · **[`kunchenguid/no-mistakes#1533`](https://github.com/kunchenguid/no-mistakes/pull/1533)** *(pipeline worktree dirt isolation)* · **[`cisco-ai-defense/defenseclaw#1362`](https://github.com/cisco-ai-defense/defenseclaw/pull/1362)** *(888★ — Linux session process-tree deduplication)*.
- **Python, AI/ML & Scientific Computing**
  - **[`udaysharmadev/Gravitas`](https://github.com/udaysharmadev/Gravitas/pull/82)** *(310★)* — Record-time path canonicalization & cross-platform normalization matrix tests.
  - **[`openSUSE/docbuild`](https://github.com/openSUSE/docbuild/pull/653)** — CLI validation & doctype-scoped cache pruning tests (`100%` branch coverage).
  - **[`great-wall-connect/blitzlog`](https://github.com/great-wall-connect/blitzlog/pull/156)** — Modular Terraform `infra/scrummaster` stack with optional EIP provisioning.
  - **Active upstream PRs**: **[`MIC-DKFZ/nnUNet#3083`](https://github.com/MIC-DKFZ/nnUNet/pull/3083)** *(9.0k★ — signature inspection for legacy `build_network_architecture` trainers)* · **[`strands-agents/harness-sdk#5342`](https://github.com/strands-agents/harness-sdk/pull/5342)** & **[`#5347`](https://github.com/strands-agents/harness-sdk/pull/5347)** *(8.9k★, AWS Strands Agents — graph interrupt state preservation & async generator `aclosing` cleanup)*.
- **TypeScript, Web & Developer Platforms**
  - **[`HoshinoSuzumi/chronoframe`](https://github.com/HoshinoSuzumi/chronoframe/pull/430)** *(2.0k★)* — Album table layout constraints and overflow truncation.
  - **[`QuorumCredit/QuorumCredit`](https://github.com/QuorumCredit/QuorumCredit/pull/2035)** — Multi-instance Redis integration test pipeline.
  - **[`TomStrepsil/regex-partial-match`](https://github.com/TomStrepsil/regex-partial-match/pull/139)** — Quantified-atom AST rewriting to prevent V8 catastrophic backtracking stack overflows.
  - **[`BrainTease/Brain-Storm`](https://github.com/BrainTease/Brain-Storm/pull/1399)** — End-to-end Playwright Page Object Model architecture.
  - **[`keatonwilson/cartoTaco`](https://github.com/keatonwilson/cartoTaco/pull/81)** — Square-root area-scaled distribution strips & tie-aware percentile copy.

---

### Focus Areas & Engineering Interests
- **Static Analysis & Language Tooling**: SQL AST/type-checking (`sqlsift`), LSP servers, regex/automata engines, and codegen drift gates.
- **Autonomous Agentic Workflows**: Multi-agent orchestration, deterministic quality gates (`ps-skills`), and MCP server security.
- **Distributed Systems & Real-Time Engines**: Authoritative game simulation (Rust + Godot / Nakama), Go data lakehouses, and local-first ledger reconciliation.
