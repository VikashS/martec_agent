# ChatAgent Builder – GenAI Agent Framework for ML Engineers

Build, test, and deploy custom generative AI agents that solve complex tasks with reasoning, tools, and ML iteration.

![ChatAgent demo](./public/demo.gif)  <!-- Add a GIF of agent in action -->

## ✨ Features

- Modular agent architecture: Chain LLMs for multi-step reasoning.
- Built-in tools: Web search, calculator, or custom integrations.
- Logging & evaluation: Monitor agent paths and compute metrics like success rate.
- Fine-tuning support: Easily swap in custom-tuned models from HF.
- CLI for quick testing; extensible to API/UI.
- Error-resilient: Automatic retries and human-in-loop fallback.

## 🛠 Tech Stack

- Python 3.12
- LangGraph (for agent orchestration)
- Hugging Face Transformers / Grok API (for LLMs)
- FastAPI (for deployment)
- SQLite (for session logs)
- Docker (for containerization)

## 🚀 Quick Start

```bash
git clone https://github.com/VikashS/martec_agent.git
