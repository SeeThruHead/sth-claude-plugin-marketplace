# Claude Code Plugin Marketplace

A personal marketplace of Claude Code plugins to enhance your development workflow.

## Installation

To install plugins from this marketplace, use the following command in Claude Code:

```bash
/plugin marketplace add https://github.com/SeeThruHead/sth-claude-plugin-marketplace
```

Then browse and install plugins:

```bash
/plugin
```

## Available Plugins

### AI Dev Tasks

A structured workflow plugin for building features with AI assistance. Provides slash commands for creating PRDs, generating tasks, and processing implementation step-by-step.

**Commands:**
- `/create-prd` - Generate a Product Requirements Document
- `/generate-tasks` - Break down a PRD into implementation tasks
- `/process-task-list` - Work through tasks one at a time

See the [AI Dev Tasks README](./plugins/ai-dev-tasks/README.md) for detailed documentation.

**Source:** Based on [snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks), licensed under Apache License 2.0.

## Contributing

Contributions are welcome! To add a new plugin:

1. Create a new folder under `plugins/`
2. Add a `.claude-plugin` folder with your plugin configuration
3. Submit a pull request

## License

See [LICENSE](./LICENSE) for details.
