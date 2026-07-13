## Mihir Wagle

Product manager on Microsoft Fabric. I build the agent tooling and data infrastructure I spend my days thinking about — MCP servers, agent-safety protocols, and pipelines that move real data.

Most of what's here started as a question I couldn't answer with a slide.

### Agents & MCP

Infrastructure and safety patterns for LLM agents.

- **[agentic-trust-protocol](https://github.com/mavaali/agentic-trust-protocol)** — path-level safety for LLM agents: a trust budget, a staging area, and an irreversibility classifier inside Plan-then-Execute.
- **[boundary](https://github.com/mavaali/boundary)** — an explicit safety envelope for tool-calling agents: scoped I/O, spend caps that fail closed, and graded runs. Published as boundary-envelope on PyPI.
- **[jugalbandi-protocol](https://github.com/mavaali/jugalbandi-protocol)** — a dialectical protocol for agent task execution.
- **[cricket-mcp](https://github.com/mavaali/cricket-mcp)** — cricket statistics MCP server: 14 tools over 21K matches and 10.9M deliveries, powered by DuckDB.
- **[daftari](https://github.com/mavaali/daftari)** — an open-source, multi-user knowledge vault exposed to AI agents over MCP.

### Data & Microsoft Fabric

Tools for the data supply chain.

- **[cricket-data-factory](https://github.com/mavaali/cricket-data-factory)** — analytics pipeline in Microsoft Fabric: 6 MCP servers, 10.9M deliveries, raw JSON to enterprise dashboards.
- **[pq-workbench](https://github.com/mavaali/pq-workbench)** — desktop app for running Power Query (M) against Fabric workspaces.
- **[tippani](https://github.com/mavaali/tippani)** — offline CLI that renders Azure DevOps PR markdown as a clean review portal.

### Writing & craft

- **[waglesworld](https://github.com/mavaali/waglesworld)** — my blog. Longer-form thinking on agents, data, and the supply chain behind both.
- **[mihirs-gyaan](https://github.com/mavaali/mihirs-gyaan)** — a portable corpus of agent skills any agent can read.

---

Writing at **[waglesworld.com](https://www.waglesworld.com)** · Puneri at heart.
