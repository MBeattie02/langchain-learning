## 🦜

# **LangGraph Essentials**

This course will cover an introduction to key LangGraph concepts: State, Nodes, Edges, Memory, and Interrupts. It consists of five core labs and one cumulative tutorial demonstrating how to build a production-style email support workflow.

## 🚀 Setup

### Prerequisites

- Ensure you're using Python 3.11 - 3.13.
- [uv](https://docs.astral.sh/uv/) package manager or [pip](https://pypi.org/project/pip/)
- OpenAI API key

Make a virtual environment and install dependancies

```bash
# Create virtual environment and install dependancies
uv sync
```

Run notebooks

```bash
# Run Jupyter notebooks directly with uv
uv run jupyter lab

# Or activate the virtual environment if preferred
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
jupyter lab
```

Optional: Setup [LangSmith Studio](https://docs.langchain.com/oss/python/langchain/studio)

```bash
# copy the .env file you created above to the studio directory
cp .env ./studio/.

#to run
langgraph dev
```

## 📚 Tutorial Overview

This repository contains notebooks for Labs 1-5, and an additional notebook showcasing an end-to-end email agent. These labs cover the foundations of LangGraph that will enable you to build any workflow or agent.

### `L1-5.ipynb` - LangGraph Essentials

- You will use all the components of LangGraph
  - State and Nodes
  - Edges
    - Parallel
    - Conditional
  - Memory
  - Interrupts/ Human-In-The-Loop

### `EmailAgent.ipynb` - Build A Workflow

Learn to implement structured workflow to process customer emails. This notebook utilizes all of the building blocks from the first notebook in an example application.:

- Task tracking with status management (pending/in_progress/completed)
