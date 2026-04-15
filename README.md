# mcp-mercury-number

mercury-number MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `mercury_number_generate` | Your random number, justified by Mercury\'s current position. Mercury is in something. It\'s always in something. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "mercury-number": {
      "url": "https://gateway.pipeworx.io/mercury-number/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use mercury-number
```

## License

MIT
