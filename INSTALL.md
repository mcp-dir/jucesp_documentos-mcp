# Instalação rápida

JUCESP: Lista de Documentos é um servidor MCP remoto hospedado em `https://api.mcp.ai/p_jucesp_documentos`. Você não baixa nem roda nada localmente — só aponta seu cliente pra essa URL.

A auth acontece em runtime: clientes com **OAuth 2.1** (Claude Desktop, Cursor, VS Code recentes) abrem o browser na 1ª chamada (magic-link). Clientes sem OAuth recebem a tool `authenticate` — abra `https://app.mcp.ai/agent-auth`, faça login, copie o JWT e cole no chat.

---

## Claude (Web e Desktop)

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → `JUCESP: Lista de Documentos` / `https://api.mcp.ai/p_jucesp_documentos`.

Config file (legado): `~/Library/Application Support/Claude/claude_desktop_config.json` (macOS) ou `%APPDATA%\Claude\claude_desktop_config.json` (Windows):

```json
{ "mcpServers": { "jucesp_documentos": { "type": "http", "url": "https://api.mcp.ai/p_jucesp_documentos" } } }
```

## Cursor

[➕ Instalar no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=jucesp_documentos&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9qdWNlc3BfZG9jdW1lbnRvcyJ9)

`.cursor/mcp.json`:
```json
{ "mcpServers": { "jucesp_documentos": { "url": "https://api.mcp.ai/p_jucesp_documentos" } } }
```

## VS Code (Copilot Chat)

[➕ Instalar no VS Code](vscode:mcp/install?name=jucesp_documentos&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_jucesp_documentos%22%7D)

`.vscode/mcp.json`:
```json
{ "servers": { "jucesp_documentos": { "type": "http", "url": "https://api.mcp.ai/p_jucesp_documentos" } } }
```

## Outros clientes MCP

Qualquer cliente com **MCP over HTTP**. URL fixa:

```
https://api.mcp.ai/p_jucesp_documentos
```

Dúvidas? [jucesp_documentos@mcp.ai](mailto:jucesp_documentos@mcp.ai)
