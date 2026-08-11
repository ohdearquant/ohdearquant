# Haiyang (Ocean) Li

Founder, [khive AI](https://khive.ai). Building memory and coordination infrastructure for long-horizon AI agents, in Rust and Python.

The commit activity here is real: my repos are built around the clock by the agent fleet they serve. I design the architecture, set the constraints, and gate the merges; the agents do the rest. Every rough edge my agents hit is one your agents would have hit too, so the product is the residue of running the thing at full intensity.

Co-founder, [Agentics Foundation](https://agentics.org) | AG2 maintainer | New York, NY

## One stack, built deep

Four systems, one loop: **khive** remembers and coordinates, **lionagi** orchestrates, **Lattice** computes, **LNkernel** proves.

| Project | What it is | Stack |
|---------|------------|-------|
| [khive](https://github.com/ohdearquant/khive) | Agentic memory and coordination substrate, served over MCP: entity graphs, hybrid retrieval, durable task state, inter-agent messaging | Rust, SQLite, Fly.io |
| [lionagi](https://github.com/ohdearquant/lionagi) | Agent orchestration framework: model-agnostic tool use, structured output, multi-agent flows | Python, 400+ stars |
| [Lattice](https://github.com/ohdearquant/lattice) | Pure Rust inference engine: SIMD kernels (AVX2, NEON, AVX-512), Metal GPU, embedding models, no Python runtime | Rust, Metal, crates.io |
| [LNkernel](https://github.com/ohdearquant/LNkernel) | Formally verified agentic kernel: Rust-to-Lean correspondence via Charon/Aeneas, 0 `sorry` | Rust, Lean4 |

## Depth

- **Retrieval**: HNSW + BM25 + reciprocal rank fusion in-process, SIMD-accelerated similarity, no external vector DB
- **Inference**: transformer forward pass from scratch, LoRA injection, QuaRot 4-bit quantization
- **Memory for agents**: salience-weighted recall, decay, provenance, feedback-trained retrieval
- **Formal methods**: Lean4 proofs extracted from the Rust that actually ships

## Background

M.S. Quantitative Finance, Fordham University. B.S. Finance and Information Management, Syracuse University. Markets first, infrastructure second, agents now.

[khive.ai](https://khive.ai) | [LinkedIn](https://www.linkedin.com/in/quantoceanli/)
