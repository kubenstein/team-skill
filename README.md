# team-skill

OpenCode skill package for team workflows.

The `team` skill lives at `skills/team/SKILL.md`.

## Installation

1. Add the plugin package to your OpenCode config at `~/.config/opencode/opencode.json`:

```json
{
  "plugin": [
    "file:///path/to/team-skill"
  ]
}
```

2. Restart OpenCode. Plugin config changes are loaded on startup.

## Claude Code

Claude Code plugin support is defined in `.claude-plugin/plugin.json`.

Validate the plugin locally:

```sh
claude plugin validate .
```

Load this checkout as a local plugin while developing:

```sh
claude --plugin-dir .
```

Invoke the skill with the namespaced slash command:

```text
/team-skill:team
```

## Usage

Load the `team` skill in OpenCode when you want to use its workflow. This package provides a skill, not a slash command.
