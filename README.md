# Patchoutech Plugins

Claude Code plugin marketplace by [Patchoutech](https://patchoutech.com).

## Installation

```bash
/plugin marketplace add hopchouinard/patchoutech-plugins
```

## Available Plugins

| Plugin | Version | Description | Install |
|--------|---------|-------------|---------|
| **cc-statusline** | 1.5.2 | 4-line ANSI dashboard showing environment, context window, session cost, and git status | `/plugin install cc-statusline@patchoutech-plugins` |
| **cmux** | 1.0.1 | Claude Code integration for cmux — workspace naming, completion notifications, progress bars, and browser splits | `/plugin install cmux@patchoutech-plugins` |
| **cowork-backup** | 1.0.0 | Cross-platform Cowork session backup & restore with automatic scheduling and one-command interactive restore | `/plugin install cowork-backup@patchoutech-plugins` |

## Plugin Details

### cc-statusline

A zero-dependency Python statusline that renders a compact dashboard in your Claude Code status bar. Shows your model, context window usage (color-coded progress bar), session cost/duration, and git branch status at a glance.

- **Version:** 1.5.2
- **License:** MIT
- **Source:** [hopchouinard/CC-StatusLine](https://github.com/hopchouinard/CC-StatusLine)

### cmux

Integration plugin for [cmux](https://cmux.dev) — the native macOS terminal built for AI coding agents. Automatically names workspaces from your git repo, fires completion notifications on task finish, reports long-running progress as live sidebar bars, and opens browser splits for visual verification. Gracefully no-ops when not running inside cmux.

- **Version:** 1.0.1
- **License:** MIT
- **Source:** [hopchouinard/cmux-plugin](https://github.com/hopchouinard/cmux-plugin)

### cowork-backup

Cross-platform Cowork session backup & restore plugin. Detects your OS and installs backup scripts and a scheduler automatically. Supports one-command interactive restore for recovering previous Cowork sessions. Gracefully handles both macOS and Linux environments.

- **Version:** 1.0.0
- **License:** MIT
- **Source:** [hopchouinard/cowork-backup-plugin](https://github.com/hopchouinard/cowork-backup-plugin)

## Author

Built by **Patchou** (Patrick Chouinard) — software engineer, AI tooling builder, and Claude Code enthusiast.
