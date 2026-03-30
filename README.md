# Myron Koch

**AI Systems Architect** · Building the tooling layer between language models and real-world infrastructure

[![Blog](https://img.shields.io/badge/Blog-operationalsemantics.dev-blue?style=flat-square)](https://operationalsemantics.dev)
[![BMCPS Standard](https://img.shields.io/badge/Standard-BMCPS_v3.0-orange?style=flat-square)](https://bmcps.dev)
[![Portfolio](https://img.shields.io/badge/Portfolio-myronkoch.dev-green?style=flat-square)](https://myronkoch.dev)

---

### What I Work On

I build infrastructure that connects AI models to real systems — giving agents the ability to query, deploy, orchestrate, and take action across live environments through structured tool interfaces.

My focus areas:

- **MCP Server Architecture** — Designed and built 7 production MCP servers exposing 200+ tools. Published [BMCPS v3.0](https://bmcps.dev), an open standard for consistent, safe tool interfaces. Built a meta-server that [generates new MCP servers automatically](https://operationalsemantics.dev/posts/11-mcp-factory-complete-story) from the standard.

- **Multi-Agent Coordination** — Built a [6-agent orchestration system](https://operationalsemantics.dev/posts/14-multi-agent-orchestration) with 33 team templates for parallel task execution. Model-agnostic — works with Claude, GPT, Ollama, and local models.

- **Semantic Memory for Agents** — Created a [persistent memory system](https://github.com/MyronKoch/longterm-memory-macos) using PostgreSQL + pgvector that gives Claude long-term recall across sessions, with a browser extension and dashboard.

- **Technical Writing** — 45 posts at [operationalsemantics.dev](https://operationalsemantics.dev) documenting the full arc from experimental MCP development to published standard.

---

### Featured Projects

| Project | What It Does |
|---------|-------------|
| [**reminisce**](https://github.com/MyronKoch/reminisce) | Cognitive science-inspired memory architecture for AI agents -- working/episodic/semantic tiers with salience scoring. 98.3% precision on user recall. [Paper](https://github.com/MyronKoch/reminisce/blob/main/paper/reminisce.pdf) &#124; [Benchmark Data](https://huggingface.co/datasets/myronkoch/reminisce-longmemeval-results) |
| [**longterm-memory-macos**](https://github.com/MyronKoch/longterm-memory-macos) | Semantic memory for Claude -- PostgreSQL + pgvector with browser extension and dashboard |
| [**ai-team-orchestrator**](https://operationalsemantics.dev/posts/14-multi-agent-orchestration) | Model-agnostic multi-agent coordination — 6-agent tmux workspace, 33 team templates, 19 MCP tools ([deep dive](https://operationalsemantics.dev/posts/15-the-ai-dream-team)) |
| [**mcp-factory**](https://operationalsemantics.dev/posts/11-mcp-factory-complete-story) | Meta-MCP server — auto-generates standard-compliant MCP servers from a single schema ([how it works](https://operationalsemantics.dev/posts/12-mcp-factory-fantom-success)) |
| [**evm-chains-mcp-server**](https://github.com/MyronKoch/evm-chains-mcp-server) | 111 tools across 7 networks — demonstrates MCP at scale for complex multi-system orchestration |
| [**ccxt-mcp-server**](https://github.com/MyronKoch/ccxt-mcp-server) | Unified MCP interface to 106+ financial data APIs with real-time arbitrage detection |
| [**academic-lectures**](https://github.com/MyronKoch/academic-lectures) | Lecture materials from teaching engagements at Ivy League institutions and Oxford |

---

### Speaking

Guest lectures at **Harvard**, **MIT**, **Princeton**, **Cornell Tech**, **NYU**, and **Oxford**. Keynote at **Web3 Summit Amsterdam**. Topics include agentic workflows, LLM architectures, AI-driven automation, and building developer tools for emerging platforms.

See the full lecture portfolio: [academic-lectures](https://github.com/MyronKoch/academic-lectures)

---

### Research

**Publications:**
- **[Reminisce: A Cognitive Science-Inspired Memory Architecture for AI Agents](https://github.com/MyronKoch/reminisce/blob/main/paper/reminisce.pdf)** (March 2026) -- Three-tier cognitive memory with salience scoring, evaluated on LongMemEvalS across 3 Claude model tiers. Key finding: precision is architecture-dependent (~81%) while coverage is model-dependent (29-40% abstention).

**Interests:**
- Cognitive science-inspired memory architectures for AI agents
- Multi-agent cooperation and task decomposition
- Tool-call runtimes and safe execution patterns
- Model behavior at the boundary of reasoning and action

---

### Stack

**Languages:** TypeScript, Python, Rust
**AI Platforms:** Claude, MCP, Ollama, LM Studio, OpenAI
**Infrastructure:** PostgreSQL, pgvector, Cloudflare Workers, Node.js, bun

---

<p align="center">
  <a href="https://operationalsemantics.dev">Blog</a> ·
  <a href="https://bmcps.dev">BMCPS Standard</a> ·
  <a href="https://myronkoch.dev">Portfolio</a> ·
  <a href="https://linkedin.com/in/myronkoch">LinkedIn</a> ·
  <a href="https://x.com/myronkoch">X</a>
</p>
