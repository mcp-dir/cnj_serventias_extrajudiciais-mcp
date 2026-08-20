# Instalação detalhada

Conselho Nacional de Justiça: Serventias Extrajudiciais (Detalhes) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_cnj_serventias_extrajudiciais`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_cnj_serventias_extrajudiciais` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_cnj_serventias_extrajudiciais` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_cnj_serventias_extrajudiciais` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.cnj_serventias_extrajudiciais` (ou `servers.cnj_serventias_extrajudiciais` no VS Code) do config do cliente e reinicie.
