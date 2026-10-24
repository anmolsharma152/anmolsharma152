## Anmol Sharma

AI and systems engineer. I build LLM agents, retrieval systems and the backend infrastructure they run on, in Python and Rust, with Go when it fits. I like working close to Linux: sandboxing, authentication, servers and runtimes. I studied Data Science and AI at IIT Mandi.

I'm looking for roles in **AI engineering, agentic systems, backend/systems engineering and applied research**.

### Building now

**CanonData** (private): a reconciliation and audit engine for e-commerce financial exports. It rebuilds one consistent view of orders, inventory and ad spend from Shopify, Amazon, Meta and Google CSVs, traces every figure back to its source row, and runs nine detectors for margin leaks. Language-model answers must match engine-computed numbers or are replaced by a deterministic template. Python, Polars, FastAPI, PostgreSQL; 200+ tests.

### Agentic AI and ML

| Project | |
|---|---|
| [Nimbus](https://github.com/anmolsharma152/nimbus) | Coding agent that runs each task in a locked-down Docker container (all capabilities dropped, memory, CPU and process limits), runs the tests and opens a pull request, streaming output over WebSockets. FastAPI, Redis/arq, PostgreSQL. [Demo](https://nimbusagent.vercel.app/) |
| [CodexEngine](https://github.com/anmolsharma152/CodexEngine) | RAG service with a LangGraph pipeline, hybrid pgvector + BM25 retrieval, CrossEncoder reranking and RAGAS evaluation on a golden query set. [Demo](https://codex-engine.vercel.app/) |
| [Disha](https://github.com/anmolsharma152/Disha) | Multi-agent job-market research platform: a LangGraph supervisor routes between specialist agents, with pgvector memory and Playwright data collection. |
| [commerce_cortex](https://github.com/anmolsharma152/commerce_cortex) | Stateful operations agent with Postgres-checkpointed LangGraph state, human-in-the-loop approvals, and tracing and evals through OpenLLMetry, Langfuse and DeepEval. |
| [Emotion-Aware Voice Assistant](https://github.com/anmolsharma152/Emotion-Aware-Voice-Assistant) | Real-time voice assistant with a fully local audio pipeline: Silero VAD in the browser, faster-whisper speech-to-text, emotion detection and Kokoro text-to-speech behind FastAPI. |
| [sarvam-1-indic-instructor](https://github.com/anmolsharma152/sarvam-1-indic-instructor) | Instruction-tuning Sarvam-1 (2B) for Hindi, Hinglish and English. 15K synthetic instructions distilled from Nemotron-Super 49B, with a QLoRA training, evaluation and serving pipeline; GPU training run in progress. |

### Systems and Linux

| Project | |
|---|---|
| [rust-agent-core](https://github.com/anmolsharma152/rust-agent-core) | Terminal agent runtime in Rust (Tokio): a single-binary REPL with tool calling gated by read-only, safe and unrestricted modes, and local ONNX embeddings, so search needs no network. |
| [respy](https://github.com/anmolsharma152/respy) | Redis-compatible server and pub/sub broker written from scratch in Go with only the standard library, including AOF and RDB persistence. |
| [Aura](https://github.com/anmolsharma152/Aura) | Face authentication for Linux login and `sudo`: a small C PAM module talks over a Unix socket to a Python daemon that runs ONNX liveness and recognition models. |
| [vad_processor](https://github.com/anmolsharma152/vad_processor) | Voice activity detection in Rust compiled to WebAssembly, running client-side in the browser. |
| [Space Marine theme](https://github.com/anmolsharma152/omarchy-space-marine-theme) | Desktop theme for Omarchy (Arch + Hyprland), listed in the official Omarchy theme gallery. |
| [Dotfiles](https://github.com/anmolsharma152/omarchy-quattro-dotfiles) and [homelab](https://github.com/anmolsharma152/homelab) | My Hyprland workstation configuration, and a Docker Compose homelab behind Caddy with PostgreSQL, Redis and self-hosted AI services. |

### Open source

- **[Omarchy](https://github.com/omacom/omarchy)**: [Space Marine theme added to the theme gallery](https://github.com/omacom/omarchy-site/pull/445) (merged); open PRs for [volume control routing](https://github.com/omacom/omarchy/pull/14683) and the [Wayland session file](https://github.com/omacom/omarchy/pull/15812).
- **[hiring-agent](https://github.com/interviewstreet/hiring-agent)** (HackerRank): [fixed parsing of nested GitHub profile fields](https://github.com/interviewstreet/hiring-agent/pull/362) (merged).

### Other projects

[AlgoDeck](https://github.com/anmolsharma152/AlgoDeck) (DSA practice workstation with an in-browser editor and SM-2 review scheduling) · [IdeaForge](https://github.com/anmolsharma152/IdeaForge) (LangGraph idea-generation agent with pgvector memory) · [Scholar-Loop](https://github.com/anmolsharma152/Scholar-Loop) (FSRS spaced-repetition study agent)

### Tools

Python, Rust, Go, SQL, TypeScript · LangGraph, PyTorch, Hugging Face, ONNX · FastAPI, PostgreSQL / pgvector, Redis, Docker · Linux

---

[Portfolio](https://anmolsharma152.vercel.app) · [LinkedIn](https://linkedin.com/in/anmolsharma152) · [Hugging Face](https://huggingface.co/okozymandias) · [X](https://x.com/ozymandias152) · [Email](mailto:anmolsharma152.dev@gmail.com)
