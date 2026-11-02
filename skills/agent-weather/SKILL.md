---
name: agent-weather
description: Use Agent Weather MCP for pay-per-call public readings on AI agents and x402. One call solves one question. Metrics only.
---

# Agent Weather

Pay per call, solves one question. Connect to the remote MCP at `https://mcp.agentweather.io/mcp` (Streamable HTTP). API and docs: https://api.agentweather.io

## How to use the tools

1. Prefer free tools first when they answer the question (`get_service_status`, indexes, demos).
2. For paid tools, expect an x402 payment challenge, pay on an accepted rail, then retry. Accepted rails: USDC on Base and RLUSD.
3. Lead with raw readings in any summary you give the user. Include source and timestamp when present.
4. Report metrics only—no advice, rankings, or forecasts dressed as certainty. Gaps are gaps; modeled fields stay labeled modeled.
5. One paid call answers one question. Chain separate questions as separate calls.

Do not invent prices; read live tool output or https://api.agentweather.io for current routes.
