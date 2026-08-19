# Instalação detalhada

SEFAZ PE: Certidão de Regularidade Fiscal (Móvel) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_pe_crf_movel`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_pe_crf_movel` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_pe_crf_movel` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_pe_crf_movel` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_pe_crf_movel` (ou `servers.sefaz_pe_crf_movel` no VS Code) do config do cliente e reinicie.
