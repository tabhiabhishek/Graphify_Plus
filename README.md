<p align="center">
  <img src="docs/images/banner.svg" alt="Graphify Plus" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?logo=python&amp;logoColor=white" alt="Python 3.11">
  <img src="https://img.shields.io/badge/MCP-14%20tools-22c55e" alt="MCP">
  <img src="https://img.shields.io/badge/FastAPI-dashboard-009688?logo=fastapi&amp;logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/NetworkX-Leiden-38bdf8" alt="NetworkX + Leiden">
  <img src="https://img.shields.io/badge/SQLite-FTS5-003B57?logo=sqlite&amp;logoColor=white" alt="SQLite FTS5">
  <img src="https://img.shields.io/badge/Ollama-local-000000?logo=ollama&amp;logoColor=white" alt="Ollama">
</p>

# 🕸️ Graphify Plus

**Stop wasting tokens. Give your AI the exact context it needs, nothing more.**

Graphify Plus is an intelligent context-engine designed to drastically minimize token usage when working with LLMs like Claude, Codex, and other AI coding assistants. By building dynamic knowledge graphs and integrating natively with the Model Context Protocol (MCP), Graphify Plus ensures your AI understands your codebase deeply without hitting context limits.

<p align="center">
  <img src="docs/images/preview.svg" alt="Graphify Plus dashboard and MCP activity" width="100%">
  <br><sub>The web dashboard (localhost:3000): project stats, Ollama enrichment, the progressive graph viewer and the MCP tool calls an AI assistant makes. Illustrative mockup with sample data.</sub>
</p>

## ✨ Key Features

- 🪶 **Token Minimization:** Intelligently filters and compresses context, sending only the most relevant code and data to Claude, Codex, and other models. Save money and avoid context-window limits.
- 🕸️ **Dynamic Graph Building:** Automatically maps your codebase, dependencies, and logic flows into an interactive knowledge graph. 
- 🔌 **Native MCP Server Integration:** Seamlessly connects to Model Context Protocol (MCP) servers, allowing AI agents to query your graph in real-time.
- 🔗 **Multi-Project Connectivity:** Easily link multiple repositories and projects together. Graphify Plus understands the relationships across your entire ecosystem, not just a single folder.

## 🧠 How It Works

<p align="center">
  <img src="docs/images/architecture.svg" alt="How Graphify Plus works" width="100%">
</p>

Traditional AI coding tools dump entire files into the prompt, wasting thousands of tokens on irrelevant boilerplate. 

**Graphify Plus** changes the game:
1. **Ingests** your project(s) and analyzes the structure.
2. **Builds** a lightweight graph of relationships, dependencies, and core logic.
3. **Connects** to your AI via an MCP server.
4. **Serves** only the specific "nodes" (files, functions, classes) the AI needs to solve your current problem.

## 🚀 Getting Started

### Prerequisites
- Python 3.11
- An MCP-compatible AI client (like Claude Desktop, Cursor, or a custom Codex setup)

### Installation

```bash
# Clone the repository
git clone https://github.com/tabhiabhishek/Graphify_Plus.git
cd Graphify_Plus

# Create a virtual environment (Python 3.11)
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate    # macOS / Linux

# Install dependencies
pip install -r requirements.txt
```

### Run the server

**PowerShell**
```powershell
$env:PYTHONPATH = "src"
python -m graphify_plus.server
```

**CMD**
```bat
set PYTHONPATH=src
python -m graphify_plus.server
```

Then open **http://localhost:3000** to use the dashboard.

> In PowerShell use `$env:PYTHONPATH = "src"`. In CMD use `set PYTHONPATH=src`. Mixing them up is the most common startup error.

### Free semantic enrichment with Ollama (optional)
1. Install [Ollama](https://ollama.com/download).
2. Pull a model:
   ```bash
   ollama pull phi3
   ```
3. In the dashboard, click **Enrich with AI** on your project card, pick the model and start enrichment.

| Model | Size | Best for |
|---|---|---|
| `qwen2:1.5b` | 1.0 GB | Very fast, works on weak machines |
| `phi3` | 2.3 GB | Fast, CPU is fine |
| `codellama` | 3.8 GB | Code-optimized |
| `llama3.1` | 4.7 GB | Best quality (needs a GPU) |

### Connect your AI assistant (MCP)
1. In the dashboard, click **Install Plugin** on your project card and choose **Claude Code** or **VS Code Cline**.
2. This writes a `.mcp.json` file into your project folder.
3. Start your assistant in that folder and ask: *"What MCP tools do you have?"* You should see the graph tools listed.

**Token-saving workflow:** ask in this order:
1. `community_summaries` to understand the codebase structure (~300 tokens)
2. `search_graph("topic", compact=true)` to find relevant nodes (~200 tokens)
3. `get_file_summary("file.py")` to decide whether you need the source (~80 tokens)
4. Read the actual file only when you need exact code

### MCP tools

| Tool | What it does | Tokens |
|---|---|---|
| `list_projects` | List all indexed projects | ~50 |
| `graph_stats` | Node / edge / community counts | ~30 |
| `search_graph` | Find nodes by meaning (FTS5 + semantic) | 50–200 |
| `get_god_nodes` | Most connected hub nodes | 100–200 |
| `get_neighbors` | Connections around a node | 100–500 |
| `shortest_path` | How two concepts connect | 200–500 |
| `nodes_in_file` | All nodes from a file | 50–500 |
| `get_community` | All nodes in a cluster | 100–1000 |
| `community_summaries` | Table of contents for the codebase | 100–500 |
| `get_file_summary` | Describe a file without reading its source | 50–100 |
| `diff_impact` | How git changes affect the graph | 100–500 |
| `rebuild_graph` | Rebuild after code changes | 0 |
| `semantic_enrich` | Run Ollama enrichment | 0 |

### Token savings

| Approach | Tokens per query | Savings |
|---|---|---|
| No graph (AI reads files) | ~50,000 | baseline |
| `GRAPH_REPORT.md` only | ~2,000 | 96% |
| MCP tools (before enrichment) | ~500 | 99% |
| MCP tools (after enrichment) | ~200 | 99.6% |

### Troubleshooting

| Problem | Fix |
|---|---|
| `ModuleNotFoundError: No module named 'graphify_plus'` | Set `PYTHONPATH` to `src` (see above) |
| Path with spaces "is not recognized" | Run `python -m graphify_plus.server` instead of the `.py` file directly |
| Ollama times out | Use a smaller model such as `phi3` or `qwen2:1.5b` |
| Ollama can't reach the registry behind a corporate proxy | Set `HTTPS_PROXY` / `HTTP_PROXY` to your proxy before `ollama pull` |
| MCP tools not showing | Click **Install Plugin** again in the dashboard to regenerate `.mcp.json` |
| Fresh start | Delete `~/.graphify-plus/graph.db` |
