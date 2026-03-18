# berrzebb Claude Code Plugins

Claude Code plugin marketplace by [@berrzebb](https://github.com/berrzebb).

## Available Plugins

| Plugin | Description | Repository |
|--------|-------------|------------|
| [consensus-loop](https://github.com/berrzebb/consensus-loop) | AI development loop — orchestrator distributes tasks to headless workers, independent auditor verifies, automated retrospective drives self-improvement. | [berrzebb/consensus-loop](https://github.com/berrzebb/consensus-loop) |

## Installation

```bash
# Add this marketplace
claude marketplace add berrzebb/berrzebb-plugins

# Install a plugin
claude plugin add consensus-loop@berrzebb-plugins
```

## Adding New Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json` with the plugin's `name`, `source`, `description`, and `version`.
