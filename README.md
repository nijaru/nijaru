I build databases, developer tools, and agents in Go, Rust, and TypeScript.

### Databases & Search

- **[omendb](https://github.com/omendb/omendb)** - Embedded vector database. 4x faster than hnswlib. Rust core with Python and TypeScript bindings
- **[omengrep](https://github.com/nijaru/omengrep)** - Semantic code search CLI. Tree-sitter parsing for 22 languages, hybrid embedding + BM25 ranking
- **[hnsw-go](https://github.com/nijaru/hnsw-go)** - Native Go HNSW graph implementation with pluggable distance metrics
- **[stt-bench](https://github.com/nijaru/stt-bench)** - Speech-to-text benchmarking across 13 acoustic conditions. Published results for 4 models

### Agents & AI

- **[ion](https://github.com/nijaru/ion)** - Terminal coding agent in Go. 43K lines. Multi-provider LLM support, tool execution, session management
- **[pi-compactor](https://github.com/nijaru/pi-compactor)** - LLM-driven context compaction for coding agents. Model decides when to compact, not thresholds
- **[pi-subagents](https://github.com/nijaru/pi-subagents)** - Agent delegation for pi. Define agents as markdown, chain them in sequence or run in parallel
- **[pi-goal](https://github.com/nijaru/pi-goal)** - Persistent autonomous goals for pi. Agent works until done, with git-native checkpoints
- **[pi-workflows](https://github.com/nijaru/pi-workflows)** - Parallel agent orchestration for pi. Budget caps, cross-session resume, cost tracking
- **[agent-research](https://github.com/nijaru/agent-research)** - Source-level analysis of frontier agent implementations (Claude Code, Codex, Gemini, Cursor)

### Developer Tools

- **[sy](https://github.com/nijaru/sy)** - File sync tool with delta transfers. Rust. 40-79% faster than rsync
- **[aku](https://github.com/nijaru/aku)** - Go API framework with typed handlers. Request parsing and OpenAPI docs derived from Go types
- **[jb](https://github.com/nijaru/jb)** - Background job manager for long-running CLI tasks
- **[tk](https://github.com/nijaru/tk)** - Task tracker for AI agents. Git-friendly storage with blocking dependencies
- **[brotli](https://github.com/nijaru/brotli)** - Pure Go Brotli encoder and decoder
- **[avc](https://github.com/nijaru/avc)** - Agent-native Git-compatible VCS. Local workbench for AI-assisted development

### Trading

- **[pacabot](https://github.com/nijaru/pacabot)** - Prediction market trading system. LLM-driven analysis of market data, news, SEC filings, and congressional trades
- **[go-clob-client](https://github.com/nijaru/go-clob-client)** - Go SDK for the Polymarket CLOB. Trading, authentication, and order signing
