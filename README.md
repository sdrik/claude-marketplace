# sdrik-plugins

A [Claude Code](https://code.claude.com) plugin marketplace maintained by Cédric Schieli.

This catalog is meant to grow — more plugins will be added over time.

## Available plugins

| Plugin | Description |
| --- | --- |
| [`git-workspace`](https://github.com/sdrik/git-workspace) | Skills for managing git workspaces (worktrees, bare repositories, ...). |

## Usage

Add the marketplace, then install a plugin:

```shell
/plugin marketplace add sdrik/claude-marketplace
/plugin install git-workspace@sdrik-plugins
```

Or from your terminal:

```bash
claude plugin marketplace add sdrik/claude-marketplace
claude plugin install git-workspace@sdrik-plugins
```

To pull in later updates:

```shell
/plugin marketplace update sdrik-plugins
```

## License

[MIT](./LICENSE)
