# Instalação detalhada

JUCESP: Lista de Documentos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_jucesp_documentos`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_jucesp_documentos` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_jucesp_documentos` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_jucesp_documentos` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.jucesp_documentos` (ou `servers.jucesp_documentos` no VS Code) do config do cliente e reinicie.
