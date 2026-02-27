# Claude Code Plugins

Claude Code plugins by Michael Ansel.

## Installation

```
/plugin install michaelansel@c3po
/plugin install michaelansel@notify-pushover
```

## Plugins

### c3po

Multi-agent coordination for Claude Code. Enables multiple Claude Code instances to communicate and collaborate via a shared coordinator server.

Source: [michaelansel/c3po](https://github.com/michaelansel/c3po)

### notify-pushover

Pushover notifications when Claude needs attention. Uses a 30-second delay with cancellation so you only get notified if you haven't already responded.

Requires: `jq`, `curl`, and a [Pushover](https://pushover.net/) account.

Source: [michaelansel/claude-code-pushover](https://github.com/michaelansel/claude-code-pushover)

### thought-graph

Graph-based thought tracker for Claude Code. Capture, refine, and execute ideas using a lightweight JSONL graph. Includes a ready queue injected at session start, auto-commit on stop, and skills for self-improvement and learning.

Source: [michaelansel/claude-code-thought-graph](https://github.com/michaelansel/claude-code-thought-graph)
