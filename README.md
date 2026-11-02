# Agent Weather MCP

Pay per call, solves one question. Remote MCP server for raw public readings on AI agents and x402 payments—each with source and timestamp. Metrics, not advice.

- **MCP (Streamable HTTP):** https://mcp.agentweather.io/mcp
- **API / docs:** https://api.agentweather.io
- **MCP Registry:** `io.agentweather/agent-weather`

## Add in Cursor

Paste this into your MCP config (or use the files in this repo: `.mcp.json`, `mcp.json`, or `.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "agent-weather": {
      "url": "https://mcp.agentweather.io/mcp"
    }
  }
}
```

No API key. Paid tools settle with x402. Accepted rails: USDC on Base and RLUSD. One call answers one question.

## What you get

Lead with raw readings. Free tools (status, indexes, demos) need no payment. Paid tools return public measurements; gaps stay gaps. Modeled fields are labelled as modeled.

Human page and OpenAPI: https://api.agentweather.io

## License

© 2026 David Lucas / Agent Weather. All rights reserved.
