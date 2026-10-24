## Anmol Sharma

I build AI agents and the systems underneath them. Most of my work sits where the two meet: an agent is only as trustworthy as the sandbox it runs in, the retrieval it relies on and the numbers it reports. I work mainly in Python, build the web side in TypeScript with Next.js, reach for Rust and Go when performance matters, and do all of it on a Linux setup I maintain myself. I studied Data Science and AI at IIT Mandi.

I'm looking for roles in AI engineering, agentic systems, backend and systems engineering, or applied research.

### What I'm building

**CanonData** (private) turns the messy CSV exports a store already has, from Shopify, Amazon, Meta and Google, into numbers the business can audit. Every figure traces back to the file, row and column it came from. When a language model answers a question, its numbers have to match what the engine computed, or the answer is replaced with a deterministic one.

### Selected work

**[Nimbus](https://github.com/anmolsharma152/nimbus)** gives a coding agent a disposable Docker container with every Linux capability dropped and hard limits on memory, CPU and processes, then lets it edit a repository, run the tests and open a pull request. [Live demo](https://nimbusagent.vercel.app/)

**[CodexEngine](https://github.com/anmolsharma152/CodexEngine)** is a retrieval service that measures its own answers: hybrid pgvector and BM25 search, CrossEncoder reranking, and RAGAS scores against a golden set of queries. [Live demo](https://codex-engine.vercel.app/)

**[rust-agent-core](https://github.com/anmolsharma152/rust-agent-core)** is a terminal agent in Rust. It ships as one binary, embeds documents locally with ONNX so search works offline, and gates every tool call behind read-only, safe or unrestricted modes.

**[respy](https://github.com/anmolsharma152/respy)** is a Redis-compatible server and pub/sub broker in Go, written with only the standard library, including both of Redis's persistence formats.

**[Aura](https://github.com/anmolsharma152/Aura)** brings face login to Linux. A small C PAM module hands each request to a Python daemon over a Unix socket, so the ONNX models never run inside the login process.

Also: [Disha](https://github.com/anmolsharma152/Disha) (multi-agent job-market research), [commerce_cortex](https://github.com/anmolsharma152/commerce_cortex) (agent with human approval steps and LLM tracing), [a local voice assistant](https://github.com/anmolsharma152/Emotion-Aware-Voice-Assistant), [Hindi and Hinglish instruction-tuning for Sarvam-1](https://github.com/anmolsharma152/sarvam-1-indic-instructor) (training in progress), [ML-Foundations](https://github.com/anmolsharma152/ML-Foundations) (coursework notebooks, from classical ML to transformers and RL), [AlgoDeck](https://github.com/anmolsharma152/AlgoDeck), [IdeaForge](https://github.com/anmolsharma152/IdeaForge) and [Scholar-Loop](https://github.com/anmolsharma152/Scholar-Loop).

### Contributions to other projects

- **[Omarchy](https://github.com/omacom/omarchy)**: my [theme was added to the official gallery](https://github.com/omacom/omarchy-site/pull/445); pull requests open for [volume routing](https://github.com/omacom/omarchy/pull/14683) and the [Wayland session file](https://github.com/omacom/omarchy/pull/15812).
- **[hiring-agent](https://github.com/interviewstreet/hiring-agent)** by HackerRank: [fixed parsing of nested GitHub profile fields](https://github.com/interviewstreet/hiring-agent/pull/362) (merged).

My [Hyprland setup](https://github.com/anmolsharma152/omarchy-quattro-dotfiles), [Space Marine theme](https://github.com/anmolsharma152/omarchy-space-marine-theme) and [homelab](https://github.com/anmolsharma152/homelab) are public too.

---

[Portfolio](https://anmolsharma152.vercel.app) · [LinkedIn](https://linkedin.com/in/anmolsharma152) · [Hugging Face](https://huggingface.co/okozymandias) · [X](https://x.com/ozymandias152) · [Email](mailto:anmolsharma152.dev@gmail.com)
