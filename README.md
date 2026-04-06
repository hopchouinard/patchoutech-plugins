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
| **claude-speak** | 1.2.0 | Voice output layer for Claude Code — passive spoken summaries and active voice capability | `/plugin install claude-speak@patchoutech-plugins` |
| **cmux-plugin** | 1.0.1 | Integrates Claude Code with cmux — automatic workspace naming, session notifications, sidebar progress reporting, browser split automation, and Superpowers awareness | `/plugin install cmux-plugin@patchoutech-plugins` |
| **cowork-backup** | 1.0.1 | Cross-platform Cowork session backup & restore with platform-specific schedulers (LaunchAgent, systemd, Task Scheduler) and one-command interactive restore | `/plugin install cowork-backup@patchoutech-plugins` |

## Plugin Details

### cc-statusline

A zero-dependency Python statusline that renders a compact dashboard in your Claude Code status bar. Shows your model, context window usage (color-coded progress bar), session cost/duration, and git branch status at a glance.

- **Version:** 1.5.2
- **License:** MIT
- **Source:** [hopchouinard/CC-StatusLine](https://github.com/hopchouinard/CC-StatusLine)

### cmux-plugin

Integration plugin for [cmux](https://cmux.dev) — the native macOS terminal built for AI coding agents. Provides automatic workspace naming, session notifications, sidebar progress reporting, browser split automation, and Superpowers plugin awareness. Gracefully no-ops when not running inside cmux.

- **Version:** 1.0.1
- **License:** MIT
- **Source:** [hopchouinard/cmux-plugin](https://github.com/hopchouinard/cmux-plugin)

### cowork-backup

Automatically backs up your Cowork conversation history across macOS, Linux, and Windows with platform-specific schedulers, and provides one-command interactive restore to recover sessions after app reset, reinstall, or data loss.

- **Version:** 1.0.1
- **License:** MIT
- **Source:** [hopchouinard/cowork-backup-plugin](https://github.com/hopchouinard/cowork-backup-plugin)
### claude-speak

Converts Claude's text responses into natural speech and plays them through your local speakers, enabling hands-free work with both automatic end-of-turn voice output and deliberate mid-turn speaking for critical events.

- **Version:** 1.2.0
- **License:** MIT
- **Source:** [hopchouinard/claude-speak](https://github.com/hopchouinard/claude-speak)
## Author

Built by **Patchou** (Patrick Chouinard) — software engineer, AI tooling builder, and Claude Code enthusiast.
