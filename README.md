# Nerq MCP Server

**Search 4.9M+ AI agents. Check compliance across 52 global jurisdictions.**

Nerq is the world's largest AI agent compliance and discovery database. This MCP server gives any AI assistant instant access to compliance intelligence, agent discovery, and safety recommendations.

## 🔧 Tools

| Tool | Description |
|------|-------------|
| `search_agents` | Search 4.9M+ AI agents by name, capability, or type |
| `recommend_agent` | Get safety-filtered recommendations with install instructions |
| `check_compliance` | Check any agent's compliance across 52 jurisdictions (EU AI Act, Colorado AI Act, UK AI regulation, etc.) |
| `compare_agents` | Compare agents side-by-side on compliance, security, and popularity |
| `nerq_stats` | Get ecosystem statistics (total agents, risk distribution, sources) |

## 🚀 Quick Start

### Claude Desktop

Add to your `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "nerq": {
      "url": "https://mcp.nerq.ai/sse"
    }
  }
}
```

### Cursor / VS Code

Add to MCP settings:
```json
{
  "nerq": {
    "url": "https://mcp.nerq.ai/sse"
  }
}
```

### Windsurf

Add to your MCP configuration:
```json
{
  "nerq": {
    "serverUrl": "https://mcp.nerq.ai/sse"
  }
}
```

## 📊 What You Can Do

**Find agents:**
> "Find me a safe MCP server for PostgreSQL"

**Check compliance:**
> "Is LangChain compliant with the EU AI Act?"

**Compare agents:**
> "Compare LangChain vs CrewAI on compliance and security"

**Get stats:**
> "How many AI agents exist and what's the risk distribution?"

## 🌍 Jurisdictions Covered

52 global jurisdictions including:
- 🇪🇺 EU AI Act (+ DE, FR, IT, ES, NL, IE, PL, SE implementations)
- 🇺🇸 US: California SB53, Colorado SB205, NY RAISE Act, and 10+ state laws
- 🇬🇧 UK AI Regulation
- 🇨🇦 Canada AIDA
- 🇰🇷 South Korea AI Basic Act
- 🇧🇷 Brazil AI Bill
- 🇨🇳 China AI Labeling & Cybersecurity
- 🇯🇵 Japan AI Bill
- 🇦🇺 Australia AI Guardrails
- And 30+ more

## 📈 Database

- **4.9M+** indexed AI agents
- **17,000+** MCP servers
- **52** jurisdictions
- **253M+** individual compliance assessments
- Sources: GitHub, npm, PyPI, HuggingFace, Docker Hub, Smithery, Glama

## 🔗 Links

- **Website:** [nerq.ai](https://nerq.ai)
- **API Docs:** [nerq.ai/docs](https://nerq.ai/docs)
- **Stats:** [nerq.ai/stats](https://nerq.ai/stats)
- **MCP Directory:** [nerq.ai/mcp-servers](https://nerq.ai/mcp-servers)

## License

MIT
