# Hootsuite MCP Server Examples

This directory contains example scripts demonstrating how to use the Hootsuite MCP Server.

## Available Examples

### basic_usage.py
Basic example showing how to start and configure the MCP server.

## Running the Examples

1. **Install the package:**
   ```bash
   pip install hootsuite-mcp-server
   ```

2. **Set up environment variables:**
   Copy the `.env.example` file from the repository root and fill in your credentials.

3. **Run the example:**
   ```bash
   python examples/basic_usage.py
   ```

## Using with Claude Desktop

Add this configuration to your Claude Desktop config file:

```json
{
  "mcpServers": {
    "hootsuite": {
      "command": "uvx",
      "args": ["hootsuite-mcp-server"],
      "env": {
        // Add your environment variables here
      }
    }
  }
}
```

## Additional Resources

- See the main [README.md](../README.md) for complete documentation
- Check the [API documentation](../README.md#available-tools) for available tools
- Review [.env.example](../.env.example) for required environment variables
