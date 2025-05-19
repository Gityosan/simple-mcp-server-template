## Simple MCP Server Template

This is a template for a simple MCP server.

### Initialize

```bash
pnpm install
```

### Build

```bash
pnpm run build
```

### MCP Configuration

```json
{
  "mcpServers": {
    "diceRoller": {
      "command": "node",
      "args": [
        "/absolute/path/to/your/simple-mcp-server-template/build/index.js"
      ]
    }
  }
}
```

If you want to make sse server, you can use `SSEServerTransport` and some ts server framework.
