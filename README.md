# Scoop Bucket for clickup-agent-chat

This is the official [Scoop](https://scoop.sh) bucket for [clickup-agent-chat](https://github.com/STR-Consulting/clickup-agent-chat), an MCP server for ClickUp Agent Notes.

## Installation

```powershell
scoop bucket add clickup-agent-chat https://github.com/STR-Consulting/scoop-clickup-agent-chat
scoop install clickup-agent-chat
```

## Configuration

Add to your MCP configuration:

```json
{
  "mcpServers": {
    "agent-notes": {
      "command": "clickup-agent-chat",
      "env": { "CLICKUP_TOKEN": "pk_..." }
    }
  }
}
```

## Updating

```powershell
scoop update clickup-agent-chat
```

## Uninstalling

```powershell
scoop uninstall clickup-agent-chat
scoop bucket rm clickup-agent-chat
```

## Issues

Report issues at [STR-Consulting/clickup-agent-chat](https://github.com/STR-Consulting/clickup-agent-chat/issues).
