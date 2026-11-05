I work on backend systems, databases, and developer tools in Rust, Go, Python, and TypeScript.

## Current work

My main projects are Ion and Vero, with Ribn as a secondary focus.

- **[Ion](https://github.com/nijaru/ion)** — An experimental Rust coding agent and runtime with SQLite-backed, forkable sessions and terminal, headless, and RPC interfaces. Its execution log distinguishes completed tool calls from interrupted calls with unknown effects.
- **Vero** *(private, experimental)* — A systems language and native compiler using MLIR/LLVM, with ownership checks for borrowed data.
- **[Ribn](https://github.com/nijaru/ribn)** — A Rust model inference engine with experimental CUDA and Metal execution, bounded HTTP generation, and decoder checks against reference implementations.

## Selected other projects

- **Pi extensions** — Tools I use and maintain for the Pi coding agent: [background subagents](https://github.com/nijaru/pi-subagents), [agent-controlled compaction](https://github.com/nijaru/pi-compactor), and [web search and fetching](https://github.com/nijaru/pi-search).
- **[brotli](https://github.com/nijaru/brotli)** — A pure-Go Brotli encoder and decoder.
- **[OmenDB](https://github.com/omendb/omendb)** — An experimental relational database in Rust, built on the SeerDB storage engine. PostgreSQL-wire access supports a subset of SQL; this is a developer preview, not a PostgreSQL replacement.
- **[go-clob-client](https://github.com/nijaru/go-clob-client)** — An unofficial Go client for the Polymarket CLOB. Checked signing and request formats against upstream SDKs and previously used the client in a trading bot.
- **[Chassis](https://github.com/nijaru/chassis)** — A pre-alpha Rust audio framework with a CLAP plugin adapter. Other plugin formats and broad host qualification remain unfinished.
- **[Stop](https://github.com/nijaru/stop)** — A Rust process-inspection CLI for macOS and Linux, with structured JSON output and process-birth identity to distinguish reused PIDs.

## Design and exploration

- **[AVC](https://github.com/nijaru/avc)** — Design work on a native, local-first version control system for developers and coding agents. Implementation was reset; there is no usable VCS yet.
- **[Canto](https://github.com/nijaru/canto)** — Exploring a local-first workspace connecting editors, coding agents, and source control. The scope is being redefined; the current repository has no application code.

## Upstream contribution

Contributed response/layout reuse, bounded caching, and regression tests to the Go
implementation of Campfire in [merged PR #9](https://github.com/basecamp/once-campfire-go/pull/9).
The guarded-layout approach adapts and credits [Nick Potts's earlier work](https://github.com/basecamp/once-campfire-go/pull/6).
