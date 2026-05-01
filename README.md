# Multi-Agent System with LangGraph

A working AI pipeline where two specialized agents collaborate —
one researches the web, the other writes a blog post — built with
LangGraph, Groq, and Llama 3.

---

## What This Project Does

Instead of asking a single AI one big question, this project breaks
the work into a team of specialized agents:

- **Researcher Agent** — searches the web in real time using DuckDuckGo
and returns current, grounded information on any topic
- **Writer Agent** — takes that research and uses Llama 3 (via Groq)
to write an engaging blog post

They communicate through a shared state object and run in sequence
using LangGraph's graph-based workflow engine.

---

## Why I Built This

I'm actively building my AI engineering skills and portfolio from the
ground up. This project taught me how to stop thinking in single
prompts and start thinking in systems — which is the foundation of
modern agentic AI development.

Key concepts I learned:
- How LangGraph manages state and agent handoffs
- How to connect real-time web search to an LLM pipeline
- How to run a local-style LLM workflow for free using Groq
- How multi-agent systems mirror real-world team structures

---

## Tech Stack

| Tool | Purpose |
|---|---|
| LangGraph | Agent orchestration and graph workflow |
| LangChain | LLM tooling and prompt management |
| Groq API | Fast, free LLM inference (Llama 3) |
| DuckDuckGo Search | Real-time web research |
| Google Colab | Cloud-based development environment |
| Python 3.12 | Core language |

---

## How to Run It

1. Open the notebook in Google Colab
2. Get a free API key at [console.groq.com](https://console.groq.com)
3. In the API key cell, replace `your_groq_api_key_here` with your key
4. Run all cells in order from top to bottom
5. Change the `topic` variable to anything you want to research

---

## Example Output

**Input topic:** "The future of AI Agents"

**Output:** A fully written, structured blog post generated from
real web search results — produced in seconds.
