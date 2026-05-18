# agent_xplor

Coursework and projects from the Claude Code Architect Certification.

## Structure

### Prompt_Eng
Prompt engineering techniques — zero-shot, few-shot, chain-of-thought, and template-based prompting using the Claude API.

### Prompt_Eval
Evaluation frameworks for assessing prompt quality. Includes automated graders and dataset-driven evaluation pipelines.

### RAG
Retrieval-Augmented Generation — document chunking strategies and embedding-based semantic search using VoyageAI.

### Tools
Claude tool use — defining tools, handling tool calls, and streaming tool responses.

### MCP
Model Context Protocol — a CLI chat agent backed by an MCP server, with resource and prompt support.

## Setup

Requires Python 3.12+ and [uv](https://github.com/astral-sh/uv).

```bash
uv sync
```

Add your API keys to a `.env` file:

```
ANTHROPIC_API_KEY=...
VOYAGE_API_KEY=...
```
