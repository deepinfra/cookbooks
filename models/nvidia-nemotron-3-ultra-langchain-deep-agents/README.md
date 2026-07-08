# Building a Deep Agent on Nemotron 3 Ultra with DeepInfra

A hands-on guide: from zero to a running [LangChain Deep Agent](https://docs.langchain.com/oss/python/deepagents/overview) powered by [NVIDIA Nemotron 3 Ultra](https://deepinfra.com/nvidia/NVIDIA-Nemotron-3-Ultra-550B-A55B), hosted on DeepInfra.

## What you'll build

By the end of the tutorial notebook you'll have a working Deep Agent — an agent that can plan, use tools, and complete multi-step tasks — running on Nemotron 3 Ultra via DeepInfra's OpenAI-compatible API, using LangChain's Deep Agents harness profile tuned for NVIDIA Nemotron 3 Ultra.

## Contents

- **[nvidia-nemotron-3-ultra-langchain-deep-agents.ipynb](nvidia-nemotron-3-ultra-langchain-deep-agents.ipynb)** — step-by-step tutorial: install, configure, define a tool, create the Deep Agent, and run it.

## Prerequisites

- A DeepInfra account and API token (get one at [deepinfra.com](https://deepinfra.com))
- Python 3.10 or newer
- Basic familiarity with LangChain (helpful but not required)

## Quick start

```bash
pip install deepagents langchain langchain-openai
export DEEPINFRA_TOKEN="your-token-here"
```

Then open the notebook and run the cells top to bottom.

## Resources

- [Nemotron 3 Ultra on DeepInfra](https://deepinfra.com/nvidia/NVIDIA-Nemotron-3-Ultra-550B-A55B)
- [LangChain Deep Agents docs](https://docs.langchain.com/oss/python/deepagents/overview)
- [DeepInfra + LangChain integration](https://docs.deepinfra.com/integrations/langchain)
