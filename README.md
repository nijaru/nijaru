I work on backend systems, databases, and developer tools in Rust, Python, Go, and TypeScript.

## `~/projects`

### `data-and-search/`

- **[omendb](https://github.com/omendb/omendb)** - Experimental relational database in Rust, built on SeerDB, with SQL transactions, foreign-key constraints, and PostgreSQL-wire access for a supported SQL subset. Under development.
- **[omendb-vector](https://github.com/omendb/omendb-vector)** - Embedded retrieval database in Rust for mutable application data: vector search, BM25 text search, metadata filtering, and hybrid ranking. Developer preview. *(WIP)*
- **[seerdb](https://github.com/omendb/omendb/tree/main/crates/seerdb)** - Transactional ordered byte-KV storage engine in Rust, developed in the OmenDB workspace as an independently versioned Apache-2.0 crate. WAL recovery, snapshots, and group commit. Developer preview. *(WIP)*
- **[omengrep](https://github.com/nijaru/omengrep)** - Local code search CLI in Rust: Tree-sitter extraction, embeddings plus BM25, owned local storage. Under rewrite. *(WIP)*
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** - HNSW approximate nearest-neighbor search in pure Go, mmap-backed, with filtering and segment merging.
- **[stt-bench](https://github.com/nijaru/stt-bench)** - Speech-to-text benchmarking across 13 acoustic conditions and four models.

### `agents/`

- **[ion](https://github.com/nijaru/ion)** - Rust coding agent with persistent, forkable sessions backed by SQLite. Its execution log distinguishes completed tool calls from interrupted calls with unknown effects. Under development.
- **[pi-search](https://github.com/nijaru/pi-search)** - Pi extension for web search, native provider search, page fetching, and local document extraction.
- **[pi-fast-mode](https://github.com/nijaru/pi-fast-mode)** - Pi extension for OpenAI Codex fast mode.
- **[pi-compactor](https://github.com/nijaru/pi-compactor)** - Pi extension that lets the agent choose when to compact its context.
- **[pi-subagents](https://github.com/nijaru/pi-subagents)** - Background task delegation for Pi. Subagents run alongside the main session and return results to it.
- **[pi-workflows](https://github.com/nijaru/pi-workflows)** - Durable, resumable workflow orchestration for pi.
- **[pi-goal](https://github.com/nijaru/pi-goal)** - Session-scoped autonomous goals for pi.
- **[pi-usage](https://github.com/nijaru/pi-usage)** - Pi extension that shows OpenAI Codex subscription quota in the footer.
- **[pi-tps](https://github.com/nijaru/pi-tps)** - Pi extension that shows per-request latency and throughput under each response, with session averages in the footer.

### `developer-tools/`

- **[sy](https://github.com/nijaru/sy)** - File synchronization in Rust with rsync-like behavior: delta transfer, parallel I/O, SSH, and reflink support. Rewrite in progress. *(WIP)*
- **[aku](https://github.com/nijaru/aku)** - Type-safe Go API framework built on net/http, with request extraction, validation, and OpenAPI generation.
- **[jb](https://github.com/nijaru/jb)** - Background job manager for long-running CLI tasks.
- **[tk](https://github.com/nijaru/tk)** - Task tracker for AI agents with Git-friendly storage and blocking dependencies.
- **[brotli](https://github.com/nijaru/brotli)** - Pure-Go Brotli encoder/decoder (RFC 7932; large-window and multi-stream decode per RFC 9841), drop-in for `andybalholm/brotli`.
- **[brutli](https://github.com/nijaru/brutli)** - Rust Brotli implementation from the spec. Decoder works and the one-shot encoder emits compressed and stored streams; still in compatibility, corpus, and performance validation, not production-ready. *(WIP)*

### `infrastructure/`

- **[ribn](https://github.com/nijaru/ribn)** - Language-model inference engine in Rust with CUDA and Metal backends and decoder checks against reference implementations. Under development.
- **vero** *(private, experimental)* - Systems language and native compiler using MLIR/LLVM, with static ownership checks for borrowed data.
- **[archon](https://github.com/nijaru/archon)** - Experimental resource manager in Rust with scheduling, process execution, and recovery code. Production-scale operation is unverified.

### `trading/`

- **[go-clob-client](https://github.com/nijaru/go-clob-client)** - Unofficial Go SDK for the Polymarket CLOB. Checked signing and request formats against upstream SDKs and previously used the client in a trading bot.
- **pacabot** *(private)* - Prediction-market research system using LLMs to analyze market data, news, SEC filings, and congressional trades.
