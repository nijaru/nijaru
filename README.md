I work on databases, developer tools, and agent infrastructure, primarily in Go, Rust, Python, TypeScript, and Mojo.

## `~/projects`

### `data-and-search/`

- **[omendb](https://github.com/omendb/omendb)** — Relational database for single-node OLTP in Rust on SeerDB, with PostgreSQL compatibility at the wire boundary. Developer preview, not alpha-ready. *(WIP)*
- **[omendb-vector](https://github.com/omendb/omendb-vector)** — Local-first retrieval engine for vector, text, sparse, and metadata search with lifecycle and source evidence. Rust-first, Mojo only where needed for GPU kernels, design from current retrieval literature. Fresh Rust rebuild, research/design phase. *(WIP)*
- **[seerdb](https://github.com/omendb/omendb/tree/main/crates/seerdb)** — Transactional ordered byte-KV storage engine in Rust, developed in the OmenDB workspace as an independently versioned Apache-2.0 crate. WAL recovery, snapshots, and group commit. Developer preview. *(WIP)*
- **[omengrep](https://github.com/nijaru/omengrep)** — Local code search CLI in Rust: Tree-sitter extraction, embeddings plus BM25, owned local storage. Under rewrite. *(WIP)*
- **[mem](https://github.com/nijaru/mem)** — Local memory CLI for agents: durable facts and decisions, past-session history with source references, per-workspace resume state. SQLite with FTS5, no daemon. Pre-1.0, interfaces may change. *(WIP)*
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** — HNSW approximate nearest-neighbor search in pure Go, mmap-backed, with filtering and segment merging.
- **[stt-bench](https://github.com/nijaru/stt-bench)** — Speech-to-text benchmarking across 13 acoustic conditions and four models.

### `agents/`

- **[ion](https://github.com/nijaru/ion)** — Terminal coding agent in Rust: model-facing loop on a single-writer session runtime. Clean-sheet v0 rewrite. *(WIP)*
- **[pi-search](https://github.com/nijaru/pi-search)** — Pi extension for web search, native provider search, page fetching, and local document extraction.
- **[pi-fast-mode](https://github.com/nijaru/pi-fast-mode)** — Pi extension for OpenAI Codex fast mode.
- **[pi-compactor](https://github.com/nijaru/pi-compactor)** — LLM-driven context compaction for coding agents.
- **[pi-subagents](https://github.com/nijaru/pi-subagents)** — Agent delegation for pi with sequential chains and parallel execution.
- **[pi-workflows](https://github.com/nijaru/pi-workflows)** — Durable, resumable workflow orchestration for pi.
- **[pi-goal](https://github.com/nijaru/pi-goal)** — Session-scoped autonomous goals for pi.
- **[pi-usage](https://github.com/nijaru/pi-usage)** — Pi extension that shows OpenAI Codex subscription quota in the footer.
- **[pi-tps](https://github.com/nijaru/pi-tps)** — Pi extension that shows per-request latency and throughput under each response, with session averages in the footer.

### `developer-tools/`

- **[sy](https://github.com/nijaru/sy)** — File synchronization in Rust with rsync-like behavior: delta transfer, parallel I/O, SSH, and reflink support. v3 rewrite in progress. *(WIP)*
- **[aku](https://github.com/nijaru/aku)** — Type-safe Go API framework built on net/http, with request extraction, validation, and OpenAPI generation.
- **[jb](https://github.com/nijaru/jb)** — Background job manager for long-running CLI tasks.
- **[tk](https://github.com/nijaru/tk)** — Task tracker for AI agents with Git-friendly storage and blocking dependencies.
- **[brotli](https://github.com/nijaru/brotli)** — Pure-Go Brotli encoder/decoder (RFC 7932; large-window and multi-stream decode per RFC 9841), drop-in for `andybalholm/brotli`.
- **[brutli](https://github.com/nijaru/brutli)** — Rust Brotli implementation from the spec. Decoder works and the one-shot encoder emits compressed and stored streams; still in compatibility, corpus, and performance validation, not production-ready. *(WIP)*

### `infrastructure/`

- **archon** *(private, WIP)* — Distributed resource manager in Rust: discovery, scheduling, enforceable leases, process and container execution, health and recovery. Lab-proven, not production-scale.
- **engine** *(private, WIP)* — Model inference runtime in Rust: loading and execution, quantized and server inference, batching and scheduling, cache management, hardware backends. Early development; first target is single-GPU NVIDIA.

### `trading/`

- **[go-clob-client](https://github.com/nijaru/go-clob-client)** — Go SDK for the Polymarket CLOB with trading, authentication, and order signing. Unofficial, not production-tested.
- **pacabot** *(private)* — Prediction-market research system using LLMs to analyze market data, news, SEC filings, and congressional trades.
