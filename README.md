# VaultRE MCP Registry

Official Model Context Protocol (MCP) server registry for VaultGroup tools.

**Registry URL**: `https://vaultgroup.github.io/vaultre-mcp-registry/registry.json`

## Servers

- **vaultre-mcp** — Atlassian integration (Jira, Confluence)
- **atlassian-mcp** — Official Atlassian Rovo (Remote) MCP server (Jira, Confluence, Compass) via the `mcp-remote` proxy to `https://mcp.atlassian.com/v1/mcp/authv2`

## How to Update

Edit `docs/registry.json` and push to main. GitHub Pages updates automatically.

## GitHub Copilot Configuration

Paste the registry URL into your GitHub organization's Copilot settings under **MCP Registry** to enable Copilot access to these servers.
