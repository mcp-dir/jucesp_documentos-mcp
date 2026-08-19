# JUCESP: Lista de Documentos

### JUCESP: Lista de Documentos for Claude, ChatGPT and AI agents

Lists a company's filed documents at JUCESP by NIRE. Platform-hosted, no credentials, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `JUCESP: Lista de Documentos`, URL `https://api.mcp.ai/p_jucesp_documentos`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=jucesp_documentos&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9qdWNlc3BfZG9jdW1lbnRvcyJ9)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=jucesp_documentos&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_jucesp_documentos%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_jucesp_documentos
```

---

## 1 tool

| Tool | Description |
|---|---|
| `jucesp_documentos_consultar` | Lista os documentos arquivados de uma empresa na JUCESP a partir do NIRE. |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_jucesp_documentos` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
