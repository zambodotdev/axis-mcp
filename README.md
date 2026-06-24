# Axis MCP

[![axis mcp](https://zambo.dev/api/axis-mcp/badge.svg)](https://zambo.dev/mcp)
[![Smithery](https://img.shields.io/badge/smithery-listed-c8f135?labelColor=1a1a18)](https://smithery.ai/server/axis-mcp)
[![Audit](https://img.shields.io/badge/system_audit-live-c8f135?labelColor=1a1a18)](https://zambo.dev/audit)

**12 tools bridging three AI networks into one cohesive agent system.**

- **Zambo.dev** — brain / strategy / product intelligence
- **x711.io** — execution / compute / x402 micropayments
- **Entangler.tech** — coordination / trustless agent messaging

**Zero auth. Zero signup.** Install alongside Zambo MCP for 41 total tools across 2 MCPs.

## Quick Install

```json
{
  "mcpServers": {
    "zambo": { "url": "https://zambo.dev/api/mcp" },
    "axis":  { "url": "https://zambo.dev/api/axis-mcp" }
  }
}
```

Install both together — Axis tools reference Zambo tools and they're designed to be used in tandem.

## All 12 Tools

| Tool | What it does |
|------|-------------|
| `axis_spark_to_swarm` | Convert a Zambo Spark goal into a full executable multi-agent workflow |
| `axis_agent_wire` | Wire two agents together across Zambo/x711/Entangler |
| `axis_tool_dispatch` | Dispatch any x711 tool through Axis with Zambo verification |
| `axis_swarm_pattern` | Design a multi-agent swarm pattern for complex goals |
| `axis_drift_monitor` | Monitor swarm drift vs original Zambo Spark strategy |
| `axis_memory_handoff` | Pass memory/context between Zambo, x711, and Entangler layers |
| `axis_chain_proof` | Generate a cryptographic proof chain for agent action provenance |
| `axis_agent_onboard` | Brief a new agent on its role in the Axis trifecta |
| `axis_pay_agent` | Execute x402 micropayment agent-to-agent (USDC on Base) |
| `axis_reputation_check` | Check trust score of any agent in the Axis swarm |
| `axis_outcome_submit` | Submit an outcome to close the loop on a Spark + update swarm memory |
| `axis_cross_search` | Search for tools, agents, or capabilities across all three networks |

## Rate Limits

- **Free tier**: 3 calls/day per tool
- **Zambo Pass** ($49/mo): Unlimited on all 41 tools — covers both Zambo MCP + Axis MCP

## Trifecta Architecture

```
          ZAMBO.DEV (brain)
         /       |       \
    strategy   audit   intel
         \       |       /
          AXIS MCP (bridge)
         /               \
   x711.io            Entangler.tech
 (execution)         (coordination)
```

## System Audit

Live endpoint status, latency metrics, and full tool verification: **[zambo.dev/audit](https://zambo.dev/audit)**

## Links

- Homepage: [zambo.dev](https://zambo.dev)
- Zambo MCP (29 tools): [github.com/zambodotdev/zambo-mcp](https://github.com/zambodotdev/zambo-mcp)
- MCP directory: [zambo.dev/mcp](https://zambo.dev/mcp)
- Smithery: [smithery.ai/server/axis-mcp](https://smithery.ai/server/axis-mcp)
- Pass ($49/mo): [zambo.dev/#zambo-pass](https://zambo.dev/#zambo-pass)
- Support: [brennanzambo@zambo.dev](mailto:brennanzambo@zambo.dev)
