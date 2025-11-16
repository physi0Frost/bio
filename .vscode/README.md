# VS Code MCP Config

This folder contains a minimal MCP (Model Context Protocol) configuration used by VS Code and associated tooling.

File: `mcp.json`

This file defines a local MCP server (Playwright) — it uses `npx` to run the MCP package for Playwright.

How to run the server manually (for testing):

```bash
npx @playwright/mcp@latest
```

If you need additional servers or custom args for the MCP server, add them to `mcp.json` under `servers`.
