I work on databases, developer tools, agent infrastructure, and systems software, primarily in Go, Rust, Python, TypeScript, and Mojo.

## `~/projects`

### `databases-and-search/`

- **[OmenDB](https://github.com/omendb/omendb)** — Server-first relational database for PostgreSQL-class single-node OLTP, written in Rust and built on SeerDB.
- **[OmenDB Vector](https://github.com/omendb/omendb-vector)** — Embedded Mojo/Python database for vector and hybrid text retrieval.
- **[SeerDB](https://github.com/omendb/seerdb)** — Embedded durable ordered byte-KV storage engine for Rust consumers.
- **[omengrep](https://github.com/nijaru/omengrep)** — Semantic code-search CLI combining Tree-sitter, embeddings, and BM25.
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** — Pure-Go HNSW vector search with mmap-backed persistence, filtering, and segment merging.

### `agents/`

- **[Ion](https://github.com/nijaru/ion)** — Terminal coding agent in Rust with a durable session runtime and multi-provider model support.
- **[pi-search](https://github.com/nijaru/pi-search)** — Provider-neutral Pi extension for web search, fetching, and bounded research.
- **[pi-subagents](https://github.com/nijaru/pi-subagents)** — Pi extension for declarative single, parallel, and chained agent delegation.
- **[pi-workflows](https://github.com/nijaru/pi-workflows)** — Pi extension for durable, resumable, provider-neutral workflow orchestration.
- **[pi-compactor](https://github.com/nijaru/pi-compactor)** — Pi extension for model-directed context compaction.
- **[pi-fast-mode](https://github.com/nijaru/pi-fast-mode)** — Pi extension for toggling OpenAI Codex fast mode with accurate cost accounting.
- **[pi-usage](https://github.com/nijaru/pi-usage)** — Pi extension that shows OpenAI Codex subscription quota in the footer.
- **[Pilon](https://github.com/nijaru/pilon)** — Desktop workbench for running, supervising, reviewing, and merging Pi coding-agent sessions.

### `developer-tools/`

- **[sy](https://github.com/nijaru/sy)** — Rust file synchronization with delta transfers, parallel I/O, SSH, and reflink support.
- **[aku](https://github.com/nijaru/aku)** — Type-safe Go API framework built on net/http, with request extraction, validation, and OpenAPI generation.
- **[jb](https://github.com/nijaru/jb)** — Background job manager for long-running CLI tasks.
- **[tk](https://github.com/nijaru/tk)** — Task tracker for AI agents with Git-friendly storage and blocking dependencies.
- **[stop](https://github.com/nijaru/stop)** — JSON-first process monitoring for agents and automation.
- **[ripgo](https://github.com/nijaru/ripgo)** — Ripgrep-compatible content search and fd-like path finding in Go.
- **[brotli](https://github.com/nijaru/brotli)** — Updated fork of the pure-Go Brotli compression and decompression library.

### `trading/`

- **[go-clob-client](https://github.com/nijaru/go-clob-client)** — Go SDK for the Polymarket CLOB with trading, authentication, and order signing.
- **pacabot** *(private)* — Prediction-market research system using LLMs to analyze market data, news, SEC filings, and congressional trades.
