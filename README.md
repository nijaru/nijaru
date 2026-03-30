I build databases, developer tools, and agents in Go, Python, and Rust. I've also used C, C++, Ruby, and JavaScript, and am exploring Mojo and Zig.

### Infrastructure

- **[omendb](https://github.com/omendb/omendb)** - Embedded vector database. 4x faster than hnswlib-based alternatives. Rust core with Python bindings via PyO3/maturin
- **[omengrep](https://github.com/nijaru/omengrep)** - Semantic code search tool. Tree-sitter parsing for 22 languages
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** - Native Go HNSW graph implementation with pluggable distance metrics and generic type support
- **[aku](https://github.com/nijaru/aku)** - Go API library with typed handlers and automatic request extraction. net/http-native with OpenAPI generation.

### AI & Agents

- **[canto](https://github.com/nijaru/canto)** - Go agent framework. Composable layers, append-only event log, and deterministic code-driven orchestration for LLM agents and swarms
- **[ion](https://github.com/nijaru/ion)** - TUI coding agent with multi-provider LLM support built on canto
- **[jb](https://github.com/nijaru/jb)** - Background job manager. Session-persistent execution for long-running tasks
- **[tk](https://github.com/nijaru/tk)** - Task tracker for AI agents. Git-friendly storage with blocking dependencies

### Trading

- **pacabot** - Prediction market trading bot. Event-driven order execution with real-time risk management
- **[go-clob-client](https://github.com/nijaru/go-clob-client)** - Go SDK for the Polymarket CLOB. Supports trading, authentication, and order signing.
- **[go-polymarket-data](https://github.com/nijaru/go-polymarket-data)** - Go client for the Polymarket data API

---

> "There are only two hard things in Computer Science: cache invalidation, naming things, and off-by-one errors."
