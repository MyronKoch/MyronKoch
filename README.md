# Myron Koch

**Independent AI Researcher & Agentic Engineer**
- Agent harnesses, multi-agent orchestration, MCP infrastructure.
- Founder of [Peak Summit Labs](https://peaksummitlabs.com).

[![Blog](https://img.shields.io/badge/Blog-operationalsemantics.dev-blue?style=flat-square)](https://operationalsemantics.dev)
[![BMCPS Standard](https://img.shields.io/badge/Standard-BMCPS_v3.0-orange?style=flat-square)](https://bmcps.dev)
[![Portfolio](https://img.shields.io/badge/Portfolio-myronkoch.dev-green?style=flat-square)](https://myronkoch.dev)
[![Peak Summit Labs](https://img.shields.io/badge/Company-Peak_Summit_Labs-0ea5e9?style=flat-square)](https://peaksummitlabs.com)

---

### What I Do

I build AI infrastructure and ship it as products. Research becomes tools. Tools become papers. Papers validate the tools. One flywheel.

- **Agent Harness & Orchestration** - Cross-machine agent coordination across multiple Macs via Cloudflare Durable Objects. A full harness: 80+ skills, 38 hooks, terminal-spawned agents with backchannel messaging. Not a framework - a production system I use daily.

- **MCP Infrastructure** - 16+ MCP servers built on MCP, now a Linux Foundation open standard. Authored [BMCPS v3.0](https://bmcps.dev), an open standard for blockchain MCP tool interfaces (25 mandatory tools, 238 automated tests, MIT licensed). Built a [meta-server that generates new MCP servers](https://operationalsemantics.dev/posts/11-mcp-factory-complete-story) from the standard.

- **Semantic Memory** - [Persistent memory system](https://github.com/MyronKoch/longterm-memory-macos) using PostgreSQL + pgvector. 10,000+ observations, cross-device sync, semantic search across sessions. [Research paper](https://huggingface.co/datasets/myronkoch/reminisce-longmemeval-results/blob/main/paper/reminisce.pdf) with 49.4-55.8% accuracy and ~81% precision on LongMemEvalS (98.3% peak on direct single-session recall).

- **Open Source** - Contributor to [Rectangle](https://github.com/rxhanson/Rectangle) (29K+ stars). Two merged PRs: [#1720](https://github.com/rxhanson/Rectangle/pull/1720) (new grid divisions + cycling) and [#1762](https://github.com/rxhanson/Rectangle/pull/1762) (overlap offset).

- **Shipped Products** - Three products through [Peak Summit Labs](https://peaksummitlabs.com). Local-first, one-time pricing, no telemetry. I build what teams quote 9 months for - solo, using the AI infrastructure I built.

---

### Featured Projects

| Project | What It Does |
|---------|-------------|
| [**reminisce**](https://github.com/MyronKoch/reminisce) | Cognitive science-inspired memory architecture for AI agents - working/episodic/semantic tiers with salience scoring. [Paper](https://huggingface.co/datasets/myronkoch/reminisce-longmemeval-results/blob/main/paper/reminisce.pdf) &#124; [Benchmark Data](https://huggingface.co/datasets/myronkoch/reminisce-longmemeval-results) |
| [**longterm-memory-macos**](https://github.com/MyronKoch/longterm-memory-macos) | Semantic memory for Claude - PostgreSQL + pgvector with browser extension and dashboard |
| [**evm-chains-mcp-server**](https://github.com/MyronKoch/evm-chains-mcp-server) | 111 tools across 7 networks - MCP at scale for complex multi-system orchestration |
| [**ccxt-mcp-server**](https://github.com/MyronKoch/ccxt-mcp-server) | Unified MCP interface to 106+ financial data APIs with real-time arbitrage detection |
| [**academic-lectures**](https://github.com/MyronKoch/academic-lectures) | Lecture materials from guest lectures to university engineering and blockchain societies at Harvard, MIT, Princeton, Cornell Tech, NYU, and Oxford |

---

### Speaking

Guest lectures to university engineering and blockchain societies at **Harvard** (x2), **MIT**, **Princeton**, **Cornell Tech**, **NYU**, and **Oxford**. Keynote at **Web3 Summit Amsterdam**. Eight talks in six months on AI systems, agent orchestration, and MCP infrastructure.

Full lecture portfolio: [academic-lectures](https://github.com/MyronKoch/academic-lectures)

---

### Research

**Papers (one preprint on arXiv; all with Zenodo DOIs; datasets on Hugging Face):**
- **[PrimeAgentOrchestrator: Memory-Primed Agent Spawning for Personal AI Infrastructure](https://arxiv.org/abs/2608.20342)** (2026) - Spawns coding agents pre-loaded with memories from PostgreSQL + semantic search. 15-task precision study, four months of production deployment. **[arXiv:2608.20342](https://arxiv.org/abs/2608.20342)** (cs.AI, cross-listed cs.MA) · DOI: [10.5281/zenodo.20735389](https://doi.org/10.5281/zenodo.20735389) · [data](https://huggingface.co/datasets/myronkoch/prime-agent-orchestrator)
- **[The Placeholder That Became Production: A Postmortem of Extractive Memory Under Continuous Multi-Agent Ingestion](https://doi.org/10.5281/zenodo.20735397)** (2026) - Production postmortem of the Reminisce memory system; noise ratio 0% → 77.2%, total-cost-of-retirement analysis. DOI: [10.5281/zenodo.20735397](https://doi.org/10.5281/zenodo.20735397) · [data](https://huggingface.co/datasets/myronkoch/reminisce-production-postmortem)
- **[Reminisce: A Cognitive Science-Inspired Memory Architecture for AI Agents](https://doi.org/10.5281/zenodo.20088749)** (2026) - Three-tier cognitive memory with salience scoring. 49.4-55.8% accuracy and ~81% precision on LongMemEvalS (98.3% peak on direct single-session recall). DOI: [10.5281/zenodo.20088749](https://doi.org/10.5281/zenodo.20088749) · [data](https://huggingface.co/datasets/myronkoch/reminisce-longmemeval-results)
- **[DeadGraph: A Rights-Aware MCP Knowledge Base for Cultural Heritage Audio Collections](https://huggingface.co/datasets/myronkoch/deadgraph/blob/main/paper.pdf)** (2026) - 13 MCP tools, 200-question benchmark, +60.1 point accuracy gain over raw LLM. Preprint on Hugging Face (Zenodo DOI coming).

---

### Products (Peak Summit Labs)

| Product | What It Is |
|---------|-----------|
| [**Push to Transcribe**](https://pushtotranscribe.com) | Voice-to-text for macOS and Windows. Hold a key, speak, release - text appears. Whisper-powered, fully local. One-time purchase. |
| [**markdossier**](https://markdossier.com) | WYSIWYG markdown editor for macOS and Windows. Renders Claude Code and Codex sessions as conversations. Hot-reload, Quick Look, annotations. One-time purchase. |
| [**DeadGraph**](https://deadgraph.com) | AI research assistant for the Grateful Dead's live history. 2,336 shows, 13 MCP tools, rights-aware pipeline. |

---

### Technical Writing

50+ posts at [operationalsemantics.dev](https://operationalsemantics.dev) documenting the full journey from MCP experiments to published standard and multi-agent systems. Includes an 8-part series on the university lecture tour.

---

### Stack

**Languages:** TypeScript, Python, Swift, Rust
**AI:** Claude, MCP, Ollama, LM Studio
**Infrastructure:** Cloudflare (Workers, D1, R2, Pages), PostgreSQL, pgvector, bun

---

<p align="center">
  <a href="https://operationalsemantics.dev">Blog</a> -
  <a href="https://bmcps.dev">BMCPS Standard</a> -
  <a href="https://myronkoch.dev">Portfolio</a> -
  <a href="https://peaksummitlabs.com">Peak Summit Labs</a> -
  <a href="https://linkedin.com/in/myronkoch">LinkedIn</a> -
  <a href="https://x.com/myronkoch">X</a>
</p>
