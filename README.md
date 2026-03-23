# berrzebb Claude Code Plugins

Claude Code plugin marketplace by [@berrzebb](https://github.com/berrzebb).

## Available Plugins

| Plugin | Description | Repository |
|--------|-------------|------------|
| [quorum](https://github.com/berrzebb/quorum) | Cross-model audit gate with domain specialists — 9 conditional expert reviewers, unified SQLite state, 17 MCP tools. Standalone CLI + Claude Code plugin. (v0.3.0) | [berrzebb/quorum](https://github.com/berrzebb/quorum) |
| [consensus-loop](https://github.com/berrzebb/consensus-loop) | AI development loop — orchestrator distributes tasks to headless workers, independent auditor verifies. (v2.5.0 frozen, succeeded by quorum) | [berrzebb/consensus-loop](https://github.com/berrzebb/consensus-loop) |

## Installation

```bash
# Add this marketplace
claude marketplace add berrzebb/berrzebb-plugins

# Install quorum (recommended)
claude plugin add quorum@berrzebb-plugins

# Or install consensus-loop (legacy, v2.5.0 frozen)
claude plugin add consensus-loop@berrzebb-plugins
```

quorum is also available as a standalone CLI via npm:

```bash
npm install -g quorum-audit
quorum setup
```

## Adding New Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json` with the plugin's `name`, `source`, `description`, and `version`.
