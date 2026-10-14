<p align="center">
  <img src="assets/banner.svg" alt="The model is the interface. khive is the computer." width="100%">
</p>

# Haiyang (Ocean) Li

Founder of [khive AI](https://khive.ai), New York. I build the infrastructure long-horizon AI agents run on:
a system of record and operations for agent organizations ([khive](https://github.com/ohdearquant/khive)),
an orchestration framework ([lionagi](https://github.com/ohdearquant/lionagi)), a workspace for AI agents
([khive computer](https://github.com/ohdearquant/khive-computer)), a pure Rust inference engine for Apple Silicon
([Lattice](https://github.com/ohdearquant/lattice)) and a formally verified agent kernel
([LNkernel](https://github.com/ohdearquant/LNkernel)). Rust and Python, open source, built in public.

Each project is run by the agents it serves before it ships. I design the architecture, set the constraints and
gate the merges.

<p>
  <a href="https://pypi.org/project/lionagi/"><img src="https://img.shields.io/pypi/v/lionagi?style=flat-square&label=lionagi&labelColor=0b0b0c&color=2a2a2e" alt="lionagi on PyPI"></a>
  <a href="https://pypi.org/project/khive-computer/"><img src="https://img.shields.io/pypi/v/khive-computer?style=flat-square&label=khive-computer&labelColor=0b0b0c&color=2a2a2e" alt="khive-computer on PyPI"></a>
  <a href="https://crates.io/search?q=khive"><img src="https://img.shields.io/badge/khive-50%2B%20crates-2a2a2e?style=flat-square&labelColor=0b0b0c" alt="khive on crates.io"></a>
  <a href="https://khive.ai"><img src="https://img.shields.io/badge/khive%20cloud-khive.ai-2a2a2e?style=flat-square&labelColor=0b0b0c" alt="khive cloud"></a>
  <a href="https://www.linkedin.com/in/quantoceanli/"><img src="https://img.shields.io/badge/LinkedIn-quantoceanli-2a2a2e?style=flat-square&labelColor=0b0b0c" alt="LinkedIn"></a>
</p>

Co-founder, [Agentics Foundation](https://agentics.org) · co-maintainer, [AG2](https://github.com/ag2ai/ag2) ·
[Lion Saturday](https://github.com/ohdearquant/Live-Streaming) live streams

## The stack

<p align="center">
  <img src="assets/stack.svg" alt="The stack: a model on top; lionagi orchestrates; khive remembers and coordinates; khive computer is the workspace; Lattice computes; LNkernel proves." width="100%">
</p>

**[khive](https://github.com/ohdearquant/khive)** <a href="https://github.com/ohdearquant/khive/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/khive?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="khive stars" align="top"></a>  
The system of record and operations for agent-native organizations, served over MCP: entity graph with typed edges, hybrid retrieval (HNSW, BM25, rank fusion, in process), durable task state, memory with salience and decay, inter-agent messaging. Hosted at [khive.ai](https://khive.ai); self-hosted from one binary and SQLite. Get it: [crates.io](https://crates.io/search?q=khive) · [docs](https://ohdearquant.github.io/khive/).

**[lionagi](https://github.com/ohdearquant/lionagi)** <a href="https://github.com/ohdearquant/lionagi/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/lionagi?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="lionagi stars" align="top"></a>  
Agent orchestration, built continuously since 2023: model-agnostic tool use, structured output, multi-agent flows, typed operations. The runtime my own fleet runs on. Get it: `pip install lionagi`.

**[khive computer](https://github.com/ohdearquant/khive-computer)** <a href="https://github.com/ohdearquant/khive-computer/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/khive-computer?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="khive computer stars" align="top"></a>  
Workspace for AI agents, over MCP. Files live in content-addressed trees and a write returns a new tree; refs move by compare-and-swap with history; commands run on a tree in a sandbox and come back as a tree, cached by their inputs; git at the edge; one token is one seat. Eight tools. Get it: `uv tool install khive-computer` · `kc up`.

**[Lattice](https://github.com/ohdearquant/lattice)** <a href="https://github.com/ohdearquant/lattice/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/lattice?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="Lattice stars" align="top"></a>  
Transformer inference in pure Rust on Apple Silicon: Qwen 3+ and Gemma 4 including vision-language and vision embedding, Metal and CPU, quantization and LoRA fine-tuning, a native macOS app. No Python, no CUDA, no ONNX; about 5% of ONNX Runtime's binary size. Serves embeddings on a Raspberry Pi.

**[LNkernel](https://github.com/ohdearquant/LNkernel)** <a href="https://github.com/ohdearquant/LNkernel/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/LNkernel?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="LNkernel stars" align="top"></a>  
A formally verified agentic kernel: Lean 4 proofs of the kernel data structures, the capability algebra and the policy rules, machine-checked against the Rust definitions.

### Also public

**[moodboard](https://github.com/ohdearquant/moodboard)** <a href="https://github.com/ohdearquant/moodboard/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/moodboard?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="moodboard stars" align="top"></a>  
Visual coherence measurement: how well an image fits a board's look, with calibrated intervals and a traceable offline report.

**[CanonSys](https://github.com/ohdearquant/canonsys)** <a href="https://github.com/ohdearquant/canonsys/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/canonsys?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="CanonSys stars" align="top"></a>  
Agent governance: a policy DSL, a charter runtime and a cryptographic evidence chain.

**[medgraph](https://github.com/ohdearquant/medgraph)** <a href="https://github.com/ohdearquant/medgraph/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/medgraph?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="medgraph stars" align="top"></a>  
ICD-10-CM read as the graph it already is, packed for khive, with a one-command demo.

**[lionag2](https://github.com/ohdearquant/lionag2)** <a href="https://github.com/ohdearquant/lionag2/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/lionag2?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="lionag2 stars" align="top"></a>  
lionagi primitives on AG2: multi-player, multi-threaded agent orchestration.

**[lean-proofs](https://github.com/ohdearquant/lean-proofs)** <a href="https://github.com/ohdearquant/lean-proofs/stargazers"><img src="https://img.shields.io/github/stars/ohdearquant/lean-proofs?style=flat-square&label=stars&labelColor=0b0b0c&color=2a2a2e" alt="lean-proofs stars" align="top"></a>  
Formal proofs in Lean 4.

**Quant notes**  
[American put optimization](American%20Put%20Optimization.md) · [SPX option intraday backtest](SPX%20option%20intraday%20backtest.md)

## Entry points

| I want to… | Start here | Then |
| --- | --- | --- |
| Give my agents a system of record: memory, tasks, messages, a graph | [khive.ai](https://khive.ai) or [self-host khive](https://github.com/ohdearquant/khive) | connect any MCP client to it |
| Give an agent a place to work: trees, refs, sandboxed commands, git | [khive computer](https://github.com/ohdearquant/khive-computer) | `kc up` and hand the client the token |
| Orchestrate agents in Python with structured output | [lionagi](https://github.com/ohdearquant/lionagi) | run them against a khive and a computer |
| Run Qwen or Gemma on a Mac with no Python runtime | [Lattice](https://github.com/ohdearquant/lattice) | embeddings, reranking and classification in process |
| Read machine-checked proofs about an agent kernel | [LNkernel](https://github.com/ohdearquant/LNkernel) | the Lean 4 side of the Rust |

## Numbers, dated

Public GitHub API, **October 14, 2026**. Owned repositories, forks excluded.

| Measure | Value |
| --- | ---: |
| Followers | 189 |
| Public repositories | 16, of which 12 owned and not forks |
| Stars across owned public non-fork repositories | 527 |
| lionagi | 412 stars, 85 forks |
| Lattice | 45 stars |
| khive | 33 stars |

Stars measure attention, not users; downloads count fetches, not people.

## Now

- **khive computer 0.1.0** is on [PyPI](https://pypi.org/project/khive-computer/) with the image on
  [ghcr](https://github.com/ohdearquant/khive-computer/pkgs/container/khive-computer): `uv tool install khive-computer`, `kc up`.
- **khive cloud** is open at [khive.ai](https://khive.ai): the hosted khive, MCP at `khive.ai/v1/mcp`.

## Background

M.S. Quantitative Finance, Fordham University. B.S. Finance and Information Management & Technology, Syracuse
University. Markets first, infrastructure second, agents now.

[khive.ai](https://khive.ai) · [LinkedIn](https://www.linkedin.com/in/quantoceanli/) · [Lion Saturday](https://github.com/ohdearquant/Live-Streaming)
