# Claude Plugin Database

A comprehensive database of Claude Code plugins for various development needs.

## Installation

To add this marketplace to your Claude Code installation:

```bash
/plugin marketplace add nickgarrison/claude-plugin-database
```

Or using the full URL:

```bash
/plugin marketplace add https://github.com/nickgarrison/claude-plugin-database.git
```

## Available Plugins

Coming soon! This marketplace is currently being set up.

## Adding New Plugins

To add a new plugin to this marketplace:

1. Add the plugin entry to `.claude-plugin/marketplace.json`
2. Choose your plugin source:
   - **Local**: `"source": "./plugins/plugin-name"`
   - **GitHub**: `"source": {"source": "github", "repo": "owner/repo"}`
   - **Git URL**: `"source": {"source": "url", "url": "https://example.com/plugin.git"}`

Example plugin entry:
```json
{
  "name": "example-plugin",
  "description": "A helpful description",
  "source": "./plugins/example-plugin"
}
```

## Contributing

Contributions are welcome! Please submit a pull request with new plugin additions.

## License

MIT
