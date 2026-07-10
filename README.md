# VaultRE MCP Registry

Official Model Context Protocol (MCP) server registry for VaultGroup tools.

**Registry URL**: `https://vaultgroup.github.io/vaultre-mcp-registry/registry.json`

## Servers

- **vaultre-mcp** — Atlassian integration (Jira, Confluence)
- **atlassian-mcp** — Official Atlassian Rovo (Remote) MCP server (Jira, Confluence, Compass) via the `mcp-remote` proxy to `https://mcp.atlassian.com/v1/mcp/authv2`
- **zendesk-mcp** — Self-built read-only Zendesk MCP server (search + fetch tickets) for the vaultre-copilot-bot
- **github-mcp** — Official GitHub remote MCP server (read-only endpoint) for the vaultre-copilot-bot code-review mode
- **elastic-mcp** — Self-built read-only Elasticsearch MCP server (log search + index listing) for the vaultre-copilot-bot

## How to Update

Edit `docs/registry.json` and push to main. GitHub Pages updates automatically.

## GitHub Copilot Configuration

Paste the registry URL into your GitHub organization's Copilot settings under **MCP Registry** to enable Copilot access to these servers.
