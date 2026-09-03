# InstantDB Agent Skills

[![InstantDB](https://instantdb.com/)](https://instantdb.com/)

Agent skills for FIDScript self-hosted InstantDB development.

## Skills

| Skill | Description |
| ----- | ----------- |
| [instant-self](./skills/instant-self/) | FIDScript self-hosted InstantDB development mode for Claude Code and MCP-compatible editors |

## Installation

Install the FIDScript skill:

```bash
npx skills add Mkid095/agent-skills -s instant-self
```

## Requirements

- A FIDScript self-hosted instance at `instant.fidscript.com`
- A Personal Access Token from your dashboard
- Claude Code, Cursor, Windsurf, or any MCP-compatible editor

## FIDScript Self-Hosted

FIDScript is the self-hosted deployment of InstantDB. Use the `instant-self` skill when working with `instant.fidscript.com` or `@fidscript/instant-mcp`.

For InstantDB Cloud (instantdb.com), use the Instant Cloud SDK instead.
