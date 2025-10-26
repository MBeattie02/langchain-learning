# 🔗 LangChain Essentials Python

## 🚀 Setup

Make a virtual environment and install dependancies

```bash
# Create virtual environment and install dependancies
uv sync
```

Run notebooks

```bash
# Run Jupyter notebooks directly with uv
uv run jupyter lab

```

# 📚 Lessons

This repository contains nine short notebooks that serve as brief introductions to many of the most-used features in LangChain, starting with the new **Create Agent**.

---

### `L1_fast_agent.ipynb` - 🤖 Create Agent 🤖

- In this notebook, you will use LangChain’s `create_agent` to build an SQL agent in just a few lines of code.
- It demonstrates how quick and easy it is to build a powerful agent. You can easily take this agent and apply it to your own project.
- You will also use **LangSmith Studio**, a handy visual debugger to run, host, and explore agents.

---

### `L2-7.ipynb` - 🧱 Building Blocks 🧱

In Lessons 2–7, you will learn how to use some of the fundamental building blocks in LangChain. These lessons explain and complement `create_agent`, and you’ll find them useful when creating your own agents. Each lesson is concise and focused.

- **L2_messages.ipynb**: Learn how messages convey information between agent components.
- **L3_streaming.ipynb**: Learn how to reduce user-perceived latency using streaming.
- **L4_tools.ipynb**: Learn basic tool use to enhance your model with custom or prebuilt tools.
- **L5_tools_with_mcp.ipynb**: Learn to use the LangChain MCP adapter to access the world of MCP tools.
- **L6_memory.ipynb**: Learn how to give your agent the ability to maintain state between invocations.
- **L7_structuredOutput.ipynb**: Learn how to produce structured output from your agent.

---

### `L8-9.ipynb` - 🪛 Customize Your Agent 🤖

Lessons 2–7 covered out-of-the-box features. However, `create_agent` also supports both prebuilt and user-defined customization through **Middleware**. This section describes middleware and includes two lessons highlighting specific use cases.

- **L8_dynamic.ipynb**: Learn how to dynamically modify the agent’s system prompt to react to changing contexts.
- **L9_HITL.ipynb**: Learn how to use Interrupts to enable Human-in-the-Loop interactions.
