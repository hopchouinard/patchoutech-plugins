# Patchoutech Plugins

Claude Code plugin marketplace by [Patchoutech](https://patchoutech.com).

## Installation

```bash
/plugin marketplace add hopchouinard/patchoutech-plugins
```

## Available Plugins

| Plugin | Version | Description | Install |
|--------|---------|-------------|---------|
| **cc-statusline** | 1.6.0 | 4-line ANSI dashboard statusline for Claude Code showing environment and reasoning effort, context window and subscription rate limits, session cost, and git and worktree status | `/plugin install cc-statusline@patchoutech-plugins` |
| **claude-speak** | 2.0.0 | Opt-in voice output for Claude Code — off by default in every session, condenses long or table-heavy replies for the ear, and interrupts instantly with !shutup | `/plugin install claude-speak@patchoutech-plugins` |
| **cmux-plugin** | 1.0.1 | Integrates Claude Code with cmux — automatic workspace naming, session notifications, sidebar progress reporting, browser split automation, and Superpowers awareness | `/plugin install cmux-plugin@patchoutech-plugins` |
| **cowork-backup** | 1.0.1 | Cross-platform Cowork session backup & restore with platform-specific schedulers (LaunchAgent, systemd, Task Scheduler) and one-command interactive restore | `/plugin install cowork-backup@patchoutech-plugins` |

## Plugin Details

### cc-statusline

A Claude Code plugin that renders a 4-line ANSI-colored statusline dashboard displaying environment info, reasoning effort, context window usage, subscription rate limits, session cost, and git/worktree status with color-coded alarms.

- **Version:** 1.6.0
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

Converts Claude's text responses into natural speech and plays them through your local speakers, enabling hands-free work.

Voice is **off by default in every session** and is activated deliberately with `/speak on` — no project ever starts talking unexpectedly. Long or table-heavy replies are condensed before they are spoken, so a six-column summary table does not become a stream of label-value pairs. Narration can be cut off instantly by typing `!shutup`, or simply by submitting your next prompt.

- **Version:** 2.0.0
- **License:** MIT
- **Source:** [hopchouinard/claude-speak](https://github.com/hopchouinard/claude-speak)
## Author

Built by **Patchou** (Patrick Chouinard) — software engineer, AI tooling builder, and Claude Code enthusiast.
