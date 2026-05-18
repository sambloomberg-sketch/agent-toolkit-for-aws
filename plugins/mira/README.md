# mira

Scaffold for the Mira plugin. Fill in the description, skills, and any MCP server configuration before publishing.

## Install

### Claude Code

```
/plugin marketplace add aws/agent-toolkit-for-aws
/plugin install mira@agent-toolkit-for-aws
```

### Codex

In your terminal:

```
codex plugin marketplace add aws/agent-toolkit-for-aws
```

Then launch Codex and run `/plugins` to browse and install the **mira** plugin.

## What's included

### Skills

Add agent skills under [`skills/`](skills/). Each skill is a directory containing a `SKILL.md` and any reference files the skill needs.

| Skill | Description |
|-------|-------------|
| _(none yet)_ | Add the first skill under `skills/<skill-name>/SKILL.md`. |

### MCP servers

If Mira ships an MCP server, add a `.mcp.json` next to this README and reference it as `"mcpServers": "./.mcp.json"` in `.claude-plugin/plugin.json` and `.codex-plugin/plugin.json`.

## Source

Upstream channel: [big-halo/mira-claude-channel](https://github.com/big-halo/mira-claude-channel)
