# Patchoutech Plugins

Claude Code plugin marketplace by [Patchoutech](https://patchoutech.com).

## Installation

```bash
/plugin marketplace add hopchouinard/patchoutech-plugins
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **cc-statusline** | 4-line ANSI dashboard showing env, context window, session cost, and git status | `/plugin install cc-statusline@patchoutech-plugins` |
| **cmux** | Claude Code integration for cmux — workspace naming, notifications, progress bars, browser splits | `/plugin install cmux@patchoutech-plugins` |

## Plugin Details

### cc-statusline

A zero-dependency Python statusline that renders a compact dashboard in your Claude Code status bar. Shows your model, context window usage (color-coded progress bar), session cost/duration, and git branch status at a glance.

**Source:** [hopchouinard/CC-StatusLine](https://github.com/hopchouinard/CC-StatusLine)

### cmux

Integration plugin for [cmux](https://cmux.dev) — the native macOS terminal built for AI coding agents. Automatically names workspaces from your git repo, fires notifications on task completion, reports long-running progress as live sidebar bars, and opens browser splits for visual verification. Gracefully no-ops when not running inside cmux.

**Source:** [hopchouinard/cmux-plugin](https://github.com/hopchouinard/cmux-plugin)

## Author

Built by **Patchou** (Patrick Chouinard) — software engineer, AI tooling builder, and Claude Code enthusiast.
