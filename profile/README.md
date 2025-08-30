# 🤗 Hugging Graph

**The GitHub for LangGraph workflows** - Share, discover, and compose reusable AI agent graphs and open source extendable chat based canvas elements for easier reusable conversational UI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![LangGraph Compatible](https://img.shields.io/badge/LangGraph-compatible-green.svg)](https://langchain-ai.github.io/langgraph/)

## 🚀 Quick Start

```bash
# Install HuggingGraph CLI
pip install hugginggraph

# Browse available graphs
hg search "quiz agent"

# Install a graph
hg install quiz-agent

# Use in your code
from hugginggraph import load_graph

quiz_graph = load_graph("quiz-agent")
result = quiz_graph.invoke({"topic": "Python basics"})
