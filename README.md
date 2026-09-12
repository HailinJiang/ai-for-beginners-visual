<div align="center">

# 🧠 AI for Beginners: Visual Edition

### Understand AI in minutes, not months.

**Simple visuals + everyday analogies that explain AI concepts to *everyone*, whether you write code or have never opened a terminal.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Made with Mermaid](https://img.shields.io/badge/diagrams-mermaid-ff3670.svg)](https://mermaid.js.org/)
[![Beginner Friendly](https://img.shields.io/badge/beginner-friendly-blue.svg)](#-the-concepts)
[![Concepts](https://img.shields.io/badge/concepts-36-blueviolet.svg)](#-the-concepts)
[![Stars Welcome](https://img.shields.io/badge/⭐_stars-welcome-gold.svg)](#)

*If this helps you finally "get" AI, drop a ⭐. It helps more people find it.*

</div>

---

## 🤔 Why this exists

AI is everywhere, but most explanations are either **too technical** (walls of math) or **too fluffy** (no real understanding). 

This repo sits in the middle. Every concept gets:

- 🧒 **An "Explain Like I'm 5" analogy**: the one-liner you'll actually remember
- 🖼️ **A simple diagram**: see the idea, don't just read it
- 🔧 **"How it actually works"**: for when you're ready to go deeper
- 🌍 **A real-world example**: where you've already seen it in action

No PhD required. No prior coding needed. Just curiosity.

---

## 📚 The Concepts

### 🌱 Start here: the foundations

| # | Concept | One-liner |
|---|---------|-----------|
| 1 | [🗣️ LLM (Large Language Model)](concepts/llm.md) | A super-reader that learned to finish your sentences. |
| 2 | [🔤 Token](concepts/token.md) | The little chunks AI reads instead of whole words. |
| 3 | [📍 Embedding](concepts/embedding.md) | Turning meaning into coordinates on a map. |
| 4 | [🕸️ Neural Network](concepts/neural-network.md) | A guessing machine that learns from its mistakes. |
| 5 | [🏋️ Training vs Inference](concepts/training-vs-inference.md) | Studying for the exam vs taking the exam. |
| 6 | [💬 Prompt](concepts/prompt.md) | The instructions you give the AI. |
| 7 | [🪟 Context Window](concepts/context-window.md) | How much the AI can "keep in mind" at once. |
| 8 | [🎯 Fine-tuning](concepts/fine-tuning.md) | Teaching a generalist to become a specialist. |
| 9 | [📖 RAG (Retrieval-Augmented Generation)](concepts/rag.md) | Letting AI "look things up" before answering. |
| 10 | [🌀 Hallucination](concepts/hallucination.md) | When AI confidently makes stuff up. |

### ⚙️ How it actually thinks: under the hood

| # | Concept | One-liner |
|---|---------|-----------|
| 11 | [⚙️ Transformer](concepts/transformer.md) | The engine that reads every word at once. |
| 12 | [👀 Attention](concepts/attention.md) | Highlighting the words that matter most. |
| 13 | [🌡️ Temperature](concepts/temperature.md) | The creativity dial (safe vs wild). |
| 14 | [🔗 Chain of Thought](concepts/chain-of-thought.md) | Making the AI "show its work." |
| 15 | [🧩 Mixture of Experts](concepts/mixture-of-experts.md) | A room of specialists, only two wake up per word. |

### 🏗️ How it's built & trained

| # | Concept | One-liner |
|---|---------|-----------|
| 16 | [👍 RLHF](concepts/rlhf.md) | Teaching AI manners with human thumbs up/down. |
| 17 | [⚡ GPU](concepts/gpu.md) | The "many hands" chip that does millions of sums at once. |
| 18 | [📏 Overfitting](concepts/overfitting.md) | Memorizing the answers instead of understanding. |
| 19 | [🎛️ Parameters / Weights](concepts/parameters-weights.md) | The billions of tiny knobs that store what AI knows. |
| 20 | [🏛️ Foundation Model](concepts/foundation-model.md) | One giant base brain everything is built on. |
| 21 | [🗜️ Quantization](concepts/quantization.md) | Shrinking a model to run on your laptop. |
| 22 | [🔙 Backpropagation](concepts/backpropagation.md) | How the machine learns from being wrong. |

### 🛠️ Using AI: tools & applications

| # | Concept | One-liner |
|---|---------|-----------|
| 23 | [🤖 AI Agent](concepts/ai-agent.md) | An AI that *does* things, not just chats. |
| 24 | [🗄️ Vector Database](concepts/vector-database.md) | A library that files things by meaning. |
| 25 | [🎨 Diffusion Model](concepts/diffusion-model.md) | Sculpting images out of pure noise. |
| 26 | [🎭 GAN](concepts/gan.md) | A forger vs a detective, until the fakes look real. |
| 27 | [🪪 System Prompt](concepts/system-prompt.md) | The AI's hidden, always-on job description. |
| 28 | [🌈 Multimodal](concepts/multimodal.md) | An AI that can see, hear, and read. |
| 29 | [🛠️ Tool Calling](concepts/tool-calling.md) | How AI reaches out and uses real tools. |
| 30 | [🔌 MCP (Model Context Protocol)](concepts/mcp.md) | The USB-C port for plugging tools into AI. |
| 31 | [🎯 Zero-shot vs Few-shot](concepts/zero-shot-few-shot.md) | Just ask, or show a few examples first. |

### ⚖️ Trust & limits: the fine print

| # | Concept | One-liner |
|---|---------|-----------|
| 32 | [⚖️ Bias](concepts/bias.md) | AI inherits the unfairness in its data. |
| 33 | [📅 Knowledge Cutoff](concepts/knowledge-cutoff.md) | Why AI doesn't know recent news. |
| 34 | [🕵️ Prompt Injection](concepts/prompt-injection.md) | Hiding sneaky instructions to trick an AI. |
| 35 | [🧭 Alignment & Guardrails](concepts/alignment.md) | Teaching AI what *not* to do. |
| 36 | [🌅 AGI](concepts/agi.md) | The hypothetical "human-level at everything" AI. |

---

## 🗺️ How it all fits together

```mermaid
flowchart LR
    A[💬 Your Prompt] --> B[🔤 Split into Tokens]
    B --> C[📍 Turned into Embeddings]
    C --> D[🕸️ Neural Network<br/>the LLM]
    D --> E[🪟 Limited by<br/>Context Window]
    D --> F[📝 Generates Answer]
    F -.->|sometimes| G[🌀 Hallucination]
    H[(📚 Your Documents)] -->|RAG| D
    I[🎯 Fine-tuning] -.->|specializes| D
    style A fill:#dbeafe,stroke:#3b82f6,color:#1f2937
    style D fill:#fef3c7,stroke:#f59e0b,color:#1f2937
    style F fill:#dcfce7,stroke:#22c55e,color:#1f2937
    style G fill:#fee2e2,stroke:#ef4444,color:#1f2937
```

> **Read it in order** if you're brand new, each concept builds on the last.
> **Jump around** if you already know the basics.

---

## 🚀 Quick Start

1. Pick a concept from the [table above](#-the-concepts).
2. Read the analogy. Look at the diagram.
3. Curious? Read "How it actually works."
4. Found it useful? **Star the repo** ⭐ and share it.

---

## 🤝 Contributing

Know a concept we're missing? Have a better analogy? **We'd love your help.**

See [CONTRIBUTING.md](CONTRIBUTING.md) for the simple template: adding a concept takes about 10 minutes.

Good first additions: *Reinforcement Learning, Deepfake, Loss Function, Speech-to-Text / Text-to-Speech, Open vs Closed Models, Distillation, Batch Size & Epochs, AI Ethics.*

---

## 📜 License

[MIT](LICENSE): free to use, share, remix, and teach with. Attribution appreciated.

---

<div align="center">

**Made for curious humans.** 🧠

If this made AI click for you, the best thank-you is a ⭐.

</div>
