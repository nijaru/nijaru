I work on databases, developer tools, and agent infrastructure, primarily in Go, Rust, Python, TypeScript, and Mojo.

## `~/projects`

### `data-and-search/`

- **[omendb](https://github.com/omendb/omendb)** — Relational database in development for PostgreSQL-class single-node OLTP, written in Rust and built on SeerDB.
- **[omendb-rs](https://github.com/omendb/omendb-rs)** — Rust vector database implementation with Python and Node.js bindings.
- **[omendb-vector](https://github.com/omendb/omendb-vector)** — Mojo/Python vector and hybrid retrieval database in development.
- **[seerdb](https://github.com/omendb/seerdb)** — Embedded durable ordered byte-KV storage engine for Rust consumers.
- **[omengrep](https://github.com/nijaru/omengrep)** — Semantic code search CLI with Tree-sitter parsing.
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** — Pure-Go HNSW vector search with mmap-backed persistence, filtering, and segment merging.
- **[stt-bench](https://github.com/nijaru/stt-bench)** — Speech-to-text benchmarking across 13 acoustic conditions and four models.

### `agents/`

- **[ion](https://github.com/nijaru/ion)** — Terminal coding agent in Rust with multi-provider LLM support, tool execution, and session management.
- **[pi-search](https://github.com/nijaru/pi-search)** — Pi extension for web search, native provider search, page fetching, and local document extraction.
- **[pi-fast-mode](https://github.com/nijaru/pi-fast-mode)** — Pi extension for OpenAI Codex fast mode.
- **[pi-compactor](https://github.com/nijaru/pi-compactor)** — LLM-driven context compaction for coding agents.
- **[pi-subagents](https://github.com/nijaru/pi-subagents)** — Agent delegation for pi with sequential chains and parallel execution.
- **[pi-goal](https://github.com/nijaru/pi-goal)** — Session-scoped autonomous goals for pi.
- **[pi-usage](https://github.com/nijaru/pi-usage)** — Pi extension that shows OpenAI Codex subscription quota in the footer.

### `developer-tools/`

- **[sy](https://github.com/nijaru/sy)** — Rust file synchronization with delta transfers, parallel I/O, SSH, and reflink support.
- **[aku](https://github.com/nijaru/aku)** — Type-safe Go API framework built on net/http, with request extraction, validation, and OpenAPI generation.
- **[jb](https://github.com/nijaru/jb)** — Background job manager for long-running CLI tasks.
- **[tk](https://github.com/nijaru/tk)** — Task tracker for AI agents with Git-friendly storage and blocking dependencies.
- **[brotli](https://github.com/nijaru/brotli)** — Improved pure-Go Brotli implementation.
- **[brutli](https://github.com/nijaru/brutli)** — Rust Brotli implementation under active development, competitive with c2rust.

### `trading/`

- **[go-clob-client](https://github.com/nijaru/go-clob-client)** — Go SDK for the Polymarket CLOB with trading, authentication, and order signing.
- **pacabot** *(private)* — Prediction-market research system using LLMs to analyze market data, news, SEC filings, and congressional trades.
