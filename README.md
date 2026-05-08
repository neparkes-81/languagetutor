# Language Tutor RAG Agent

## Introduction

This multi-model RAG agent serves as a personal language tutor checking my mistakes and informing of areas I really struggles with. It utilizes 2 helper agents to get the job done. First is the Historian, a context driven RAG agent which utilizes embedding data stored in Chroma DB derived from my past Russian assginments and essays. This agent knows what I historically struggle with and can point out trend or recognize what I need more explination on. The second is the Researcher, an agent equiped to search the web. This one provides useful resources that can further my studies.
---

<!-- ## 🚀 Setup

### Prerequisites

- The [Chrome](https://www.google.com/chrome/) browser is recommended
- [git](https://git-scm.com/install/) is recommended
- A package/project manager: [uv](https://docs.astral.sh/uv/) (recommended) or [pip](https://pypi.org/project/pip/)
- note: `uv` is also required in Module 2, Lesson 1 to run the MCP server with `uvx`
- The course requires Python >=3.12, <3.14  If you use `uv`, it will take care of this for you. [More info](#python-virtual-environments)

### Installation

Download the course repository
```bash
# Clone the repo
git clone --depth 1 https://github.com/langchain-ai/lca-lc-foundations.git
cd lca-lc-foundations
```

Make a copy of example.env
```bash
# Create .env file
cp example.env .env
``` -->