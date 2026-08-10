# sdrik-plugins

A [Claude Code](https://code.claude.com) plugin marketplace maintained by Cédric Schieli.

This catalog is meant to grow — more plugins will be added over time.

## Available plugins

| Plugin | Description |
| --- | --- |
| [`git-workspace`](https://github.com/sdrik/git-workspace) | Skills for managing git workspaces (worktrees, bare repositories, ...). |
| [`wezterm`](https://github.com/sdrik/wezterm/tree/claude-plugin) | Development and debugging tools for the WezTerm terminal emulator. |
| [`statusline`](https://github.com/sdrik/claude-statusline) | Installs a rich Claude Code status line: email, mode, model, effort, context-window gauge, and 5h/7d rate-limit gauges. |
| [`hygiene`](https://github.com/sdrik/claude-hygiene) | Keeps conversation-internal shorthand out of public artifacts: branch names, commit messages, PR text. |

## Usage

Add the marketplace, then install a plugin:

```shell
/plugin marketplace add sdrik/claude-marketplace
/plugin install git-workspace@sdrik-plugins
/plugin install wezterm@sdrik-plugins
/plugin install statusline@sdrik-plugins
/plugin install hygiene@sdrik-plugins
```

Or from your terminal:

```bash
claude plugin marketplace add sdrik/claude-marketplace
claude plugin install git-workspace@sdrik-plugins
claude plugin install wezterm@sdrik-plugins
claude plugin install statusline@sdrik-plugins
claude plugin install hygiene@sdrik-plugins
```

To pull in later updates:

```shell
/plugin marketplace update sdrik-plugins
```

## License

[MIT](./LICENSE)
