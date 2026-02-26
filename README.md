# helpscout-navigator

Guidance for correctly using HelpScout MCP tools. Bundles the MCP server.

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin from the [not-my-job](https://github.com/drewburchfield/not-my-job) marketplace.

## Features

- Decision tree for choosing the right search tool
- Correct sequencing (always lookup inbox IDs first)
- Prevents the "active-only" search trap
- Complete parameter reference for all 9 tools

**Requires:** `HELPSCOUT_APP_ID` and `HELPSCOUT_APP_SECRET` environment variables

## Install

```
claude plugins install helpscout-navigator@not-my-job
```

## License

MIT
