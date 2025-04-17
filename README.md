# My Slack MCP Server Extension

This is an extension of the [Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) that enables Claude to interact with Slack workspaces with additional custom functionality.

## Additional Tools

### slack_search_messages

- Searches for messages across channels with optional DM exclusion
- Required inputs:
  - `query` (string): The search query
- Optional inputs:
  - `count` (number, default: 5): Number of results to return
- Configuration options:
  - `excludeDMsFromSearch` (boolean, default: false): When true, excludes DM results from search by adding `-in:@` to the query
- Returns: JSON response containing search results

For all other available tools and functionality, please refer to the [original Slack MCP Server documentation](https://github.com/modelcontextprotocol/servers/tree/main/src/slack).

## Setup

Please refer to the [original Slack MCP Server documentation](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) for setup instructions.

## Development

Instructions for developing and contributing to your extension.

## License

This extension is licensed under the MIT License.
